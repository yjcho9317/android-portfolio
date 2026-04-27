## 경력기술서

---

**이름:** 조영진  
**포지션:** Mobile / Android Engineer  
**직책:** 책임연구원  
**소속:** 라온시큐어 (2018.04 ~ 현재, 9년차)  
**GitHub:** https://github.com/yjcho9317  
**포트폴리오:** https://yjcho9317.github.io/android-portfolio  
**블로그:** https://velog.io/@yjcho9317 · https://yjcho9317.tistory.com

금융·공공 200여 기업, 1,000만+ 사용자 서비스에 탑재된 SDK와 50만 다운로드 B2C 앱을 개발·운영하며, API 설계부터 NDK 네이티브 레이어, OEM 호환성 관리까지 플랫폼 전 구간을 설계·운영해온 9년차 Android 엔지니어. 신규 프로젝트의 개발을 리드하며 의사결정과 설계 수행, 최근 2년은 딥페이크·보이스피싱·악성앱 AI 탐지 3건을 리드하여 연구 개발 및 서비스 출시. 업무 외에도 개인 앱 배포, 오픈소스 개발 등 사이드 프로젝트도 진행.

---

### 주요 프로젝트

#### 1. TouchEn mVaccine SDK/APP 개발 및 운영

- **소속 회사:** 라온시큐어
- **담당 역할:** 메인 담당 (Android/iOS SDK, App)
- **업무 기간:** 2019.04 -- 현재
- **기술 스택:** Android SDK, Android NDK, iOS SDK, Kotlin, Coroutines, Java, C++, Objective-C, Swift, MVVM, Clean Architecture, Multi-module, WorkManager, JUnit, Firebase Crashlytics, Firebase Analytics, Jenkins
- **프로젝트 개요:** 금융·공공 200여 기업의 1,000만+ 사용자 서비스에 탑재되는 모바일 SDK. Android·iOS 동시 운영. 멀티모듈 아키텍처 설계, KISA 인증 획득.

**주요 업무 및 성과:**
- Java→Kotlin 99% 전환과 MVVM 리팩토링을 public API 하위 호환성을 유지하며 완료. AAR 멀티모듈 구조(core/detection/ui)로 기능별 독립 빌드·배포 가능한 SDK 구조 설계.
- NDK/JNI(CMake) 기반 네이티브 모듈 개발. 시스템 레벨 탐지 로직 구현.
- WorkManager·Coroutines 기반 비동기·병렬 처리 도입. JNI 네이티브 메모리 릭까지 추적하여 ANR 0건 달성.
- AIDL/Bound Service 기반 프로세스 간 통신(앱 간), URL Scheme 기반 앱-웹 간 통신 기능 개발.
- Android 5~16, 삼성·LG·샤오미·Pixel OEM 단편화 대응. Reflection 기반 제조사·OS별 비공개 API 차이 흡수 레이어 구현.
- **Public API 운영:** 업데이트 시 호스트 앱 코드 수정 0건 원칙 기반으로, 200여 기업이 통합하는 SDK의 Public API를 하위 호환성을 유지하며 설계·운영.
- **DX·통합 지원:** 연동 가이드·샘플 프로젝트·마이그레이션 문서·릴리즈 노트 작성. 빌드 사이즈·ProGuard/R8 규칙·의존성 충돌 등 호스트 앱 영향 지표 관리.
- 통합→분할 다운로드 전환으로 데이터 사용량 절감. SDK 바이너리에서 패턴·엔진 파일 분리로 사이즈 최적화.
- KISA 인증 획득. JUnit 기반 SDK 품질 관리. Jenkins CI/CD 자동화. Firebase Crashlytics/Analytics 원격 모니터링·분석 체계 구축.
- NDK/JNI 기반 런타임 위협 탐지 및 iOS 보안 모듈 개발. Frida 기반 공격 시뮬레이션으로 방어 로직 검증.

관련 링크: https://play.google.com/store/apps/details?id=com.TouchEn.mVaccine.webs


#### 2. 라온 모바일 시큐리티 앱 개발 및 운영

- **소속 회사:** 라온시큐어
- **담당 역할:** 개발 및 운영, 기술 리드
- **업무 기간:** 2021.07 -- 현재
- **기술 스택:** Kotlin, Coroutines + Flow, Room, Hilt, MVVM, Lifecycle, Navigation, Paging, Datastore, Retrofit2, OkHttp3, Firebase Crashlytics, Firebase Analytics
- **프로젝트 개요:** B2C 모바일 서비스 앱. 10가지 이상 기능을 하나의 앱에서 제공. 50만 다운로드, 1,000명+ 평가, 평점 4.5.

