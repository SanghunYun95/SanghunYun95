# 윤상훈 (Yun, Sanghun)
**Backend & Architecture Engineer | Python & TypeScript**

시스템이 직면하는 구조적 한계와 병목 현상을 분석하고, 이를 설계 단계에서부터 통제하는 것에 집중하는 5년 차 백엔드 엔지니어입니다. 단순히 외부 API를 래핑(Wrapping)하는 데 그치지 않고, 런타임 지연 시간, 단일 장애점(SPOF), 스트림 파싱 오류 등 실제 서비스 환경의 크리티컬한 문제들을 아키텍처 레벨에서 해결합니다. 

비즈니스 운영 및 회계 관리 도메인에서의 실무 경험을 바탕으로, 개발을 위한 개발이 아닌 **비용 최적화와 안정적인 도메인 로직 구현**을 최우선으로 고려합니다.

---

### 💡 Engineering Philosophy
- **Critical Architecture:** 서드파티 의존성을 맹신하지 않고, 오프라인 ETL 및 로컬 모델 병합을 통해 외부 API 장애가 시스템에 미치는 영향을 차단합니다.
- **Resource Isolation:** 무거운 텍스트 생성 작업과 가벼운 벡터 연산을 분리하여 시스템 부하와 클라우드 비용을 엄격하게 통제합니다.
- **Stream Stability:** 비동기 I/O 및 Multi-Event SSE 프로토콜을 활용하여, 프론트엔드 렌더링 수명 주기와 백엔드 데이터 스트림 간의 충돌을 방지합니다.

---

### 🛠 Tech Stack & Tools

**Backend & API**
- Python (FastAPI), TypeScript, Node.js
- Asynchronous I/O, SSE (Server-Sent Events) Stream Control

**AI & Data Engineering**
- LLM Orchestration (Google Gemini API, LangChain)
- Vector Search & Embeddings (Supabase `pgvector`, HuggingFace `sentence-transformers`)
- Offline ETL Pipeline Design

**Environment & Tools**
- Git, Next.js (App Router, Strict Client/Server isolation)
- Antigravity IDE (VibeCoding-driven rapid prototyping)

---

### 🚀 Featured Project

**[PhiloRAG: Enterprise-Grade RAG Architecture]** *현대인의 심리적 문제와 고전 철학을 연결하는 하이브리드 RAG 시스템*
- **SPOF 완화:** 외부 서점 API 의존도를 낮추기 위해 오프라인 상태에서 메타데이터를 사전 적재(Pre-fetch)하는 배치 파이프라인 구축.
- **스트림 상태 제어:** 단일 스트림에서 발생하는 고질적인 JSON 파싱 에러를 해결하기 위해, 메타데이터와 텍스트 청크를 엄격히 분리한 사용자 정의 다중 이벤트 SSE 아키텍처 설계.
- **비용/속도 최적화:** 로컬 임베딩 모델을 적용하여 벡터 연산 비용을 제거하고, 고부하 다국어 추론에만 외부 LLM을 배치.

---

### 📬 Contact
- **Email:** ysn6514@gmail.com
