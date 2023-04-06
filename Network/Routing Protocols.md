## Routing Information Protocol (RIP)
* *__distance-vector routing protocol__* that is used for small-scale internal routing
* sends the complete routing table to the neighboring router out all active interfaces every 30 seconds
* uses the hop count as a metric and the Bellman–Ford algorithm to calculate the routing decision
* maximum hop count of 15
* RIP version 1 = broadcast, classful
* RIP version 2 = multicast, classless
* RIPng (RIP next generation) = IPv6 implementation, multicast

## Open Shortest Path First (OSPF)
* *__link-state routing protocol__* that is extremely scalable and used for extremely large networks
* uses the Dijkstra algorithm to construct the initial shortest path tree and calculates routes based on the bandwidth metric
* unlimited hop count, unlike EIGRP and RIP
* OSPFv3 is the IPv6 version of OSPF version 2 (IPv4)

## Enhanced Interior Gateway Routing Protocol (EIGRP)
* *__hybrid routing protocol__* that is proprietary to Cisco and used for medium to large company networks
* more modern protocol than RIP
* default hop count of 100 and a maximum of 255
* supports classless routing (subnets), variable-length subnet masking (VLSM), discontiguous networks, and summarization of networks
* By default, routing decisions use a combination of bandwidth and delay called a composite metric

## Border Gateway Protocol (BGP)
* *__path-vector routing protocol__* used on the Internet for routing


