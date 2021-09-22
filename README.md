# Recent Advances in AI4CODE.

A niche collection of AI4Code papers and other resources (dataset, tutorial, etc.), this list will focus mostly on the papers that use pre-trained models and deep learning techniques for programming languages processing. There are also other collections that cover a wider range of AI4Code papers, such as:
- https://ml4code.github.io/
- https://github.com/src-d/awesome-machine-learning-on-source-code (Due to the lack of maintainers, this collection may be obsolete).
## Academic Conferences that usually published AI4Code papers:
#### Software Enginnering/Programming Languages
The emphasis is on combining program analysis and deep learning to solve novel software engineering/programming languages task. In most cases, strong empirical results are required. Typically, new datasets are usually curated.
- [Interational Conference on Software Engineering (ICSE)](http://www.icse-conferences.org/)
- [Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE)](https://www.esec-fse.org/)
- [Automated Software Engineering (ASE)](https://conf.researchr.org/home/ase-2021).
- [Programming Language Design and Implementation (PLDI)](https://conf.researchr.org/series/pldi)
#### Machine Learning/AI
The emphasis is on desigining novel neural network architectures to process code. Typically, new datasets are usually curated.
- [Association for the Advancement of Artificial Intelligence (AAAI)](https://aaai.org/Conferences/conferences.php)
- [Interational Conference in Machine Learning (ICML)](https://icml.cc/)
- [International Conference on Neural Information Processing Systems(NeurIPS)](https://nips.cc/)
- [International Conference on Learning Representation (ICLR)](https://iclr.cc/)

#### Natural Language Processing
The emphasis is on applying NLP techniques for code, and the evaluation is primarily on running the models on known benchmark datasets; unique tasks are rarely introduced.
- [Empirical Methods in Natural Language Processing (EMNLP)](https://aclanthology.org/venues/emnlp/)
- [North American Chapter of the Association for Computational Linguistics (NAACL)](https://aclanthology.org/venues/naacl/)


## Pretrained Models for Code
- [CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation](https://arxiv.org/pdf/2109.00859.pdf) - Yue Wang, Weishi Wang, Shafiq Joty, Steven C.H. Hoi (EMNLP 2021) (***CodeT5***).  
- [CodeBERT:A Pre-Trained Model for Programming and Natural Language](https://arxiv.org/pdf/2002.08155.pdf) - Zhangyin Feng, Daya Guo, Duyu Tang, Nan Duan, Xiaocheng Feng, Ming Gong, Linjun Shou, Bing Qin, Ting Liu, Daxin Jiang, Ming Zhou (EMNLP 2020 Findings) (***CodeBERT***).
- [Learning and Evaluating Contextual Embedding of Source Code](https://arxiv.org/abs/2001.00059) - Aditya Kanade, Petros Maniatis, Gogul Balakrishnan, Kensen Shi. (ICML 2020) (***CuBERT***).
- [GraphCodeBERT: Pre-training Code Representations with Data Flow](https://arxiv.org/pdf/2009.08366.pdf) - Daya Guo, Shuo Ren, Shuai Lu, Zhangyin Feng, Duyu Tang, Shujie Liu, Long Zhou, Nan Duan, Alexey Svyatkovskiy, Shengyu Fu, Michele Tufano, Shao Kun Deng, Colin Clement, Dawn Drain, Neel Sundaresan, Jian Yin, Daxin Jiang, Ming Zhou (ICLR 2021) (***GraphCodeBERT***).
- [InferCode: Self-Supervised Learning of Code Representations by Predicting Subtrees](https://bdqnghi.github.io/files/ICSE_2021.pdf) -Nghi D. Q. BUI, Yijun YU, Lingxiao JIANG (ICSE 2021) (***InferCode***).
- [Self-Supervised Learning for Code Retrieval and Summarization through Semantic-Preserving Program Transformations](https://arxiv.org/pdf/2009.08366.pdf) - Nghi D. Q. BUI, Yijun YU, Lingxiao JIANG (SIGIR 2021) (***Corder***).
- [Unsupervised Translation of Programming Languages](https://arxiv.org/pdf/2006.03511.pdf) - Marie-Anne Lachaux, Baptiste Roziere, Lowik Chanussot, Guillaume Lample (NeurIPS 2020) (***Transcoder***).
- [Contrastive Code Representation Learning](https://arxiv.org/pdf/2007.04973.pdf) - 
Paras Jain, Ajay Jain, Tianjun Zhang, Pieter Abbeel, Joseph E. Gonzalez, Ion Stoica (arxiv 2020) (***ContraCode***).
- [CoTexT: Multi-task Learning with Code-Text Transformer](https://arxiv.org/abs/2105.08645), Long Phan, Hieu Tran, Daniel Le, Hieu Nguyen, James Anibal, Alec Peltekian, Yanfang Ye (arXiv 2021) (***CoTexT***)
- [How could Neural Networks understand Programs?](https://arxiv.org/pdf/2105.04297.pdf), Dinglan Peng, Shuxin Zheng, Yatao Li, Guolin Ke, Di He, Tie-Yan Liu (ICML 2021) (***OSCAR***)
- [Unified Pre-training for Program Understanding and Generation](https://aclanthology.org/2021.naacl-main.211.pdf), Wasi Uddin Ahmad, Saikat Chakraborty, Baishakhi Ray, Kai-Wei Chang (NAACL 2021) (***PLBART***).
- [Exploring Software Naturalness through Neural Language Models](https://arxiv.org/abs/2006.12641), Luca Buratti, Saurabh Pujar, Mihaela Bornea, Scott McCarley, Yunhui Zheng, Gaetano Rossiello, Alessandro Morari, Jim Laredo, Veronika Thost, Yufan Zhuang, Giacomo Domeniconi, (arXiv 2020) (***C-BERT***).
- [PYMT5: multi-mode translation of natural language and PYTHON code with transformers](https://arxiv.org/abs/2010.03150), Colin B. Clement, Dawn Drain, Jonathan Timcheck, Alexey Svyatkovskiy, Neel Sundaresan (EMNLP 2020) (***PYMT5***).
- [DOBF: A Deobfuscation Pre-Training Objective for Programming Languages](https://arxiv.org/abs/2102.07492), Baptiste Roziere, Marie-Anne Lachaux, Marc Szafraniec, Guillaume Lample, (arXiv 2021) (***DOBF***).
- [Studying the Usage of Text-To-Text Transfer Transformer to Support Code-Related Tasks](https://arxiv.org/abs/2102.02017), , Antonio Mastropaolo, Simone Scalabrino, Nathan Cooper, David Nader Palacio, Denys Poshyvanyk, Rocco Oliveto, Gabriele Bavota (ICSE 2021).
- [CodeTrans: Towards Cracking the Language of Silicone’s Code Through Self-Supervised Deep Learning and High Performance Computing](https://arxiv.org/abs/2104.02443), Ahmed Elnaggar, Wei Ding, Llion Jones, Tom Gibbs, Tamas Feher, Christoph Angerer, Silvia Severini, Florian Matthes, Burkhard Rost (arXiv 2021/04( (***CodeTrans***).
- [Disentangled Code Representation Learning for Multiple Programming Languages](https://aclanthology.org/2021.findings-acl.391.pdf),Jingfeng Zhang, Haiwen Hong, Yin Zhang, Yao Wan, Ye Liu, Yulei Sui (ACL-Fingings 2021) (***CODEDISEN***).
- [SYNCOBERT: Syntax-Guided Multi-Modal Contrastive Pre-Training for Code Representation](https://arxiv.org/pdf/2108.04556v3.pdf), Xin Wang, Yasheng Wang, Fei Mi, Pingyi Zhou, Yao Wan, Xiao Liu, Li Li, Hao Wu, Jin Liu, Xin Jiang, (arXiv 2021) (***SYNCOBERT***).


## Dataset and Benchmark
- [CodeSearchNet Challenge](https://github.com/github/CodeSearchNet).
- [IBM Project CodeNet](https://github.com/IBM/Project_CodeNet).
- [Semantic Parsing Text to SQL Challenge](https://yale-lily.github.io/spider).
- [CodeXGlue Benchmark](https://github.com/microsoft/CodeXGLUE).
- [APPS (Automated Programming Progress Standard)](https://github.com/hendrycks/apps).
- [Python Programming Puzzles](https://github.com/microsoft/PythonProgrammingPuzzles).
- [Big Clone Bench](https://github.com/clonebench/BigCloneBench).
- [Google Code Jam](https://github.com/Jur1cek/gcj-dataset).

## Talk and Tutorial
- [How Facebook use Machine Learning to increase developer's productivity](https://www.youtube.com/watch?v=S7VJzAhzPTU).
- [Machine Programming at Intel](https://www.youtube.com/watch?v=JMBEmUMSo8M).
- [ETH Zurich Workshop on Software Correctness and Reliability](https://www.youtube.com/channel/UCNDScEU0cJlOoWeqvg11hDw).
