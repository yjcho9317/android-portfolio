<!--
[사람인/원티드 입력용 숏버전]

간략소개:
9년차 Android 개발자. 50만 DL B2C 앱 기술 리드, 금융·공공 200여 기업 납품 SDK 메인 담당(1,000만+ 사용자 탑재). Kotlin 99% 전환, ANR 0건. AI 탐지 3건 리드. App/SDK/AI를 넘나드는 엔지니어.

자소서 (자유양식 1,000자 이내):
50만 다운로드 B2C 앱인 라온 모바일 시큐리티를 기술 리드로 운영하며 평점 4.5를 기록했습니다. 동시에 금융·공공 200여 기관에 납품하는 모바일 SDK를 메인 담당해왔고, SDK가 탑재된 서비스의 사용자는 1,000만 명 이상입니다. Java 레거시를 Kotlin 전환하고 MVVM으로 재설계하여 내부 QA 기준 ANR 재현 0건을 유지하고 있습니다. AI 딥페이크 탐지에서는 온디바이스 추론 한계를 측정해 클라우드로 전환했고, 보이스피싱 탐지에서는 Recall 99.34%에도 FP Rate 22%를 보고 제품화를 보류했습니다. 셀카픽(Compose), nworks(MCP 서버), mcp-fence(보안 방화벽)를 오픈소스로 배포했습니다. App/SDK/AI를 넘나드는 엔지니어링 경험을 바탕으로, 대규모 트래픽을 다루는 서비스 앱 개발로 확장하고 싶습니다.
-->

# 조영진

## 간략 소개

50만 다운로드 B2C 앱을 기술 리드로 운영해온 9년차 Android 개발자. 금융·공공 200여 기업에 납품되어 1,000만+ 사용자 서비스에 탑재되는 SDK를 메인 담당해왔으며, 최근 2년은 딥페이크·보이스피싱·악성앱 AI 탐지 3건을 리드하고 있습니다. B2C 앱 UX부터 SDK API, NDK 네이티브, 온디바이스 AI 모델 배포까지 플랫폼 전 레이어를 다뤄왔습니다.

Java 레거시였던 SDK를 Kotlin으로 전환하고 MVVM으로 재설계하여 내부 QA 기준 ANR 재현 0건을 달성했습니다. AI 딥페이크 탐지 프로젝트에서는 TFLite 양자화·지식증류 적용 후 온디바이스 한계를 실측해 클라우드 아키텍처로 전환했고, 50만 다운로드 앱에 탑재하여 실서비스로 출시한 경험이 있습니다.

---

## 스킬

**Core:** Kotlin, Java, C++, Coroutines + Flow, Jetpack (Compose, Hilt, Room, Lifecycle, WorkManager, Datastore, Paging, Navigation), MVVM, Clean Architecture, Multi-module, Retrofit2, OkHttp3, Android SDK, Android NDK/JNI (CMake/ndk-build)

**AI/ML:** Python, PyTorch, TFLite (on-device inference), ML Kit

**Testing & CI/CD:** JUnit, GitHub Actions, Jenkins

**Monitoring:** Firebase Crashlytics, Firebase Analytics

**iOS:** iOS SDK, Swift, Objective-C, Xcode, CocoaPods

**Sub:** Git, Frida

---

## 경력

**총 9년**

| 기간 | 회사 | 소속/직급 | 비고 |
|------|------|---------|------|
| 2018.04 ~ 현재 | 라온시큐어 | AI 연구 2팀 · 책임연구원 | 9년차 |

**주요 타임라인:**
- AI 기반 악성앱 탐지 -- 전체/모델 개발 리드 (2026.02 -- 현재)
- 클라우드 서비스 전환 -- 앱 개발 리드, 5인 팀 (2025.02 -- 2025.10)
- AI 보이스피싱 탐지 연구 -- 전체/모델 개발 리드, 3인 팀 (2025.09 -- 2025.12)
- AI 딥페이크 탐지 -- 앱 개발 리드 / 모델 서브, 6인 팀 (2024.04 -- 2024.12)
- 라온 모바일 시큐리티 앱 설계·운영 (2021.07 -- 현재)
- TouchEn mVaccine (Android/iOS SDK) 메인 담당 (2019.04 -- 현재)
- TouchEn nxKey (macOS) 개발 (2019.04 -- 2021.09)
- TouchEn Transkey / mTranskey (Web SDK) 개발·운영 (2018.10 -- 2021.07)

---

## 경력기술서

### 주요 프로젝트

#### 1. 라온 모바일 시큐리티 앱 개발 및 운영

