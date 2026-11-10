# 🐴 DongkeyChess (동키체스)

> **"말하는 동키 AI 로봇과 즐기는 스마트 & 펀 체스 게임!"**  
> 2D/3D 이소메트릭 시점, 재치 있는 AI 감정 TTS, 입체적인 위협 경로 시각화 및 맞춤 복기 학습 모드를 제공하는 안드로이드 체스 애플리케이션입니다.

---

## 🌟 주요 특징 (Key Features)

### 🤖 1. 재치 있는 AI 로봇 & 한국어 TTS 음성 대국
- **10단계 난이도 AI**: 입문자부터 숙련자까지 즐길 수 있는 AI 대국 (실력에 맞춘 난이도 자동 조절)
- **실시간 로봇 감정 표현**: 게임 상황(잘난척, 가르침, 약올림, 분노, 하소연)에 따른 AI 감정 일러스트 및 한국어 TTS 음성 대사 출력

### 🎨 2. 2D & 3D 이소메트릭(Isometric) 뷰 지원
- **시점 전환**: 클래식한 평면 2D 시점과 입체감 넘치는 3D 이소메트릭 체스판 시점 제공
- **반전 및 가로/세로 지원**: 체스판 180도 회전 및 화면 방향에 맞춘 유연한 레이아웃

### ⚔️ 3. 생동감 넘치는 애니메이션 & 사운드
- **전투 및 이동 애니메이션**: 기물 이동 및 포획(체크메이트/공격) 시 펼쳐지는 역동적인 이펙트
- **기물별 특화 사운드**: 폰, 나이트, 비숍, 룩, 퀸, 킹 각각의 개별 타격 사운드 탑재

### 🧠 4. 체스 실력 향상을 위한 복기 & 시뮬레이션 모드
- **기보 복기 및 자동 재생**: 경기 종료 후 전체 기보를 타임라인별로 복기
- **실수 교정 퀴즈**: 대국 중 발생한 실수(Mistake), 놓친 포획 기회(Missed Capture), 결정적 수(Decisive Move)를 직접 다시 풀어보는 맞춤 시뮬레이션 기능

### 🎯 5. 위협 시각화 (Threat Visualization)
- **체크 & 경로 봉쇄 화살표**: 킹을 직접 위협하는 공격 경로와 탈출로 봉쇄 화살표 시각화
- **공격 영역 하이라이트**: 위험 영역을 한눈에 파악하여 전략적 판단 지원

### 👥 6. 2인 대국 (Pass & Play) & 난이도별 통계
- 한 기기로 친구와 함께 즐기는 2인 대국 모드
- AI 난이도별 승/패/무 통계 관리 기능

---

## 🛠 기술 스택 (Tech Stack)

| 항목 | 기술 |
|---|---|
| **Language** | Kotlin 100% |
| **UI Framework** | Jetpack Compose (Material 3) |
| **Graphics** | Custom Canvas Drawing (2D & 3D Isometric View) |
| **Architecture** | MVVM (StateFlow, ViewModel, Lifecycle-runtime) |
| **Audio & Voice** | TextToSpeech (Korean TTS), Android MediaPlayer |
| **Min / Target SDK** | Min SDK 24 (Android 7.0+) / Target SDK 37 |
| **Build Tool** | Gradle (Kotlin DSL, AGP 9.5+) |

---

## 📱 스크린샷 (Screenshots)

| 2D 체스판 | 3D 이소메트릭 뷰 | 로봇 감정 대국 | 복기 시뮬레이션 |
|:---:|:---:|:---:|:---:|
| *(이미지 첨부)* | *(이미지 첨부)* | *(이미지 첨부)* | *(이미지 첨부)* |

---

## 🚀 시작하기 (Getting Started)

### 요구 사항
- Android Studio Ladybug (2024.2.1+) 이상
- JDK 11 이상
- Android SDK 37

### 빌드 및 실행
```bash
# 저장소 클론
git clone https://github.com/사용자계정/DongkeyChess.git

# 프로젝트 디렉토리 이동
cd DongkeyChess

# 디버그 APK 빌드
./gradlew assembleDebug
