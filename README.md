# Portfolio
제게 GitHub ID와 함께 제 저장소를 보여주는 메일을 보내주세요.
그러면 초대해 드리겠습니다.
감사합니다.

안녕하세요. 이 저장소는 제가 진행한 주요 AI/자동화 프로젝트를 한눈에 볼 수 있도록 정리한 포트폴리오입니다.

## Projects

### 1. LangGraph + LangChain + OpenSearch 기반 LLM 챗봇 및 LangFuse를 통한 모니터링

GitHub: https://github.com/dwChris/LangGraph-LangChain-LangFuse-OpenSearch-Extention

LangGraph, LangChain, Hugging Face Inference API, OpenSearch를 결합한 FastAPI 채팅 및 RAG 프로젝트입니다. 로컬 파일 첨부 저장과 벡터 검색을 지원하고, 필요할 때 외부 검색 API를 함께 사용할 수 있도록 구성했습니다. 기본 모델은 `Qwen2.5-7B-Instruct`입니다.

주요 포인트:

- FastAPI 기반 REST API와 브라우저 UI, CLI 클라이언트 제공
- `POST /chat`과 `POST /chat/stream`으로 일반 응답과 SSE 스트리밍 지원
- 업로드 파일을 `/files` API로 저장, 조회, 삭제하고 RAG 검색에 활용 가능
- LangChain 기반 프롬프트 오케스트레이션과 Hugging Face 모델 교체 지원
- Docker Compose로 앱, MinIO, OpenSearch, LangFuse를 함께 실행 가능

### 2. Whisper 기반 STT 회의록 작성 및 업무 시스템 연계

GitHub: https://github.com/dwChris/VoiceLog

Whisper 기반 음성 인식을 중심으로 회의 내용을 텍스트화하고, HuggingFace 모델을 활용해 요약과 후처리를 수행하는 회의록 플랫폼입니다. 회의 메타데이터 관리, 인증, 웹 프론트엔드, 공통 인프라를 분리한 모듈형 구조로 구성했습니다.

주요 포인트:

- Whisper 기반 STT 파이프라인
- 요약, 분류, 후처리를 위한 HuggingFace 활용
- 회의록 생성, 저장, 조회 흐름 분리
- 공통 인프라, STT/TTS, 회의록 API, 정적 프론트엔드의 모듈형 구조
- HTTPS 기반 마이크 입력 환경을 고려한 운영 설계

### 3. Playwright / Robot Framework 기반 E2E 웹서비스 테스트 솔루션

GitHub: https://github.com/dwChris/E2E_WebServiceTester

웹서비스 테스트의 시나리오 생성과 실행을 분리한 E2E 테스트 솔루션입니다. 자연어 기반 시나리오 정리, 브라우저 grounding, Robot Framework 실행, 실행 결과와 아티팩트 관리까지 이어지는 구조를 지향합니다.

주요 포인트:

- Frontend, Main API, AI Agent, Worker로 역할 분리
- LangChain / LangGraph 기반 시나리오 초안 생성
- Playwright 기반 브라우저 grounding
- Robot Framework 기반 자동화 실행
- PostgreSQL, Redis, Neo4j, MinIO를 활용한 상태 및 아티팩트 관리

## Tech Stack Highlights

- Python, FastAPI, LangChain, LangGraph
- Hugging Face API, Whisper
- OpenSearch, MinIO, PostgreSQL, Redis
- Playwright, Robot Framework
- Docker, Docker Compose

## Contact

- Email: dw_chris@naver.com

---

# Portfolio

Please email me your GitHub ID if you would like to view my repositories.
I will invite you.
Thank you.

This repository is a portfolio that highlights the major AI and automation projects I have worked on.

## Projects

### 1. LangChain + OpenSearch based LLM chatbot

GitHub: https://github.com/dwChris/LangChain-OpenSearch-Extention

This is a FastAPI chat and RAG project that combines LangChain, the Hugging Face Inference API, and OpenSearch. It supports local attachment storage, vector search, and optional external search integration. The default model is `Qwen2.5-7B-Instruct`.

Key points:

- FastAPI-based REST API with a browser UI and CLI client
- Support for both regular responses and SSE streaming through `POST /chat` and `POST /chat/stream`
- Upload, list, and delete files through the `/files` API, and use them in RAG retrieval
- LangChain-based prompt orchestration with Hugging Face model override support
- Docker Compose support for running the app, MinIO, OpenSearch, and LangFuse together

### 2. Whisper-based STT meeting notes and business system integration

GitHub: https://github.com/dwChris/VoiceLog

This is a meeting-notes platform that uses Whisper-based speech-to-text to convert meeting audio into text, then uses Hugging Face models for summarization and post-processing. It is built as a modular system with separate layers for meeting metadata management, authentication, web frontend, and shared infrastructure.

Key points:

- Whisper-based STT pipeline
- Hugging Face for summarization, classification, and post-processing
- Separate flows for meeting note creation, storage, and retrieval
- Modular architecture for shared infrastructure, STT/TTS, meeting notes API, and static frontend
- Deployment design that considers HTTPS microphone input environments

### 3. Playwright / Robot Framework based E2E web service testing solution

GitHub: https://github.com/dwChris/E2E_WebServiceTester

This is an E2E testing solution that separates scenario generation from execution for web services. It aims to connect natural-language scenario preparation, browser grounding, Robot Framework execution, and execution-result / artifact management in one workflow.

Key points:

- Separation of frontend, main API, AI agent, and worker responsibilities
- Scenario draft generation with LangChain / LangGraph
- Browser grounding with Playwright
- Automated execution with Robot Framework
- State and artifact management using PostgreSQL, Redis, Neo4j, and MinIO

## Tech Stack Highlights

- Python, FastAPI, LangChain, LangGraph
- Hugging Face API, Whisper
- OpenSearch, MinIO, PostgreSQL, Redis
- Playwright, Robot Framework
- Docker, Docker Compose

## Contact

- Email: dw_chris@naver.com


