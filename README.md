# coredns_system
Coredns system inclusive of monitoring, redundancy, and change processes.  The goal is a end to end system for the deployment of a Coredns edge cluster on docker providing:
 - forward lookups
 - reverse lookups
 - zone forwarding
 - caching capabilities
 -root lookups (might require libunbound)