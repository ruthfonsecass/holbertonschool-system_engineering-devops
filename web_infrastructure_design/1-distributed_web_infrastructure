# 1 - Why Add Additional Elements:
Each additional component in the infrastructure, such as extra servers, load balancers, and replicated databases, is integrated to increase redundancy, scalability, and availability.

# 2 - Load Balancer Distribution Algorithm:
The load balancer, like HAproxy, can be configured with various algorithms, such as round-robin, least connections, or IP hash. The round-robin algorithm, for example, distributes requests evenly among servers, moving to the next server in the list with each new request, helping ensure an equitable distribution of traffic.

# 3 - Active-Active vs. Active-Passive Load Balancer Configuration:
## Active-Active:
All servers are active and distributing loads simultaneously. Improves resource utilization and loading capacity.
## Active-Passive:
 One server is active while the other remains on standby, acting only if the active fails. Increases availability by ensuring a backup in case of failures.

# 4 - How a Database Primary-Replica (Master-Slave) Cluster Works:
In a Primary-Replica cluster, the primary node (master) handles reads and writes, while the replica nodes (slaves) synchronize in real-time with the primary, mainly dealing with reads to distribute load and increase availability.

# 5 - Difference Between Primary and Replica Nodes in Relation to the Application:
## Primary Node: 
Responsible for all write and update operations on the data. Can also serve reads but is generally reserved for tasks that change the database.
## Replica Node:
Primarily used for reads, relieving load on the primary and improving query performance. In some configurations, it can take over the primary role in case of its failure.