**주요 업무 및 성과:**
- 기존 스레드·RxJava 기반 구조의 보일러플레이트 과다, 테스트 자동화 부적합을 근거로 MVVM + Coroutines + Flow + Hilt 도입을 결정·실행. Compose 도입은 검토 진행 중.
- MVVM 아키텍처 전환과 함께 Room·Lifecycle·Navigation·Paging·Datastore 등 Jetpack 스택 도입.
- AI 딥페이크 탐지를 앱 개발 메인 + 모델 개발 서브로 참여하여 50만 다운로드 B2C 앱에 직접 탑재·서비스.
- 50만 다운로드, 1,000명+ 평가, 평점 4.5 달성. 플레이스토어 배포·업데이트 운영.

관련 링크: https://play.google.com/store/apps/details?id=com.raonsecure.mobile.security


#### 3. AI 기반 딥페이크 영상 탐지

- **소속 회사:** 라온시큐어
- **담당 역할:** 앱 개발 리드 / 모델 개발 서브 (6인 팀)
- **업무 기간:** 2024.04 -- 2024.12
- **기술 스택:** Android SDK, Kotlin, Python, PyTorch, TFLite, i3d, ResNet
- **프로젝트 개요:** 영상 속 딥페이크를 AI로 탐지. 오픈소스 딥페이크 탐지 모델을 모바일 보안 앱에 적용. 앱 개발을 메인으로, 모델 추가 학습·튜닝을 서브로 담당.

**주요 업무 및 성과:**
- 자체 데이터셋 구축 및 튜닝으로 동양인 탐지 정확도 95% 기록.
- TFLite 모델 경량화(양자화) 적용 후 온디바이스 추론 성능과 MediaProjection 프레임 캡처 제약(720p, 30fps 미달)을 측정. 측정 데이터를 근거로 팀과 합의해 클라우드 비동기 아키텍처로 전환.
- 50만 다운로드 B2C 앱(라온 모바일 시큐리티)에 탑재하여 실서비스 출시.
- 이를 바탕으로 KISA 과제로 온디바이스 딥페이크 탐지 SDK 개발 진행 중 — SDK 설계·개발 메인, 모델 경량화(양자화·지식증류) 연구 서브. 인터페이스 추상화 기반 단일 진입점 구조 설계 (모델 백엔드·입출력·다중 탐지기). 제품화 단계 예정.


#### 4. AI 기반 악성앱 탐지

- **소속 회사:** 라온시큐어
- **담당 역할:** 전체/모델 개발 리드
- **업무 기간:** 2026.02 -- 현재
- **기술 스택:** Python, PyTorch, MLflow, MLOps, Docker, Android
- **프로젝트 개요:** 시그니처 기반 탐지의 한계(제로데이 대응 불가, 패턴 DB 유지 비용)를 해결하기 위해 ML 모델 기반 탐지 시스템 설계·개발.

**주요 업무 및 성과:**
- APK 정적 분석 기반 특징 추출 파이프라인을 구성하고 ML 모델 학습 아키텍처 구축.
- MLflow·모델 레지스트리·FastAPI 서빙·GitHub Actions CI/CD까지 MLOps 파이프라인 선제 구축·운용. 데이터·모델 안정화에 따라 단계적 고도화 예정.
- Docker 기반 학습 환경 구성.
- 현재 PoC 단계 (2개월차) — 샘플 수집 및 학습 진행 중.


#### 5. AI 기반 보이스피싱 탐지

- **소속 회사:** 라온시큐어
- **담당 역할:** 전체/모델 개발 리드 (3인 팀)
- **업무 기간:** 2025.09 -- 2025.12
- **기술 스택:** KoBERT, 경량 LLM, Python, NLP
- **프로젝트 개요:** 보이스피싱 통화를 AI로 실시간 탐지. Recall 99.34%에도 오탐 문제로 출시 보류.

**주요 업무 및 성과:**
- KoBERT 기반 모델과 경량 LLM 모델을 통한 실시간 탐지 파이프라인 설계. Recall 99.34% 기록.
- 데이터 불균형으로 FP Rate 22%(정상 통화 5건 중 1건 오탐) 확인. 오탐률을 위험한 수치로 보고 체감 가능한 형태로 정리해 팀·상위 보고에 공유, 합의를 거쳐 제품화 보류 결정.
- 후속 방향으로 정상 대화·합성 데이터 보강과 오탐 데이터 중심 재학습 적용을 제안.


