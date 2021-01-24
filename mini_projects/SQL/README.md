# Description of the data

`**books**`

Contains data on books:

- `book_id`
- `author_id`
- `title`
- `num_pages` — number of pages
- `publication_date`
- `publisher_id`

`**authors**`

Contains data on authors:

- `author_id`
- `author`

`**publishers**`

Contains data on publishers:

- `publisher_id`
- `publisher`

`**ratings**`

Contains data on user ratings:

- `rating_id`
- `book_id`
- `username` — the name of the user who rated the book
- `rating`

`**reviews**`

Contains data on customer reviews:

- `review_id`

- `book_id`
- `username` — the name of the user who reviewed the book
- `text` — the text of the review
