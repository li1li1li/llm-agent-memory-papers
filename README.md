### Long term memory agent  papers

动态更新工作中实现或者阅读过的llm的agent 的长记忆性质的相关论文和学习资料，也希望能为大模型agent相关行业的同学带来便利。 所有资料均来自于互联网，如有侵权，请联系我。

Email: luluyeye1@163.com

知乎同步有更新

## 目录

- ### survey


- Wu Y, Liang S, Zhang C, et al. From human memory to ai memory: A survey on memory mechanisms in the era of llms[J]. arXiv preprint arXiv:2504.15965, 2025.  [pdf](https://arxiv.org/abs/2504.15965)
- Zhang Z, Dai Q, Bo X, et al. A survey on the memory mechanism of large language model based agents[J]. ACM Transactions on Information Systems, 2024.[pdf](https://arxiv.org/abs/2404.13501)

### 用户调研

- Han S, Zhang Q, Yao Y, et al. LLM multi-agent systems: Challenges and open problems[J]. arXiv preprint arXiv:2402.03578, 2024.  [pdf](https://arxiv.org/abs/2402.03578)
- Jones B, Stemmler K, Su E, et al. Users' Expectations and Practices with Agent Memory[C]//Proceedings of the Extended Abstracts of the CHI Conference on Human Factors in Computing Systems. 2025: 1-8. [pdf](https://dl.acm.org/doi/abs/10.1145/3706599.3720158)

### memory架构与管理

*这类方法的核心在于探索如何构建、组织、更新和遗忘记忆，即关注记忆系统本身的设计。*

- **TiM**  Liu L, Yang X, Shen Y, et al. Think-in-memory: Recalling and post-thinking enable llms with long-term memory[J]. arXiv preprint arXiv:2311.08719, 2023. [pdf](https://arxiv.org/abs/2311.08719)
- **FireAct**  Chen B, Shu C, Shareghi E, et al. Fireact: Toward language agent fine-tuning[J]. arXiv preprint arXiv:2310.05915, 2023.  [pdf](https://arxiv.org/abs/2310.05915), [code](https://github.com/anchen1011/FireAct)
- Self-Controlled Memory (SCM)**  Wang B, Liang X, Yang J, et al. Enhancing large language model with self-controlled memory framework[J]. arXiv preprint arXiv:2304.13343, 2023.  [pdf](https://arxiv.org/abs/2304.13343), [code](https://github.com/wbbeyourself/SCM4LLMs)
- **Reflexion**  Shinn N, Cassano F, Labash B, et al. Reflexion: Language agents with verbal reinforcement learning, 2023[J]. URL https://arxiv. org/abs/2303.11366, 2023, 1.  [pdf](https://arxiv.org/abs/2303.11366), [code](https://github.com/noahshinn/reflexion)
- **RAP**  Kagaya T, Yuan T J, Lou Y, et al. Rap: Retrieval-augmented planning with contextual memory for multimodal llm agents[J]. arXiv preprint arXiv:2402.03610, 2024.[pdf](https://arxiv.org/abs/2402.03610), [code](https://github.com/PanasonicConnect/rap)
- **THEANINE**  Ong K T, Kim N, Gwak M, et al. Towards lifelong dialogue agents via timeline-based memory management[J]. arXiv preprint arXiv:2406.10996, 2024.  [pdf](https://aclanthology.org/2025.naacl-long.435/)
- **AriGraph**  Anokhin P, Semenov N, Sorokin A, et al. Arigraph: Learning knowledge graph world models with episodic memory for llm agents[J]. arXiv preprint arXiv:2407.04363, 2024.  [pdf](https://arxiv.org/abs/2407.04363), [code](https://github.com/AIRI-Institute/AriGraph)
- **MEMTRee**  Rezazadeh A, Li Z, Wei W, et al. From isolated conversations to hierarchical schemas: Dynamic tree memory representation for llms[J]. arXiv preprint arXiv:2410.14052, 2024. [pdf](https://arxiv.org/abs/2410.14052)
- **LOCOMO**  Maharana A, Lee D H, Tulyakov S, et al. Evaluating very long-term conversational memory of llm agents[J]. arXiv preprint arXiv:2402.17753, 2024. [pdf](https://arxiv.org/abs/2402.17753) , [code](https://github.com/snap-research/LoCoMo)
- **Agentic-RAG** Ravuru C, Sakhinana S S, Runkana V. Agentic retrieval-augmented generation for time series analysis[J]. arXiv preprint arXiv:2408.14484, 2024. [pdf](https://arxiv.org/abs/2408.14484)
- **SAGE** Liang X, He Y, Xia Y, et al. Self-evolving Agents with reflective and memory-augmented abilities[J]. arXiv preprint arXiv:2409.00872, 2024.   [pdf](https://arxiv.org/abs/2409.00872)
- **MEMLLM**  Modarressi A, Köksal A, Imani A, et al. Memllm: Finetuning llms to use an explicit read-write memory[J]. arXiv preprint arXiv:2404.11672, 2024. [pdf](https://arxiv.org/abs/2404.11672), [code](https://github.com/amodaresi/MemLLM)
- **VIMBANK**  Li K, Jing X, Jing C. Vector storage based long-term memory research on llm[J]. International Journal of Advanced Network, Monitoring and Controls, 2024. [[pdf](https://sciendo-parsed.s3.eu-central-1.amazonaws.com/6707978f5313275c67556b95/10.2478_ijanmc-2024-0029.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIA6AP2G7AKCMILP2VA%2F20250718%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20250718T094459Z&X-Amz-Expires=3600&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHEaDGV1LWNlbnRyYWwtMSJIMEYCIQD6k1MtOBq02aNodqfh7S2I7ePSmy4oSpvXYYvw9icc0gIhAPBl2JrUFzKn3lFcoE39Vcwj0JdJe2UMVUk1KG7Pk39xKsYFCIr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQAhoMOTYzMTM0Mjg5OTQwIgz6kqEP6sjlOUvvNlQqmgVFZGpx37iVAKAxkBCUHzUNvnMRc40wo05BJRyFjutcfEK86TTpH4%2FYnVwxSi%2FIOn8HA1jz7stteZAo3xC8PmPiv4QE1x4DYtAmcihUKDhyNuh9cmTByuEPcymX4DqNkwD9NJvdP%2F3RkPYMYQNUFY5gh%2Bw9CApM4jkjAc39RR%2BCMrG3SoiR9zx0Q2bbiwil2f1JT4FKsx6JC06P9UjKLu37qOeDRn7K6eOFFeMV%2B0SyjCkgDLneV61re7%2FP4CtRqnOCdojvrtnoI%2Fn9Qz5ZA5dsVXT%2Fpcjk30B3kv9KfuueM8GMF1AZtHkmurlGLAMFjN02nYfsdgXMT%2FwigVwUxehb6SaAlHSOEKrLRp0CX10%2BPFluvHrvnJSeZoup5PuAXwan86Jm4VI5H76k69HsVRMH3xHzJIzQeUAxZmcfyqfClrA%2F2qDU4mBrK8HW22HueJUrzG7GbPkI5w8dCmoB3vPw9lnDZitRbq9yRMCira8ym3B6VBjobKK%2B3hSd4sc7JAiBvmz9%2BKccHRndDW63xT1r%2FrDP%2Fk8f%2FtVh6hSycEQikOowAFDhmOw5f3QTremvPJO8KMZZ064eYw3YhWvGGLX8TEkye8DMFa%2FGdghShnSrkquFWqUwFltx1TioLC2522wa98FyuXou6QcVENV6vgGap5bdFXMmGJrY4eEZ84f7ylyN3FcUSa%2FPZ9vSmZw6jearnCgBL8M%2FbvbwEwg6%2BZ0FUESqEGjlk9sql22t200yaVUPogC9oBhtvurNk8%2F1WmvajTe6G26%2B6f0N1CinOcOdMnyi6G5hrFad5DMFRQNAAh5TwSj2xzXOXD6mWCyZgQAgcAHu%2FeW1FG5u3JpV4%2FWlBTFx%2BsmktT6PxuZPNK8YeyY6Iv%2FAMp7oSEAw7qHowwY6sAH1YpZ6cQkZFxQ%2FGtfZaIqANbEtNe3iB0fMH3AH09scZxGFdBdx%2BifKYIdWSEs9ltEFmcGKvBbv9thzUUuHyHBZHCgjH3xJ5r8Muzn63JJ6rizNVfoJ5leaeDy33nt%2FeVeXlHgB6PgnuoqJE39qs2FcDEHRSVodL94gT%2FFck3Thknl%2FAnwhI9s5ytJKPnz4uFktPUGqlL5h0wPzacbywDEE4Rf4BSFYKOoYQXh7SScY4g%3D%3D&X-Amz-Signature=a216b660176cf6ba12969a7a18f496419dab28d47651504e8d1a16fc9f586700&X-Amz-SignedHeaders=host&x-amz-checksum-mode=ENABLED&x-id=GetObject)]
- **MemoryBank**  Zhong W, Guo L, Gao Q, et al. Memorybank: Enhancing large language models with long-term memory[C]//Proceedings of the AAAI Conference on Artificial Intelligence. 2024, 38(17): 19724-19731. [pdf](https://arxiv.org/abs/2305.10250), [code](https://github.com/zhongwanjun/MemoryBank-SiliconFriend)
- **LONGMEM**  Yu H, Chen T, Feng J, et al. MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent[J]. arXiv preprint arXiv:2507.02259, 2025.[][pdf][pdf](https://arxiv.org/abs/2507.02259#content)  ,[code](https://github.com/BytedTsinghua-SIA/MemAgent)
- ​
- **EM-LLM**  Fountas Z, Benfeghoul M, Oomerjee A, et al. Human-inspired episodic memory for infinite context LLMs[C]//The Thirteenth International Conference on Learning Representations. 2025. [pdf](https://openreview.net/forum?id=BI2int5SAC) , [code](https://github.com/em-llm/EM-LLM-model)
- **SECOM ** Pan Z, Wu Q, Jiang H, et al. On memory construction and retrieval for personalized conversational agents[J]. arXiv preprint arXiv:2502.05589, 2025.  [pdf](https://arxiv.org/abs/2502.05589)   [code](https://github.com/microsoft/SeCom/)
- **CAIM** Westhäußer R, Berenz F, Minker W, et al. CAIM: Development and Evaluation of a Cognitive AI Memory Framework for Long-Term Interaction with Intelligent Agents[J]. arXiv preprint  arXiv:2505.13044, 2025.   [pdf](https://arxiv.org/abs/2505.13044), 
- **EHC**  Qiao C, Lu M. Efficiently Enhancing General Agents With Hierarchical-categorical Memory[J]. arXiv preprint arXiv:2505.22006, 2025.  [pdf](https://arxiv.org/abs/2505.22006)
- **mem0**  Chhikara P, Khant D, Aryan S, et al. Mem0: Building production-ready ai agents with scalable long-term memory[J]. arXiv preprint arXiv:2504.19413, 2025.  [pdf](https://arxiv.org/abs/2504.19413), [code](https://github.com/mem0ai/mem0)
- **MEmoryOS**   Kang J, Ji M, Zhao Z, et al. Memory OS of AI Agent[J]. arXiv preprint arXiv:2506.06326, 2025.[pdf](https://arxiv.org/pdf/2506.06326), [code](https://github.com/BAI-LAB/MemoryOS)
- **TME**  Ye Y. Task Memory Engine: Spatial Memory for Robust Multi-Step LLM Agents[J]. arXiv preprint arXiv:2505.19436, 2025. [pdf](https://arxiv.org/abs/2504.08525), [code](https://github.com/biubiutomato/TME-Agent)
- **STMA**  Lei M, Zhao Y, Wang G, et al. STMA: A spatio-temporal memory agent for long-horizon embodied task planning[J]. arXiv preprint arXiv:2502.10177, 2025. [pdf](https://arxiv.org/abs/2502.10177)
- **MemInsight**  Salama R, Cai J, Yuan M, et al. Meminsight: Autonomous memory augmentation for llm agents[J]. arXiv preprint arXiv:2503.21760, 2025.  [pdf](https://arxiv.org/abs/2503.21760), [code](https://github.com/eng-rana-s/MemInsight)
- **A-MEM**  Xu W, Mei K, Gao H, et al. A-mem: Agentic memory for llm agents[J]. arXiv preprint arXiv:2502.12110, 2025. [pdf](https://arxiv.org/abs/2502.12110), [code](https://github.com/agiresearch/A-mem)
- **CDMem**  Gao P, Zhao J, Chen X, et al. An Efficient Context-Dependent Memory Framework for LLM-Centric Agents[C]//Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 3: Industry Track). 2025: 1055-1069. [pdf](https://aclanthology.org/2025.naacl-industry.80/), [code](https://github.com/piri-gao/CDMem)
- **RMM**  Tan Z, Yan J, Hsu I, et al. In prospect and retrospect: Reflective memory management for long-term personalized dialogue agents[J]. arXiv preprint arXiv:2503.08026, 2025. [pdf](https://arxiv.org/abs/2503.08026)
- **TReMu ** Ge Y, Romeo S, Cai J, et al. Tremu: Towards neuro-symbolic temporal reasoning for llm-agents with memory in multi-session dialogues[J]. arXiv preprint arXiv:2502.01630, 2025.  [pdf](https://arxiv.org/abs/2502.01630)



### 特定领域应用

*这类方法为解决特定场景（如个性化对话、推荐系统、具身智能）的需求而设计了专门的记忆系统。*

- **FINMEM**   Yu Y, Li H, Chen Z, et al. Finmem: A performance-enhanced llm trading agent with layered memory and character design[C]//Proceedings of the AAAI Symposium Series. 2024, 3(1): 595-597. [pdf](https://ojs.aaai.org/index.php/AAAI-SS/article/view/31290),[code](https://github.com/pipiku915/FinMem-LLM-StockTrading)

- **MaLP**   Zhang K, Kang Y, Zhao F, et al. Llm-based medical assistant personalization with short-and long-term memory coordination[J]. arXiv preprint arXiv:2309.11696, 2023. [pdf](https://aclanthology.org/2024.naacl-long.132/),[code](https://github.com/MatthewKKai/MaLP)

- **NADINE**  Kang H, Moussa M B, Magnenat-Thalmann N. Nadine: an LLM-driven intelligent social robot with affective capabilities and human-like memory[J]. arXiv preprint arXiv:2405.20189, 2024.   [pdf](https://onlinelibrary.wiley.com/doi/full/10.1002/cav.2290). 

- **RAISE**  Liu N, Chen L, Tian X, et al. From llm to conversational agent: A memory enhanced architecture with fine-tuning of large language models[J]. arXiv preprint arXiv:2401.02777, 2024. [pdf](https://arxiv.org/abs/2401.02777)

- **Optimus**  Li Z, Xie Y, Shao R, et al. Optimus-1: Hybrid multimodal memory empowered agents excel in long-horizon tasks[J]. Advances in neural information processing systems, 2024, 37: 49881-49913. [pdf](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5949a8750a110ce1f0631b1776c500a2-Abstract-Conference.html),  [code](https://github.com/JiuTian-VL/Optimus-1) 

-  **MRSTEVE **  Park J, Cho J, Ahn S. Mrsteve: Instruction-following agents in minecraft with what-where-when memory[J]. arXiv preprint arXiv:2411.06736, 2024.  [pdf](https://arxiv.org/abs/2411.06736), [code](https://github.com/frechele/MrSteve)

- **AgentCF++ **  Liu J, Gu S, Li D, et al. AgentCF++: Memory-enhanced LLM-based Agents for Popularity-aware Cross-domain Recommendations[C]//Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval. 2025: 2566-2571. [pdf](https://dl.acm.org/doi/abs/10.1145/3726302.3730161), [code](https://github.com/jhliu0807/AgentCF-plus) 

- **CarMem**  Kirmayr J, Stappen L, Schneider P, et al. Carmem: Enhancing long-term memory in llm voice assistants through category-bounding[J]. arXiv preprint arXiv:2501.09645, 2025.  [pdf](https://arxiv.org/abs/2501.09645), [code](https://github.com/johanneskirmayr/CarMem)

- **Crafting Personalized Agents**   Wang Z, Li Z, Jiang Z, et al. Crafting personalized agents through retrieval-augmented generation on editable memory graphs[J]. arXiv preprint arXiv:2409.19401, 2024.  [pdf](https://arxiv.org/abs/2409.19401)

  ​



### 记忆的评估与安全

*这类方法主要关注如何评估代理的记忆能力，或是研究记忆系统的潜在安全风险。*

* **MINJA**  Dong S, Xu S, He P, et al. A practical memory injection attack against llm agents[J]. arXiv preprint arXiv:2503.03704, 2025. [pdf](https://arxiv.org/html/2503.03704)
* **MemSim**   Zhang Z, Dai Q, Chen L, et al. Memsim: A bayesian simulator for evaluating memory of llm-based personal assistants[J]. arXiv preprint arXiv:2409.20163, 2024. [pdf](https://arxiv.org/abs/2409.20163), [code](https://github.com/nuster1128/MemSim)
