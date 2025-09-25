# Awesome Streaming Video Understanding [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of research papers, benchmarks, and resources on **Streaming Video Understanding**.  

In offline video understanding, the system first obtains the entire video (all frames, all timestamps) before doing any analysis or answering questions. Because it has full access to the complete content, it can revisit, rewind, or look ahead arbitrarily, and exploit global context or future cues to reason about events. In contrast, online/streaming video understanding must work in real time: video frames arrive sequentially, and the model’s inference is **causal** — at time *t*, it can only base decisions on frames up to *t* (never on future frames). The model cannot freely rewind or peek ahead, and must make incremental updates as new data arrives. 

---

## Models

| Title                                                        | Model           | Date    | Code                                                         | Venue        |
| ------------------------------------------------------------ | --------------- | ------- | ------------------------------------------------------------ | ------------ |
| [StreamMem: Query-Agnostic KV Cache Memory for Streaming Video Understanding](http://arxiv.org/abs/2508.15717) | StreamMem       | 08/2025 | [Project Page](https://yangyanl.ai/streammem/)               | arXiv        |
| [StreamAgent: Towards Anticipatory Agents for Streaming Video Understanding](http://arxiv.org/abs/2508.01875) | StreamAgent     | 08/2025 | —                                                            | arXiv        |
| [CogStream: Context-guided Streaming Video Question Answering](http://arxiv.org/abs/2506.10516) | CogStream       | 06/2025 | [GitHub](https://github.com/LiamZhao326/CogStream)           | arXiv        |
| [Proactive Assistant Dialogue Generation from Streaming Egocentric Videos](http://arxiv.org/abs/2506.05904) | IPS             | 06/2025 | [GitHub](https://github.com/pro-assist/ProAssist)            | arXiv        |
| [Flash-VStream: Efficient Real-Time Understanding for Long Video Streams](http://arxiv.org/abs/2506.23825) | Flash-VStream   | 06/2025 | [GitHub](https://github.com/IVGSZ/Flash-VStream)             | ICCV 2025    |
| [Learning Streaming Video Representation via Multitask Training](http://arxiv.org/abs/2504.20041) | Streamformer    | 04/2025 | [Project Page](https://go2heart.github.io/streamformer)      | ICCV 2025    |
| [LiveCC: Learning Video LLM with Streaming Speech Transcription at Scale](http://arxiv.org/abs/2504.16030) | LiveCC          | 04/2025 | [Project Page](https://showlab.github.io/livecc/)            | CVPR 2025    |
| [ViSpeak: Visual Instruction Feedback in Streaming Videos](http://arxiv.org/abs/2503.12769) | ViSpeak         | 03/2025 | [GitHub](https://github.com/HumanMLLM/ViSpeak)               | ICCV 2025    |
| [LION-FS: Fast-Slow Video Language Thinker as Online Video Assistant](http://arxiv.org/abs/2503.03663) | LION-FS         | 03/2025 | [GitHub](https://github.com/JiuTian-VL/LION-FS)              | CVPR 2025    |
| [STREAMMIND: Unlocking Full Frame Rate Streaming Video Dialogue through Event-Gated Cognition](http://arxiv.org/abs/2503.06220) | STREAMMIND      | 03/2025 | [GitHub](https://aka.ms/StreamMind)                          | ICCV 2025    |
| [Streaming Video Understanding and Multi-round Interaction with Memory-enhanced Knowledge](http://arxiv.org/abs/2501.13468) | STREAMCHAT      | 01/2025 | [GitHub](https://github.com/hmxiong/StreamChat)              | ICLR 2025    |
| [DisPider: Enabling Video LLMs with Active Real-Time Interaction via Disentangled Perception, Decision, and Reaction](http://arxiv.org/abs/2501.03218) | DisPider        | 01/2025 | [GitHub](https://github.com/Mark12Ding/Dispider)             | CVPR 2025    |
| [StreamChat: Chatting with Streaming Video](https://arxiv.org/abs/2412.08646) | StreamChat      | 12/2024 | [Project Page](https://jihaonew.github.io/projects/streamchat.html) | CVPR 2024    |
| [VideoLLM Knows When to Speak: Enhancing Time-Sensitive Video Comprehension with Video-Text Duet Interaction](http://arxiv.org/abs/2411.17991) | MMDuet          | 11/2024 | [GitHub](https://github.com/yellow-binary-tree/MMDuet)       | arXiv        |
| [VideoLLaMB: Long Streaming Video Understanding with Recurrent Memory Bridges](http://arxiv.org/abs/2409.01071) | VideoLLaMB      | 09/2024 | [GitHub](https://github.com/bigai-nlco/VideoLLaMB)           | ICCV 2025    |
| [VideoLLM-MoD: Efficient Video-Language Streaming with Mixture-of-Depths Vision Computation](http://arxiv.org/abs/2408.16730) | VideoLLM-MoD    | 08/2024 | —                                                            | arXiv        |
| [VideoLLM-online: Online Video Large Language Model for Streaming Video](https://arxiv.org/abs/2406.11816)) | VideoLLM-online | 06/2024 | [GitHub](https://github.com/showlab/VideoLLM-online)         | CVPR 2024    |
| [Streaming Long Video Understanding](https://arxiv.org/pdf/2405.16009) | —               | 05/2024 | —                                                            | NeurIPS 2024 |

## Datasets, Benchmarks

| Name               | Paper                                                        | Date    | Link                                                         | Venue     |
| ------------------ | ------------------------------------------------------------ | ------- | ------------------------------------------------------------ | --------- |
| PROASSIST          | [Proactive Assistant Dialogue Generation from Streaming Egocentric Videos](http://arxiv.org/abs/2506.05904) | 06/2025 | [Link]((https://github.com/pro-assist/ProAssist))            | arXiv     |
| Live-WhisperX-526K | [LiveCC: Learning Video LLM with Streaming Speech Transcription at Scale](http://arxiv.org/abs/2504.16030) | 04/2025 | [Link](https://huggingface.co/datasets/chenjoya/Live-WhisperX-526K) | CVPR 2025 |
| Live-CC-5M         | [LiveCC: Learning Video LLM with Streaming Speech Transcription at Scale](http://arxiv.org/abs/2504.16030) | 04/2025 | [Link](https://huggingface.co/datasets/chenjoya/Live-CC-5M)  | CVPR 2025 |
| OmniMMI            | [OmniMMI: A Comprehensive Multi-modal Interaction Benchmark in Streaming Video Contexts](https://arxiv.org/abs/2503.22952) | 03/2025 | [Link](https://omnimmi.github.io/)                           | CVPR 2025 |
| SVBench            | [SVBench: A Benchmark with Temporal Multi-Turn Dialogues for Streaming Video Understanding](https://arxiv.org/abs/2502.10810) | 02/2025 | [Link](https://yzy-bupt.github.io/SVBench/)                  | ICLR 2025 |
| StreamBench        | [Streaming Video Understanding and Multi-round Interaction with Memory-enhanced Knowledge](http://arxiv.org/abs/2501.13468) | 01/2025 | [Link](https://github.com/hmxiong/StreamChat)                | ICLR 2025 |
| OVO-Bench          | [OVO-Bench: How Far is Your Video-LLMs from Real-World Online Video Understanding?](https://arxiv.org/abs/2501.05510) | 01/2025 | [Link](https://github.com/JoeLeelyf/OVO-Bench)               | CVPR 2025 |
| MMDuetIT           | [VideoLLM Knows When to Speak: Enhancing Time-Sensitive Video Comprehension with Video-Text Duet Interaction](http://arxiv.org/abs/2411.17991) | 11/2024 | [Link](https://github.com/yellow-binary-tree/MMDuet)         | arXiv     |



## 🚀 Contributing

Contributions are welcome! Please submit a PR or open an issue to add new papers, benchmarks, or resources.  

---

## 📌 License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)

---

⭐ If you find this repository useful, please consider giving it a star!