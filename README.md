# A Collection of Tools, Papers and Recent Trendings in AI for Software (AI4SE, AI4Code).

A niche collection of AI4Code papers and other resources (dataset, tutorial, etc.). There are also other collections that cover a wider range of content about AI4Code, such as:
- https://ml4code.github.io/
- https://github.com/src-d/awesome-machine-learning-on-source-code (Due to the lack of maintainers, this collection may be obsolete).

## Tools/Products

A list of of AI coding tools (assistants, completion, refactoring, etc.).

### AI code completion tools

- [GitHub Copilot](https://github.com/features/copilot)
- [CodiumAI](https://www.codium.ai/)
- [Refact.ai](https://refact.ai/)
- [FauxPilot](https://github.com/fauxpilot/fauxpilot)
- [CodeComplete](https://codecomplete.ai)
- [Continue](https://continue.dev/)
- [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/)
- [Obsidian copilot auto completion](https://github.com/j0rd1smit/obsidian-copilot-auto-completion)
- [JetBrains AI](https://www.jetbrains.com/ai/)
  [Codeium](https://www.codeium.com/)
- [Tabnine](https://www.tabnine.com/)
- [Replit Ghostwriter](https://replit.com/site/ghostwriter)
- [GitLab Code Suggestions](https://docs.gitlab.com/ee/user/project/repository/code_suggestions.html)
- [Sourcegraph Cody](https://about.sourcegraph.com/cody)

### More General Coding Assistants

- [Replit Ghostwriter](https://replit.com/site/ghostwriter)
- [Cosine](https://ai.cosine.sh/)
- [Autodoc](https://github.com/context-labs/autodoc)
- [Sourcegraph Cody](https://about.sourcegraph.com/cody)
- [ZZZ Code AI](https://zzzcode.ai/)
- [StackSpot AI](https://ai.stackspot.com/)
- [Pixee](https://pixee.ai)
- [16x Prompt](https://prompt.16x.engineer/)
- [Cursor](https://www.cursor.sh/) (editor)
- [Wizi](https://github.com/wizi-ai/code-search)
- [Phind](https://www.phind.com/)
- [Safurai](https://www.safurai.com/)
- [CensusGPT](https://censusgpt.com/)

### ChatGPT in your editor
- [CodeGPT.nvim](https://github.com/dpayne/CodeGPT.nvim)
- [org-ai](https://github.com/rksm/org-ai)
- [Genie AI - ChatGPT - VS Code](https://github.com/ai-genie/chatgpt-vscode)

### LLM-powered natural language compilers 
- [Parsel 🐍](https://github.com/ezelikman/parsel)


## Academic
### Conferences
##### Software Enginnering/Programming Languages
The emphasis is on combining program analysis and deep learning to solve novel software engineering/programming languages task. In most cases, strong empirical results are required. Typically, new datasets are usually curated.
- [Interational Conference on Software Engineering (ICSE)](http://www.icse-conferences.org/)
- [Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE)](https://www.esec-fse.org/)
- [Automated Software Engineering (ASE)](https://conf.researchr.org/home/ase-2021).
- [Programming Language Design and Implementation (PLDI)](https://conf.researchr.org/series/pldi)
##### Machine Learning/AI
The emphasis is on desigining novel neural network architectures to process code. Typically, new datasets are usually curated.
- [Association for the Advancement of Artificial Intelligence (AAAI)](https://aaai.org/Conferences/conferences.php)
- [Interational Conference in Machine Learning (ICML)](https://icml.cc/)
- [International Conference on Neural Information Processing Systems(NeurIPS)](https://nips.cc/)
- [International Conference on Learning Representation (ICLR)](https://iclr.cc/)

##### Natural Language Processing
The emphasis is on applying NLP techniques for code, and the evaluation is primarily on running the models on known benchmark datasets; unique tasks are rarely introduced.
- [Empirical Methods in Natural Language Processing (EMNLP)](https://aclanthology.org/venues/emnlp/)
- [North American Chapter of the Association for Computational Linguistics (NAACL)](https://aclanthology.org/venues/naacl/)
- [Annual Meeting of the Association for Computational Linguistics (ACL)](https://2021.aclweb.org/)

### Papers (This list is a bit outdated, need to update)
#### Evaluate CodeLLMs
- [Large Language Models of Code Fail at Completing Code with Potential Bugs](https://arxiv.org/pdf/2306.03438.pdf) - Tuan Dinh, Jinman Zhao, Samson Tan, Renato Negrinho, Leonard Lausen, Sheng Zha, George Karypis.
- [Large Language Models Meet NL2Code: A Survey](https://arxiv.org/pdf/2212.09420.pdf) - Daoguang Zan, Bei Chen, Fengji Zhang, Dianjie Lu, Bingchao Wu, Bei Guan, Yongji Wang, Jian-Guang Lou (EMNLP 2023)

#### Techniques for Code Generation
- [SKCODER: A Sketch-based Approach for Automatic Code Generation)(https://arxiv.org/pdf/2302.06144.pdf) - Jia Allen Li, Yongmin Li, Ge Li, Zhi Jin, Yiyang Hao, Xing Hu

#### Repo-Level CodeLLMs
- [RepoFusion: Training Code Models to Understand Your Repository](https://arxiv.org/pdf/2306.10998.pdf) - Disha Shrivastava, Denis Kocetkov, Harm de Vries, Dzmitry Bahdanau, Torsten Scholak

#### Benchmarking CodeLLMs
- [XCODEEVAL: An Execution-based Large Scale Multilingual Multitask Benchmark for Code Understanding, Generation, Translation and Retrieval](https://arxiv.org/pdf/2303.03004v3.pdf) - Mohammad Abdullah Matin Khan, M Saiful Bari, Xuan Long Do, Weishi Wang, Md Rizwan Parvez, Shafiq Joty
- 
## Pretrained CodeLLMs
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
- [TreeBERT: A Tree-Based Pre-Trained Model for Programming Language](https://arxiv.org/abs/2105.12485), Xue Jiang, Zhuoran Zheng, Chen Lyu, Liang Li, Lei Lyu, (UAI 2021) (***TreeBERT***).
- [Empirical Study of Transformers for Source Code](https://arxiv.org/abs/2010.07987), Nadezhda Chirkova, Sergey Troshin (ESEC/FSE 2021).

## Dataset and Benchmark
- [CodeSearchNet Challenge](https://github.com/github/CodeSearchNet).
- [IBM Project CodeNet](https://github.com/IBM/Project_CodeNet).
- [Semantic Parsing Text to SQL Challenge](https://yale-lily.github.io/spider).
- [CodeXGlue Benchmark](https://github.com/microsoft/CodeXGLUE).
- [APPS (Automated Programming Progress Standard)](https://github.com/hendrycks/apps).
- [Python Programming Puzzles](https://github.com/microsoft/PythonProgrammingPuzzles).
- [Big Clone Bench](https://github.com/clonebench/BigCloneBench).
- [Google Code Jam](https://github.com/Jur1cek/gcj-dataset).
- [HumanEval][https://arxiv.org/abs/2107.03374]
- [SWE-Bench][https://github.com/princeton-nlp/SWE-bench]

## Talks and Tutorials
- [How Facebook uses Machine Learning to increase developer's productivity](https://www.youtube.com/watch?v=S7VJzAhzPTU).
- [Machine Programming at Intel](https://www.youtube.com/watch?v=JMBEmUMSo8M).
- [ETH Zurich Workshop on Software Correctness and Reliability](https://www.youtube.com/channel/UCNDScEU0cJlOoWeqvg11hDw).
- [Workshop on Natural Language Processing for Programming](https://nlp4prog.github.io/2021/)
- [KDD Workshop on Programming Language Processing](https://nlp4prog.github.io/2021/)

## Articles
- <a href="https://cacm.acm.org/magazines/2020/7/245690-your-wish-is-my-cmd/fulltext" target="_blank"> Automating the writing of code.</a>
- <a href="https://arxiv.org/pdf/1709.06182.pdf" target="_blank"> A Survey of Machine Learning for Big Code and Naturalness.</a>
- <a href="https://www.forbes.com/sites/moorinsights/2021/06/04/ibm-codenet-artificial-intelligence-that-can-program-computers-and-solve-a-100-billion-legacy-code-problem/?sh=153c91d16cdc" target="_blank"> Artificial Intelligence That Can Program Computers.</a>
- <a href="https://betanews.com/2023/12/04/software-testers-turn-to-ai-to-improve-productivity/" target="_blank"> Software testers turn to AI to improve productivity.</a>
- <a href="https://www.computerworld.com/article/3711404/heres-why-half-of-developers-will-soon-use-ai-augmented-software.html" target="_blank"> Half of developers will soon use AI-augmented software.</a>
- <a href="https://github.blog/2023-11-08-the-state-of-open-source-and-ai/" target="_blank"> State of AI in Software Development, Github.</a>
- <a href="https://arxiv.org/pdf/2306.15033.pdf" target="_blank"> Sea Change in Software Development: Economic and Productivity Analysis of the AI-Powered Developer Lifecycle, from Github and Havard Business Review.</a>
- <a href="https://www.watermelontools.com/post/reimagining-code-review-with-rag-to-save-us-from-lgtm" target="_blank"> WatermelonTools for AI-based Code Review.</a>
- <a href="https://cio.economictimes.indiatimes.com/news/artificial-intelligence/impact-of-genai-on-software-development/105405709" target="_blank"> Impact of AI on Software Development.</a>
- <a href="https://www.semafor.com/article/11/08/2023/githubs-ai-coding-assistant-copilot-is-a-moneymaker" target="_blank"> GitHub’s AI coding assistant, Copilot, is a moneymaker.</a>
- <a href="https://www.infoworld.com/article/3709191/is-chatgpt-writing-your-code-watch-out-for-malware.html" target="_blank"> Is ChatGPT writing your code? Watch out for malware.</a>
- <a href="https://www.ft.com/content/81db7c36-f9ae-496b-9dd4-971aefe6f9a9" target="_blank"> Microsoft pioneers use of generative AI in software — at a price .</a>
- <a href="https://blogs.sap.com/2023/11/02/why-sap-build-code-is-a-game-changer-for-sap-developers/" target="_blank"> SAP Build Code is a Game-Changer for SAP Developers .</a>
- <a href="https://learn.gitlab.com/ailgf/2023-devsecops-report-ai" target="_blank"> The State of AI in Software Development, Gitlab.</a>
- <a href="https://stackoverflow.blog/2023/10/12/integrating-ai-tools-into-your-workflow/" target="_blank"> Integrating AI tools into your workflow.</a>
- <a href="https://www.semafor.com/article/10/04/2023/ai-is-spurring-the-rise-of-the-novice-coder" target="_blank"> The rise of the novice coder: Can AI turn every employee into a developer?.</a>