#### 6. 클라우드 서비스 전환

- **소속 회사:** 라온시큐어
- **담당 역할:** 앱 개발 리드 (5인 팀)
- **업무 기간:** 2025.02 -- 2025.10
- **기술 스택:** Android SDK, Java, Kotlin
- **프로젝트 개요:** 라이선스에서 사용량 기반 과금 방식으로 비즈니스 모델 전환.

**주요 업무 및 성과:**
- 로컬 기반 호출에서 클라우드 기반으로 아키텍처를 전환.
- 로컬 DB 용량 제약 제거로 검사 가능한 악성앱 탐지 패턴을 5배 이상 확장 가능한 구조로 변경.
- 기존 CDN 기반 패턴 배포 대비 서버 비용 절감.
- 실제 사용 횟수 기반 집계·통계 수집 구조 도입.


---

### 기술 스택

**Expert:** Kotlin · Java · Android SDK · NDK/JNI · C++ · MVVM · Clean Architecture · Multi-module · Coroutines + Flow · AIDL/IPC

**Production:** Jetpack Compose · Room · Hilt · WorkManager · Retrofit2 · OkHttp3 · Python · PyTorch · TFLite · iOS SDK · Swift · Objective-C · TypeScript

**Familiar:** MLflow · Docker · FastAPI · ML Kit · AdMob · Frida

**DevOps & Tools:** JUnit · GitHub Actions · Jenkins · Firebase Crashlytics/Analytics · Git · npm

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

#### 1. 셀카픽 (1인 기획·설계·배포 · 운영 중)

- **기술 스택:** Kotlin, Coroutines, Jetpack Compose, MVVM, ML Kit, AdMob
- **프로젝트 개요:** AI 기반 셀카 분석 앱. ML Kit 얼굴 인식으로 사진첩 셀카를 자동 그룹핑하고 베스트샷 추천.
- ML Kit Face Detection 기반 유사도 점수 산출 알고리즘 설계.
- 유사도 임계값 조정에 따른 정확도-오탐률 트레이드오프 경험.
- Google AdMob 광고 연동. 기획부터 스토어 배포까지 단독 진행.
- [Google Play](https://play.google.com/store/apps/details?id=com.yjcho.aiphotocleaner)

#### 2. nworks (1인 설계·개발 · 오픈소스)

- **기술 스택:** TypeScript, MCP, npm, GitHub Actions
- **프로젝트 개요:** AI 에이전트가 NAVER WORKS(메일·캘린더·메시지 등)를 직접 호출할 수 있게 만든 CLI & MCP Server.
- NAVER WORKS API를 MCP 프로토콜로 래핑. Service Account vs User OAuth 인증 구조 구현, 에이전트 호출 흐름 정의.
- awesome-mcp-servers 등록(PR 머지), Glama AAA 인증. 다국어 README(EN/KO/JA), npm 배포.
- [GitHub](https://github.com/yjcho9317/nworks) · [npm](https://www.npmjs.com/package/nworks)

#### 3. aiignore-cli (1인 설계·개발 · 오픈소스)

- **기술 스택:** TypeScript, npm, GitHub Actions
- **프로젝트 개요:** AI 코딩 도구용 ignore 파일 생성 CLI.
- .gitignore처럼 주요 AI 코딩 도구(Cursor, Claude Code 등)의 ignore 파일을 자동 생성.
- 바이브 코딩 시 private key 등 민감 정보가 AI에 노출되는 것을 방지. 보안 관점에서 개발.
- [GitHub](https://github.com/yjcho9317/aiignore-cli) · [npm](https://www.npmjs.com/package/aiignore-cli)

#### 4. mcp-fence (1인 설계·개발 · 오픈소스)

- **기술 스택:** TypeScript, MCP, OWASP, npm, GitHub Actions
- **프로젝트 개요:** MCP 프로토콜용 보안 프록시. nworks 개발 중 프로토콜 보안 문제를 직접 겪었으나 탐지 도구가 없어 자체 개발. 프롬프트 인젝션, 시크릿 유출, 도구 변조를 탐지.
- 양방향 스캐닝, SHA-256 기반 도구 설명 해시 피닝, 정책 엔진(allow/deny + 인자 검증), SQLite 감사 로그 구현.
- OWASP MCP Top 10 중 9개 항목 커버. npm 배포.
- [GitHub](https://github.com/yjcho9317/mcp-fence) · [npm](https://www.npmjs.com/package/mcp-fence)
