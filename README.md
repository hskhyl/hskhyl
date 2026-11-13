## Who I am

LLM 에이전트를 설계하고 구현합니다. 현업 담당자에게 업무를 듣고, 필요한 데이터를 정리한 뒤, 에이전트가 이를 조회하고 답하는 흐름까지 만듭니다. PoC와 BMT, 파일럿에서 실제 고객사 상주 프로젝트까지 참여하고 있습니다.

## What I work on

- Agent 구조 설계: LangGraph 기반 Master / Sub Agent, Plan-Execute, HITL(interrupt)
- Text2SQL: 집계 테이블 설계, SQL 실행 MCP 서버, DuckDB / PostgreSQL
- RAG: Elasticsearch 필터 검색, Weaviate, 문서 청킹과 메타데이터, 답변 출처 표시
- 운영 품질: Langfuse 토큰 추적, 도구 호출 / 반환 행 수 상한, 프롬프트 다이어트, LLM-as-Judge 평가

## Open Source

| Project | Contribution | Status |
|---|---|---|
| [NVIDIA/NeMo-Agent-Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit) | [#2587](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2587) fix(langchain): keep `langgraph_wrapper` streaming without node messages. LangChain 1.x `create_agent` 미들웨어와 `create_deep_agent`의 스트리밍이 첫 청크에서 끊기던 버그를 수정하고 테스트 8개를 추가했습니다. | Merged · 2026.11 |

## Stack

Python · LangGraph / LangChain · MCP · Elasticsearch · Weaviate · DuckDB · PostgreSQL · Langfuse · OpenRouter · FastAPI

## Background

- Naver Boostcamp AI Tech 7기 (NLP)
