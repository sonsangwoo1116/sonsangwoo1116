## Sangwoo Son

**AI/Voice Engineer / Team Lead** @ Soundmind
**AI Engineer** @ [WIGTN Crew](https://wigtn.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sangwooson)
[![WIGTN](https://img.shields.io/badge/WIGTN.com-4285F4?style=flat&logo=google-chrome&logoColor=white)](https://wigtn.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=notion&logoColor=white)](https://www.notion.so/3437d23f3681805e895ff003d02adbd5)

---

### About

Building voice AI agents for real phone call environments. Leading the full cycle — STT/TTS model serving & optimization, dialogue state machine design, and model evaluation at scale.

I believe the gap between paper benchmarks and production performance is real, and the only way to find out is to build it and stress-test it yourself.

### Tech Stack

`Python` `PyTorch` `vLLM` `TensorRT` `Triton` `FastAPI` `Docker` `LangGraph` `LangChain`

---

### Current Work @ Soundmind

**Voice AI Agent**

- **AI Call Center Voice Agent** — Outbound AI call bot + inbound complaint intake. 5-stage hybrid routing reduced LLM calls by 85%, GPU utilization 2.3% per call
- **Multilingual Simultaneous Interpretation & Voice Analysis** — 3 models (ASR+Translation+TTS) co-served on single GPU, 13 languages. Correctional facility risk utterance detection (7-stage NLP pipeline, sub-ms)

**STT/TTS Model Evaluation & Optimization**

- **STT 3-Model Benchmark** — Zipformer2 vs Qwen3-ASR under 200 concurrent / 30min sustained load (RPS 1,036, p95 250ms)
- **ASR TensorRT Optimization** — Qwen3-ASR encoder TRT FP16: inference 11.2ms → 5.6ms (2x), model size -49%
- **TTS 4-Engine Comparison** — CosyVoice2/MeloTTS/Qwen3-TTS evaluated on RTF/TTFA/concurrency/VRAM under same GPU. Built 3-stage defense for GPU Stuck recovery
- **Finetuning Effect Quantification** — CosyVoice2 Base vs ft_ko: RTF +32%, TTFA -61%, degenerate outputs eliminated

**Production Systems**

- **English Education ASR System** — Triton + Faster Whisper, 3-Worker architecture. Success rate 82% → 95%+, 300 req/min stable on 2x RTX 3090
- **Enterprise Document RAG QA** — LangGraph dual-graph design, Upstage Document Parse, recursive Map-Reduce summarization
- **Custom Voice Keyword Spotting** — Dual-threshold detection: 96.81% recall, 0.0% false alarm (430K+ window test). TFLite INT8 edge deployment
- **VoiceNote Meeting Analyzer** — Whisper STT + pyannote diarization + LLM summarization, 5 microservices
- **Senior Care Chatbot** — LLM-based elderly health check, 2-level state machine (16 sub-states, 40+ transitions)

---

### WIGTN — AI-Native Builder Crew

**AI R&D**

- **WIGVO** — Real-time bidirectional speech translation over PSTN. Dual-session + 3-stage echo filter, 0 echo loops in 147 live calls, 557ms latency, $0.27/min (ACL 2026 Demo Accepted, 2nd Author, Rating 7.50) [Repo](https://github.com/wigtn/wigvo-v2)
- **WigtnOCR** — VLM-based Korean public document parser, 2B model matching 30B Teacher quality [Repo](https://github.com/wigtn/wigtnOCR-v1)

**Open Source**

- **WIGTN-Coding** — Claude Code AI-Native development workflow plugins [Repo](https://github.com/wigtn/wigtn-plugins-with-claude-code)
- **TimeLens** — Multimodal AI museum curator with voice + camera (Gemini Live Agent) [Repo](https://github.com/wigtn/wigtn-timelens)

**Products**

- **WIGVU** — YouTube subtitle extraction, translation & AI analysis service [Repo](https://github.com/wigtn/wigvu)
- **WIGENT** — AI Agent real-time debate platform 🏆 Build with TRAE Hackathon Grand Prize

---

### Awards & Publications

- 🏆 **Build with TRAE Hackathon** · Grand Prize · WIGENT: AI Agent Real-time Debate Platform · 2026
- 🏆 **International oneM2M Hackathon** · Encouragement Award · 2022
- 📝 Implementation of an IoT Cocktail Machine Using ChatGPT API and ConvAnalyser in the Metaverse (IEEE Metacom 2024)
- 📝 A Metaverse Avatar Teleport System Using an AIoT Pose Estimation Device (IEEE Metacom 2023)
- 📄 IoT-based Metaverse Management Platform · Patent 10-2023-0189803
