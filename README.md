# 온톨로지 · 지식그래프 · GraphRAG 관계 인포그래픽

온톨로지(Ontology) · 지식그래프(Knowledge Graph) · GraphRAG의 **관계와 시너지 구조**를 한 장으로 정리한 인포그래픽입니다.

## 보기

- 웹 페이지: https://smmgcho-cmd.github.io/ontology-kg-graphrag/
- 이미지(PNG, 2800×10676): `ontology-kg-graphrag-infographic.png`
- 인쇄용 PDF: `ontology-kg-graphrag-infographic.pdf`

## 구성

1. 세 층의 정체와 경계 — 온톨로지(계약·T-Box) / 지식그래프(사실·A-Box) / GraphRAG(검색·검증 런타임)
2. 관계도 — 데이터 흐름(본류) · 규칙 경로 · 환류
3. 자기 강화 루프 — 회차마다 스키마·추출·검색이 강해지는 원리
4. AI가 설계하고, 도메인 전문가가 검증한다 — 초안 자동화와 승인 게이트
5. 두 개씩 짝지어 본 관계 — 각 쌍을 잇는 **구현 기술 스택** 포함
6. 셋이 붙을 때 생기는 시너지 8
7. 벤치마킹한 사례 — 공개 표준·제품 문서·논문
8. 도입 판단 기준과 흔한 실패

## 근거와 한계

- 인용한 사례는 **공개 표준·제품 문서·논문을 직접 열어 확인한 내용**만 담았습니다(각 항목에 출처 링크).
- 확인하지 못한 성능 수치·고객 사례·내부 자료는 넣지 않았습니다.
- 그림의 구조 정리(3계층·규칙/환류/자기강화·시너지)는 작성자의 해석입니다.

## 주요 출처

- W3C OWL 2 Overview — https://www.w3.org/TR/owl2-overview/
- W3C SHACL — https://www.w3.org/TR/shacl/
- W3C PROV-O — https://www.w3.org/TR/prov-o/
- GraphRAG 논문 — https://arxiv.org/abs/2404.16130
- KAG 논문 — https://arxiv.org/abs/2409.13731
- Microsoft GraphRAG 문서 — https://microsoft.github.io/graphrag/index/overview/ · https://microsoft.github.io/graphrag/prompt_tuning/auto_prompt_tuning/
- Neo4j GraphRAG (Python) — https://neo4j.com/docs/neo4j-graphrag-python/current/
- AWS graphrag-toolkit — https://github.com/awslabs/graphrag-toolkit
- Palantir Foundry Ontology 문서 — https://www.palantir.com/docs/foundry/ontology/overview
- Stardog Voicebox — https://www.stardog.com/voicebox/
- Google Knowledge Graph 발표 — https://blog.google/products/search/introducing-knowledge-graph-things-not/

## 파일

| 파일 | 설명 |
|---|---|
| `index.html` | 인포그래픽 (자체 완결 HTML, 외부 의존 없음) |
| `ontology-kg-graphrag-infographic.png` | 이미지 버전 |
| `ontology-kg-graphrag-infographic.pdf` | 인쇄·공유용 PDF |
