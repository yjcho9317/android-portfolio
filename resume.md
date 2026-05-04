# 조영진 / Android SDK · App Engineer

> 200+ 기업 · 1,000만+ 사용자 SDK 메인 / 50만 DL B2C 앱 개발 및 운영 / AI 프로젝트 3건

---

| | |
|---|---|
| **포지션** | Android SDK · App Engineer |
| **직책** | 책임연구원 (AI 연구 2팀) |
| **소속** | 라온시큐어 (RaonSecure), 2018.04 ~ 현재 (9년차) |
| **병역** | 군필 (육군 병장 만기전역, 2013.02 ~ 2014.11) |
| **포트폴리오** | https://yjcho9317.github.io/android-portfolio |
| **GitHub** | https://github.com/yjcho9317 |
| **블로그** | https://velog.io/@yjcho9317 / https://yjcho9317.tistory.com |

## Summary

라온시큐어 9년차 Android 엔지니어. 200+ 금융/공공 기업의 앱에 탑재되어 1,000만+ 사용자에게 제공되는 Android/iOS SDK의 메인 개발자로, Public API 설계부터 하위 호환성, NDK 네이티브 레이어, OEM 호환성까지 SDK의 설계와 개발 전반을 직접 다뤄왔다. 50만 다운로드 B2C 앱(라온 모바일 시큐리티)은 MVVM 전환·Jetpack 도입 같은 리팩토링부터 신규 기능 개발까지, 기술 의사결정과 개발을 함께 해왔다.

최근 2년은 AI 프로젝트 3건을 리드하고 있다. 딥페이크 탐지는 앱에 탑재해 서비스 출시했고, 보이스피싱 탐지는 ML 모델을 연구·개발했으며, 악성앱 탐지는 ML 모델부터 MLOps까지 개발 진행 중이다. 현재는 KISA 과제로 온디바이스 딥페이크 탐지 SDK 개발과 모델 경량화 연구를 진행하고 있다.

---

## 기술 스택

**SDK / Platform Engineering**
Android SDK · NDK / JNI · C++ · AIDL / IPC · 멀티모듈(Multi-module) · Public API 설계 · 하위 호환성 · DX(개발자 경험) · AAR · OEM 호환성 · Reflection · ProGuard / R8

**Android App Engineering**
Kotlin · Jetpack Compose · Coroutines · Flow · Hilt · Java · Room · Navigation · Paging · DataStore · WorkManager · Lifecycle · Retrofit2 · OkHttp3 · MVVM · Clean Architecture

**AI / ML**
온디바이스 · TFLite · PyTorch · ML Kit · 양자화 · 지식증류 · BERT(KoBERT) · MLOps · MLflow · FastAPI · Docker · Python

**iOS**
iOS SDK · Swift · Objective-C

**CI/CD · Tools**
JUnit · Jenkins · GitHub Actions · Firebase Crashlytics · Firebase Analytics · AdMob · Git

---

## 경력

**라온시큐어** · AI 연구 2팀 · 책임연구원 · 2018.04 ~ 현재 (9년차)

- AI 악성앱 탐지 - 전체/모델 개발 리드 (2026.02 ~ 현재)
- AI 보이스피싱 탐지 - 전체/모델 개발 리드, 3인 팀 (2025.09 ~ 2025.12)
- 클라우드 서비스 전환 - 앱 개발 리드, 5인 팀 (2025.02 ~ 2025.10)
- AI 딥페이크 탐지 - 앱 개발 리드 / 모델 서브, 6인 팀 (2024.04 ~ 2024.12)
- 라온 모바일 시큐리티 (B2C 앱) - 개발 및 운영 (2021.07 ~ 현재)
- TouchEn mVaccine SDK (Android/iOS) - 메인 개발자 (2019.04 ~ 현재)
- TouchEn nxKey (macOS) - 개발 (2019.04 ~ 2021.09)
- TouchEn Transkey / mTranskey (Web SDK) - 개발 및 운영 (2018.10 ~ 2021.07)

---

## 메인 프로젝트

#### 1. TouchEn mVaccine SDK / APP - 메인 개발자

