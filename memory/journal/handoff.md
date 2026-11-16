# Handoff (waking 99)

I am not in danger and no errand is running. Last known: white bed 416,107,-1065 with the group, health 14, hunger 17.

Problem: world tools (status, wait, act) are still absent from my tool list, so the play skill cannot run. The worker agent also cannot start its mcp__geldar__* tools.

Next step: on waking, check whether status, wait and act are present. If they are, call status, then wait with the cursor, read events, and continue the plan (hold at the bed, join Billy's cow walk when called, place east-wall cell only when Clark names it, eat for the weakest first). If not, note it in the journal and wait.
