# 조영진 / Android SDK · Platform Engineer

> **9년차 Android SDK · Platform Engineer** / **200+ 기업 · 1,000만+ 사용자** 모바일 SDK 메인 개발 / **50만+ 다운로드 서비스 앱 개발·운영** / **AI 기능 출시 · 온디바이스 AI SDK 개발**

| | |
|---|---|
| **포지션** | Android SDK · Platform Engineer |
| **직책** | 책임연구원 (AI 연구 2팀) |
| **소속** | 라온시큐어 (RaonSecure), 2018.04 ~ 현재 |
| **포트폴리오** | https://yjcho9317.github.io/android-portfolio |
| **GitHub** | https://github.com/yjcho9317 |
| **블로그** | https://velog.io/@yjcho9317 / https://yjcho9317.tistory.com |
| **병역** | 군필 (육군 병장 만기전역, 2013.02 ~ 2014.11) |

---

## Summary

- **Android SDK · Platform** — **200+ 기업 / 1,000만+ 사용자** 모바일 SDK 메인 개발. Android 5~16 · OEM 4사 · Public API 하위 호환 · NDK/JNI · 고객사 연동. Java→Kotlin·멀티모듈 점진 전환, 고객사 코드 수정 없이 업데이트.
- **Android App** — **50만+ 다운로드 / 평점 4.5 서비스 앱**. 구조 전환 · 신규 기능 · AI 기능 출시 · Play Store 운영.
- **AI Application · Deployment** — **50만+ 다운로드 앱에 AI 기능 출시**. 현재 Android/iOS 공통 온디바이스 AI SDK 설계·개발 메인.

---

## 기술 스택

- **Android SDK · Platform** — Android SDK · Kotlin · Java · NDK/JNI · C/C++ · AIDL/IPC · Public API 설계·하위 호환 · AAR · ProGuard/R8 · OEM 호환성 · 멀티모듈 · WorkManager · CMake
- **Android Application** — Coroutines/Flow · Hilt · Jetpack Compose · Room · Retrofit · ML Kit · Firebase Crashlytics/Analytics
- **iOS SDK** — Swift · Objective-C
- **AI Application · Deployment** — ONNX Runtime · NNAPI · XNNPACK · TFLite · CoreML · 양자화
- **ML · MLOps** — Python · PyTorch · MLflow · FastAPI · Docker
- **AI Agent · MCP** — LangGraph · n8n · MCP · TypeScript · OAuth
- **테스트 · CI/CD** — JUnit · GoogleTest · Jenkins · GitHub Actions

---

## 경력

**라온시큐어** · AI 연구 2팀 · 책임연구원 · 2018.04 ~ 현재

- KISA 온디바이스 딥페이크 탐지 SDK 과제 · SDK 설계·개발 메인 · 2026.04 ~ 현재 · 2026.10 (예정)
- AI 악성앱 탐지 · 개발 리드 (2026.02 ~ 현재)
- 클라우드 서비스 전환 · 앱 개발 리드 (2025.02 ~ 2025.10)
- AI 딥페이크 탐지 · 앱 개발 리드 (2024.04 ~ 2024.12)
- 라온 모바일 시큐리티 · Android 앱 개발 및 운영 (2021.07 ~ 현재)
- TouchEn mVaccine · Android/iOS SDK 메인 개발자 (2019.04 ~ 현재)
- TouchEn nxKey · macOS App 개발 (2019.04 ~ 2021.09)
- TouchEn Transkey / mTranskey · Web SDK 개발 및 운영 (2018.10 ~ 2021.07)

---

## 메인 프로젝트

#### 1. TouchEn mVaccine SDK / APP

