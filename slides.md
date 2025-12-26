---
theme: apple-basic
title: Juhyun Nam - Naver Labs Interview
info: |
  https://juhyun-nam.github.io/slide-naverlabs-interview/
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
duration: 20min
fonts:
  sans: Noto Sans Korean, sans-serif
  mono: JetBrains Mono
layout: center
hideInToc: true
---

# 남주현 - 네이버랩스 1차 인터뷰

2025.12.29

---
hideInToc: true
---

# 목차

<style>
  a {
    border-style: none !important;
  }
</style>

<Toc listClass="list-disc list-inside" maxDepth="1" />

---

# 자기소개

<br />

<div class="p-6 rounded-2xl bg-black/5">
  새로운 도메인에서도 기초부터 구조를 이해하며 시스템을 설계해온 소프트웨어 엔지니어입니다.
</div>

<br />

<style>
  li {
    font-weight: 400;
  }
</style>

- 8년 이상 경력의 소프트웨어 엔지니어
- 데이터베이스 병렬 처리 엔진 개발로 커리어 시작
- 고성능, 대규모, 분산 시스템 중심의 플랫폼 개발 경험
- 카카오에서 머신러닝 플랫폼 파트 리드 경험
- 최근에는 그래프 저장소, 형태소 분석기 등 성능 중심 시스템 개발

---
transition: slide-up
---

# 경력

<div class="grid grid-cols-2 gap-6 mt-8 text-left">
  <div class="p-6 rounded-2xl bg-black/5">
    <div class="text-sm opacity-70">2017 – 2020</div>
    <div class="text-2xl font-bold mt-1">티맥스티베로</div>
    <div class="text-base font-semibold opacity-80 mt-1">
      데이터베이스 병렬 처리 엔진 연구원
    </div>
    <ul class="mt-4 list-disc list-inside space-y-1 text-base opacity-90">
      <li>병렬 처리 엔진 설계 및 개발</li>
      <li>대용량 데이터베이스 성능 최적화</li>
    </ul>
  </div>

  <div class="p-6 rounded-2xl bg-black/5">
    <div class="text-sm opacity-70">2020 – 현재</div>
    <div class="text-2xl font-bold mt-1">카카오</div>
    <div class="text-base font-semibold opacity-80 mt-1">추천팀</div>
    <ul class="mt-4 list-disc list-inside space-y-1 text-base opacity-90">
      <li>MLSaaS 플랫폼 설계 및 개발</li>
      <li>머신러닝 플랫폼 파트 Lead</li>
      <li>형태소 분석기, 추천 API 등 고성능 시스템 개발</li>
    </ul>
  </div>
</div>

---

## 경력 상세 – 티맥스티베로

<div class="mt-4 p-6 rounded-2xl bg-black/5">
  <div class="text-sm opacity-70">2017 – 2020</div>
  <div class="text-2xl font-bold mt-1">티맥스티베로</div>
  <div class="text-base font-semibold opacity-80 mt-1">
    DB에서 조인, 정렬, 집계 등 대용량 연산을 병렬로 처리하는 엔진의 설계와 구현 및 유지보수 담당
  </div>
  <ul class="mt-4 list-disc list-inside space-y-1 text-base opacity-90">
    <li>기존 데이터베이스 제품의 병렬 처리 기능 유지보수 및 성능 개선</li>
    <li>테라 바이트급 데이터베이스 성능 최적화 프로젝트 수행</li>
    <li>Modern C++, 디자인 패턴 등 관련 세미나/스터디 주도</li>
    <li>코드 리뷰와 리팩토링 프로세스 도입으로 개발 문화 개선</li>
  </ul>
</div>

---

## 경력 상세 – 카카오

