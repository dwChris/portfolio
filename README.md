# Portfolio
제게 GitHub ID와 함께 제 저장소를 보여주는 메일을 보내주세요.
그러면 초대해 드리겠습니다.
감사합니다.

안녕하세요. 이 저장소는 제가 진행한 주요 AI/자동화 프로젝트를 한눈에 볼 수 있도록 정리한 포트폴리오입니다.

## Projects

### 1. LangChain + OpenSearch 기반 LLM 챗봇

GitHub: https://github.com/dwChris/LangChain-OpenSearch-Extention

OpenSearch 기반 RAG와 LangChain을 결합한 FastAPI 챗봇 프로젝트입니다. Hugging Face API를 통해 `Qwen2.5-7B-Instruct` 모델을 사용하고, 외부 검색 결과나 업로드 파일을 함께 활용할 수 있도록 설계했습니다.

주요 포인트:

- FastAPI 기반 REST API와 간단한 웹 UI 제공
- LangChain을 활용한 모델 오케스트레이션
- Hugging Face API 연동 및 모델 교체 지원
- OpenSearch 기반 벡터 검색과 첨부파일 검색 지원
- Docker Compose로 `app`, `minio`, `opensearch`를 함께 실행 가능

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

This is a FastAPI chatbot project that combines OpenSearch-based RAG with LangChain. It uses the `Qwen2.5-7B-Instruct` model through the Hugging Face API and is designed to work with external search results and uploaded files.

Key points:

- FastAPI-based REST API with a simple web UI
- Model orchestration with LangChain
- Hugging Face API integration and model override support
- OpenSearch-based vector search and attachment search support
- Docker Compose support for running `app`, `minio`, and `opensearch`

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


