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


