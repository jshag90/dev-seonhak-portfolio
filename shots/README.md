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
| `malware-analysis.png` ✅ | 악성코드 통합 분석 기능 개발 — 종합 판단 화면 |
| `prompt-agent-download.png` ✅ 🔒 | 프롬프트 수집 에이전트 — 배포 화면 (API 키 마스킹) |
| `prompt-agent-install-01.png` ✅ | 프롬프트 수집 에이전트 — 설치 콘솔 |
| `prompt-agent-install-02.png` ✅ 🔒 | 프롬프트 수집 에이전트 — 설치 결과 (계정 이메일 · SID 마스킹) |
| `prompt-agent-admin-01.png` ✅ | 프롬프트 수집 에이전트 — 사용자별 제출 현황 |
| `prompt-agent-admin-02.png` ✅ | 프롬프트 수집 에이전트 — 런타임 설정 |
| `prompt-agent-collect-01.png` ✅ | 프롬프트 수집 에이전트 — 해시별 응답 수집 현황 |
| `prompt-agent-collect-02.png` ✅ | 프롬프트 수집 에이전트 — LLM 사례 합의 상세 |
| `pe-similarity-engine.png` | PE 실행파일 유사도 검색 및 MLP 기반 이상치 탐지 엔진 개발 (Rust 네이티브 인코더 전환 포함) |
| `rag-chat-01~04.png` ✅ | RAG 에이전트 — 문서 질의응답과 원문 대조 화면 |
| `rag-app-ui.png` ✅ | RAG 에이전트 — 데스크톱 앱 UI |
| `rag-ingest-flow.svg` ✅ | RAG 에이전트 — 수집 · 청킹 · 임베딩 · 저장 프로세스 |
| `rag-query-flow.svg` ✅ | RAG 에이전트 — 검색 · MCP 도구 호출 · 응답 프로세스 |
| `mcp-docstory.png` ✅ | RAG 에이전트 — DocStory MCP 연결 및 화이트리스트 조회 |
| `mcp-virustotal.png` ✅ | RAG 에이전트 — VirusTotal MCP 연결 및 해시 분석 |
| `docstory-ai-settings.png` ✅ | 예측 ML 서버 — 운영환경의 모델 경로와 판별 기준값 |
| `docstory-whitelist.png` ✅ | 예측 ML 서버 — 화이트리스트 (AI 자동 · 수동 구분) |
| `docstory-score-detail.png` ✅ | 예측 ML 서버 — 예측 score와 EMBER 정적 피처 상세 |
| `docstory-org.png` ✅ 🔒 | 부서별 정책 — 조직 관리 (이름 1건 마스킹) |
| `docstory-org-select.png` ✅ | 부서별 정책 — 조직 선택 |
| `docstory-template-apply.png` ✅ | 부서별 정책 — 템플릿 적용 |
| `docstory-template.png` ✅ | 부서별 정책 — 템플릿 내용 |
| `log-query-perf.png` | 디자인 패턴 적용 및 성능 개선 리팩터링, 테스트 코드 작성 |
| `devops-gitlab-jenkins.png` | 백엔드 팀 개발 환경 개선 |
| `docstory-dashboard.png` ✅ | Spring Boot 리뉴얼 — 대시보드 (crontab 통계) |
| `docstory-clients.png` ✅ | Spring Boot 리뉴얼 — 클라이언트 정보 |
| `docstory-auditlog.png` ✅ | Spring Boot 리뉴얼 — 감사로그 |
| `docstory-report.png` ✅ | Spring Boot 리뉴얼 — 차단 보고서 |
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
| `personal-koosi-main.png` ✅ | 개인 프로젝트 — 한국안전원(주) 웹사이트 |
| `personal-koosi-edu.png` ✅ | 개인 프로젝트 — 한국안전원(주) 에듀센터 |
| `personal-koosi-qr.png` ✅ | 개인 프로젝트 — 종사자 의견 QR 배포 화면 |
| `personal-koosi-qr-form.jpg` ✅ | 개인 프로젝트 — QR 스캔 후 의견 등록 화면 (모바일) |
| `personal-koosi-list01-masked.png` ✅ | 개인 프로젝트 — 종사자 의견 관리 목록 (개인정보 마스킹) |
| `personal-koosi-list02-masked.png` ✅ | 개인 프로젝트 — 의견 상세 (개인정보 마스킹) |

✅ 표시는 이미 적용된 이미지입니다. 🔒 표시는 민감 정보를 가린 뒤 올린 이미지입니다.

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

## 마스킹한 캡처

`personal-koosi-list01/02`는 고객사 종사자의 실명 · 휴대폰번호 · 소속회사와 작업자 얼굴 사진이 담겨 있어
원본을 `.gitignore`로 차단하고 가린 사본만 커밋합니다. 원본은 로컬에만 있습니다.

다시 가려야 할 일이 생기면 Pillow로 처리할 수 있습니다.

```python
from PIL import Image, ImageDraw
im = Image.open("shots/원본.png").convert("RGBA")
ImageDraw.Draw(im).rectangle([x1, y1, x2, y2], fill=(200, 205, 210, 255))
im.save("shots/원본-masked.png")
```

## 권장 사양

- 형식: PNG (스크린샷), 사진성 이미지는 JPG
- 가로: 1200~1600px 정도면 충분합니다. 페이지 본문 폭에 맞춰 자동으로 축소됩니다.
- 용량: 파일당 500KB 이하를 권장합니다. GitHub Pages는 저장소 1GB, 월 100GB 트래픽 제한이 있습니다.
