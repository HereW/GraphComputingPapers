# Some Papers on Graph Algorithms 

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#algorithms">2. Algorithms</a></td></tr>
<tr>
    <td>&emsp;<a href="#breadth-first-search">2.1 Breadth-First Search</a></td>
    <td>&ensp;<a href="#pagerank">2.2 PageRank</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#louvain">2.3 Louvain</a></td>
    <td>&ensp;<a href="#cycle-detection">2.4 Cycle Detection</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#label-propagation">2.5 Label Propagation</a></td>
    <td>&ensp;<a href="#subgraph-matching">2.6 Subgraph Matching</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#triangle-counting">2.3 Triangle Counting</a></td>
    <td>&ensp;<a href="#shortest-path">2.4 Shortest Path</a></td>
</tr>
<tr><td colspan="2"><a href="#framework">3. Frameworks</a></td></tr> 
<tr>
    <td>&emsp;<a href="#distributed-system">3.1 Distributed System</a></td>
    <td>&ensp;<a href="single-gpu-and-multiple-gpus">3.2 Single GPU and Multiple GPUs</a></td>
</tr>
</table>

## [Survey Papers](#content)

1. **Graph Processing on GPUs: A Survey.** ACM Computing Surveys (CSUR) 2018. [paper](https://dl.acm.org/doi/abs/10.1145/3128571)

   *Xuanhua Shi, Zhigao Zheng, Yongluan Zhou, Hai Jin, Ligang He, Bo Liu, and Qiang-Sheng Hua.*

2. **Thinking Like a Vertex: A Survey of Vertex-centric Frameworks for Large-scale Distributed Graph Processing.** ACM Computing Surveys (CSUR) 2015. [paper](https://dl.acm.org/doi/abs/10.1145/2818185)

    *Robert Ryan McCune, Tim Weninger, and Greg Madey.*

## [Algorithms](#content)

### [Breadth-First Search](#content)

1. **XBFS: eXploring runtime optimizations for breadth-first search on GPUs.** HPDC 2019. [paper](https://dl.acm.org/doi/abs/10.1145/3307681.3326606)
   
   *Anil Gaihre, Zhenlin Wu, Fan Yao, and Hang Liu.*

2. **GPU-based Graph Traversal on Compressed Graphs.** SIGMOD 2019. [paper](https://dl.acm.org/doi/abs/10.1145/3299869.3319871)

   *Mo Sha, Yuchen Li, and Kian-Lee Tan.* 

3. **Dr. BFS: Data Centric Breadth-First Search on FPGAs.** DAC 2019. [paper](https://ieeexplore.ieee.org/abstract/document/8806902)

   *Eric Finnerty, Zachary Sherer, Hang Liu, and Yan Luo.*

5. **Traversing Large Graphs on GPUs with Unified Memory.** PVLDB 2020. [paper](https://dl.acm.org/doi/abs/10.14778/3384345.3384358) 

   *Prasun Gera, Hyojong Kim, Piyush Sao, Hyesoon Kim, and David Bader.*

6. **Self-adaptive Graph Traversal on GPUs.** SIGMOD 2021. [paper](https://dl.acm.org/doi/abs/10.1145/3448016.3457279)

   *Mo Sha, Yuchen Li, and Kian-Lee Tan.*

7. **EMOGI: Efficient Memory-access for Out-of-memory Graph-traversal in GPUs.** PVLDB 2020. [paper](https://dl.acm.org/doi/abs/10.14778/3425879.3425883)

   *Seung Won Min, Vikram Sharma Mailthody, Zaid Qureshi, Jinjun Xiong, Eiman Ebrahimi, and Wen-mei Hwu.* 

8. **Fast and Efficient Parallel Breadth-First Search with Power-law Graph Transformation.** arXiv 2020. [paper](https://arxiv.org/abs/2012.10026)
   
   *Zite Jiang, Tao Liu, Shuai Zhang, Zhen Guan, Mengting Yuan, and Haihang You.* 

### [PageRank](#content)

#### [Personalized PageRank](#content)

### [Louvain](#content)



### [Cycle Detection](#content)


#### [s-t Path Enumeration](#content)


### [Label Propagation](#content)


#### [Overlapping Label Propagation](#content)


### [Subgraph Matching](#content)


### [Triangle Counting](#content)


### [Shortest Path](#content)

1. **A Fast Work-efficient SSSP Algorithm for GPUs.** PPoPP 2021. [paper](https://dl.acm.org/doi/abs/10.1145/3437801.3441605)

   *Wang, Kai, Don Fussell, and Calvin Lin.* 





## [Frameworks](#content)

### [Distributed System](#content)

1. **Ligra: A Lightweight Graph Processing Framework for Shared Memory.** PPoPP 2013. [paper](https://doi.org/10.1145/2442516.2442530)

   *Julian Shun, and Guy E. Blelloch.*


### [Single GPU and Multiple GPUs](#content)

1. **Medusa: Simplified Graph Processing on GPUs.** TPDS 2013. [paper](https://ieeexplore.ieee.org/abstract/document/6497047)

   *Jianlong Zhong, and Bingsheng He.* 
   
2. **CuSha: Vertex-centric Graph Processing on GPUs.** HPDC 2014. [paper](https://dl.acm.org/doi/abs/10.1145/2600212.2600227)
   <br/>

   *Farzad Khorasani, Keval Vora, Rajiv Gupta, and Laxmi N. Bhuyan.*
   <br/>

3. **Gunrock: A High-performance Graph Processing Library on the GPU.** PPoPP 2016. [paper](https://dl.acm.org/doi/abs/10.1145/2851141.2851145)
   <br/>

   *Yangzihao Wang, Andrew Davidson, Yuechao Pan, Yuduo Wu, Andy Riffel, and John D. Owens.* 
   <br/>

