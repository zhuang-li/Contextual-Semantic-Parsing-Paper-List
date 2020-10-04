# Context Dependent Semantic Parsing: Awesome Paper List
It is currently an emerging field. Welcome to contribute!
## Survey 

## Leaderboard
- **SParC 1.0** [[url]](https://yale-lily.github.io/sparc)
- **CoSQL 1.0** [[url]](https://yale-lily.github.io/cosql)
## Datasets
Not all the datasets are released on their papers. For some datasets, you may need to email the author to acquire them.
### Non-interactive Datasets
- **Evaluation of spoken language systems: The atis domain.** (1990), Patti J Price. [[paper]](https://www.aclweb.org/anthology/H90-1020.pdf) [[data]](https://catalog.ldc.upenn.edu/LDC2019T04)
- **Search-based Neural Structured Learning for Sequential Question Answering.** (ACL 2017), Mohit Iyyer, Wen-tau Yih, and Ming-Wei Chan [[paper]](https://www.aclweb.org/anthology/P17-1167.pdf) [[data]](https://github.com/microsoft/DynSP)
- **Sparc: Cross-domain semantic parsing in context.** (ACL 2019), Tao Yu, Rui Zhang, Michihiro Yasunaga, Yi Chern Tan, Xi Victoria Lin, Suyi Li, Heyang Er, Irene Li, Bo Pang,Tao Chen, et al. [[paper]](https://arxiv.org/pdf/1906.02285.pdf) [[data]](https://yale-lily.github.io/sparc)
- **Context-dependent semantic parsing for time expressions.** (ACL 2014) Kenton Lee, Yoav Artzi, Jesse Dodge, and Luke Zettlemoyer. [[paper]](https://www.aclweb.org/anthology/P14-1135.pdf) [[data]](https://bitbucket.org/kentonl/uwtime/src/master/)
- **Context-dependent semantic parsing over temporally structured data.** (NAACL 2019) Charles Chen and Razvan Bunescu. [[paper]](https://www.aclweb.org/anthology/N19-1360.pdf) [[data]](https://github.com/charleschen1015/SemanticParsing)
- **Simpler context-dependent logical forms via model projections.** (ACL 2016) Reginald Long, Panupong Pasupat, and Percy Liang. [[paper]](https://arxiv.org/pdf/1606.05378.pdf) [[data]](https://nlp.stanford.edu/projects/scone/)
- **Complex sequential question answering: Towards learning to converse over linked question answer pairs with a knowledge graph.** (AAAI 2018) Amrita Saha, Vardaan Pahuja, Mitesh M Khapra, Karthik Sankaranarayanan, and Sarath Chandar. [[paper]](https://arxiv.org/pdf/1801.10314.pdf) [[data]](https://amritasaha1812.github.io/CSQA/)
### Interactive Datasets
- **A new corpus and imitation learning framework for context-dependent semantic parsing.** (TACL 2014) Andreas Vlachos and Stephen Clark. [[paper]](https://www.aclweb.org/anthology/Q14-1042.pdf) [[data]](https://sites.google.com/site/andreasvlachos/resources)
- **Parsing natural language conversations using contextual cues.** (IJCAI 2019) Shashank Srivastava, Amos Azaria, and Tom M Mitchell. [[paper]](https://www.ijcai.org/Proceedings/2017/0571.pdf)
- **Cosql: A conversational text-to-sql challenge towards cross-domain natural language interfaces to databases.** (EMNLP 2019) Tao Yu, Rui Zhang, He Yang Er, Suyi Li, Eric Xue, Bo Pang, Xi Victoria Lin, Yi Chern Tan, Tianze Shi, Zihan Li, et al. [[paper]](https://arxiv.org/pdf/1909.05378.pdf) [[data]](https://yale-lily.github.io/cosql)
## Methods
There is a lot of work going on but without paper released. We will update this list once those work on contextual semantic parsing is published.
### Symbolic Approaches
- **Learning context-dependent mappings from sentences to logical form.** (ACL 2019) Luke S Zettlemoyer and Michael Collins. [[paper]](https://www.aclweb.org/anthology/P09-1110.pdf)
- **Parsing natural language conversations using contextual cues.** (IJCAI 2019) Shashank Srivastava, Amos Azaria, and Tom M Mitchell. [[paper]](https://www.ijcai.org/Proceedings/2017/0571.pdf)
- **Simpler context-dependent logical forms via model projections.** (ACL 2016) Reginald Long, Panupong Pasupat, and Percy Liang. [[paper]](https://arxiv.org/pdf/1606.05378.pdf)
### Neural Approaches
- **Learning to map context-dependent sentences to executable formal queries.** (NAACL 2018) Alane Suhr, Srinivasan Iyer, and Yoav Artzi. [[paper]](https://arxiv.org/pdf/1804.06868.pdf) [[code]](https://github.com/lil-lab/atis)
- **Situated mapping of sequential instructions to actions with single-step reward observation.** (ACL 2018) Alane Suhr and Yoav Artzi. [[paper]](https://www.aclweb.org/anthology/P18-1193.pdf) [[code]](https://github.com/lil-lab/scone)
- **Editing-based sql query generation for cross-domain context-dependent questions.** (EMNLP 2019) Rui Zhang, Tao Yu, He Yang Er, Sungrok Shim, Eric Xue, Xi Victoria Lin, Tianze Shi, Caiming Xiong, Richard Socher, and Dragomir Radev. [[paper]](https://arxiv.org/pdf/1909.00786.pdf) [[code]](https://github.com/ryanzhumich/editsql)
- **A pointer network architecture for context-dependent semantic parsing.** (ALTA 2019) Xuanli He, Quan Hung Tran, and Gholamreza Haffari. [[paper]](https://www.aclweb.org/anthology/U19-1013.pdf)
- **How far are we from effective context modeling? an exploratory study on semantic parsing in context.** (IJCAI 2020) Qian Liu, Bei Chen, Jiaqi Guo, Jian-Guang Lou, Bin Zhou, and Dongmei Zhang. [[paper]](https://www.ijcai.org/Proceedings/2020/0495.pdf) [[code]](https://github.com/microsoft/ContextualSP/tree/master/semantic_parsing_in_context)
- **From language to programs: Bridging reinforcement learning and maximum marginal likelihood.** (ACL 2017) Kelvin Guu, Panupong Pasupat, Evan Zheran Liu, and Percy Liang. [[paper]](https://arxiv.org/pdf/1704.07926.pdf) [[code]](https://github.com/kelvinguu/lang2program)
- **Context-dependent semantic parsing over temporally structured data.** (2019) Charles Chen and Razvan Bunescu. [[paper]](https://www.aclweb.org/anthology/N19-1360.pdf) [[code]](https://github.com/charleschen1015/SemanticParsing)
### Neural-Symbolic Approaches
- **How far are we from effective context modeling? an exploratory study on semantic parsing in context.** (IJCAI 2020) Qian Liu, Bei Chen, Jiaqi Guo, Jian-Guang Lou, Bin Zhou, and Dongmei Zhang. [[paper]](https://www.ijcai.org/Proceedings/2020/0495.pdf) [[code]](https://github.com/microsoft/ContextualSP/tree/master/semantic_parsing_in_context)
- **Multi-task learning for conversational question answering over a large-scale knowledge base.** (EMNLP 2019) Tao Shen, Xiubo Geng, Tao Qin, Daya Guo, Duyu Tang, Nan Duan, Guodong Long, and Daxin Jiang. [[paper]](https://www.aclweb.org/anthology/D19-1248.pdf) [[code]](https://github.com/taoshen58/MaSP)
- **Context-dependent semantic parsing over temporally structured data.** (2019) Charles Chen and Razvan Bunescu. [[paper]](https://www.aclweb.org/anthology/N19-1360.pdf) [[code]](https://github.com/charleschen1015/SemanticParsing)
- **Search-based Neural Structured Learning for Sequential Question Answering.** (ACL 2017), Mohit Iyyer, Wen-tau Yih, and Ming-Wei Chan [[paper]](https://www.aclweb.org/anthology/P17-1167.pdf) [[code]](https://github.com/microsoft/DynSP)
- **Knowledge-aware conversational semantic parsing over web tables.** (NLPCC 2019) Yibo Sun, Duyu Tang, Jingjing Xu, Nan Duan, Xiaocheng Feng, Bing Qin, Ting Liu, and Ming Zhou. [[paper]](https://arxiv.org/pdf/1809.04271.pdf)
- **Dialog-to-action: Conversational question answering over a large-scale knowledge base.** (Neurips 2018) Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, and Jian Yin. [[paper]](https://papers.nips.cc/paper/7558-dialog-to-action-conversational-question-answering-over-a-large-scale-knowledge-base.pdf) [[code]](https://github.com/guoday/Dialog-to-Action)
- **Coupling retrieval and meta-learning for context-dependent semantic parsing.** (ACL 2019) Daya Guo, Duyu Tang, Nan Duan, Ming Zhou, and Jian Yin. [[paper]](https://arxiv.org/pdf/1906.07108.pdf)
