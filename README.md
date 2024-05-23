# Accelerated Generation Techniques for LLMs



## 📚 What is This Survey About?

This survey paper, titled **"Accelerated Generation Techniques for Large Language Models (LLMs)"**, focuses on the cutting-edge algorithmic advancements developed to enhance the efficiency and speed of generating responses from LLMs. As LLMs are increasingly used in various applications such as chatbots, content creation, and language translation, the computational demands for real-time response generation become a significant challenge. Our survey explores a range of novel algorithms and methodologies designed to optimize the generation process. These include **Speculative decoding** techniques, **Early-exiting**  strategies, and **Non-autoregressive** mechanisms. By consolidating the latest research and breakthroughs in these algorithmic approaches, this paper aims to provide valuable insights and practical guidance for researchers and practitioners working to implement faster and more efficient LLMs in their projects.


## 📖 Table of Content

### 💥 Speculative Decoding

- Blockwise parallel decoding for deep autoregressive models, NIPS, 2018. [Paper](https://arxiv.org/abs/1811.03115)

- Speculative Decoding: Exploiting Speculative Execution for Accelerating Seq2seq Generation, EMNLP-findings, 2023. [Paper](https://aclanthology.org/2023.findings-emnlp.257.pdf), [Code](https://github.com/hemingkx/SpecDec)

- Accelerating Large Language Model Decoding with Speculative Sampling, ArXiv, 2023. [Paper](https://arxiv.org/abs/2302.01318)
- Fast Inference from Transformers via Speculative Decoding, ArXiv, 2023. [Paper](https://arxiv.org/abs/2211.17192)

- Online Speculative Decoding, ArXiv, 2023. [Paper](https://arxiv.org/abs/2310.07177)

- Draft & Verify: Lossless Large Language Model Acceleration via Self-Speculative Decoding, ArXiv 2023. [Paper](https://arxiv.org/abs/2309.08168), [Code](https://github.com/dilab-zju/self-speculative-decoding)

- DistillSpec: Improving Speculative Decoding via Knowledge Distillation, ArXiv, 2023. [Paper](https://arxiv.org/abs/2310.08461)

- REST: Retrieval-Based Speculative Decoding, NAACL 2024 [Paper](https://arxiv.org/abs/2311.08252), [Code](https://github.com/FasterDecoding/REST)

- Cascade Speculative Drafting for Even Faster LLM Inference, ArXiv, 2023. [Paper](https://arxiv.org/abs/2312.11462), [Code](https://github.com/lfsszd/CS-Drafting)

- Accelerating LLM Inference with Staged Speculative Decoding, ICML, 2023. [Paper](https://arxiv.org/abs/2308.04623)

- PASS: Parallel Speculative Sampling, NeurIPS 2023. [Paper](https://arxiv.org/abs/2311.13581)

- Medusa: Simple LLM Inference Acceleration Framework with Multiple Decoding Heads, ArXiv, 2024. [Paper](https://arxiv.org/abs/2401.10774), [Code](https://github.com/FasterDecoding/Medusa?tab=readme-ov-file)

- Eagle: Speculative Sampling Requires Rethinking Feature Uncertainty, ICML, 2024. [Paper](arxiv.org/abs/2401.15077), [Code](https://github.com/SafeAILab/EAGLE)

- SpecInfer: Accelerating Generative Large Language Model Serving with Tree-Based Speculative Inference and Verification, ACL, 2024. [Paper](https://arxiv.org/abs/2305.09781)

- Spectr: Fast Speculative Decoding via Optimal Transport, NeurIPS, 2023. [Paper](https://arxiv.org/abs/2310.15141)

- Speculative Decoding with Big Little Decoder, NeurIPS, 2023. [Paper](https://arxiv.org/abs/2302.07863)

- Optimal Block-Level Draft Verification for Accelerating Speculative Decoding, ArXiv, 2024. [Paper](https://arxiv.org/abs/2403.10444)

- Multi-candidate Speculative Decoding, ArXiv, 2024. [Paper](https://arxiv.org/abs/2401.06706), [Code](https://github.com/NJUNLP/MCSD/tree/main/MCSD)

- The Synergy of Speculative Decoding and Batching in Serving Large Language Models, ArXiv, 2023. [Paper](https://arxiv.org/abs/2310.18813)

- BITA: Bi-directional Tuning for Lossless Acceleration in Large Language Models, ArXiv, 2024. [Paper](https://arxiv.org/abs/2401.12522)

- Generation Meets Verification: Accelerating Large Language Model Inference with Smart Parallel Auto-correct Decoding, ArXiv, 2024. [Paper](https://arxiv.org/abs/2402.11809)

- Inference with Reference: Lossless Acceleration of Large Language Models, ArXiv, 2023. [Paper](https://arxiv.org/abs/2304.04487)

- Lookahead: An Inference Acceleration Framework for Large Language Model with Lossless Generation Accuracy, ArXiv, 2024. [Paper](https://arxiv.org/abs/2312.12728), [Code](https://github.com/alipay/PainlessInferenceAcceleration)

- Speculative Contrastive Decoding, ArXiv, 2023. [Paper](https://arxiv.org/abs/2311.08981)

- Sarathi: Efficient LLM Inference by Piggybacking Decodes with Chunked Prefills, ArXiv, 2023. [Paper](https://arxiv.org/abs/2308.16369)

- SPEED: Speculative Pipelined Execution for Efficient Decoding, NeurIPS, 2023. [Paper](https://arxiv.org/abs/2310.12072)

- Triforce: Lossless Acceleration of Long Sequence Generation with Hierarchical -Speculative Decoding, ArXiv, 2024. [Paper](https://arxiv.org/abs/2404.11912)


### ⚡ Early-Exiting

- Confident adaptive language modeling, NeurIPS, 2022. [Paper](https://arxiv.org/abs/2207.07061)


- Fast and Robust Early-Exiting Framework for Autoregressive Language Models with Synchronized Parallel Decoding, EMNLP 2023. [Paper](https://aclanthology.org/2023.emnlp-main.362), [Code](https://github.com/raymin0223/fast_robust_early_exit)

- A Simple Hash-Based Early Exiting Approach For Language Understanding and Generation, ACL, 2022. [Paper](https://arxiv.org/abs/2203.01670)

- Accelerating Inference for Pretrained Language Models by Unified Multi-Perspective Early Exiting, ACL, 2022. [Paper](https://aclanthology.org/2022.coling-1.414.pdf), [Code](https://github.com/JunKong5/MPEE)

- Predictive Pipelined Decoding: A Compute-Latency Trade-off for Exact LLM Decoding, ICML, 2023. [Paper](https://arxiv.org/abs/2307.05908)

- Consistentee: A consistent and hardness-guided early exiting method for accelerating language models inference, AAAI, 2024. [Paper](https://arxiv.org/abs/2312.11882)

- Skipdecode: Autoregressive skip decoding with batching and caching for efficient LLM inference, ArXiv, 2023. [Paper](https://arxiv.org/abs/2307.02628)

- EE-LLM: Large-scale training and inference of early-exit large language models with 3D parallelism, ArXiv, 2023. [Paper](https://arxiv.org/abs/2312.04916), [Code](https://github.com/pan-x-c/EE-LLM)

- Layer skip: Enabling early exit inference and self-speculative decoding, ArXiv, 2024. [Paper](https://arxiv.org/abs/2404.16710)


### ✨  Non-Autoregressive

- Non-Autoregressive Neural Machine Translation, ICLR, 2018. [Paper](https://arxiv.org/abs/1711.02281)

- Non-Autoregressive Neural Machine Translation with Enhanced Decoder Input, AAAI, 2019. [Paper](https://arxiv.org/abs/1812.09664)

- Fast decoding in sequence models using discrete latent variables, ICML, 2018. [Paper](https://arxiv.org/abs/1803.03382)

- FlowSeq: Non-autoregressive conditional sequence generation with generative flow, EMNLP, 2019. [Paper](https://arxiv.org/abs/1909.02480), [Code](https://github.com/XuezheMax/flowseq)

- Deterministic non-autoregressive neural sequence modeling by iterative refinement, EMNLP, 2018. [Paper](https://arxiv.org/abs/1802.06901), [Code](https://github.com/nyu-dl/dl4mt-nonauto)

- Syntactically supervised transformers for faster neural machine translation, ACL, 2019. [Paper](https://aclanthology.org/P19-1122/)

- Fine-tuning by curriculum learning for non-autoregressive neural machine translation, AAAI, 2020. [Paper](https://arxiv.org/abs/1911.08717)

- Non-autoregressive translation with dependency-aware decoder, IWSLT, 2023. [Paper](https://aclanthology.org/2023.iwslt-1.47/)

- Non-autoregressive text generation with pre-trained language models, EACL, 2021.[Paper](https://arxiv.org/abs/2102.08220), [Code](https://github.com/yxuansu/NAG-BERT)

- Semi-autoregressive neural machine translation, EMNLP, 2018. [Paper](https://arxiv.org/abs/1808.08583), [Code](https://github.com/chqiwang/sa-nmt)

- Fast structured decoding for sequence models, NeurIPS, 2019. [Paper](https://arxiv.org/abs/1910.11555)

- Mask-predict: Parallel decoding of conditional masked language models, EMNLP, 2019. [Paper](https://arxiv.org/abs/1904.09324)

- Accelerating transformer inference for translation via parallel decoding, ACL, 2023. [Paper](https://arxiv.org/abs/2305.10427), [Code](https://github.com/teelinsan/parallel-decoding)

- CLLMs: Consistency large language models, ICML, 2024. [Paper](http://arxiv.org/abs/2403.00835), [Code](https://github.com/hao-ai-lab/Consistency_LLM)

- Skeleton-of-thought: Large language models can do parallel decoding, ICLR, 2024. [Paper](https://arxiv.org/abs/2307.15337)
