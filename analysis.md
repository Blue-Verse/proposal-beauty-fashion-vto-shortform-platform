# AI 기반 뷰티/패션 가상 피팅(VTO) 및 숏폼 영상 생성 플랫폼 — 제안 분석 로그

> 생성일: 2026-03-13
> 공고 URL: https://www.wishket.com/project/153111/

## 1. 공고 파싱 결과

```yaml
job:
  title: "AI 기반 뷰티/패션 가상 피팅(VTO) 및 숏폼 영상 생성 플랫폼 구축"
  category: "AI / 웹 / 개발·디자인·기획"
  budget_range: "70,000,000원 (조율 가능)"
  duration: "120일 (조율 가능)"
  tech_stack: [AI 엔진(제안), Backend(제안), Frontend(제안), AWS GPU, RunPod]
  description: "AI 기술을 활용하여 뷰티 및 패션 제품을 가상 모델에 피팅하고, 다양한 컨셉의 이미지와 숏폼 영상을 생성하는 플랫폼 구축"
  requirements:
    - AI 모델 생성 및 커스터마이징 엔진 (프리셋 + 커스텀 프롬프트 + Face Swap)
    - 뷰티 VTO (메이크업 피팅, Hex 색상, 비포/애프터)
    - 패션 VTO (의류 착장, 코디 매칭, 6종 앵글)
    - Image-to-Video 숏폼 영상 생성 (5~7초)
    - 배경 생성 (프롬프트/레퍼런스), 편집 도구 (누끼, 업스케일링)
    - 웹 UI + 관리자 페이지 (PC Web 반응형)
  client_questions: []
  deadline: "2026-03-17"
  job_post_url: "https://www.wishket.com/project/153111/"
  urls: []
  images: []
```

## 2. URL/이미지 분석

참고 URL/이미지 없음 — 건너뜀.

## 3. 실현 가능성 분석 (내부용)

- **프로젝트 유형**: AI 파이프라인 + 웹 플랫폼 → "조건부 가능" (+20% 버퍼)

### 기본 공수 산정 (AI 보조 없이)

| 작업 영역 | 기본 M/D | AI 절감률 | 조정 M/D |
|-----------|---------|----------|---------|
| 기획/설계 | 15 | 35% | 10 |
| Figma 디자인 | 12 | 15% | 10 |
| AI 엔진 개발 | 55 | 40% | 33 |
| FE 개발 | 25 | 65% | 9 |
| BE 개발 | 28 | 55% | 13 |
| QA/배포 | 15 | 55% | 7 |
| **합계** | **150** | | **82** |

- 버퍼 +20% (AI 파이프라인 복잡도) → **99 M/D**
- 달력 일수: 99 × (7/5) = **139일**
- 클라이언트 예상 기간: **120일**
- 차이: 19일 (15.8% 초과, 20% 이내)
- **판정**: 120일로 제안 가능, 단계별 납품(MVP 우선) 전략으로 리스크 관리

### AI 엔진 절감률 40% 적용 근거
- VTO는 기존 오픈소스 모델(IDM-VTON, CatVTON 등) 기반 파이프라인 통합이 핵심
- 모델 학습/훈련이 아닌 추론 파이프라인 구축이므로 AI 코딩 보조 효과 높음
- Face Swap(InsightFace), I2V(SVD)도 기존 라이브러리 활용

## 4. 포트폴리오 매칭

| 포트폴리오 | 매칭 점수 | 근거 |
|-----------|----------|------|
| AI Agent | ★★★★★ | AI 파이프라인 오케스트레이션, 멀티 모델 관리, 비동기 작업 큐 |
| Series-B | ★★★★☆ | 대규모 웹 플랫폼(1,652 PR), AI 연동(ChatGPT), 관리자 대시보드 |
| Harmony Link | ★★★★☆ | AI 분석(OpenAI), 대용량 파일 처리, 관리자 페이지, SaaS 아키텍처 |

## 5. 최종 제안 요약

- **지원 금액**: 63,000,000원 (VAT 별도) — 클라이언트 예상 70M의 90%
- **지원 기간**: 120일 (4개월)
- **핵심 제안 포인트**:
  1. SDXL + ControlNet + IP-Adapter 기반 VTO 파이프라인
  2. Identity Preservation 최적화 (제품 로고/패턴/색감 보존)
  3. Celery 비동기 큐 + GPU 최적화 아키텍처
  4. 4단계 마일스톤 (1개월차 PoC → VTO → I2V → 안정화)
  5. AI 파이프라인 오케스트레이션 + 대규모 웹 플랫폼 구축 경험

## 6. 최종 산출물 (8단계 출력 전문)

### 제안서 사이트 URL

https://proposal-beauty-fashion-vto-shortform-platform.pages.dev/

### 지원 금액

63,000,000원

### 지원 기간

120일

### 클라이언트 질문 답변

해당 없음

### 지원 내용

안녕하세요, AI 기반 뷰티/패션 가상 피팅(VTO) 및 숏폼 영상 생성 플랫폼 구축 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-beauty-fashion-vto-shortform-platform.pages.dev/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석

본 프로젝트는 AI 기술(Stable Diffusion 기반)을 활용하여 뷰티/패션 제품의 가상 모델 피팅과 숏폼 영상을 생성하는 플랫폼입니다. 핵심 과제는 다음 3가지입니다:
1) VTO(Virtual Try-On) 파이프라인: 뷰티(메이크업) + 패션(의류) 가상 피팅
2) Image-to-Video: 5~7초 숏폼 영상 자동 생성
3) Identity Preservation: 제품 로고, 패턴, 색감의 원본 유지