- **소속:** 라온시큐어
- **역할:** 메인 개발자 (Android/iOS SDK, App)
- **기간:** 2019.04 ~ 현재
- **기술 스택:** Android SDK · NDK · iOS SDK · Kotlin · Coroutines · Java · C++ · Objective-C · Swift · MVVM · Clean Architecture · Multi-module · AAR · WorkManager · ProGuard / R8 · JUnit · Firebase Crashlytics · Firebase Analytics · Jenkins
- **개요:** 금융/공공 200+ 기업의 앱에 탑재되는 Android/iOS SDK. 1,000만+ 사용자 서비스에 탑재된 SDK로, 악성앱, 루팅, 디버깅, 통신 위변조 탐지가 핵심 기능. Public API 설계부터 NDK 네이티브 레이어, OEM 호환성까지 SDK의 설계, 개발, 운영을 담당.
- **핵심 성과:** Public API 설계·운영(호스트 앱 코드 수정 0건 원칙, 연동 가이드·마이그레이션 문서 기반 DX(개발자 경험) 운영), 멀티모듈(core/detection/ui) 분리 + Java→Kotlin 마이그레이션, SDK 사이즈 최적화(통합→분할 다운로드, 패턴/엔진 파일 분리), 비즈니스 모델 전환(클라우드 전환 프로젝트, 앱 개발 리드 5인 팀, 2025.02~2025.10 - 라이선스 기반 → 사용량 과금, 로컬 DB 제약 제거로 탐지 패턴 DB 5배+ 확장, CDN 대비 서버 비용 절감), 200+ 고객사 OEM 호환성 대응(Android 5~16 메이저 12개 버전, 삼성·LG·샤오미·Pixel, Reflection 기반 호환성 레이어), AIDL/IPC·WorkManager·Coroutines 기반 비동기 처리 + JNI 메모리 릭 해결, JUnit + Jenkins CI/CD + Firebase 기반 품질 체계 + KISA 백신 인증 획득, iOS 탈옥/원격/디버깅 탐지 모듈 개발.

관련 링크: https://play.google.com/store/apps/details?id=com.TouchEn.mVaccine.webs


#### 2. 라온 모바일 시큐리티 (B2C 앱) - 개발 및 운영

- **소속:** 라온시큐어
- **역할:** 개발 및 운영
- **기간:** 2021.07 ~ 현재
- **기술 스택:** Kotlin · Coroutines · Flow · Room · Hilt · MVVM · Lifecycle · Navigation · Paging · DataStore · Retrofit2 · OkHttp3 · Firebase Crashlytics · Firebase Analytics
- **개요:** 50만 다운로드, 평점 4.5의 B2C 앱. 악성앱, 스미싱, 딥페이크 등 10가지 이상 보안 기능을 하나의 앱에 모았다. MVVM 전환·Jetpack 도입 같은 리팩토링부터 신규 기능 개발까지, 기술 의사결정과 개발을 함께 해왔다.
- **핵심 성과:** 스레드/RxJava → MVVM + Coroutines + Flow + Hilt 기반으로 설계·전환(보일러플레이트 제거, 유지보수·테스트 적합 구조 정비), Jetpack 스택(Room, Navigation, Paging, DataStore) 점진 마이그레이션 완료 + Compose 도입 진행, mVaccine SDK 모듈화 구조 활용해 10가지+ 보안 기능 단일 앱 통합, 딥페이크 탐지 AI 직접 탑재·서비스 제공, 50만 다운로드 / 1,000명+ 평가 / 평점 4.5 운영, Firebase 기반 운영 지표 모니터링 + Play Store 정기 릴리즈·사용자 피드백 기반 개선 사이클 운영.

관련 링크: https://play.google.com/store/apps/details?id=com.raonsecure.mobile.security


#### 3. AI 딥페이크 탐지 - 온디바이스 vs 클라우드 아키텍처 판단

- **소속:** 라온시큐어
- **역할:** 앱 개발 리드 / 모델 개발 서브 (6인 팀)
- **기간:** 2024.04 ~ 2024.12
- **기술 스택:** Android SDK · Kotlin · Python · PyTorch · TFLite · i3d · ResNet
- **개요:** 영상 속 딥페이크를 AI로 탐지하는 기능을 라온 모바일 시큐리티 앱에 탑재. 오픈소스 모델을 자체 데이터셋으로 튜닝하고, 온디바이스 vs 클라우드 아키텍처 의사결정 후 출시.
- **핵심 성과:** 자체 데이터셋 구축·튜닝으로 동양인 탐지 정확도 65% → 95%(+30%p), TFLite 양자화 + 온디바이스 PoC 측정(MediaProjection 720p/30fps 미달, 추론 latency 실시간 임계 초과) → 측정 데이터 기반 클라우드 비동기 아키텍처로 전환·출시, 영상 업로드 + 유튜브/SNS URL 입력 UX + 실시간 탐지 현황·랭킹 UI/UX 구현, 50만 다운로드 B2C 앱 탑재 및 실서비스 출시, 후속 KISA 과제(온디바이스 딥페이크 탐지 SDK)에서 SDK 설계·개발 메인 / 모델 경량화(양자화, 지식증류) 연구 서브 진행 중.


