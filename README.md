# Distributed-Consistency-and-Consensu-Algorithms
Distributed Consistency and Consensus Algorithms This database is used to organize and display literature and papers related to distributed consensus algorithms and hierarchical management of related papers (0: the most basic paper, 1: the most relevant paper, 2: other related papers)



## [ 0 : The most classic consensus algorithm ]
### Classic
* Spanner: Google’s Globally Distributed Database[[TOCS'13](https://dl.acm.org/doi/abs/10.1145/2491245)]

### Paxos and variants
* Original Paxos | The part-time parliament[[paper](https://dl.acm.org/doi/abs/10.1145/3335772.3335939)]
  * Paxos Made Simple[[paper](https://www.microsoft.com/en-us/research/publication/paxos-made-simple/)]
  * Cheap Paxos[[paper](https://ieeexplore.ieee.org/abstract/document/1311900)]
  * Fast Paxos[[paper](https://link.springer.com/article/10.1007/s00446-006-0005-x)]
  * Multipaxos | Paxos made live: an engineering perspective[[PODC'07](https://dl.acm.org/doi/abs/10.1145/1281100.1281103)]
  * Egalitarian Paxos[[paper](https://www.usenix.org/system/files/nsdip13-paper14.pdf)]
    * There is more consensus in Egalitarian parliaments[[SOSP'13](https://dl.acm.org/doi/abs/10.1145/2517349.2517350)]
  * SwiftPaxos: Fast Geo-Replicated State Machine[[Nsdi'24](https://software.imdea.org/events/software-seminars/2021/03-16/)]
  * SDPaxos: Building Efficient Semi-Decentralized Geo-replicated State Machines[[SoCC'18](https://www.microsoft.com/en-us/research/uploads/prod/2018/09/172-zhao.pdf)]
### Raft and variants
* In Search of an Understandable Consensus Algorithm[[ATC'14](https://www.usenix.org/system/files/conference/atc14/atc14-paper-ongaro.pdf),[dl](https://www.usenix.org/conference/atc14/technical-sessions/presentation/ongaro)]
  * Elastic, geo-distributed RAFT[[IWQoS'19](https://dl.acm.org/doi/abs/10.1145/3326285.3329046)]

### Contrast
* Paxos vs Raft: Have we reached consensus on distributed consensus?[[PaPoC'20](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Howard+H%2C+Mortier+R.+Paxos+vs+Raft%3A+Have+we+reached+consensus+on+distributed+consensus&btnG=)]
* On the Parallels between Paxos and Raft, and how to Port Optimizations[[PODC'19](http://mpaxos.com/pub/raft-paxos.pdf)]

## [ 1 : the most relevant paper ]  
  * SLOG: serializable, low-latency, geo-replicated transactions[[VLDB'19](https://par.nsf.gov/servlets/purl/10126332)]
  * CockroachDB: The Resilient Geo-Distributed SQL Database[[SIGMOD'19](https://dl.acm.org/doi/abs/10.1145/3318464.3386134)]
  * Linearizable State Machine Replication of State-Based CRDTs without Logs[[PODC '19](https://dl.acm.org/doi/abs/10.1145/3293611.3331568)]
  * GeoGauss: Strongly Consistent and Light-Coordinated OLTP for Geo-Replicated SQL Database[[SIMOD'23](https://dl.acm.org/doi/abs/10.1145/3588916)]
  * Near-Optimal Latency Versus Cost Tradeoffs in Geo-Distributed Storage[[NSDI'20](https://www.usenix.org/conference/nsdi20/presentation/uluyol)]
  * Cost-Effective Strong Consistency on Scalable Geo-Diverse Data Replicas[[paper](https://ieeexplore.ieee.org/abstract/document/9740519)]

## [ 2 : Other related papers ]
  * Hydra: Serialization-Free Network Ordering for Strongly Consistent Distributed Applications[[Nsdi'23](https://www.usenix.org/system/files/nsdi23-choi.pdf)]
  * On Modular Learning of Distributed Systems for Predicting End-to-End Latency[[Nsdi'23](https://www.usenix.org/system/files/nsdi23-liang-chieh-jan.pdf)]
  * Electrode: Accelerating Distributed Protocols with eBPF[[Nsdi'23](https://www.usenix.org/conference/nsdi23/presentation/zhou)]
  * Waverunner: An Elegant Approach to Hardware Acceleration of State Machine Replication[[Nsdi'23](https://www.usenix.org/conference/nsdi23/presentation/alimadadi)]
  * Skyplane: Optimizing Transfer Cost and Throughput Using Cloud-Aware Overlays[[Nsdi'23](https://arxiv.org/abs/2210.07259)]
  * Calvin: fast distributed transactions for partitioned database systems[[SIGMOD'12](https://dl.acm.org/doi/abs/10.1145/2213836.2213838)]
  * Planet-scale leaderless consensus[[paper](http://repositorium.uminho.pt/handle/1822/81307)]
  * Dynamo: amazon's highly available key-value store[[SIGOPS'07]](https://dl.acm.org/doi/abs/10.1145/1323293.1294281)
  
#### SMR:State-machine replication
  * State-machine replication for planet-scale systems[[EuroSys'20](https://dl.acm.org/doi/abs/10.1145/3342195.3387543)]