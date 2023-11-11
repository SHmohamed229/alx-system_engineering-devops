

Issue Summary

From 6:00 PM to 8:58 PM ُEG,There was a public power outage in the area, which led to a power outage to the main servers, which affected the main servers to malfunction.Users could continue to access certain APIs that run on separate infrastructures.The root cause of this failure was the failure to isolate the main servers’ electricity from the general electricity.

Timeline (All times are in standard time zone)

6:00 PM: Configuration push begins
6:14 PM: Outage begins
6:26 PM: Pagers alerted teams
6:54 PM: Failed configuration change rollback
7:0.My first postmortem15 PM: Successful configuration change rollback
8:19 PM: Server restarts begin
7:58 PM: 100% of traffic back online


Root Cause
AT 6:00 PM to 8:58 PM ُEG,There was a public power outage in the area, which led to a power outage to the main servers, which affected the main servers to malfunction.Users could continue to access certain APIs that run on separate infrastructures.The root cause of this failure was the failure to isolate the main servers’ electricity from the general electricity.

Corrective and Preventative Measures
In the last two days, we’ve conducted an internal review and analysis of the outage. 
The following are actions we are taking to address the underlying causes of the issue and to help prevent recurrence and improve response times:
First, make sure to isolate the general electrical current from the main servers’ electrical current.
Secondly, make sure to reduce the pressure on the main servers by distributing the work to the secondary servers.
Third, monitor the servers and the power indicator periodically so that no other malfunction occurs

