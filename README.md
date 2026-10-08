# SnapFlow

**Windows용 가볍고 빠른 화면 녹화 프로그램**입니다. 화면(전체·영역)을 녹화해서 바로 쓸 수 있는 MP4로 저장하고, 녹화 목록에서 바로 자르고 합칠 수 있습니다.

> 이 저장소는 **설치 파일 배포용**입니다. 소스 코드는 공개하지 않습니다.

## 다운로드

[**최신 버전 받기 (Releases)**](../../releases/latest) — `SnapFlow-Setup-x.y.z.exe`를 받아 실행하면 설치됩니다.

## 주요 기능

- **화면 녹화**: 모니터 전체 또는 원하는 영역을 골라 MP4(H.264/AAC)로 저장합니다.
- **소리 녹음**: 시스템 소리와 마이크를 따로 켜고 끌 수 있고, 장치를 고르면 입력 레벨이 표시됩니다.
- **웹캠**: 녹화 화면에 웹캠 영상을 함께 넣을 수 있습니다.
- **마우스 커서 표시·강조**, **로고(워터마크)** 넣기
- **확대(줌)**: 녹화 중에 화면을 100·200·300·400% 중에서 골라 확대해서 보여 줍니다.
- **화면 주석**: 녹화 중에 화면 위에 바로 그릴 수 있습니다.
- **스크린샷**: 단축키 한 번으로 PNG 저장
- **일시정지 / 다시 시작 / 시작 전 3초 카운트다운**
- **녹화 목록 · 자르기**: 원하는 구간만 잘라 냅니다. 재인코딩 없이 빠르게 자르는 방식과 프레임 단위로 정확하게 자르는 방식 중에서 고를 수 있습니다.
- **녹화 목록 · 합치기**: 영상 여러 개를 하나로 합칩니다. 설정이 같은 영상은 **재인코딩 없이** 몇 초 만에 합치고, 해상도가 다르면 크기를 맞춰서 합칩니다.
- 시스템 트레이에 상주하며, 한국어와 영어를 지원합니다.

## 기본 단축키

| 단축키 | 동작 |
|---|---|
| `Ctrl+F9` | 녹화 시작 / 정지 |
| `Ctrl+F8` | 일시정지 / 다시 재생 |
| `Ctrl+Shift+F9` | 처음부터 다시 녹화 |
| `Ctrl+F7` | 스크린샷 |
| `Ctrl+Alt+1` ~ `4` | 확대 100% / 200% / 300% / 400% |
| `Ctrl+/` | 화면 주석 |
| `Ctrl+\` | 컨트롤 패널 숨김 / 표시 |
| `Ctrl+]` | 녹화 영역 테두리 숨김 / 표시 |

## 설치와 사용

- **필요 환경**: Windows 10 (버전 2004) 이상, 64비트. .NET 런타임이 포함되어 있어 따로 설치할 필요가 없습니다.
- **설치 위치**: 기본은 현재 사용자 설치라서 관리자 권한이 필요 없습니다. (설치 중에 "모든 사용자" 설치도 고를 수 있습니다.)
- **저장 위치**: 녹화 파일은 기본으로 `내 동영상\SnapFlow` 폴더에 `Rec 0001.mp4`처럼 번호가 붙어 저장됩니다. 설정에서 바꿀 수 있습니다.
- **SmartScreen 경고**: 설치 파일에 코드 서명이 없어서 처음 실행할 때 "Windows의 PC 보호" 경고가 뜰 수 있습니다. **추가 정보 → 실행**을 누르면 설치할 수 있습니다.
- 제거는 Windows 설정의 "설치된 앱"에서 SnapFlow를 지우면 됩니다.

---

## English

**SnapFlow** is a lightweight screen recorder for Windows. It records a monitor or a region to MP4, can mix in system sound, microphone and webcam, and lets you cut and join recordings right from its recording list (joining clips with the same settings needs no re-encoding).

> This repository only distributes the installer; the source code is not public.

- **Download:** get `SnapFlow-Setup-x.y.z.exe` from [Releases](../../releases/latest).
- **Requires:** Windows 10 (version 2004) or later, 64-bit. The .NET runtime is included.
- **Install:** per-user by default (no administrator rights needed); Korean and English.
- **SmartScreen:** the installer is not code-signed, so Windows may warn on first launch — choose *More info → Run anyway*.
