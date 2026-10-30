# Lookout (룩아웃)

데드락을 하면서 옆에 켜 두는 무료 도우미 앱입니다. Windows 오버레이와 설치 없이 쓰는 웹 공략을 제공합니다.

Lookout is a free Windows companion for Deadlock, with an in-game overlay and browser-based guides, hero builds and maps.

**[공식 사이트 · Website](https://obeloworks.com/)** · [English](https://obeloworks.com/en/) · [简体中文](https://obeloworks.com/zh/) · [Русский](https://obeloworks.com/ru/)

## 다운로드와 설치

**[Windows용 무료 다운로드](https://github.com/inspace9018/lookout-releases/releases/latest/download/Lookout-Setup.exe)**

1. 경기를 마친 뒤 설치 파일을 실행합니다.
2. Deadlock을 창 모드나 테두리 없는 창 모드로 실행합니다.
3. 대시보드에서 게임 연결 상태를 확인합니다.

이 저장소는 설치 파일과 변경 내역을 배포하는 곳입니다. 앱 소스 저장소는 아닙니다.

[설치·표시 문제 해결](https://obeloworks.com/help/install/) · [변경 내역과 이전 버전](https://github.com/inspace9018/lookout-releases/releases)

## 오버레이

- 정글 캠프 재생성 시간과 시간 알림
- 영웅 정보와 능력 투자 효과
- Tab 화면의 팀 정보, 일반 경기와 난투에 맞춘 표시
- 설정에서 표시 항목, 글자 크기, 배경 농도와 단축키 조절

기본 단축키는 **F10 표시·숨기기**, **F11 미니맵 자세히 보기**입니다. 0.1.14부터 F10으로 숨기면 화면 캡처와 글자 인식도 일시 중지합니다.

![Lookout 경기 화면 예시](https://obeloworks.com/img/overlay-play.jpg)

화면 예시입니다. 모든 PC의 실제 경기 인식률이나 성능을 보장하는 자료는 아닙니다.

## 브라우저에서 쓰기

앱을 설치하지 않아도 볼 수 있습니다.

- [데드락 공략](https://obeloworks.com/guide/)
- [영웅별 능력·빌드·상대법](https://obeloworks.com/guide/heroes.html)
- [지도](https://obeloworks.com/guide/map.html)와 [라인 동선](https://obeloworks.com/guide/routes.html)
- [정글 생성·재생성 시간](https://obeloworks.com/guide/jungle-timers/)
- [도움말](https://obeloworks.com/help/)과 [웹 화면 둘러보기 영상](https://obeloworks.com/media/lookout-web-tour.mp4)

## 성능과 데이터 처리

고정된 FPS 감소량은 아직 실제 경기에서 측정하지 않았습니다. CPU 자료와 FPS를 구분한 [성능 확인 방법](https://obeloworks.com/help/performance/)을 제공합니다.

기본 화면 인식은 PC 안에서 처리합니다. 선택 기능인 게임 HUD 연동은 백업 후 게임 폴더에 모드 파일 한 개와 gameinfo.gi의 SearchPaths 세 줄을 적용하며, 대시보드에서 제거할 수 있습니다. 게임 메모리 읽기, DLL 주입과 패킷 조작은 사용하지 않습니다.

영웅 통계에는 [Deadlock API](https://deadlock-api.com/) 자료를 사용합니다. 웹사이트에는 자료 기준일과 집계 기간을 표시합니다. 피드백 진단과 스크린샷은 내용을 확인하고 전송에 동의한 경우에만 보냅니다. 대시보드와 웹사이트에는 광고가 있습니다.

## 피드백

앱의 피드백 창이나 [이슈 양식](https://github.com/inspace9018/lookout-releases/issues/new/choose)을 사용해 주세요. 게임 패치, 영웅, 발생 상황을 함께 적어 주면 확인하기 쉽습니다.

만든 곳: Nexus lab. Valve와 관계없는 팬 제작 도구입니다. Deadlock과 게임 이미지의 권리는 Valve에 있습니다.
