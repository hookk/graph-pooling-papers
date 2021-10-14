# graph-pooling-papers

Papers on Graph Pooling 

| Title                                                        |      Conf.      | Type                        | Task                                                         | Dataset                                                      | Code                                                         |
| :----------------------------------------------------------- | :-------------: | --------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1. Set2set: [Order Matters: Sequence to Sequence for Sets](https://arxiv.org/abs/1511.06391) |    ICLR 2016    |                             |                                                              |                                                              | [PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/benchmark/kernel/set2set.py) |
| 2. SortPool:  [An End-to-End Deep Learning Architecture for Graph Classification](https://www.cse.wustl.edu/~muhan/papers/AAAI_2018_DGCNN.pdf) |    AAAI 2018    |                             |                                                              |                                                              | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/benchmark/kernel/sort_pool.py), [2.Origin-matlab](https://github.com/muhanzhang/DGCNN), [3.Origin-pytorch](https://github.com/muhanzhang/pytorch_DGCNN) |
| 3. DiffPool:  [Hierarchical Graph Representation Learning with Differentiable Pooling](https://arxiv.org/abs/1806.08804) |    NIPS 2018    | Node Clustering             | 1. Graph Classification                                      | D&D, PROTEINS, COLLAB, ENZYMES, REDDIT-MULTI                 | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/examples/proteins_diff_pool.py),[2.Origin-pytorch](https://github.com/RexYing/diffpool) |
| 4. TopKPool:  [Graph U-Nets](https://arxiv.org/abs/1905.05178) |    ICML 2019    | Node  Drop                  | 1. Graph Classification 2. Node Classification               | D&D, PROTEINS, COLLAB                                        | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/examples/proteins_topk_pool.py),[2.Origin-pytorch](https://github.com/HongyangGao/Graph-U-Nets) |
| 5. SAGPool:  [Self-Attention Graph Pooling](https://arxiv.org/abs/1904.08082) |    ICML 2019    | Node  Drop                  | 1. Graph Classification                                      | D&D, PROTEINS, NCI1, NCI109, FRANKENSTEIN                    | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/benchmark/kernel/sag_pool.py),[2.Origin-pytorch](https://github.com/inyeoplee77/SAGPool) |
| 6. EdgePool:  [Towards Graph Pooling by Edge Contraction](https://graphreason.github.io/papers/17.pdf) |   ICML-W 2019   |                             | 1. Graph Classification                                      | PROTEINS, COLLAB, REDDIT-BINARY, REDDIT-MULTI                | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/benchmark/kernel/edge_pool.py) |
| 7. EigenPool: [Graph Convolutional Networks with EigenPooling](https://arxiv.org/pdf/1904.13107.pdf) |    KDD 2019     | Spectral                    | 1. Graph Classification                                      | D&D, PROTEINS, NCI1, NCI109, MUTAG, ENZYMES                  | [1.Origin-pytorch](https://github.com/alge24/eigenpooling)   |
| 8. AttPool : [Towards Hierarchical Feature Representation in Graph Convolutional Networks via Attention Mechanism](https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_AttPool_Towards_Hierarchical_Feature_Representation_in_Graph_Convolutional_Networks_via_ICCV_2019_paper.pdf) |    ICCV 2019    | Node Drop                   | 1. Graph Classification                                      | D&D, PROTEINS, COLLAB, REDDIT-BINARY,REDDIT-MULTI, NCI1      | [1. Origin-pytorch](https://github.com/hjjpku/Attention_in_Graph) |
| 9. MInCutPool: [Spectral Clustering with Graph Neural Networks for Graph Pooling](https://arxiv.org/pdf/1907.00481.pdf) |    ICML 2020    | Node Clustering             | 1. Graph Classification 2. Graph Regression                  | D&D, PROTEINS, COLLAB, REDDIT-BINARY, Mutagenicity, QM9(regression) | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/examples/proteins_mincut_pool.py),[2.Origin-pytorch](https://github.com/FilippoMB/Spectral-Clustering-with-Graph-Neural-Networks-for-Graph-Pooling) |
| 10.  ASAP:  [ Adaptive Structure Aware Pooling for Learning Hierarchical Graph Representations](https://arxiv.org/abs/1911.07979) |    AAAI 2020    | Node Drop                   | 1. Graph Classification                                      | D&D, PROTEINS, NCI1, NCI109, FRANKENSTEIN                    | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/benchmark/kernel/asap.py),[2.Origin-PyG](https://github.com/malllabiisc/ASAP) |
| 11. HGP-SL: [Hierarchical Graph Pooling with Structure Learning](https://arxiv.org/abs/1911.05954) |    AAAI 2020    | Node Drop                   | 1. Graph Classification                                      | D&D, PROTEINS, NCI1, NCI109, ENZYMES, Mutagencity            | [1.Origin-PyG](https://github.com/cszhangzhen/HGP-SL)        |
| 12. HaarPool: [Haar Graph Pooling](https://arxiv.org/abs/1909.11580) |    ICML 2020    | Spectral                    | 1. Graph Classification  2. Graph Regression                 | MUTAG, PROTEINS,  NCI1, NCI109, MUTAGEN, TRIANGLES, QM7(regression), | [1.Origin-PyG](https://github.com/YuGuangWang/HaarPool)      |
| 13. LaPool : [Towards Interpretable Molecular Graph Representation Learning ](https://openreview.net/forum?id=HyljY04YDB) |   ArXiv 2019    | Spectral                    | 1. Graph Classification 2. Graph Regression  3. Molecular Generation | TOX21, D&D, PROTEINS, FRANKENSTEIN, QM9(regression)          | 1. [Origin-Pytorch](https://anonymous.4open.science/r/941cb9ee-302f-4c81-bbf9-abcff1e98894/README.md) |
| 14. GASPool: [Structure-Feature based Graph Self-adaptive Pooling](https://dl.acm.org/doi/fullHtml/10.1145/3366423.3380083) |    WWW 2020     | Node Drop                   | 1. Graph Classification                                      | D&D, NCI1, NCI109,  Mutagencity                              | [1.Pytorch](https://github.com/psp3dcg/GSAPool)              |
| 15. PANPool:  [Path Integral Based Convolution and Pooling for Graph Neural Networks](https://arxiv.org/abs/2006.16811) |    NIPS 2020    |                             | 1. Graph Classification                                      | PROTEINS, PROTEINS-FULL, NCI1, AIDS, MUTAGENCITY             | [1.PyG](https://pytorch-geometric.readthedocs.io/en/latest/modules/nn.html#torch_geometric.nn.pool.PANPooling) |
| 16. MemPool:  [Memory-Based Graph Networks](https://arxiv.org/abs/2002.09518) |    ICLR 2020    |                             | 1. Graph Classification  2. Graph Regression                 | D&D, PROTEINS, COLLAB, REDDIT-BINARY,ENZYMES ESOL(reg), Lipophilicity(reg) | [1.PyG](https://github.com/pyg-team/pytorch_geometric/blob/master/examples/mem_pool.py),[2.Origin-pytorch](https://github.com/amirkhas/GraphMemoryNet) |
| 17.SOPool:  [Second-Order Pooling for Graph Neural Networks](https://arxiv.org/abs/2007.10467) |   TPAMI 2020    |                             | 1. Graph Classification                                      | MUTAG, PTC PROTEINS, NCI1, COLLAB, IMDB-B, IMDB-M, REDDIT-BINARY,REDDIT-MULTI, | None                                                         |
| 18. UGPool: [Uniform Pooling for Graph Networks](https://www.mdpi.com/2076-3417/10/18/6287) | Appl. Sci. 2020 | Node Drop                   | 1. Graph Classification                                      | D&D, PROTEINS, NCI1, NCI109, ENZYMES,  HCP(Brain), ABIDE(Brain) | None                                                         |
| 19. MuchPool: [Multi-Channel Pooling Graph Neural Networks](https://www.ijcai.org/proceedings/2021/0199.pdf) |   IJCAI 2021    | Node Drop + Node Clustering | 1. Graph Classification                                      | D&D, PROTEINS, NCI1, NCI109, ENZYMES, COLLAB                 | None                                                         |
| 20. GMT: [Accurate Learning of Graph Representations with Graph Multiset Pooling.](https://openreview.net/forum?id=JHcqXGaqiGn) 🌟 |    ICLR 2021    | Node Clustering             | 1. Graph Classification  2. Graph Reconstruction 3. Graph Generation | D&D, PROTEINS,  MUTAG, IMDB-B, IMDB-M, COLLAB, HIV, Tox21, ToxCast, BBBP, ZINC(Reconstruction),  QM9(Generation) | [1.Origin-Pytorch]( https://github.com/JinheonBaek/GMT)      |
| 21. VIPool: [Graph Cross Networks with Vertex Infomax Pooling](https://papers.nips.cc/paper/2020/file/a26398dca6f47b49876cbaffbc9954f9-Paper.pdf) |    NIPS 2020    | Node Clustering             | 1. Graph Classification 2. Node Classification               | IMDB- B,  IMDB-M, COLLAB,  D&D, PROTEINS,  ENZYMES           | [1.Origin-pytorch](https://github.com/limaosen0/GXN)         |
| 22. CGIPool: [Graph Pooling via Coarsened Graph Infomax](https://arxiv.org/pdf/2105.01275.pdf) |   SIGIR 2021    | Node Drop                   | 1. . Graph Classification                                    | NCI1,  NCI109, Mutagenicity,  IMDB-B, IMDB-M, COLLAB PROTEINS | [1.Origin-pytorch](https://github.com/PangYunsheng8/CGIPool) |
| 23. CommPOOL:[An Interpretable Graph Pooling Framework for Hierarchical Graph Representation Learning](https://arxiv.org/pdf/2012.05980.pdf) |    AAAI 2021    | Node Drop                   | 1. Graph Classification                                      | BZR,  FRANKENSTEIN, PROTEINS,  AIDS, Synthie                 | None                                                         |
| 24. Ipool: [Information-Based Pooling in Hierarchical Graph Neural Networks](https://ieeexplore.ieee.org/document/9392315) |   TNNLS  2021   | Node Drop                   | 1.Graph Classification                                       | D&D, PROTEINS, NCI1, NCI109, ENZYMES, MNIST, CIFAR-10        | None                                                         |
| 25. StructPool:[Structured Graph Pooling via Conditional Random Fields](https://openreview.net/forum?id=BJxg_hVtwH) |    ICLR 2020    | Node Clustering             | 1.Graph Classification                                       | ENZYMES, PTC, MUTAG, PROTEINS, COLLAB, IMDB-B, IMDB-M        | [1. Origin](https://github.com/Nate1874/StructPool)          |
| 26. [Rethinking pooling in graph neural networks](https://proceedings.neurips.cc/paper/2020/hash/1764183ef03fc7324eb58c3842bd9a57-Abstract.html) 🌟 |    NIPS 2020    | Node Clustering             | 1.Graph Classification                                       | PROTEINS, NCI109, D&D, IMDB-B, HIV                           | [1.Origin-PyG](https://github.com/AaltoPML/Rethinking-pooling-in-GNNs) |
| 27. [Understanding Attention and Generalization in Graph Neural Networks](https://arxiv.org/abs/1905.02850) 🌟 |    NIPS 2019    | Node Drop                   | 1.Graph Classification                                       | COLORS, TRIANGLES, MNIST-75SP, PROTEINS, D&D ,COLLAB         | [1.Origin-pytorch](https://github.com/bknyaz/graph_attention_pool) |
| 28.ProxPool: [Graph Pooling with Node Proximity for Hierarchical Representation Learning]() |   ArXiv 2020    | Spectral                    | 1.Graph Classification                                       | D&D, PROTEINS, NCI1, NCI109, MUTA-GENICITY                   | None                                                         |
| 29. [LookHops: light multi-order convolution and pooling for graph classification](https://www.x-mol.com/paperRedirect/1345168184696049664) |   ArXiv 2020    | Node Drop                   | 1.Graph Classification                                       | PROTEINS, D&D, NCI1, NCI109, Mutagenicity, FRANKENSTEIN      | None                                                         |
| 30. [Adversarial Attack on Hierarchical Graph Pooling Neural Networks](https://arxiv.org/pdf/2005.11560.pdf) |   ArXiv 2020    |                             |                                                              |                                                              | None                                                         |
| 31. [KGPool: Dynamic Knowledge Graph Context Selection for Relation Extraction](https://arxiv.org/abs/2106.00459) |    ACL 2021     |                             |                                                              |                                                              |                                                              |
| 32. [Learning to Pool in Graph Neural Networks for Extrapolation](https://arxiv.org/abs/2106.06210) |   ArXiv 2021    |                             |                                                              |                                                              | None                                                         |
| 33. HIBPool: [Structure-Aware Hierarchical Graph Pooling using Information Bottleneck](https://arxiv.org/abs/2104.13012) |   IJCNN 2021    |                             |                                                              |                                                              | [1.Origin](https://github.com/forkkr/HIBPool)                |
| 34. RepPool:[Graph Pooling with Representativeness](https://ieeexplore.ieee.org/document/9338397) |    ICDM 2020    | Node Drop                   | 1.Graph Classification                                       | PROTEINS, D&D, NCI1, NCI109, MUTAG, PTC, IMDB-BINARY, Synthie | [1.Origin-pytorch]( https://github.com/Juanhui28/RepPool/tree/master/RepPool) |
| 35. [User-as-Graph: User Modeling with Heterogeneous Graph Pooling for News Recommendation](https://www.ijcai.org/proceedings/2021/224) |   IJCAI 2021    |                             |                                                              |                                                              |                                                              |
| 36. MxPool: [Multiplex Pooling for Hierarchical Graph Representation Learning](https://arxiv.org/abs/2004.06846) |   ArXiv 2021    |                             | 1.Graph Classification                                       | D&D , ENZYMES , PROTEINS , NCI109, COLLAB, RDT-MULTI         | None                                                         |
| 37.TAPPool:[Topology-Aware Graph Pooling Networks]()         |   TPAMI 2021    | Node Drop                   | 1.Graph Classification                                       | DD, PTC, MUTAG, COLLAB, REDDIT-MULT,                         | None                                                         |
| 38. CLIQUE POOL:[CLIQUE POOLING FOR GRAPH CLASSIFICATION]()  |   ICLR-W 2019   |                             | 1.Graph Classification                                       | ENZYMES, DD, PROTEINS, COLLAB                                | None                                                         |
| 39. [Effects of Graph Pooling Layers on Classification with Graph Neural Networks](https://ieeexplore.ieee.org/abstract/document/9145008/) |    SDS 2020     |                             |                                                              |                                                              | None                                                         |
| 40. PAS:  [Pooling Architecture Search for Graph Classification](http://arxiv.org/abs/2108.10587) |   ArXiv 2021    |                             | 1.Graph Classification                                       |                                                              | None                                                         |