#### 4. AI 보이스피싱 탐지 - Recall 99.34% / FP 22% 출시 보류 판단

- **소속:** 라온시큐어
- **역할:** 전체/모델 개발 리드 (3인 팀)
- **기간:** 2025.09 ~ 2025.12
- **기술 스택:** KoBERT · 경량 LLM · Python · NLP
- **개요:** 보이스피싱 통화를 AI로 실시간 탐지하는 프로젝트. KoBERT + 경량 LLM 기반 파이프라인을 3인 팀 리드로 구축.
- **핵심 성과:** KoBERT + 경량 LLM 실시간 탐지 파이프라인 구축, 3인 팀 기획부터 프로토타입까지 전체 리드, 데이터 부족 대응으로 정상 통화 + 보이스피싱 시나리오 + 경계선 사례 합성 보강, Recall 99.34%(데이터 불균형 기반 과적합 시그널) + FP Rate 22%(정상 통화 5건 중 1건 오탐, 사용자 신뢰 훼손 수준) 분석 → 팀·상위 보고 후 합의 거쳐 출시 보류 결정, 후속 전략으로 Hard Negative Mining 기반 재학습 + 정상 대화/합성 데이터 보강 방안 제안.


#### 5. AI 악성앱 탐지 - 시그니처 기반 한계 해결

- **소속:** 라온시큐어
- **역할:** 전체/모델 개발 리드
- **기간:** 2026.02 ~ 현재
- **기술 스택:** Python · PyTorch · MLflow · Docker · MLOps · Android
- **개요:** ML 모델 기반 악성앱 탐지 시스템 구축 중. 시그니처 기반 한계(제로데이 대응)를 ML로 해결하는 장기 프로젝트.
- **핵심 성과:** 4단계 장기 계획 수립(탐지 시스템 구축 → ML 학습 파이프라인 → 클라우드 실시간 탐지 → 온디바이스 탐지), Tesseract 논문 기반 실용 가능한 ML 악성앱 탐지 시스템 설계, 핵심 문제 정의(기간/버전에 따라 정상↔악성 분류 변동) → 기간별 데이터셋 별도 학습 방식 채택, 난독화 대응으로 GNN 기반 모델 적용·학습 진행 중, MLOps 환경 선제 구축(MLflow 실험 추적 + 모델 레지스트리, FastAPI 서빙, GitHub Actions CI/CD, Docker 학습 환경).

---

## 기타 프로젝트

#### TouchEn Transkey / mTranskey - Web SDK

- **소속:** 라온시큐어
- **역할:** 개발 및 운영
- **기간:** 2018.10 ~ 2021.07
- **기술 스택:** JavaScript · Java Servlet · REST API
- **개요:** 웹 기반 보안 키보드 솔루션. 키 입력 보호 및 패턴 잠금 기능 제공. 금융/공공기관 대상.
- **핵심 성과:** 세션 미사용 통신 개발, 반응형 웹 디자인, 웹 접근성 심사 기준 준수, RESTful API 설계 및 제공.


#### TouchEn nxKey - macOS App

- **소속:** 라온시큐어
- **역할:** 개발
- **기간:** 2019.04 ~ 2021.09
- **기술 스택:** Objective-C · C++ · macOS DriverKit
- **개요:** macOS용 보안 키보드 솔루션. 키 입력 후킹 및 보안 기능 제공.
- **핵심 성과:** Hooking Daemon 개발, macOS DriverKit 기반 가상 키 발생 기능 개발.


---

## 사이드 프로젝트

#### 1. 셀카픽 - 온디바이스 AI 셀카 분류 앱
*1인 기획·설계·배포, Google Play 운영 중*

- **기술 스택:** Kotlin · Coroutines · Jetpack Compose · MVVM · ML Kit · AdMob
- **개요:** 사진첩의 셀카를 ML Kit Face Detection으로 분석해 유사 셀카 자동 그룹핑/베스트샷 추천하는 Android 앱. 1인 기획/설계 + Compose + 멀티모듈 구조 풀스택 구현, Google Play 배포/운영 중.