- **소속 회사:** 라온시큐어
- **담당 역할:** 개발 및 운영, 기술 리드
- **업무 기간:** 2021.07 -- 현재
- **기술 스택:** Kotlin, Coroutines + Flow, Room, Hilt, MVVM, Lifecycle, Navigation, Paging, Datastore, Retrofit2, OkHttp3, Firebase Crashlytics, Firebase Analytics
- **프로젝트 개요:** B2C 모바일 보안 서비스 앱. 10가지 이상 보안 기능을 하나의 앱에서 제공. 50만 다운로드, 1,000명+ 평가, 평점 4.5.

**주요 업무 및 성과:**
- 신규 기능(딥페이크 탐지 등) 도입 시 기술 스택 선정 및 아키텍처 설계.
- MVVM 리팩토링. 확장성을 고려해 Coroutines + Flow, Room, Hilt(DI) 선제 도입.
- 스미싱 문자 패턴화·정규화를 통한 실시간 탐지 기능 개발.
- 50만 다운로드, 1,000명+ 평가, 평점 4.5 기록.
- 플레이스토어 배포·업데이트 운영.

관련 링크: https://play.google.com/store/apps/details?id=com.raonsecure.mobile.security


#### 2. TouchEn mVaccine SDK/APP 개발 및 운영

- **소속 회사:** 라온시큐어
- **담당 역할:** 메인 담당 (Android/iOS SDK, App)
- **업무 기간:** 2019.04 -- 현재
- **기술 스택:** Android SDK, Android NDK, iOS SDK, Kotlin, Coroutines, Java, C++, Objective-C, Swift, MVVM, Clean Architecture, Multi-module, WorkManager, JUnit, Firebase Crashlytics, Firebase Analytics, Jenkins
- **프로젝트 개요:** 금융·공공기관 200여 곳에 납품하는 모바일 SDK. 1,000만+ 사용자 서비스에 탑재. 멀티모듈 아키텍처 기반 설계, KISA 백신 보안 성능 인증 획득.

**주요 업무 및 성과:**
- Java→Kotlin 99% 전환과 MVVM 리팩토링을 public API 하위 호환을 유지하며 완료. AAR 멀티모듈 구조(core/detection/ui 등)로 기능별 독립 빌드·배포 가능한 아키텍처 설계.
- NDK/JNI(CMake) 기반 네이티브 모듈 개발. 시스템 레벨 탐지 로직 구현.
- WorkManager·Coroutines 기반 비동기·병렬 처리 설계. 초기 빈번했던 ANR과 메모리 릭을 JNI 레벨까지 추적·해결하여 내부 QA 기준 ANR 재현 0건 달성.
- JUnit 기반 SDK 품질 관리. Jenkins CI/CD를 통한 빌드·배포 자동화.
- Firebase Crashlytics/Analytics 도입으로 원격 크래시 모니터링·분석 체계 구축, 버그 대응 시간 단축.
- NDK/JNI 기반 런타임 위협 탐지(루팅/탈옥, 디버거, 코드 변조) 및 iOS 보안 모듈 개발. Frida 기반 공격 시뮬레이션으로 방어 로직 검증.
- URL Scheme 기반 앱-웹 간 통신 및 AIDL/Bound Service 기반 앱 간 통신 기능 개발.
- 삼성·LG·샤오미·Pixel 등 제조사별 커스텀 OS와 Android 5~16 버전 호환성 대응. 분기 릴리즈 운영. 플레이스토어 배포 및 업데이트 운영.

관련 링크: https://play.google.com/store/apps/details?id=com.TouchEn.mVaccine.webs


#### 3. AI 기반 딥페이크 영상 탐지

- **소속 회사:** 라온시큐어
- **담당 역할:** 앱 개발 리드 / 모델 개발 서브 (6인 팀)
- **업무 기간:** 2024.04 -- 2024.12
- **기술 스택:** Android SDK, Kotlin, Python, PyTorch, TFLite, i3d, ResNet
- **프로젝트 개요:** 오픈소스 기반 딥페이크 탐지 모델을 모바일 보안 서비스에 응용. 앱 개발을 메인으로, 모델 추가 학습·튜닝을 서브로 담당.

**주요 업무 및 성과:**
- 자체 데이터셋 구축으로 동양인 탐지 정확도 65%→95% 달성.
- TFLite 양자화(FP32→FP16→INT8) 적용 후 온디바이스 추론 성능과 MediaProjection 프레임 캡처 제약(720p, 30fps 미달)을 측정하여 클라우드 비동기 아키텍처로 전환. 측정 데이터를 팀에 공유해 모델 담당자·기획과 합의 후 방향 확정.
- 50만 다운로드 B2C 앱(라온 모바일 시큐리티)에 탑재하여 실서비스 출시.
- 본 경험을 이어 온디바이스 딥페이크 탐지 AI SDK 개발 진행 중.


