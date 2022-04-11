# astra-eis-vac

Implement plan
effective robots at a local level that will chase down dirt and get the job done
need to handle their own states - self reliant. Handle variety of states sizes of maps and obstacles.
helpful to each other, but not to the point of getting confused or getting in each other's way.

We have to sense a number of different conditions.
THe dust hunger takes cares of opening up closed off areas.

They share a mechanism to share parts of routes and verboten areas that have been explored
plan was to test build it out, but was imposible to get 100% stability
Tuning for emergent behavours of spreading out and looking for dust
always one eye on performance - at robot level - first attempt to wakeup least productive robots. Selected because audction pattern pervide a platform for frobbing
second to guide them to good dirt - tah where the dirt is and chase it down preferentially.
Somewhat chaotic - there are iterations of tuning, there is space to catch emergent behaviours - one eye on performance at org level - what's being finished, what's reacting to changes like generate dust at a robot level. How does the system behave at both levels, the org and the local.
Affect the choices of the other robots by supplying them with certain learned info - dead ends to avoid and if time and stability - allows dust on the table, reducing the search space from what the agent can know.
Performance of the bots - measures of wall following and productivity and a culling via an auction process. Useful for weeding out the broken robots. Could be a basis for agent evolution. Works only really when dust appearing

Measures: runtime with running robots in different states - see the configurtations.

testing techniques - dense logging and speeded up footage

taking out conflicting error states where trying to make routes and make the agents manager and cleaner's interactions to break loops.

general purpose strategy tested against random confugrations, many times.