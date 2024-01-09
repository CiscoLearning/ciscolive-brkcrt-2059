# Enterprise Advanced Routing and Switching (ENARSI)

This is a sample ENARSI lab scenario.

## Troubleshoot BGP

To complete this lab you must do the following:

Full-mesh IBGP peering in AS 65001 uses Loopback1 interfaces instead of directly connected interfaces. R2 and R3 advertise correct next hop information to their IBGP peers. EBGP peering between R2 and R4 uses Loopback1 interfaces instead of directly connected interfaces.

R6 should prefer the path through R7 to reach the 10.1.1.0/24 network.

Why isn’t BGP working throughout?  There are five neighbour relationship issues, one routing issues, and one path selection issue.

Find and fix the problems and make sure all loopbacks are pingable!

Import the `topology.yaml` file to have a base with which to work.  If you get stuck, import the `topology-solution.yaml` file to see the fully working topology.
