# 제품 UI 캡처 이미지

이 폴더에 캡처 파일을 올리고, `index.html`에서 해당 항목의 `<img>` 주석만 풀면 됩니다.
안내 문구(점선 상자)는 이미지가 들어오면 자동으로 사라집니다.

```html
<figure class="shot">
  <!-- <img src="shots/ransomware-model.png" alt="랜섬웨어 탐지 모델 화면 캡처"> -->
  <figcaption>제품 UI 캡처 위치<br><code>shots/ransomware-model.png</code></figcaption>
</figure>
```

위 주석 기호(`<!--`, `-->`)를 지우면 이렇게 됩니다.

```html
<figure class="shot">
  <img src="shots/ransomware-model.png" alt="랜섬웨어 탐지 모델 화면 캡처">
  <figcaption>제품 UI 캡처 위치<br><code>shots/ransomware-model.png</code></figcaption>
</figure>
```

## 파일 목록

| 파일명 | 프로젝트 |
|---|---|
| `training-pipeline-01.png` ✅ | 랜섬웨어 탐지 모델 학습 파이프라인 고도화 — 전처리 판정 대시보드 |
| `training-pipeline-02.png` ✅ | 랜섬웨어 탐지 모델 학습 파이프라인 고도화 — 학습 대상 샘플 목록 |
| `training-pipeline-03.png` ✅ | 랜섬웨어 탐지 모델 학습 파이프라인 고도화 — 재학습 워크플로우 |
| `malware-analysis.png` | 악성코드 통합 분석 기능 개발 |
| `pe-similarity-engine.png` | PE 실행파일 유사도 검색 및 MLP 기반 이상치 탐지 엔진 개발 (Rust 네이티브 인코더 전환 포함) |
| `rag-docstory.png` | 공공기관 문서 관리용 RAG AI 에이전트(DocStory Insight) (MCP 서버 구축 및 도구 연동 포함) |
| `ml-predict-api.png` | PE 정적 파일 학습 데이터 기반 악성코드 예측 머신러닝 서버 개발 |
| `dept-policy.png` | 인사 DB 연동 기반 부서별 솔루션 정책 관리 기능 개발 |
| `log-query-perf.png` | 디자인 패턴 적용 및 성능 개선 리팩터링, 테스트 코드 작성 |
| `devops-gitlab-jenkins.png` | 백엔드 팀 개발 환경 개선 |
| `spring-renewal.png` | 자사 솔루션 PHP 웹 서버의 Spring Boot 리뉴얼 |
| `security-verification.png` | 자사 솔루션 국정원 보안적합성 검증 시험 프로젝트 |
| `seoul-cyber-app.png` | 서울사이버안전센터 실증사업 (침해 대응 애플리케이션) |
| `vuln-diagnosis.png` | 전자정부프레임워크 기반 취약점 진단 웹 페이지 개발 |
| `multimodal-auth.png` | 멀티모달 인증 시스템 개발 |
| `otp-console.png` | OTP 인증 웹 관리 콘솔 개발 |
| `demo-site.png` | 인증 솔루션 연동 데모 사이트 개발 |
| `signature-analysis-01.png` ✅ | 서명 수집 · 분석 시스템 개발 — 인증 현황 대시보드 |
| `signature-analysis-02.png` ✅ | 서명 수집 · 분석 시스템 개발 — 서명 분석 정보 |
| `customer-deploy-01.png` ✅ | 고객사 인증 시스템 구축 — 사용자 관리 |
| `customer-deploy-02.png` ✅ | 고객사 인증 시스템 구축 — 인증 현황 대시보드 |
| `personal-koosi-main.png` ✅ | 외주 — 한국안전원(주) 웹사이트 |
| `personal-koosi-edu.png` ✅ | 외주 — 한국안전원(주) 에듀센터 |
| `personal-koosi-qr.png` ✅ | 외주 — 종사자 의견 QR 수집시스템 |

✅ 표시는 이미 적용된 이미지입니다.

## 한 프로젝트에 두 장 이상 넣기

`figure.shot`을 `div.shot-row`로 감싸면 나란히 배치됩니다. 화면이 좁아지면 자동으로 세로로 쌓입니다.

```html
<div class="shot-row">
  <figure class="shot"><img src="shots/customer-deploy-01.png" alt="..."></figure>
  <figure class="shot"><img src="shots/customer-deploy-02.png" alt="..."></figure>
</div>
```

## 파일명 규칙

한글 파일명은 시스템마다 유니코드 정규화 방식(NFC/NFD)이 달라 GitHub Pages에서 404가 날 수 있습니다.
영문 소문자와 하이픈만 쓰는 편이 안전합니다.

파일명은 자유롭게 바꿔도 됩니다. 바꿀 경우 `index.html`의 `src` 값도 같이 고쳐주세요.

## 캡처 전 확인할 것

공개 페이지에 올라가는 이미지입니다. 캡처 안에 아래 내용이 없는지 확인해 주세요.

- 고객사명, 기관명, 담당자 이름, 사번, 이메일, 내부 IP, 호스트명
- 실제 악성코드 해시나 샘플 경로, 내부 서버 주소
- 사내 시스템 URL, 계정 정보, 토큰

가리는 편이 안전한 부분은 캡처 단계에서 모자이크 처리하거나, 값을 더미로 바꿔 띄운 화면을 찍는 방법을 권합니다.
재직 중인 회사의 제품 화면이므로 공개 가능 범위를 회사 쪽에 먼저 확인하시는 편이 좋습니다.

## 권장 사양

- 형식: PNG (스크린샷), 사진성 이미지는 JPG
- 가로: 1200~1600px 정도면 충분합니다. 페이지 본문 폭에 맞춰 자동으로 축소됩니다.
- 용량: 파일당 500KB 이하를 권장합니다. GitHub Pages는 저장소 1GB, 월 100GB 트래픽 제한이 있습니다.
