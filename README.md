# vgrp
Method for calculating Variation Graph mapped Read Probabilities given a set of paths in a GBWT index.

### Compilation
*vgprob* requires that [protobuf](https://github.com/protocolbuffers/protobuf), [htslib](https://github.com/samtools/htslib) and OpenMP are installed before compilation. 

1. `git clone https://github.com/jonassibbesen/vgprob.git`
2. `cd vgprob`
3. `mkdir build && cd build`
4. `cmake ..`
5. `make -j <threads>`