<div class="mt-4 p-6 rounded-2xl bg-black/5">
  <div class="text-sm opacity-70">2020 – 현재</div>
  <div class="text-2xl font-bold mt-1">카카오</div>
  <div class="text-base font-semibold opacity-80 mt-1">
    카카오의 서비스에 사용되는 추천 시스템의 플랫폼 개발 및 운영 담당
  </div>
  <ul class="mt-4 list-disc list-inside space-y-1 text-base opacity-90">
    <li>머신러닝 플랫폼 개발 담당 / 개발 Lead</li>
    <li>그래프 저장소, 형태소 분석기 등 고성능 시스템 개발 담당</li>
    <li>개발 프로세스·문화 개선: CI/CD, GitOps, 코드 리뷰, 커밋 로그 관리, 기술 세미나 운영</li>
    <li>애자일 프로세스 정착: 스토리 포인트 기반 Jira 운영, 플래닝·회고·백로그 교육 진행</li>
    <li>인재 영입 기여: 코딩 테스트 및 기술 과제 설계, 면접 가이드라인 마련</li>
  </ul>
</div>

---

# 기술 역량

<div class="mt-4 grid grid-cols-2 gap-4 mx-auto text-left">

  <div>
    <div class="text-sm font-semibold opacity-60 mb-2">
      개발 언어 · 도구
    </div>
    <div class="leading-relaxed text-sm">
      <ul class>
        <li>C++ 11/14/17/20 경험 다수. CMake, Core Guidelines</li>
        <li>Rust (Tokio 기반 비동기, lock/atomic 동시성 제어) 경험 다수</li>
        <li>Python API 서버, 데이터 처리, 자동화 스크립트 작성 경험 다수</li>
        <li>TypeScript 기반 프론트엔드 및 Node.js 백엔드 개발 경험</li>
        <li>Go, SQL, Bash 등 기타 언어 경험</li>
      </ul>
    </div>
  </div>

  <div>
    <div class="text-sm font-semibold opacity-60 mb-2">
    플랫폼 · 인프라
    </div>
    <div class="leading-relaxed text-sm">
      <ul>
        <li>Kubernetes 클러스터 운영, Helm 차트 작성, Controller 개발 경험</li>
        <li>Kafka 기반 대규모 데이터 파이프라인 구축 및 운영 경험</li>
        <li>관계형(MySQL, PostgreSQL) 및 NoSQL(Redis, MongoDB) 경험</li>
        <li>ArgoCD, Prometheus & Grafana 등 클라우드 인프라 경험</li>
      </ul>
    </div>
  </div>

  <div>
    <div class="text-sm font-semibold opacity-60 mb-2">
    설계 · 아키텍처
    </div>
    <div class="leading-relaxed text-sm">
      <ul>
        <li>MSA, 이벤트 기반 아키텍처, DDD, Clean Architecture</li>
        <li>OOP 및 디자인 패턴, 병렬 처리 및 분산 시스템 설계</li>
        <li>성능 최적화 및 튜닝, TDD, CI/CD, GitOps</li>
      </ul>
    </div>
  </div>

  <div>
    <div class="text-sm font-semibold opacity-60 mb-2">
    운영 · 협업
    </div>
    <div class="leading-relaxed text-sm">
      <ul>
        <li>애자일 개발 프로세스 (Scrum, Kanban)</li>
        <li>Jira, Confluence 등 협업 도구 활용</li>
        <li>멘토링 및 팀 리딩 경험</li>
        <li>OKR 설정 및 관리</li>
      </ul>
    </div>
  </div>

</div>

---
transition: slide-up
---

# 대표 프로젝트 소개

- MLSaaS 플랫폼 개발 1
- MLSaaS 플랫폼 개발 2
- 경량 형태소 분석기 개발

---
transition: slide-up
---

## 대표 프로젝트 - MLSaaS 플랫폼 개발 1

<style>
  ul {
    margin-bottom: 0;
  }
</style>

<span class="text-sm m-0">
  (2021 - 2023)
</span>

