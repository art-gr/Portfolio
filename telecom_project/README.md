## Description of the data

The datasets contain data on the use of the virtual telephony service CallMeMaybe.
Its clients are organizations that need to distribute large numbers of incoming calls among various operators or make outgoing calls through their operators. 
Operators can also make internal calls to communicate with one another. These calls go through CallMeMaybe's network.

`date` — date the statistics were retrieved<p>
`direction` — call direction (`out` for outgoing, `in` for incoming)<p>
`**internal` — whether the call was internal (between a client's operators)**<p>
`operator_id` — operator identifier<p>
`is_missed_call` — whether the call was missed<p>
`user_id` — client account ID<p>
`calls_count` — number of calls<p>
`call_duration` — call duration (excluding waiting time)<p>
`total_call_duration` — call duration (including waiting time)<p>

<p>
<p>
The dataset `telecom_clients_us.csv` has the following columns:<p>

`tariff_plan` — client's current plan<p>
`date_start` — client's registration date<p>