#### 4. AI 기반 악성앱 탐지

- **소속 회사:** 라온시큐어
- **담당 역할:** 전체/모델 개발 리드
- **업무 기간:** 2026.02 -- 현재
- **기술 스택:** Python, PyTorch, MLflow, Docker, Android
- **프로젝트 개요:** 시그니처 기반 탐지의 한계(제로데이 대응 불가, 패턴 DB 유지 비용)를 해결하기 위해, ML 모델 기반 탐지 시스템을 설계·개발 중.

**주요 업무 및 성과:**
- APK 정적 분석 기반 특징 추출 파이프라인 설계 및 ML 모델 학습 아키텍처 구축.
- MLflow 실험 추적 구조까지 구축. 모델 레지스트리·FastAPI 서빙·GitHub Actions CI/CD는 PoC 수준에서 설계를 고정해둔 상태. 현재 악성앱 샘플 수집과 모델 학습을 진행하며 단계적으로 붙여나가는 중.
- Docker 기반 학습 환경 구성.


#### 5. AI 기반 보이스피싱 탐지 연구

- **소속 회사:** 라온시큐어
- **담당 역할:** 전체/모델 개발 리드 (3인 팀)
- **업무 기간:** 2025.09 -- 2025.12
- **기술 스택:** KoBERT, 경량 LLM, Python, NLP
- **프로젝트 개요:** 보이스피싱 통화를 AI로 실시간 탐지하는 연구. Recall 99.34%를 달성했으나 실서비스 적용에는 오탐이 많아 제품화 보류.

**주요 업무 및 성과:**
- KoBERT 기반 모델과 경량 LLM 모델을 통한 실시간 탐지 파이프라인 설계. Recall 99.34% 기록.
- 데이터 불균형으로 FP Rate 22%(정상 통화 5건 중 1건 오탐) 확인. 오탐률을 위험한 수치로 보고 체감 가능한 형태로 정리해 팀·상위 보고에 공유, 합의를 거쳐 제품화 보류 결정.
- 후속 방향으로 정상 대화 데이터 보강, 합성 데이터 보강 및 Hard Negative Mining 전략을 제안.


#### 6. 클라우드 서비스 전환

- **소속 회사:** 라온시큐어
- **담당 역할:** 앱 개발 리드 (5인 팀)
- **업무 기간:** 2025.02 -- 2025.10
- **기술 스택:** Android SDK, Java, Kotlin
- **프로젝트 개요:** 기존 로컬 기반 보안 검사를 클라우드 기반으로 전환. 라이선스 기반 수익 구조에서 사용량 기반 과금 구조로의 전환을 목표로 설계.

**주요 업무 및 성과:**
- 로컬 기반 호출에서 클라우드 기반으로 아키텍처를 전환.
- 로컬 DB 용량 제약 제거로 검사 가능한 악성앱 탐지 패턴 5배 이상 확장 가능한 구조로 설계.
- 기존 CDN 기반 패턴 배포 대비 서버 비용 절감.
- 실제 사용 횟수 기반 집계 및 통계 수집 구조 설계.


---

### 기타 프로젝트

#### 1. TouchEn Transkey / mTranskey -- Web SDK 개발 및 운영

- **업무 기간:** 2018.10 -- 2021.07
- **기술 스택:** JavaScript, Java Servlet, REST API
- **프로젝트 개요:** 웹 기반 보안 키보드 솔루션. 키 입력 보호 및 패턴 잠금 기능 제공. 금융·공공기관 대상.
- 세션 미사용 통신 개발, 반응형 웹 디자인, 웹 접근성 심사 기준 준수, RESTful API 설계·제공.

#### 2. TouchEn nxKey -- macOS App 개발

- **업무 기간:** 2019.04 -- 2021.09
- **기술 스택:** Objective-C, C++, macOS DriverKit
- **프로젝트 개요:** macOS용 보안 키보드 솔루션. 키 입력 후킹 및 보안 기능 제공.
- Hooking Daemon 개발, macOS DriverKit 기반 가상 키 발생 기능 개발.

---

### 사이드 프로젝트

#### 1. 셀카픽 (1인 개발 · 배포 중)

