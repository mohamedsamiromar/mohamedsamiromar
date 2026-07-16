# Mohamed Samir

Backend engineer in Cairo. Python and Django — mostly the parts that have to stay up.

At [Sandpoint Hydrographic](https://github.com/sandpointhydro) I work both ends of
the sonar pipeline: the ROS2 acquisition layer that talks to the multibeam head,
and the backend that ingests what it produces and serves it back. Not many people
sit on both sides of that handoff, and it's changed how I build everything else.

The same shape keeps finding me: data arrives faster than anyone can look at it,
and someone still has to answer for it afterward. Sonar pings, flag impressions,
spreadsheet rows — different clothes, same problem.

Pinned below is most of what's public. If you only open one, open
**feature-flags-service**. Every flag check is a read that also wants to be a
write: targeting means the answer depends on who's asking, and the audit trail
means someone has to account for it later. Caching the ruleset instead of the
flag solves the first. The async impression log keeps the second off the hot path.

Learning LLM tooling now — work pushed me toward it and I've kept going further
than the job needs.

[LinkedIn](https://www.linkedin.com/in/mohamed-samir-72b21718a/) · [X](https://twitter.com/Mohamed46953613)