- **역할·기간:** Android/iOS SDK 메인 개발자 · 2019.04 ~ 현재
- **규모:** 금융·공공 **200+ 기업 / 1,000만+ 사용자** · Android **5~16** · 주요 OEM 4사
- **기술:** Android SDK · Kotlin · Java · NDK/JNI · C++ · AIDL/IPC · Coroutines · WorkManager · 멀티모듈 · Objective-C · Swift
- **개요:** 악성앱·루팅·디버깅·통신 위변조를 탐지하는 모바일 보안 SDK. Public API부터 네이티브 레이어, OEM 호환성, 배포·운영까지 담당.
- **주요 경험:**
  - **Public API · 200+ 고객사** — 외부 API 유지, 내부 구조만 단계적으로 변경 → 고객사 마이그레이션 없이 업데이트.
  - **고객사 연동** — ProGuard/R8·의존성 충돌 대응, 연동 가이드·샘플 프로젝트·마이그레이션 문서·릴리즈 노트 운영.
  - **Android 5~16 · OEM 4사** — 삼성/LG/샤오미/Pixel별 차이를 Reflection 기반 호환성 레이어에서 흡수.
  - **멀티모듈 · Java→Kotlin** — `core / detection / ui` 분리, API 시그니처 유지 → 모듈 단위 테스트·선택적 기능 구성. 서비스 앱의 선택적 기능 연동에 활용.
  - **업데이트 안정성** — 패턴/엔진 분리·필요 파일만 분할 업데이트 → 전체 파일 교체 최소화. 실패 시 재시도·무결성 재검증·중복 실행 방지, WorkManager + Coroutines로 백그라운드 작업 정리.
  - **JNI 메모리 릭** — 원인 추적·해결.
  - **클라우드 전환 · 5인 앱 개발팀 리드** — 로컬 DB의 패턴 확장 한계 → 클라우드 전환. 사용량 과금 구조를 지원하고 **패턴 DB 5배+ 확장**, KISA 백신 성능 평가 인증 획득.
  - **iOS** — 탈옥·원격 제어·디버깅 탐지 모듈 개발, Objective-C SDK 유지보수.

관련 링크: https://play.google.com/store/apps/details?id=com.TouchEn.mVaccine.webs

#### 2. 라온 모바일 시큐리티 (서비스 앱)

- **역할·기간:** Android 앱 개발 및 운영 · 2021.07 ~ 현재
- **규모:** **50만+ 다운로드 / 평점 4.5 / 1,000+ 사용자 평가**
- **기술:** Kotlin · Coroutines · Flow · Hilt · Room · Retrofit · MVVM · Jetpack Compose · Firebase Crashlytics/Analytics
- **개요:** mVaccine 탐지 기능을 일반 사용자에게 제공하는 모바일 백신 앱. 악성앱·스미싱·딥페이크 등 10가지+ 보안 기능 운영.
- **주요 경험:**
  - **점진 전환** — Thread/RxJava와 화면 코드가 얽힌 구조 → 화면 단위 MVVM + Coroutines + Flow + Hilt 전환. 정기 릴리즈 유지.
  - **XML + Compose** — 기존 화면은 유지하고 신규 화면부터 Compose 적용 → 전면 재작성 없이 공존 구조 운영.
  - **SDK 기능 재사용** — mVaccine 멀티모듈 구조를 활용해 앱에 필요한 탐지 기능만 선택적으로 연동.
  - **AI 기능 출시 · 2024** — 딥페이크 영상 업로드·URL 입력·결과/랭킹 흐름 구현 및 출시.
  - **서비스 운영** — Play Store 정기 릴리즈, Crashlytics/Analytics, 사용자 리뷰 기반 운영·개선.

관련 링크: https://play.google.com/store/apps/details?id=com.raonsecure.mobile.security

#### 3. AI 딥페이크 탐지

