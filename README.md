## Sang-Woo Son (Diego Son)

**AI Research Engineer** @ [WIGTN](https://wigtn.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sangwooson)
[![WIGTN](https://img.shields.io/badge/WIGTN.com-4285F4?style=flat&logo=google-chrome&logoColor=white)](https://wigtn.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=github&logoColor=white)](https://sonsangwoo1116.github.io/portfolio/)

LLM agents that hold up in production, including tool-calling control and guardrails, multi-agent orchestration, retrieval-grounded evaluation, and agents that act over real-time voice.

---

### Publications

- **Retrieval-Conditional Parsing Score (RCPS): Choosing Document Parsers by Retrieval, Not by Appearance**
  EMNLP 2026 Industry Track · First author · [GitHub](https://github.com/wigtn/WigtnOCR-RADP)
- **WIGVO: Real-Time Bidirectional Speech Translation over Legacy PSTN Calls via Dual-Session Echo Gating**
  ACL 2026 System Demonstrations · Second author · [Paper](https://aclanthology.org/2026.acl-demo.33/) · [Video](https://youtu.be/jK1CDOQExLw) · [GitHub](https://github.com/wigtn/wigvo-v2)
- **Implementation of an IoT Cocktail Machine Using ChatGPT API and ConvAnalyser in the Metaverse**
  IEEE MetaCom 2024 · First author · [Paper](https://doi.org/10.1109/MetaCom62920.2024.00057)
- **A Metaverse Avatar Teleport System Using an AIoT Pose Estimation Device**
  IEEE MetaCom 2023 · [Paper](https://doi.org/10.1109/MetaCom57706.2023.00131)

---

### Experience

**WIGTN** · AI Research Engineer · 2026.01 – Present

- Develop WIGVO, a production real-time phone translation service over PSTN, improving translation quality through the echo gate and VAD pipeline, operator speaker identification, and a noise-robust audio front end.
- Built call observability and evaluation: per-turn Langfuse tracing, a live pipeline monitor, and an LLM-judge translation-quality evaluation with self-validation.

**Soundmind** · Team Lead, AX Division · 2026.03 – 2026.06

- Led a real-time voice AI agent engine for insurance sales-compliance monitoring: rule-based guardrails for simple intents, LLM tool calling only for risky utterances, complaints, and answer reversals.
- 5 concurrent calls on a single RTX 3090 with a 9B model at 154 ms P50 / under 300 ms P99, 47% fewer input tokens, 55/55 edge-case QA scenarios passed.

**Soundmind** · Manager, AX Division · 2025.01 – 2026.02

- **Batch STT pipeline** (Temporal, Triton, Faster Whisper): decoupled STT from result callbacks, success rate 82% → 95%+, 200 req/min on 2× RTX 3090.
- **Custom Korean wake-word model** (KWT-3): dual-threshold detection, 0 false alarms over 430K+ windows, 96.81% recognition, 75% smaller with TFLite INT8.
- **Document RAG** with a LangGraph dual graph (up to 50 MB / 100 pages) and a **meeting-analysis platform** with Whisper, pyannote diarization, and speaker-transcript alignment.

**AID Lab, Hanshin University** · 2022.09 – 2024.12

- Government-funded R&D on multimodal (text + speech) depression classification, on-device behavior recognition, and edge AI for small businesses.

---

### Hackathons

- 🏆 **ByteDance Build with TRAE Hackathon 2026 · Grand Prize** — [WIGENT](https://github.com/wigtn/wigent): AI agents debate a business idea and turn the outcome into a landing page.
- 🏅 **OBA Weekendthon S1 2026 · Top 6** — [MyunZy](https://github.com/wigtn/myunzy-hackathone): spoken mock interviews with four interviewer personas that follow up on weak answers.
- **Google Cloud Rapid Agent Hackathon** — [Custos](https://devpost.com/software/wigtn-bot): always-on AI code review bot for GitLab.
- **H0: Hack the Zero Stack · Vercel × AWS** — [OpenSlot](https://devpost.com/software/openslot): zero-oversell ticketing infrastructure.
- **Gemini Live Agent Challenge · Google** — [TimeLens](https://github.com/wigtn/wigtn-timelens): multimodal AI museum curator with voice and camera.
- 🏅 **International oneM2M Hackathon 2022 (Nov) · Encouragement Award** — travel logging with biometric data from IoT wearables.

---

### Education

- Convergence of IT Image Data Analytics, Hanshin University (2023.09 – 2025.02) · GPA 4.5 / 4.5
- IT Transmedia Contents, Hanshin University (2018.03 – 2023.08)

### Patents & Software

- IoT-Based Metaverse Management Platform · Patent application No. 10-2023-0189803 (2023.12)
- Metaverse Emotion Mapping System Using an AIoT Facial-Expression Device · Software registration No. C-2023-054487 (2023.11)
- LSTM-Based Walking Motion Recognition in Industrial Sites Using YOLOv7 Pose Estimation · Software registration No. C-2023-049743 (2023.11)
