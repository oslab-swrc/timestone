# TimeStone (Durable Transactional Memory Can Scale with Timestone)

TimeStone is a highly scalable DTM system with low write amplification and minimal memory footprint. TimeStone uses a novel multi-layered hybrid logging technique, called TOC logging, to guarantee crash consistency. Also, TimeStone further relies on Multi-Version Concurrency Control (MVCC) mechanism to achieve high scalability and to support different isolation levels on the same data set.

All Timestone source codes are provided under the terms of Apache 2.0 License, except ```lib-nv-jemalloc``` which provided under BSD-2-Clause. 

## Directory structure
```{.sh}
timestone
├── include             # public headers of timestone
├── lib                 # timestone library
├── lib++               # timestone C++ APIs
├── tools               # misc build tools
```

## How to configure, build, and clean
```{.sh}
cd timestone/
make
```

## Contact 
Please contact us at madhavakrishnan@vt.edu and changwoo@vt.edu

## Citation
https://dl.acm.org/doi/abs/10.1145/3373376.3378483
```
@inproceedings{krishnan:timestone,
author = {Krishnan, R. Madhava and Kim, Jaeho and Mathew, Ajit and Fu, Xinwei
and Demeri, Anthony and Min, Changwoo and Kannan, Sudarsun},
title = {Durable Transactional Memory Can Scale with Timestone},
year = {2020},
isbn = {9781450371025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3373376.3378483},
doi = {10.1145/3373376.3378483},
booktitle = {Proceedings of the Twenty-Fifth International Conference on
Architectural Support for Programming Languages and Operating Systems},
pages = {335–349},
numpages = {15},
location = {Lausanne, Switzerland},
series = {ASPLOS '20}
}
```