<div class="mt-10 items-center grid gap-x-8 gap-y-4 text-left mx-auto" style="grid-template-columns: auto 1fr;">
  <div class="text-sm font-semibold opacity-60">
    프로젝트 요약
  </div>
  <div class="leading-relaxed">
    카카오 내 많은 서비스에 추천 기능을 서비스 형태로 제공하는 ML as a Service 플랫폼
  </div>
  <div class="text-sm font-semibold opacity-60">
    역할
  </div>
  <div class="leading-relaxed">
    플랫폼 아키텍처 설계 및 개발 Lead (추후 파트 Lead)
  </div>
  <div class="text-sm font-semibold opacity-60">
    핵심 기여
  </div>
  <div class="text-base leading-relaxed">
    <ul>
      <li>아키텍처 설계 및 기술 스택 선정</li>
      <li>핵심 컴포넌트 개발 (스케줄러, 프레임워크 등)</li>
      <li>코칭 및 코드 리뷰를 통한 팀 역량 강화</li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    결과
  </div>
  <div class="leading-relaxed">
    다음 슬라이드에서 설명
  </div>

  <div class="text-sm font-semibold opacity-60">
    기록
  </div>
  <div class="text-sm opacity-80">
    <ul>
      <li><a href="https://tech.kakao.com/posts/555">추천팀의 DDD 도입기</a></li>
      <li><a href="https://tech.kakao.com/posts/571">파이썬과 러스트</a></li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    기술 키워드
  </div>
  <div class="text-sm opacity-80">
    Kubernetes · MSA · DDD · Kafka · Python · Rust · Go
  </div>
</div>

---

### 결과 · 학습

<!-- (추천 업무 생산성 vs 서비스 품질 vs 비즈니스) -->

<style>
  ul {
    margin-bottom: 0;
  }
</style>

<div class="mt-10 items-center grid gap-x-8 gap-y-6 text-left text-sm max-w-5xl mx-auto" style="grid-template-columns: auto 1fr;">
  <div class="text-sm font-semibold opacity-60">
    관찰
  </div>
  <div class="leading-relaxed">
    <ul class="mb-0">
      <li>플랫폼의 목표와 방향성이 이해관계자 간에 명확히 정렬되지 않은 상태</li>
      <li>추천 업무 특성상 엔지니어링 개입과 문제별 최적화가 필수적이었으나, 플랫폼은 자동화 자체에 초점을 두고 있었음</li>
      <li>플랫폼 운영 비용이 지속적으로 증가했지만, 팀의 최우선 과제인 추천 품질 및 개발 생산성 향상으로 연결되지 않음</li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    판단
  </div>
  <div class="leading-relaxed">
    <ul>
      <li>플랫폼의 목표와 성공 기준이 불명확한 상태에서는 기술적 완성도를 높여도 실질적인 가치로 이어지기 어렵다고 판단</li>
      <li>추천 문제의 특성상 자동화보다 문제별 엔지니어링 역량이 더 큰 효과를 낼 수 있는 단계라고 판단</li>
      <li>이 상태로 플랫폼을 확장하는 것은 향후 더 큰 운영 비용과 기술 부채를 초래할 가능성이 높다고 판단</li>
  </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    결정
  </div>
  <div class="leading-relaxed">
    프로젝트 리드로서 프로젝트 중단과 방향 재정의를 제안했고, 조직 합의를 통해 종료했습니다.
  </div>
</div>

<div class="mt-8 text-base opacity-75 text-center">
  → 플랫폼은 기술적 완성 이전에, 대상 사용자·목표·성공 기준이 먼저 명확히 정의되어야 함
</div>

---

## 대표 프로젝트 - MLSaaS 플랫폼 개발 2

<span class="text-sm m-0">
  (2024.06 - 2024.12)
</span>