- ML Kit Face Detection 기반 유사도 점수 산출 알고리즘 설계. 사진첩에서 유사 셀카 자동 그룹핑 후 베스트샷 추천.
- 유사도 임계값 조정에 따른 정확도-오탐률 트레이드오프를 직접 측정 및 튜닝.
- Google AdMob 광고 연동, 기획부터 스토어 배포 및 업데이트 운영까지 단독 진행.
- [Google Play](https://play.google.com/store/apps/details?id=com.yjcho.aiphotocleaner)


#### 2. nworks - NAVER WORKS MCP 서버
*1인 설계·개발, 오픈소스*

- **기술 스택:** TypeScript · MCP · npm · GitHub Actions
- **개요:** AI 에이전트가 NAVER WORKS(메일/캘린더/메시지 등)를 직접 호출할 수 있게 만든 CLI & MCP 서버. awesome-mcp-servers 등재, Glama AAA 인증, 다국어 README(EN/KO/JA).

- NAVER WORKS API를 MCP 프로토콜로 래핑한 도구. Service Account와 User OAuth 인증 구조를 분리해 구현했고, 에이전트 호출 흐름을 정의했다.
- 외부 API를 에이전트가 직접 호출하는 구조라 권한 오용이나 의도하지 않은 동작이 일어날 수 있어, 인증 흐름 설계 단계에서 이 부분을 함께 고려했다.
- [GitHub](https://github.com/yjcho9317/nworks) / [npm](https://www.npmjs.com/package/nworks)


#### 3. aiignore-cli - AI 코딩 도구 보안 가드레일
*1인 설계·개발, 오픈소스*

- **기술 스택:** TypeScript · npm · GitHub Actions
- **개요:** AI 코딩 도구(Cursor, Claude Code 등)에 민감 정보가 노출되지 않도록 ignore 파일을 자동 생성하는 CLI. 바이브 코딩 시 private key 등 시크릿이 AI 컨텍스트로 유입되는 보안 리스크에 대응.

- 주요 AI 코딩 도구의 ignore 파일을 .gitignore처럼 자동 생성한다. 단일 명령으로 다양한 도구의 보안 설정을 일괄 처리.
- 바이브 코딩 시 AI 컨텍스트로 시크릿이 유입되는 보안 리스크에 대응해 만든 도구. AI 시스템 자체를 안전하게 만드는 가드레일 쪽 관심사다. npm publish.
- [GitHub](https://github.com/yjcho9317/aiignore-cli) / [npm](https://www.npmjs.com/package/aiignore-cli)


#### 4. mcp-fence - MCP 프로토콜 보안 방화벽
*1인 설계·개발, 오픈소스*

- **기술 스택:** TypeScript · MCP · npm · GitHub Actions
- **개요:** nworks(MCP 서버)를 개발하며 발견한 MCP 프로토콜 보안 문제(탐지 도구 부재)를 해결하기 위해 직접 만든 양방향 보안 프록시. 프롬프트 인젝션, 시크릿 유출, 도구 변조를 탐지.

- 양방향 스캐닝, SHA-256 기반 도구 설명 해시 피닝, 정책 엔진(allow/deny + 인자 검증), SQLite 감사 로그로 탐지 엔진 구성.
- 56개 탐지 패턴, 1,426개 테스트, 자체 측정 86% 탐지율. OWASP MCP Top 10 중 9개 항목 커버.
- nworks를 만들면서 발견한 MCP 프로토콜 보안 문제(탐지 도구 부재)에서 출발해 양방향 보안 프록시로 발전시킨 도구. AI 시스템 자체를 안전하게 만드는 가드레일 쪽 관심사다. npm publish.
- [GitHub](https://github.com/yjcho9317/mcp-fence) / [npm](https://www.npmjs.com/package/mcp-fence)

---

## 학력

**신한대학교** · 컴퓨터공학 전공 · 2015.03 ~ 2018.08 졸업 (편입, 학점 4.22 / 4.5)
- 졸업 프로젝트: 비콘 기반 스마트 홈 서비스 개발 · 학술 논문 대회 수상

**신흥대학교** · 웹프로그래밍 전공 · 2012.03 ~ 2015.02 수료 (학점 3.95 / 4.5)

---

## 자격증 · 수상

- **정보처리기사** (한국산업인력공단, 2017.08)
- **융복합지식학회 추계학술대회 우수논문상** (2017.10)
