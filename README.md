# System Design Compendium
Open-source compendium of system design resources

## Getting Started
### System Design?
The desigining of systems to satisfy demands, constraints, and use requirements

### Scalability
The ability of a system to handle growth which is achieved by adding more resource to the system like more hardware (horizontal scaling) or better hardware (vertical scaling).

### Load Balancing
Distributes and balances requests traffic between multiple servers
Learn more: https://avinetworks.com/what-is-load-balancing/

### Clustering
 A group of servers are logically combined into a cluster and seen as one device

## Redundancy
The duplication of components to achieve better performance and reliability
### RAID
Fault tolerance solution for hard drives
- RAID0: 2 drives, Stripe data split in half to double Performance
- RAID1: 2 drives, Mirroring Data
- RAID5: +3 drives, only one for mirroring
- RAID6: +3 drives, two drives for mirroring 
- RAID10: 4 drives, Striping and Mirroring, twice the cost

## Storage
### Caching
#### Memcached
#### Redis

## Partitioning
Seperating data into multiple chunks to distribute and balance read and write loads.

### Sharding
Seperating a single dataset onto multiple datasbases.
