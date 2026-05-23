# 바이브 코딩 교육 프로젝트 — SOP

> 프로젝트명: vibe-coding-edu
> 위치: ~/projectm/vibe-coding-edu/
> 목적: 비전공자를 위한 바이브 코딩 IT 기초 교육 자료 제작 및 유지

---

## 프로젝트 목표

YouTube 영상 `https://youtu.be/2vnr5g4DFqU` 분석을 기반으로
IT 비전공자가 바이브 코딩(AI 보조 개발)을 시작할 수 있도록 돕는
교육 콘텐츠 패키지를 제작·유지한다.

---

## 디렉토리 구조

```
vibe-coding-edu/
├── CLAUDE.md              ← 이 파일 (SOP)
├── source/
│   └── youtube_analysis.md    ← 영상 분석 원본
├── content/
│   └── edu_material_nonit.md  ← 비전공자 교육 자료 (메인)
├── prompts/
│   ├── claude_pptx_prompt.md  ← Claude 앱 PPTX 생성 프롬프트
│   └── notebooklm_guide.md    ← Google NotebookLM 활용 가이드
└── output/                    ← 생성된 결과물 (gitignore)
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

## 핵심 교육 개념 10가지 (변경 금지 목록)

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
