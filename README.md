# Explainable Knowledge Graph Construction Papers

This repository aims to collect papers related to the topic of "eXplainable automatic Knowledge Graph Construction" (XKGC). 
We categorize these works based on various tasks within XKGC, including knowledge extraction (entity and relation extraction), 
knowledge integration (entity linking), knowledge completion (link prediction), etc. 
- Our working paper which includes the analysis of the collected papers: [Towards Explainable Automatic Knowledge Graph Construction with Human-in-the-Loop](https://ebooks.iospress.nl/doi/10.3233/FAIA230091).
- For in-depth task descriptions, please refer to the following two surveys on natural language processing and knowledge graph development.
  - NLP: [A Decade of Knowledge Graphs in Natural Language Processing: A Survey](https://arxiv.org/abs/2210.00105)
  - KGC: [Defining a Knowledge Graph Development Process Through a Systematic Review](https://dl.acm.org/doi/full/10.1145/3522586)

## Papers

### Entity Extraction
- **AutoTriggER: Named Entity Recognition with Auxiliary Trigger Extraction** [EACL '23]
    - [[URL](https://arxiv.org/abs/2109.04726)]
- **BTPK-based learning: An Interpretable Method for Named Entity Recognition** [arXiv '22]
    - [[URL](https://arxiv.org/abs/2201.09523)]
- **Expert-Guided Entity Extraction using Expressive Rules** [SIGIR '19]
    - [[URL](https://dl.acm.org/doi/10.1145/3331184.3331392)]
- **Instance-Based Learning of Span Representations: A Case Study through Named Entity Recognition** [ACL '20]
    - [[URL](https://arxiv.org/abs/2004.14514)] [[GitHub](https://github.com/hiroki13/instance-based-ner)]
- **Lightly-supervised Representation Learning with Global Interpretability** [Workshop on Structured Prediction for NLP '19]
    - [[URL](https://aclanthology.org/W19-1504/)]
- **TriggerNER: Learning with Entity Triggers as Explanations for Named Entity Recognition** [ACL '20]
    - [[URL](https://arxiv.org/abs/2004.07493)] [[GitHub](https://github.com/INK-USC/TriggerNER)]

### Relation Extraction
- **Broad-coverage biomedical relation extraction with SemRep** [BMC Bioinformatics, Volume 21]
    - [[URL](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-3517-7)]
- **D-REX: Dialogue Relation Extraction with Explanations** [Workshop on NLP for Conversational AI '22]
    - [[URL](https://arxiv.org/abs/2109.05126)] [[GitHub](https://github.com/alon-albalak/D-REX)]
- **Document-level relation extraction using evidence reasoning on RST-GRAPH** [Knowledge-Based Systems, Volume 228]
    - [[URL](https://www.sciencedirect.com/science/article/abs/pii/S0950705121005360)]
- **Learning Logic Rules for Document-level Relation Extraction** [EMNLP '21]
    - [[URL](https://arxiv.org/abs/2111.05407)] [[GitHub](https://github.com/rudongyu/LogiRE)]
- **NERO: A Neural Rule Grounding Framework for Label-Efficient Relation Extraction** [WWW '20]
    - [[URL](https://dl.acm.org/doi/10.1145/3366423.3380282)] [[GitHub](https://github.com/INK-USC/NERO)]
- **Prototypical Representation Learning for Relation Extraction** [ICLR '21]
    - [[URL](https://arxiv.org/abs/2103.11647)] [[GitHub](https://github.com/Alibaba-NLP/ProtoRE)]
- **Relation Extraction with Explanation** [ACL '20]
    - [[URL](https://arxiv.org/abs/2005.14271)]
- **SAIS: Supervising and Augmenting Intermediate Steps for Document-Level Relation Extraction** [NAACL '22]
    - [[URL](https://arxiv.org/abs/2109.12093)] [[GitHub](https://github.com/xiaoyuxin1002/SAIS)]
- **SIRE: Separate Intra- and Inter-sentential Reasoning for Document-level Relation Extraction** [ACL-IJCNLP '21]
    - [[URL](https://aclanthology.org/2021.findings-acl.47/)] [[GitHub](https://github.com/DreamInvoker/SIRE)]

### Entity Linking
- **EABlock: a declarative entity alignment block for knowledge graph creation pipelines** [SAC '22]
    - [[URL](https://dl.acm.org/doi/10.1145/3477314.3507132)] [[GitHub](https://github.com/SDM-TIB/EABlock)]
- **Effective Explanations for Entity Resolution Models** [ICDE '22]
    - [[URL](https://arxiv.org/abs/2203.12978)] [[GitHub](https://github.com/tteofili/certa)]
- **EXPLAINER: Entity Resolution Explanations** [ICDE '19]
    - [[URL](https://ieeexplore.ieee.org/document/8731597)]
- **From Alignment to Assignment: Frustratingly Simple Unsupervised Entity Alignment** [EMNLP '21]
    - [[URL](https://arxiv.org/abs/2109.02363)] [[GitHub](https://github.com/MaoXinn/SEU)]
- **Interpretable and Low-Resource Entity Matching via Decoupling Feature Learning from Decision Making** [ACL '21]
    - [[URL](https://arxiv.org/abs/2106.04174)] [[GitHub](https://github.com/THU-KEG/HIF-KAT)]
- **Interpretable entity meta-alignment in knowledge graphs using penalized regression: a case study in the biomedical domain** [Progress in Artificial Intelligence, Volume 11]
    - [[URL](https://link.springer.com/article/10.1007/s13748-021-00263-1)]
- **Interpreting deep learning models for entity resolution: an experience report using LIME** [aiDM '19]
    - [[URL](https://dl.acm.org/doi/10.1145/3329859.3329878)]
- **Keys as Features for Graph Entity Matching** [ICDE '20]
    - [[URL](https://ieeexplore.ieee.org/document/9101779)]
- **Landmark Explanation: An Explainer for Entity Matching Models** [CIKM '21]
    - [[URL](https://dl.acm.org/doi/10.1145/3459637.3481981)] [[GitHub](https://github.com/softlab-unimore/landmark)]
- **LEMON: Explainable Entity Matching** [IEEE Transactions on Knowledge and Data Engineering, Early Access]
    - [[URL](https://arxiv.org/abs/2110.00516)] [[GitHub](https://github.com/NilsBarlaug/lemon)]
- **LightEA: A Scalable, Robust, and Interpretable Entity Alignment Framework via Three-view Label Propagation** [EMNLP '22]
    - [[URL](https://arxiv.org/abs/2210.10436)] [[GitHub](https://github.com/MaoXinn/LightEA)]
- **Minun: evaluating counterfactual explanations for entity matching** [DEEM '22]
    - [[URL](https://dl.acm.org/doi/10.1145/3533028.3533304)] [[GitHub](https://github.com/megagonlabs/minun)]
- **Synthesizing entity matching rules by examples** [VLDB Endowment, Volume 11]
    - [[URL](https://dl.acm.org/doi/10.14778/3149193.3149199)]
- **SystemER: a human-in-the-loop system for explainable entity resolution** [VLDB Endowment, Volume 12]
    - [[URL](https://dl.acm.org/doi/10.14778/3352063.3352068)]
- **TuneR: Fine Tuning of Rule-based Entity Matchers** [CIKM '19]
    - [[URL](https://dl.acm.org/doi/10.1145/3357384.3357854)]
- **xER: An Explainable Model for Entity Resolution using an Efficient Solution for the Clique Partitioning Problem** [Workshop on Trustworthy Natural Language Processing '21]
    - [[URL](https://aclanthology.org/2021.trustnlp-1.5/)]
- **XINA: Explainable Instance Alignment Using Dominance Relationship** [ IEEE TKDE, Volume 32]
    - [[URL](https://ieeexplore.ieee.org/document/8540085)]

### Link Prediction
- **An Approach Based on Semantic Similarity to Explaining Link Predictions on Knowledge Graphs** [WI-IAT '21]
  - [[URL](https://dl.acm.org/doi/10.1145/3486622.3493956)] [[GitHub](https://github.com/pierulohacker/SemanticCrossE/tree/master/explanation)]
- **An Interpretable Knowledge Transfer Model for Knowledge Base Completion** [ACL '17]
  - [[URL](https://arxiv.org/abs/1704.05908)]
- **CAKE: A Scalable Commonsense-Aware Framework For Multi-View Knowledge Graph Completion** [ACL '22]
  - [[URL](https://arxiv.org/abs/2202.13785)] [[GitHub](https://github.com/ngl567/CAKE)]
- **CogKR: Cognitive Graph for Multi-Hop Knowledge Reasoning** [IEEE TKDE, Volume 35]
  - [[URL](https://ieeexplore.ieee.org/document/9512424)] [[GitHub](https://github.com/THUDM/CogKR)]
- **Collaborative Policy Learning for Open Knowledge Graph Reasoning** [EMNLP '19]
  - [[URL](https://arxiv.org/abs/1909.00230)] [[GitHub](https://github.com/INK-USC/CPL)]
- **Contextual relation embedding and interpretable triplet capsule for inductive relation prediction** [Neurocomputing, Volume 505]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0925231222008992)]
- **DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning** [EMNLP '17]
  - [[URL](https://arxiv.org/abs/1707.06690)] [[GitHub](https://github.com/xwhan/DeepPath)]
- **DensE: An enhanced non-commutative representation for knowledge graph embedding with adaptive semantic hierarchy** [Neurocomputing, Volume 476]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0925231221019342)]
- **Differentiable Learning of Logical Rules for Knowledge Base Reasoning** [NIPS '17]
  - [[URL](https://arxiv.org/abs/1702.08367)] 
- **DisenKGAT: Knowledge Graph Embedding with Disentangled Graph Attention Network** [CIKM '21]
  - [[URL](https://dl.acm.org/doi/10.1145/3459637.3482424)] [[GitHub](https://github.com/junkangwu/DisenKGAT)]
- **DRUM: End-To-End Differentiable Rule Mining On Knowledge Graphs** [NIPS '19]
  - [[URL](https://arxiv.org/abs/1911.00055)] 
- **End-to-end Differentiable Proving** [NIPS '17]
  - [[URL](https://papers.nips.cc/paper/2017/hash/b2ab001909a8a6f04b51920306046ce5-Abstract.html)] 
- **Explainable GNN-Based Models over Knowledge Graphs** [ICLR '22]
  - [[URL](https://openreview.net/forum?id=CrCvGNHAIrz)]
- **Explainable Link Prediction for Emerging Entities in Knowledge Graphs** [ISWC '20]
  - [[URL](https://arxiv.org/abs/2005.00637)] [[GitHub](https://github.com/kingsaint/InductiveExplainableLinkPrediction)]
- **Explaining Link Prediction Systems based on Knowledge Graph Embeddings** [SIGMOD '22]
  - [[URL](https://dl.acm.org/doi/10.1145/3514221.3517887)] [[GitHub](https://github.com/AndRossi/Kelpie)]
- **Explaining Neural Matrix Factorization with Gradient Rollback** [AAAI '21]
  - [[URL](https://arxiv.org/abs/2010.05516)] [[GitHub](https://github.com/carolinlawrence/gradient-rollback)]
- **Fine-grained relational learning for few-shot knowledge graph completion** [ACM SIGAPP Applied Computing Review, Volume 22]
  - [[URL](https://dl.acm.org/doi/10.1145/3570733.3570735)]
- **Fusing topology contexts and logical rules in language models for knowledge graph completion** [Information Fusion, Volume 90]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S1566253522001592)]
- **Go for a Walk and Arrive at the Answer: Reasoning Over Paths in Knowledge Bases using Reinforcement Learning** [ICLR '18]
  - [[URL](https://arxiv.org/abs/1711.05851)] [[GitHub](https://github.com/shehzaadzd/MINERVA)]
- **Graph Intention Neural Network for Knowledge Graph Reasoning** [IJCNN '22]
  - [[URL](https://ieeexplore.ieee.org/document/9892730)]
- **HiAM: A Hierarchical Attention based Model for knowledge graph multi-hop reasoning** [Neural Networks, Volume 143]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0893608021002409)]
- **HopfE: Knowledge Graph Representation Learning using Inverse Hopf Fibrations** [CIKM '21]
  - [[URL](https://dl.acm.org/doi/10.1145/3459637.3482263)] [[GitHub](https://github.com/ansonb/HopfE)]
- **Influence Functions for Interpretable link prediction in Knowledge Graphs for Intelligent Environments** [SpliTech '22]
  - [[URL](https://ieeexplore.ieee.org/abstract/document/9854264)] [[GitHub](https://github.com/unai-zulaika/KGInfluence)]
- **Interaction Embeddings for Prediction and Explanation in Knowledge Graphs** [WSDM '19]
  - [[URL](https://dl.acm.org/doi/10.1145/3289600.3291014)] [[GitHub](https://github.com/wencolani/CrossE)]
- **Interpretable Graph Convolutional Neural Networks for Inference on Noisy Knowledge Graphs** [NIPS '18 ML4H Workshop]
  - [[URL](https://arxiv.org/abs/1812.00279)]
- **Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications** [NAACL '19]
  - [[URL](https://arxiv.org/abs/1905.00563)] [[GitHub](https://github.com/pouyapez/criage)]
- **Iterative rule-guided reasoning over sparse knowledge graphs with deep reinforcement learning** [Information Processing & Management, Volume 59]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0306457322001492)]
- **Joint semantics and data-driven path representation for knowledge graph reasoning** [Neurocomputing, Volume 483]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0925231222001515)]
- **Knowledge Graph Embedding in E-commerce Applications: Attentive Reasoning, Explanations, and Transferable Rules** [IJCKG '21]
  - [[URL](https://dl.acm.org/doi/abs/10.1145/3502223.3502232)] 
- **Knowledge Graph Reasoning with Relational Digraph** [WWW '22]
  - [[URL](https://arxiv.org/abs/2108.06040)] [[GitHub](https://github.com/LARS-research/RED-GNN)]
- **Learning Collaborative Agents with Rule Guidance for Knowledge Graph Reasoning** [EMNLP '20]
  - [[URL](https://arxiv.org/abs/2005.00571)] [[GitHub](https://github.com/derenlei/KG-RuleGuider)]
- **Learning to Walk across Time for Interpretable Temporal Knowledge Graph Completion** [KDD '21]
  - [[URL](https://dl.acm.org/doi/10.1145/3447548.3467292)] [[GitHub](https://github.com/jaehunjung1/T-GAP)]
- **Logic and Commonsense-Guided Temporal Knowledge Graph Completion** [AAAI '23]
  - [[URL](https://arxiv.org/abs/2211.16865)] [[GitHub](https://github.com/ngl567/LCGE)]
- **METransE: Manifold-like mechanism enhanced embedding for reasoning over knowledge graphs** [Expert Systems with Applications, Volume 209]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0957417422014245)]
- **Modeling Paths for Explainable Knowledge Base Completion** [ACL '19 BlackboxNLP Workshop]
  - [[URL](https://aclanthology.org/W19-4816/)] [[GitHub](https://github.com/JosuaStadelmaier/CPM)]
- **Negative sampling and rule mining for explainable link prediction in knowledge graphs** [Knowledge-Based Systems, Volume 250]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0950705122005342)] 
- **Reasoning on Knowledge Graphs with Debate Dynamics** [AAAI '20]
  - [[URL](https://ojs.aaai.org//index.php/AAAI/article/view/6600)] [[GitHub](https://github.com/m-hildebrandt/R2D2)]
- **Reinforced Anytime Bottom Up Rule Learning for Knowledge Graph Completion** [arXiv '20]
  - [[URL](https://arxiv.org/abs/2004.04412)] [[URL](https://web.informatik.uni-mannheim.de/AnyBURL/)]
- **Relational Message Passing for Knowledge Graph Completion** [KDD '21]
  - [[URL](https://dl.acm.org/doi/10.1145/3447548.3467247)] [[GitHub](https://github.com/hwwang55/PathCon)]
- **RNNLogic: Learning Logic Rules for Reasoning on Knowledge Graphs** [ICLR '21]
  - [[URL](https://arxiv.org/abs/2010.04029)] [[GitHub](https://github.com/DeepGraphLearning/RNNLogic)]
- **Rule-Guided Compositional Representation Learning on Knowledge Graphs** [AAAI '20]
  - [[URL](https://arxiv.org/abs/1911.08935)] [[GitHub](https://github.com/ngl567/RPJE)]
- **SAFRAN: An interpretable, rule-based link prediction method outperforming embedding models** [AKBC '21]
  - [[URL](https://arxiv.org/abs/2109.08002)] [[GitHub](https://github.com/OpenBioLink/SAFRAN)]
- **Self-Supervised Learning of Contextual Embeddings for Link Prediction in Heterogeneous Networks** [WWW '21]
  - [[URL](https://dl.acm.org/doi/10.1145/3442381.3450060)] [[GitHub](https://github.com/pnnl/SLICE)]
- **SQUIRE: A Sequence-to-sequence Framework for Multi-hop Knowledge Graph Reasoning** [EMNLP '22]
  - [[URL](https://arxiv.org/abs/2201.06206)] [[GitHub](https://github.com/bys0318/SQUIRE)]
- **Step by step: A hierarchical framework for multi-hop knowledge graph reasoning with reinforcement learning** [Knowledge-Based Systems, Volume 248]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0950705122004026)] [[GitHub](https://github.com/CC1st/step-by-step-mindspore)] [[GitHub](https://github.com/AnneZhu1020/Step-by-step)]
- **Supervised Knowledge Aggregation for Knowledge Graph Completion** [ESWC '22]
  - [[URL](https://link.springer.com/chapter/10.1007/978-3-031-06981-9_5)] [[GitHub](https://github.com/Nzteb/latent-rules)]
- **TAGAT: Type-Aware Graph Attention neTworks for reasoning over knowledge graphs** [Knowledge-Based Systems, Volume 233]
  - [[URL](https://www.sciencedirect.com/science/article/pii/S0950705121007620)]
- **Theoretical Rule-based Knowledge Graph Reasoning by Connectivity Dependency Discovery** [IJCNN '22]
  - [[URL](https://ieeexplore.ieee.org/document/9891938)]
- **TimeTraveler: Reinforcement Learning for Temporal Knowledge Graph Forecasting** [EMNLP '21]
  - [[URL](https://arxiv.org/abs/2109.04101)] [[GitHub](https://github.com/JHL-HUST/TITer/)]
- **TLogic: Temporal Logical Rules for Explainable Link Forecasting on Temporal Knowledge Graphs** [AAAI '22]
  - [[URL](https://ojs.aaai.org/index.php/AAAI/article/view/20330)] [[GitHub](https://github.com/liu-yushan/TLogic)]
- **Towards Learning Instantiated Logical Rules from Knowledge Graphs** [arXiv '20]
  - [[URL](https://arxiv.org/abs/2003.06071)] [[GitHub](https://github.com/irokin/GPFL)]
- **xERTE: Explainable Reasoning on Temporal Knowledge Graphs for Forecasting Future Links** [ICLR '21]
  - [[URL](https://arxiv.org/abs/2012.15537)] [[GitHub](https://github.com/TemporalKGTeam/xERTE)]
- **XTransE: Explainable Knowledge Graph Embedding for Link Prediction with Lifestyles in e-Commerce** [JIST '19]
  - [[URL](https://link.springer.com/chapter/10.1007/978-981-15-3412-6_8)]

### Ontology Evolution
- **Multi-domain and Explainable Prediction of Changes in Web Vocabularies** [K-CAP '21]
  - [[URL](https://dl.acm.org/doi/10.1145/3460210.3493583)] [[GitHub](https://github.com/albertmeronyo/ConceptDrift)]

### Inconsistency Detection
- **Fast Computation of Explanations for Inconsistency in Large-Scale Knowledge Graphs** [WWW '20]
  - [[URL](https://dl.acm.org/doi/abs/10.1145/3366423.3380014)] [[GitHub](https://github.com/boschresearch/kg_inconsistency_explanation)]

## Cite

```text
@inproceedings{zhang-et-al-2023-towards,
  author       = {Bohui Zhang and
                  Albert Mero{\~{n}}o{-}Pe{\~{n}}uela and
                  Elena Simperl},
  editor       = {Paul Lukowicz and
                  Sven Mayer and
                  Janin Koch and
                  John Shawe{-}Taylor and
                  Ilaria Tiddi},
  title        = {{Towards Explainable Automatic Knowledge Graph Construction with Human-in-the-Loop}},
  booktitle    = {{HHAI} 2023: Augmenting Human Intellect - Proceedings of the Second
                  International Conference on Hybrid Human-Artificial Intelligence,
                  June 26-30, 2023, Munich, Germany},
  series       = {Frontiers in Artificial Intelligence and Applications},
  volume       = {368},
  pages        = {274--289},
  publisher    = {{IOS} Press},
  year         = {2023},
  url          = {https://doi.org/10.3233/FAIA230091},
  doi          = {10.3233/FAIA230091},
  timestamp    = {Fri, 07 Jul 2023 23:30:40 +0200},
  biburl       = {https://dblp.org/rec/conf/hhai/ZhangMS23.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
