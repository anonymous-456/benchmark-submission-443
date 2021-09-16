This repository contains benchmarks for NSDI submission #443.

## Data center benchmarks
`datacenter/shortest-path/`: FatTree topologies with a shortest-path routing policy in ACORN_IR, NV, and ShapeShifter formats.

`datacenter/valley-free/`: FatTree topologies with a valley-free policy, in ACORN_IR, NV, and ShapeShifter formats.

`datacenter/external-access/`: FatTree topologies with a valley-free policy that uses regular expressions to enforce isolation, in ACORN_IR format.

## Wide Area network benchmarks
`wan/topologyZoo/`: Topologies from Topology Zoo (annotated with business relationships and  running a policy that implements the Gao-Rexford conditions) in ACORN_IR format. Annotated topologies are in the subdirectory annotated_topologies

`wan/bgpStream/`: Networks from BGPStream (with  business relationships given by the CAIDA AS relationships dataset and a policy that implements the Gao-Rexford conditions) in ACORN_IR format. 