- **기술 스택:** Kotlin, Coroutines, Jetpack Compose, MVVM, ML Kit, AdMob
- **프로젝트 개요:** ML Kit 기반 얼굴 유사도 분석 앱. 사진첩에서 유사한 셀카를 자동으로 묶어주고 베스트샷을 추천. 기획부터 스토어 배포까지 단독 진행.
- [Google Play](https://play.google.com/store/apps/details?id=com.yjcho.aiphotocleaner)

#### 2. nworks (1인 개발 · 오픈소스)

- **기술 스택:** TypeScript, MCP, npm, GitHub Actions
- **프로젝트 개요:** NAVER WORKS API를 CLI와 MCP 서버로 래핑한 오픈소스 도구. awesome-mcp-servers 등록(PR 머지), Glama AAA 인증 획득. npm 배포, Docker 지원.
- [GitHub](https://github.com/yjcho9317/nworks) · [npm](https://www.npmjs.com/package/nworks)

#### 3. aiignore-cli (1인 개발 · 오픈소스)

- **기술 스택:** TypeScript, npm, GitHub Actions
- **프로젝트 개요:** AI 코딩 도구용 ignore 파일 생성 CLI. 바이브 코딩 시 private key 등 민감 정보가 AI에 노출되는 것을 방지. 보안 관점에서 개발.
- [GitHub](https://github.com/yjcho9317/aiignore-cli) · [npm](https://www.npmjs.com/package/aiignore-cli)

#### 4. mcp-fence (1인 개발 · 오픈소스)

- **기술 스택:** TypeScript, npm, GitHub Actions
- **프로젝트 개요:** nworks(MCP 서버)를 개발하면서 MCP 프로토콜의 보안 문제를 직접 겪어, 탐지 도구가 없어서 직접 만든 보안 프록시. OWASP MCP Top 10 중 7개 항목 커버. npm 배포.
- [GitHub](https://github.com/yjcho9317/mcp-fence) · [npm](https://www.npmjs.com/package/mcp-fence)

---

## 학력

| 기간 | 학교 | 전공 | 비고 |
|------|------|------|------|
| 2015.03 ~ 2018.08 | 신한대학교 (4년제) | 컴퓨터공학 | 편입/졸업 |
| 2012.03 ~ 2015.02 | 신흥대학교 (2·3년제) | 웹프로그래밍 | 수료 |

**졸업작품:** 비콘 기반의 맞춤형 스마트 홈 서비스 (융복합지식학회 우수논문상 수상)

---

## 자격/수상

| 시기 | 항목 | 발급 |
|------|------|------|
| 2017.08 | 정보처리기사 | 한국산업인력공단 |
| 2017.10 | 융복합지식학회 추계학술대회 우수논문상 | 융복합지식학회 |

---

## 자기소개서

50만 다운로드 B2C 앱인 라온 모바일 시큐리티를 기술 리드로 운영하며 평점 4.5를 기록했습니다. 동시에 금융·공공 200여 기관에 납품하는 모바일 보안 SDK, TouchEn mVaccine을 메인 담당해왔습니다. SDK가 탑재된 서비스의 사용자는 1,000만 명 이상이며, KISA 백신 보안 성능 인증을 획득한 제품입니다.

합류 당시 mVaccine은 Java 레거시였습니다. 기능이 추가될수록 변경 영향 범위를 예측할 수 없는 구조였고, Kotlin 전환과 MVVM 리팩토링을 직접 제안하고 실행했습니다. 단순한 언어 교체가 아니라 테스트 가능한 구조로 바꾸는 게 목표였습니다. 비동기 처리가 많은 SDK 특성상 ANR과 메모리 릭이 잦았는데, JNI 레벨까지 추적해서 해결했고 현재 내부 QA 기준 ANR 재현 0건을 유지하고 있습니다. Android 5~16까지 멀티 벤더 환경에서 분기 릴리즈를 이어가고 있습니다.

AI 기반 위협 탐지 프로젝트에서는 모델 개발과 서비스 적용을 함께 담당했습니다. 딥페이크 탐지에서는 온디바이스 추론 한계를 직접 측정한 뒤 클라우드로 전환했고, 보이스피싱 탐지에서는 Recall 99.34%에도 FP Rate 22%를 보고 제품화를 보류했습니다.

셀카픽(Jetpack Compose + ML Kit)을 기획부터 스토어 배포까지 단독으로 진행했고, nworks(MCP 서버)와 mcp-fence(MCP 보안 방화벽)를 오픈소스로 npm에 배포했습니다. App/SDK/AI를 넘나드는 엔지니어링 경험을 바탕으로, 대규모 트래픽을 다루는 서비스 앱 개발로 확장하고 싶습니다.