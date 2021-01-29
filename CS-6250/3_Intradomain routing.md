Linkstate Routing Algorithm - Dijkstra

Distance Vector Routing:
- based on Bellman Ford Algorithm
- iterative (the algorithm iterates until the neighbors do not have new updates to send tos each other)
- asynchronous (the algorithm does not require the nodes to be synchronized with each other)
- distributed (direct nodes send information to one another, and then they resend their results back after performing their own calculations, so the calculations are not happening in a centralized manner).
- count-to-infinity problem when large link cost changes
- poison reverse (falsely increase expensive link cost to infinity)



Routing Information Protocol (RIP):
- based on distance vector routing
- uses hop count as metric

hot-potato routing - if destination is outside network, use the closest exit point