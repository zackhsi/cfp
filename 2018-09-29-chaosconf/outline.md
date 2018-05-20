Halloween Outage Friday, October 31st
-------------------------------------

Tell story.

https://docs.google.com/document/d/1eBiomN-1Jh7oD-nWWbKqIkQ6I8nV69BJsqKLru9GiXc/edit

**outages** are typically caused by large increases in traffic.

**takeaway**: chaos is inevitable.

Chaos phase 0: reactive friday night firefighting
-------------------------------------------------

Halloween happened during phase 0.

Chaos phase 1: proactive friday night firefighting
--------------------------------------------------

- Beginnings of "chaos engineering". Taming the chaos.
- DDOS ourselves. No theories or models, must take empirical approach.
    - "Use what's on the fucking truck."
- Extremely operationally burdensome.
- Outage inducing. Coarse-grain controls.

**takeaway**: ain't nothing like production. "i don't always test, but when i do, i do it in production" (transferrability of results)

Prerequisites to taming chaos
-----------------------------
Prerequisites:
- Monitoring: stats, traces, logs
    - Run through flow of handling a production incident
- Chaos experiments cannot cause a significant problem in the system
    - Mongo death spiral

"The performance of complex systems is typically optimized at the edge of chaos, just before system behavior will become unrecognizably turbulent" - Sidney Dekker
- Lyft-specific interpretations of quote:
    - Edge of chaos. Where is the edge? Show weekly traffic with "edge" annotation.
    - Unrecognizably turbulent. Euphemism for outage, e.g. mongo death spiral.

Performance is familiar with the edge. Stories to come later.

**takeaway**: do not try at home until you are ready, severe injury may occur


Chaos phase 2: proactive business hours firefighting
----------------------------------------------------

- First time talking about simulated rides. Explain how it works, and load testing principles.

"The performance of complex systems is typically optimized at the edge of chaos, just before system behavior will become unrecognizably turbulent" - Sidney Dekker

- Simulated rides lets us optimize at the edge of chaos.

Stories.

#### Dispatch

#### Account

**outages** typically caused increasingly arcane system interactions that we methodically burn down.

**takeaway** investments in chaos engineering have huge business impact

Chaos phase 3: proactive continuous testing
-------------------------------------------

- Obligatory Envoy plug.
- Not operationally burdensome.

**outages** what outages? :)

**takeaway** maslow's hierarchy of resilience must be climbed one step at a time.
