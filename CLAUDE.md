# 바이브 코딩 교육 프로젝트 — SOP

> 프로젝트명: vibe-coding-edu
> 위치: ~/projectm/vibe-coding-edu/
> 목적: 비전공자를 위한 바이브 코딩 IT 기초 교육 자료 제작 및 유지

---

## 프로젝트 목표

YouTube 영상 분석을 기반으로 IT 비전공자가
바이브 코딩(AI 보조 개발)과 온프레미스 네트워크를 쉽게 이해할 수 있도록
교육 콘텐츠 패키지를 제작·유지한다.

---

## 디렉토리 구조

```
vibe-coding-edu/
├── CLAUDE.md                        ← 이 파일 (SOP)
├── source/
│   ├── youtube_analysis.md          ← 영상 분석 원본 (바이브 코딩 편)
│   └── youtube_analysis_network.md  ← 영상 분석 원본 (네트워크 편)
├── content/
│   ├── edu_material_nonit.md        ← 비전공자 교육 자료 — 바이브 코딩 편
│   └── edu_network_basics.md        ← 비전공자 교육 자료 — 네트워크 기초 편
├── prompts/
│   ├── claude_pptx_prompt.md        ← Claude 앱 PPTX 생성 프롬프트 (바이브 코딩)
│   ├── notebooklm_guide.md          ← Google NotebookLM 가이드 (바이브 코딩)
│   ├── network_pptx_prompt.md       ← Claude 앱 PPTX 생성 프롬프트 (네트워크)
│   └── network_notebooklm_guide.md  ← Google NotebookLM 가이드 (네트워크)
└── output/                          ← 생성된 결과물 (gitignore)
```

---

## 콘텐츠 업데이트 원칙

1. 새 YouTube 소스 추가 시 → `source/` 폴더에 분석 파일 추가
2. 교육 자료 개정 시 → `content/edu_material_nonit.md` 버전 업
3. 프롬프트 개선 시 → `prompts/` 파일 직접 수정
4. 결과물(PPTX, PDF 등) → `output/` 저장 (git 제외)

---

## 대상 독자

- IT 비전공 직장인
- AI 코딩 도구(Claude, Cursor)를 처음 접하는 분
- 바이브 코딩으로 간단한 앱을 만들고 싶은 분

---

## Topic 1 — 바이브 코딩 IT 기초 핵심 개념 10가지 (변경 금지)

1. AI 도구 선택 (ChatGPT / Claude / Cursor)
2. CLI vs IDE
3. 소스 → 빌드 → 배포 흐름
4. Git (commit / push / pull)
5. 프론트엔드 vs 백엔드
6. 포트 개념
7. API (HTTP 메서드 4종)
8. JSON
9. 데이터베이스 (SQL vs NoSQL)
10. 배포 서비스 (Vercel / Cloudflare / AWS)

---

## Topic 2 — 온프레미스 네트워크 기초 핵심 개념 10가지 (변경 금지)

1. 인터넷 vs 웹 (도로망 vs 자동차)
2. IP 주소 (우편 주소, IPv4 vs IPv6)
3. TCP (데이터 분할·순서·재전송)
4. HTTP (요청/응답 주문서, 상태코드)
5. 라우터 (교차로 신호등)
6. 스위치 (사무실 내선 교환기)
7. 방화벽 (건물 보안 게이트, 허용 포트)
8. CDN (전국 편의점 물류 거점)
9. DMZ (외부 손님 대기실)
10. Web/WAS/DB 이중화 아키텍처