- **역할·기간:** 앱 개발 리드 / 모델 개발 서브 · 6인 팀 · 2024.04 ~ 2024.12
- **기술:** Android SDK · Kotlin · Python · PyTorch · TFLite · I3D · ResNet
- **개요:** 실시간 온디바이스 탐지로 시작해 **실기기 측정 결과를 근거로 클라우드 비동기 구조로 전환**, 라온 모바일 시큐리티에 출시.
- **주요 경험:**
  - **실기기 검증** — TFLite 양자화 모델 적용. MediaProjection 캡처 **720p·30fps 미달**, 추론 지연도 실시간 처리 기준 초과.
  - **구조 전환** — FPS·추론 지연 측정값 공유 → 온디바이스 대신 클라우드 비동기 구조로 전환 결정.
  - **서비스 출시** — 영상 업로드·URL 입력·결과/랭킹 흐름 구현 → **50만+ 다운로드 앱**에 출시.
  - **모델 개발 서브** — 자체 데이터셋 구축·튜닝 → 동양인 탐지 정확도 **65% → 95%**(내부 검증셋).
  - **KISA SDK로 확장** — 실기기에서 확인한 온디바이스 제약을 2026 KISA SDK 설계에 반영.

#### 4. KISA 온디바이스 딥페이크 탐지 SDK 과제

- **역할·기간:** SDK 설계·개발 메인 / 모델 경량화 서브 · 3사 협업 · 2026.04 ~ 현재 · 2026.10 (예정)
- **기술:** Kotlin · Swift · C++ · NDK/JNI · ONNX Runtime · NNAPI · XNNPACK · CoreML · CMake
- **개요:** 서버 없이 Android/iOS 단말에서 딥페이크를 탐지하는 SDK. **C++ 공통 코어, SDK와 분리된 모델 배포, 단말·런타임 호환성, 출력 재현성**을 중심으로 설계·개발.
- **주요 경험:**
  - **크로스플랫폼 · Android + iOS** — Kotlin/Swift 인터페이스 → C++ 공통 코어 → ONNX Runtime 추론 계층으로 분리. 탐지·전처리·후처리를 C++에서 공통화.
  - **모델 교체·배포** — `model + config + golden I/O`를 SDK와 분리 → SDK 재배포 없이 모델 교체. mVaccine 서명 검증 구조를 계승해 암호화·서명 검증을 적용하고, 샘플링 해싱 대신 전체 SHA-256 검증 후 스테이징 교체·실패 시 자동 롤백.
  - **모델 최초 설치 · 14.8초 → 0.3초** — 설치 전 검증과 실제 적재 과정에서 중복되던 복호화를 제거하고 OTA 모델 검증은 유지.
  - **모델 단위 API · 다중 모델·멀티모달** — **모델 1개 = 인스턴스 1개** 구조. 전·후처리 Builder 주입, 모델 갱신 시점은 앱에서 제어.
  - **단말·런타임 호환성** — NNAPI 우선·XNNPACK(CPU) fallback 구성. ARM32 SIGBUS 원인을 ORT 그래프 최적화 단계까지 추적해 문제 최적화만 비활성화.
  - **출력 재현·검증** — 협력사 기준 출력을 **≤ 1e-5** 오차로 재현. C++ 회귀 테스트 **257건** + 실단말 계측 **52건** 검증.
  - **오디오·비주얼 멀티모달** — 멜 스펙트로그램·컬러맵·리샘플링·몽타주 전처리를 Python에서 C++ 공통 코어로 이식.

---

## 기타 프로젝트

#### 보안 동향 보고서 AI 에이전트
- **역할·기간·기술:** 1인 설계·개발 · 사내 운영 · 2026.02 ~ 현재 · LangGraph · n8n · Python
- **200+ 기업 · 월간 보고서 · 기존 수작업 2~3일** — 리서치→작성→검증→수정을 단계별 에이전트로 자동화. 검증 실패 건만 재처리하는 분기 구성.