<div class="mt-4 items-center grid gap-x-8 gap-y-4 text-left max-w-5xl mx-auto" style="grid-template-columns: auto 1fr;">
  <div class="text-sm font-semibold opacity-60">
    프로젝트 요약
  </div>
  <div class="text-lg leading-relaxed">
    추천팀과 협업하는 서비스팀이 개인화 추천 API를 직접 생성·운영할 수 있는 플랫폼
  </div>

  <div class="text-sm font-semibold opacity-60">
    역할
  </div>
  <div class="text-base leading-relaxed">
    플랫폼 아키텍처 설계 및 주요 컴포넌트 개발 전반 담당
  </div>

  <div class="text-sm font-semibold opacity-60">
    핵심 기여
  </div>
  <div class="text-base leading-relaxed">
    <ul>
      <li>
        사용자 데이터 연동 후 모델 선택 → 추천 API 배포까지의 표준화된 플랫폼 흐름 설계
      </li>
      <li>
        추천 API의 기반이 되는 모델 템플릿 생성·관리 구조 설계 및 구현
      </li>
      <li>
        추천 모델 운영을 위한 모델 저장소 및 라이프사이클 관리 기능 구축
      </li>
      <li>
        인증/인가, Observability, 장애 알림 등 운영 필수 기능을 플랫폼 책임으로 통합
      </li>
      <li>
        Next.js 기반 웹 UI 제공으로 서비스 팀의 셀프 서비스 환경 구현
      </li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    결과
  </div>
  <div class="text-base leading-relaxed">
    <ul>
      <li>
        서비스 팀이 클릭 몇 번으로 추천 API 생성 가능
      </li>
      <li>
        신규 서비스 적용 속도 단축 및 추천팀 개발 리소스 절감
      </li>
      <li>
        모니터링·시각화 체계 도입으로 운영 효율성과 장애 대응 속도 개선
      </li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    기술 키워드
  </div>
  <div class="text-sm opacity-80">
    Kubernetes · CRD · Rust · Helm · OAuth2 · Frontend (React)
  </div>
</div>

---

## 대표 프로젝트 - 경량 형태소 분석기 개발

<style>
  ul {
    margin-bottom: 0;
  }
</style>

<span class="text-sm m-0">
  (2025.04 - 2025.07)
</span>

<div class="mt-10 items-center grid gap-x-8 gap-y-4 text-left mx-auto" style="grid-template-columns: auto 1fr;">
  <div class="text-sm font-semibold opacity-60">
    프로젝트 요약
  </div>
  <div class="text-lg leading-relaxed">
    모바일 애플리케이션에 탑재되는 경량 형태소 분석기 라이브러리 개발
  </div>

  <div class="text-sm font-semibold opacity-60">
    역할
  </div>
  <div class="text-base leading-relaxed">
    설계부터 구현까지 전반을 담당
  </div>

  <div class="text-sm font-semibold opacity-60">
    핵심 기여
  </div>
  <div class="text-base leading-relaxed">
    <ul>
      <li>모바일 환경을 고려한 C++ 기반 경량 라이브러리 구조 설계 및 구현</li>
      <li>메모리 사용량과 처리 속도의 트레이드오프를 고려한 알고리즘 선택</li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    결과 · 영향
  </div>
  <div class="text-base leading-relaxed">
    <ul>
      <li>프로젝트 POC 성공 및 모바일 앱 탑재 논의 진행</li>
      <li>기존 형태소 분석기 사전 데이터 크기 89% 절감</li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    기록
  </div>
  <div class="text-sm opacity-80">
    <ul>
      <li><a href="https://tech.kakao.com/posts/805">초경량 클래식 형태소 분석기 개발기</a></li>
    </ul>
  </div>

  <div class="text-sm font-semibold opacity-60">
    기술 키워드
  </div>
  <div class="text-sm opacity-80">
    C++ · 연산 최적화 · 데이터 압축 알고리즘
  </div>
</div>

---

# 마무리

<style>
  p {
    margin-bottom: 2rem;
  }
</style>

<div class="mt-16 text-base opacity-85 max-w-3xl mx-auto text-center">

새로운 도메인에서도 기초부터 구조를 이해하며 시스템을 설계해온 소프트웨어 엔지니어입니다.

이 경험을 토대로 <b>Robot OS 플랫폼 엔지니어로서</b> 안정적이고 확장 가능한 시스템 설계에 기여할 수 있다고 생각합니다.

감사합니다.

</div>
