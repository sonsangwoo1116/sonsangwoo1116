## Hi, I'm Sangwoo Son 👋

**AI/Voice Engineer** @ SoundMind | **AI Engineer** @ [WIGTN Crew](https://wigtn.com)

### About Me

실시간 전화 통화 환경에서 음성 AI 에이전트를 설계·개발하고 있습니다.
STT/TTS 모델 서빙 및 최적화, 대화 상태 머신 설계, 모델 비교 평가 체계 구축까지 전체 과정을 주도하고 있으며, 음성 도메인의 품질·지연·비용 트레이드오프를 정량 데이터로 판단합니다.

WIGTN이라는 5인 AI 개발 크루에서 아이디어를 직접 서비스화하는 것을 목표로 프로젝트를 진행하고 있습니다.

---

### Work Projects — SoundMind (팀장 / AX)

**AI 콜센터 음성 에이전트 시스템** `2026.02 ~ 진행중`
- 아웃바운드 AI 콜봇(보험 완전판매 모니터링) + 인바운드 민원 접수 시스템
- 5단계 하이브리드 라우팅으로 LLM 호출 85% 절감, GPU 점유율 2.3%
- STT 엔진 비교 평가 (Zipformer2 vs Qwen3-ASR, 200 동시접속/30분 지속)
- ASR TensorRT 최적화: 추론 11.2ms → 5.6ms (2x), 모델 크기 49% 절감
- TTS 4종 비교 평가 (CosyVoice2/MeloTTS/Qwen3-TTS), 파인튜닝 효과 정량 측정

**다국어 동시통역 및 음성 분석 시스템** `2026.02 ~ 진행중`
- 단일 GPU에서 ASR + 번역 + TTS 3개 모델 동시 서빙, 13개 언어 지원
- 교정시설 위험 발화 탐지: 7단계 규칙 기반 NLP 파이프라인, sub-ms 처리

**영어 교육용 음성인식 시스템** `2025.11 - 2026.03`
- Triton + Faster Whisper 기반 배치 STT, 3-Worker 분리 아키텍처
- 성공률 82% → 95%+, RTX 3090 2장에서 분당 300건 안정 처리

**기업 문서 RAG 질의응답 시스템** `2025.06 - 2025.07`
- LangGraph 듀얼 그래프 설계, Upstage Document Parse + Map-Reduce 요약

**커스텀 음성 키워드 인식 시스템** `2025.03 - 2025.07`
- 이중 임계값 설계로 인식률 96.81%, 오탐률 0.0% (43만+ 윈도우 테스트)
- TFLite INT8 양자화 → 엣지 디바이스 배포

**VoiceNote — 회의록 분석 플랫폼** `2025.02 - 2025.05`
- Whisper STT + pyannote 화자분리 + LLM 요약, 5개 마이크로서비스

**시니어 케어 챗봇** `2025.02 - 2025.05`
- LLM 기반 고령자 건강체크 챗봇, 2단계 상태 머신 (16개 서브 상태, 40+ 전이)

---

### Side Projects — WIGTN Crew

**WIGVO v2 — AI 실시간 전화통역** `2026.02` [GitHub](https://github.com/wigtn/wigvo-v2)
- OpenAI Realtime API + Twilio PSTN, 듀얼 세션 + 3단계 에코 필터
- 147통 실전 테스트 에코 루프 0건, 557ms 레이턴시, $0.27/분

**WIGVU — YouTube AI 분석 서비스** `2026.01` [GitHub](https://github.com/wigtn/wigvu)
- 4개 언어 난이도 분석 + 레벨별 적응 프롬프트

**WIGENT — AI Agent 토론 플랫폼** `2026` 🏆 Build with TRAE 해커톤 대상

---

### Tech Stack

**Voice AI** · Whisper · Qwen3-ASR · Zipformer2 · CosyVoice2 · MeloTTS · Qwen3-TTS · Silero VAD

**LLM & Agent** · LangGraph · RAG · Tool Calling · vLLM · TensorRT

**Infra** · Triton · Docker · FastAPI · Temporal · Prometheus · Grafana

---

### Links

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sangwooson)
[![WIGTN](https://img.shields.io/badge/WIGTN-000000?style=flat&logo=github&logoColor=white)](https://github.com/wigtn)
[![Website](https://img.shields.io/badge/WIGTN.com-4285F4?style=flat&logo=google-chrome&logoColor=white)](https://wigtn.com)