SDXL + ControlNet + IP-Adapter 조합의 AI 파이프라인과 Celery 비동기 작업 큐 기반 GPU 오케스트레이션 아키텍처로 성능 목표(이미지 15초, 영상 2분)를 달성하겠습니다.

■ 제안 기술 스택

- AI 엔진: SDXL, ControlNet, IP-Adapter, IDM-VTON, InsightFace, Stable Video Diffusion, ComfyUI, PyTorch
- Backend: FastAPI (Python), Celery + Redis, PostgreSQL, AWS S3
- Frontend: Next.js 14, TypeScript, TailwindCSS, React Query
- Infra: AWS GPU (g5.xlarge) / RunPod, Docker, Nginx

■ 작업 일정

[Phase 1: 기획 및 AI 파이프라인 검증] Day 1~30
- 요구사항 분석 및 기능 명세서 작성
- UI/UX 와이어프레임 및 Figma 디자인
- SDXL + ControlNet + IP-Adapter PoC 검증
- VTO 핵심 파이프라인 검증 (뷰티 1종 + 패션 1종)
- DB 스키마, API 명세서 설계

[Phase 2: 뷰티/패션 VTO 기능 구현] Day 31~60
- 뷰티 VTO 전체 구현 (메이크업 피팅, Hex 색상, 비포/애프터)
- 패션 VTO 전체 구현 (의류 착장, 6종 앵글)
- Face Swap 기능 (InsightFace)
- AI 모델 선택/생성 엔진 (프리셋 + 커스텀 프롬프트)

[Phase 3: 영상 생성 및 웹 프론트엔드 연동] Day 61~90
- Image-to-Video 숏폼 영상 생성 (SVD, 5~7초)
- 배경 생성, 편집 도구 (누끼, 업스케일링)
- 코디 매칭, 관리자 페이지, FE-BE-AI 통합

[Phase 4: 통합 테스트 및 안정화] Day 91~120
- 통합 테스트 (이미지/영상 품질 검수)
- Identity Preservation 검수, 성능 최적화
- 매뉴얼 작성 및 인수인계

■ 마일스톤 및 산출물

- M1 (Day 30): 기획서, 디자인, AI PoC 결과
- M2 (Day 60): 뷰티/패션 VTO 데모, Face Swap
- M3 (Day 90): I2V 영상 생성, 웹 UI 통합 데모
- M4 (Day 120): 최종 검수 완료, 소스 코드/가중치 인수인계

■ 미팅 시 협의 필요 사항

- AI 생성 결과물 품질 검수 기준 (Identity Preservation 정량 평가 방법)
- GPU 서버 사양 및 비용 최적화 방안 (AWS vs RunPod)
- AI 모델 프리셋 범위 (초기 프리셋 수량 및 카테고리)
- 월 단위 유지보수 범위 및 GPU 운영 지원 범위
- 이미지/영상 생성 성능 목표 상세 협의 (GPU 사양별)

---

<유사 프로젝트 진행 경험>

▶ AI-Native 개발 프레임워크 (2025~)
- 프로젝트 유형: AI 파이프라인 오케스트레이션 플랫폼
- 핵심 기능: 멀티 AI 프로바이더 오케스트레이션, 134+ 스킬 모듈, 48 API 엔드포인트
- 유사점: AI 파이프라인 관리, 비동기 작업 큐, 멀티 모델 연쇄 처리 아키텍처
- 기술 스택: TypeScript, React, Hono, Claude SDK, PostgreSQL

▶ VC 펀드 관리 플랫폼 — Series-B (2023.11~2024.12)
- 프로젝트 유형: B2B SaaS / 핀테크
- 핵심 기능: PR 1,652건, 50+ 페이지, AI 보고서 생성(ChatGPT), 200-300+ API
- 유사점: 대규모 웹 플랫폼 구축, AI API 연동, 비동기 처리, 관리자 대시보드
- 기술 스택: Next.js, NestJS, TypeScript, MySQL, ChatGPT API, AWS

▶ 시니어 주간보호 관리 플랫폼 — Harmony Link (2025)
- 프로젝트 유형: B2B SaaS / 헬스케어
- 핵심 기능: 133K+ LOC, 140+ API, AI 건강 분석(OpenAI), 6 플랫폼 지원
- 유사점: AI 서비스 통합, 대용량 파일 처리, 관리자 페이지, SaaS 아키텍처
- 기술 스택: Flutter, NestJS, Next.js, OpenAI API, AWS CDK

---

<사용 기술과 툴>

▶ AI 기술
- Stable Diffusion XL, ControlNet, IP-Adapter
- IDM-VTON (Virtual Try-On)
- InsightFace (Face Swap)
- Stable Video Diffusion (Image-to-Video)
- ComfyUI, PyTorch, Python

▶ 개발 기술
- Backend: FastAPI, Celery, Redis, PostgreSQL
- Frontend: Next.js 14, TypeScript, TailwindCSS, React Query
- Infra: AWS GPU (g5.xlarge), RunPod, Docker, Nginx, S3

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions
- 클라우드: AWS (GPU Instances)
- 컨테이너: Docker

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues

### 관련 포트폴리오 추천

1. AI-Native 개발 프레임워크 — AI 파이프라인 오케스트레이션 역량
2. VC 펀드 관리 플랫폼 (Series-B) — 대규모 웹 플랫폼 + AI 연동
3. 시니어 주간보호 관리 플랫폼 (Harmony Link) — AI 분석 서비스 + SaaS