#### AI 악성앱 탐지
- **역할·기간·기술:** 개발 리드(모델 포함) · 2026.02 ~ 현재 · Python · PyTorch · MLflow · FastAPI · Docker · GitHub Actions · Android
- **13.4만 건 · DexRay** — 자체 수집 데이터로 DexRay 베이스라인 구축.
- **시간 기준 Holdout · F1 0.83~0.88** — 랜덤 분할 F1 0.925가 성능을 과대평가함을 확인하고 수집 시점 기준으로 재평가.
- **MLOps** — MLflow 실험 추적 · FastAPI/Docker 서빙 · GitHub Actions CI.

#### AI 보이스피싱 탐지
- **역할·기간·기술:** 개발 리드(모델 포함) · 3인 팀 · 2025.09 ~ 2025.12 · KoBERT · STT · INT8 · Android
- **351MB → 89MB · 0.39s** — KoBERT INT8 양자화, Recall 손실 없이 Android 실기기 추론.
- **Recall 99.34% / FP 22%** — 높은 Recall에도 정상 통화 오탐이 제품 기준을 충족하지 못해 출시 보류 제안.

#### TouchEn Transkey / mTranskey - Web SDK
- **역할·기간·기술:** 개발 및 운영 · 2018.10 ~ 2021.07 · JavaScript · Java · Servlet/JSP · REST API
- 금융·공공기관 대상 웹 보안 키보드 SDK. 세션 없는 통신 구조, 웹 접근성 대응, 패턴 잠금·반응형 UI 개발.

#### TouchEn nxKey - macOS App
- **역할·기간·기술:** 개발 · 2019.04 ~ 2021.09 · Objective-C · C++ · macOS DriverKit
- macOS 보안 키보드. Hooking Daemon 및 DriverKit 기반 가상 키 입력 생성 기능 구현.

---

## 개인 프로젝트

#### 1. 셀카픽 - 온디바이스 AI 셀카 분류 앱
- **1인 기획·설계·개발·배포 / Google Play 운영** · Kotlin · Coroutines · Jetpack Compose · MVVM · ML Kit · AdMob
- **온디바이스 AI** — ML Kit Face Detection 기반 유사 셀카 그룹핑·베스트샷 추천. 임계값별 정확도–오탐률 측정·튜닝.
- **1인 개발·운영** — 멀티모듈 · AdMob 수익화 · Play Store 배포·업데이트.
- **링크:** https://play.google.com/store/apps/details?id=com.yjcho.aiphotocleaner

#### 2. nworks - NAVER WORKS MCP 서버
- **1인 설계·개발 / 오픈소스·npm 배포** · TypeScript · MCP · Tool Calling · OAuth · GitHub Actions
- **MCP 연동** — Mail/Calendar/Message API를 AI 에이전트가 호출할 수 있는 CLI/서버로 구현.
- **인증 구조** — Service Account / User OAuth 인증 흐름 분리.
- **오픈소스** — awesome-mcp-servers 등재.
- **링크:** https://github.com/yjcho9317/nworks / https://www.npmjs.com/package/nworks

#### 3. mcp-fence - MCP 프로토콜 보호 프록시
- **1인 설계·개발 / 오픈소스·npm 배포** · TypeScript · MCP · Policy Engine · SQLite · GitHub Actions
- nworks 개발 중 확인한 MCP 도구 호출 보호 필요성을 별도 프록시로 구현.
- **보호 기능** — tool description SHA-256 해시 고정, allow/deny 정책, 인자 검증, 감사 로그.
- **대응 범위** — **56개 탐지 패턴**, OWASP MCP Top 10 중 **9개 항목 대응**.
- **링크:** https://github.com/yjcho9317/mcp-fence / https://www.npmjs.com/package/mcp-fence

---

## 학력

**신한대학교** · 컴퓨터공학 전공 · 2015.03 ~ 2018.08 졸업 (편입, 4.22 / 4.5)

**신흥대학교** · 웹프로그래밍 전공 · 2012.03 ~ 2015.02 수료

---

## 자격증 · 수상

- 정보처리기사 · 한국산업인력공단 · 2017.08
- 융복합지식학회 추계학술대회 우수논문상 · 2017.10
