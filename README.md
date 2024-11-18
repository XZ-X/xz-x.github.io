# Xiangzhe Xu

<img src="IMG_4550.jpg" width="200"/>

I’m Xiangzhe. I’m a Ph.D. student at Purdue University advised by Prof. [Xiangyu Zhang](https://www.cs.purdue.edu/homes/xyzhang/).
My research interest lies in the intersection of program analysis and machine learning models for code. 
I explore code quality assurance with software engineering practices. For example, I measure and [mitigate biases in a code language model inspired by metamorphic testing](https://dl.acm.org/doi/pdf/10.1145/3597926.3598121); I develop [a proactive code model security technique inspired by scenario-based testing](https://github.com/XZ-X/xz-x.github.io/blob/master/SecAlign.pdf).
Besides model quality assurance, I believe formulating program semantics is a key for better code models. My exploration ranges from lower-level semantics, such as formal semantics ([CompCertELF](https://dl.acm.org/doi/pdf/10.1145/3428265)), probabilistic execution semantics([PEM](https://arxiv.org/pdf/2308.15449.pdf)), to higher-level semantics that reflects developers’ abstraction ([GenNm](https://arxiv.org/abs/2306.02546),[ProRec](https://arxiv.org/abs/2405.19581v1)).

<!--
I'm Xiangzhe, a Ph.D. student at Purdue University, advised by Prof. [Xiangyu Zhang](https://www.cs.purdue.edu/homes/xyzhang/). I obtained my B.Eng. degree from Nanjing University.
My research interest focuses on combining machine learning techniques with binary program analysis.
Specifically, I am working on recovering high-level information (e.g., program behaviors, variable names, types) from lower-level programs (e.g., stripped binary programs).
I use program analysis to construct better features from programs (e.g., [input/output values reflecting dynamic program behaviors](pem.pdf), [state machine reflecting input specifications](https://www.usenix.org/system/files/usenixsecurity23-shi-qingkai.pdf)); and enhance the performance of machine learning models with program analysis techniques (e.g., making binary program models more robust by [preventing models emphasizing on binary instructions that are not import for program semantics](https://dl.acm.org/doi/pdf/10.1145/3597926.3598121), improving the performance of LLM on recovering variable names from binary programs by [formulating name recovery as a type-inference like task](https://arxiv.org/pdf/2306.02546.pdf)).

-->

Email: xzx@purdue.edu


## Publications

### Code Model Quality Assurance

**SecAlign: Fortifying Code LLMs with Proactive Security Alignment**, Xiangzhe Xu*, Zian Su*, Jinyao Guo, Kaiyuan Zhang, Zhenting Wang, Xiangyu Zhang. [PDF](https://github.com/XZ-X/xz-x.github.io/blob/master/SecAlign.pdf)

**Improving Binary Code Similarity Transformer Models by Semantics-Driven Instruction Deemphasis**, Xiangzhe Xu, Shiwei Feng, Yapeng Ye, Guangyu Shen, Zian Su, Siyuan Cheng, Guanhong Tao, Qingkai Shi, Zhuo Zhang, and Xiangyu Zhang. The 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA'23). [PDF](https://dl.acm.org/doi/pdf/10.1145/3597926.3598121)

### Program Semantics Formulation

**Symbol Preference Aware Generative Models for Recovering Variable Names from Stripped Binary**, Xiangzhe Xu, Zhuo Zhang, Zian Su, Ziyang Huang, Shiwei Feng, Yapeng Ye, Nan Jiang, Danning Xie Siyuan Cheng, Lin Tan, Xiangyu Zhang. [PDF](https://arxiv.org/pdf/2306.02546)

**Source Code Foundation Models are Transferable Binary Analysis Knowledge Bases**, Zian Su, **Xiangzhe Xu**, Ziyang Huang, Kaiyuan Zhang, Xiangyu Zhang.  NeurIPS'2024. [PDF](https://arxiv.org/pdf/2405.19581v2)


**Codeart: Better code models by attention regularization when symbols are lacking**, Zian Su, **Xiangzhe Xu**, Ziyang Huang, Zhuo Zhang, Yapeng Ye, Jianjun Huang, Xiangyu Zhang. The ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE'24). [PDF](https://dl.acm.org/doi/pdf/10.1145/3643752)

**PEM: Representing Binary Program Semantics for Similarity Analysis via A Probabilistic Execution Model**, Xiangzhe Xu\*, Zhou Xuan\*, Shiwei Feng, Siyuan Cheng, Yapeng Ye, Qingkai Shi, Guanhong Tao, Le Yu, Zhuo Zhang, Xiangyu Zhang. The ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (FSE'23). [PDF](pem.pdf), [Full-length version](https://arxiv.org/pdf/2308.15449.pdf)


**CompCertELF: Verified Separate Compilation of C Programs into ELF Object Files**, Yuting Wang, **Xiangzhe Xu**, Pierre Wilke, Zhong Shao.
The 2020 ACM International Conference on Object-Oriented Programming, Systems, Languages, and Applications (OOPSLA'20). [PDF](https://dl.acm.org/doi/pdf/10.1145/3428265)


### Program Analysis and Verification

**LLMDFA:Analyzing Dataflow in Code with Large Language Models**, Chengpeng Wang, Wuqi Zhang, Zian Su, **Xiangzhe Xu**, Xiaoheng Xie, Xiangyu Zhang. NeurIPS'2024. [PDF](https://chengpeng-wang.github.io/publications/LLMDFA_NeurIPS2024.pdf)

**Sanitizing Large Language Models in Bug Detection with Data-Flow**, Chengpeng Wang, Wuqi Zhang, Zian Su, **Xiangzhe Xu**, Xiangyu Zhang. EMNLP'2024, [PDF](https://chengpeng-wang.github.io/publications/LLMSAN_EMNLP2024.pdf)

**ROCAS: Root Cause Analysis of Autonomous Driving Accidents via Cyber-Physical Co-mutation**, Shiwei Feng, Yapeng Ye, Qingkai Shi, Zhiyuan Cheng, **Xiangzhe Xu**, Siyuan Cheng, Hongjun Choi, Xiangyu Zhang. IEEE/ACM International Conference on Automated Software Engineering (ASE 2024). 🎖 **ACM SIGSOFT Distinguished Paper Award** [PDF](https://arxiv.org/pdf/2409.07774)

**ParDiff: Practical Static Differential Analysis of Network Protocol Parsers**, Mingwei Zheng, Qingkai Shi, Xuwei Liu, **Xiangzhe Xu**, Le Yu, Congyu Liu, Guannan Wei, Xiangyu Zhang. The ACM SIGPLAN Conference on Object Oriented Programming, Systems, Languages, and Applications (OOPSLA 2024). 🎖 **ACM SIGPLAN Distinguished Paper Award** [PDF](https://zmw12306.github.io/files/oopsla.pdf)

**Extracting Protocol Format as State Machine via Controlled Static Loop Analysis**, Qingkai Shi, **Xiangzhe Xu**, Xiangyu Zhang. The USENIX Security Symposium (USENIX'23). [PDF](https://www.usenix.org/system/files/usenixsecurity23-shi-qingkai.pdf)

**Automatic Generation and Validation of Instruction Encoders and Decoders**, Xiangzhe Xu, Jinhua Wu, Yuting Wang*, Zhenguo Yin and Pengfei Li.
The 33rd International Conference on Computer-Aided Verification (CAV'21). [PDF](https://link.springer.com/content/pdf/10.1007%2F978-3-030-81688-9_34.pdf)

**CPC: Automatically Classifying and Propagating Natural Language Comments via Program Analysis**, Juan Zhai, **Xiangzhe Xu**, Yu Shi, Guanhong Tao, Minxue Pan, Shiqing Ma, Lei Xu, Weifeng Zhang, Lin Tan, Xiangyu Zhang 
Proceedings of the 42nd International Conference on Software Engineering (ICSE'20). [PDF](https://dl.acm.org/doi/pdf/10.1145/3377811.3380427) 

## Services

Review: ACM Transactions on Software Engineering and Methodology(TOSEM)

Artifact Evaluation: ACM SIGPLAN Conference on Programming Language Design and Implementation (PLDI'24), IEEE/ACM International Symposium on Code Generation and Optimization(CGO'24-25), International Symposium on Software Testing and Analysis (ISSTA'24), ACM Conference on Computer and Communications Security (CCS'23)

The 42nd International Conference on Software Engineering(ICSE'20) Track Scheduling co-Chair

<!-- ### Links to my friends

[Han Zhou](https://zhouhan760503.github.io/)(in Chinese),
[Yaoming Wen](https://wym0120.github.io)(in Chinese),
[Yihui Wang](https://wyhfanofariajzh.com)(in Chinese),
[Yuqing Yang](https://frostwing98.com),
[Yuchao Lin](https://kruskallin.github.io) -->
