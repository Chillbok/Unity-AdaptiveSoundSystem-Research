# Unity Game Adaptive Music System Research

이 프로젝트는 Unity와 FMOD를 활용한 게임 내 적응형 음악(Adaptive Music) 시스템을 연구하고 구현하기 위한 저장소입니다.

## 개요

게임의 상황(전투, 탐험, 긴장감 등)에 따라 동적으로 변화하는 음악 시스템을 구축하는 것을 목표로 합니다. FMOD Studio를 사용하여 음악 에셋을 관리하고, Unity에서 이를 제어합니다.

## 프로젝트 구조

- **`Fmod-GameAdaptiveMusicSystem/`**: FMOD Studio 프로젝트 파일이 포함되어 있습니다. 음악 디자인 및 파라미터 설정을 담당합니다.
- **`Unity-GameAdaptiveMusicSystem/`**: Unity 프로젝트 파일이 포함되어 있습니다. 게임 로직과 FMOD 이벤트를 연결합니다.

## 시작하기

### 사전 준비

이 프로젝트를 실행하려면 다음 소프트웨어가 필요합니다:
- **Unity**: 6000.3.15f1
- **FMOD Studio**: 2.02.xx 이상 권장

### 사용 방법

1.  **FMOD 프로젝트 열기**: `Fmod-GameAdaptiveMusicSystem/Fmod-GameAdaptiveMusicSystem.fspro` 파일을 FMOD Studio에서 엽니다.
2.  **FMOD 뱅크 빌드**: FMOD Studio에서 `File > Build`를 실행하여 뱅크를 빌드합니다.
3.  **Unity 프로젝트 열기**: `Unity-GameAdaptiveMusicSystem` 폴더를 Unity Hub를 통해 엽니다.
4.  **FMOD 설정 확인**: Unity의 `Edit > Project Settings > FMOD`에서 뱅크 경로 및 설정이 올바른지 확인합니다.

## 연구 항목 (예정)

- 게임 파라미터(Parameter)에 따른 실시간 음악 레이어 변화
- 상태(State) 기반 음악 전환 및 크로스페이드
- 유니티 타임라인(Timeline)과 FMOD 연동
- 동적 비트 매칭 및 리듬 시스템

