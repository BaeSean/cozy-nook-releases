# Cozy Nook · With 마나

방을 꾸미고 캐릭터·고양이와 함께 지내는 Windows 데스크톱 컴패니언 게임입니다. 이 저장소는 배포 파일과 안내 전용이며 소스와 사용자 저장 데이터는 포함하지 않습니다.

## 설치 및 실행

[최신 설치 버전 v0.327-beta.1](https://github.com/BaeSean/cozy-nook-releases/releases/tag/v0.327-beta.1)

[With-Mana-Setup.exe 다운로드](https://github.com/BaeSean/cozy-nook-releases/releases/download/v0.327-beta.1/With-Mana-Setup.exe)

1. Setup을 실행하고 설치 경로를 선택하세요. 기본값은 `%LOCALAPPDATA%\CozyNook.WithMana`입니다.
2. 설치 완료 화면의 **게임 실행**을 누르세요.
3. 이후에는 바탕화면 또는 시작 메뉴의 **With 마나** 바로가기로 실행하세요.

직접 실행할 경우 선택한 설치 폴더 안의 `current\CozyNook.FourTail.exe`를 사용하세요. 다른 파일과 섞이지 않는 전용 설치 폴더를 선택해 주세요. 설치할 드라이브에 여유 공간 3GB가 필요합니다.

Windows 64비트용이며 .NET 런타임을 포함합니다. YouTube에는 WebView2 Runtime과 인터넷이 필요합니다. 개인 음악은 포함하지 않습니다. 전체·감상·미니·집중 모드를 지원합니다.

## 자동 업데이트와 저장

게임 실행 시 새 버전을 다운로드·적용한 뒤 다시 실행합니다. 공개된 베타도 업데이트 대상이며 다운로드 취소나 네트워크 오류 시 기존 버전으로 실행합니다.

0.324 이하 ZIP 사용자는 Setup을 최초 한 번 설치해야 합니다. 0.325 자동 업데이트 설치본은 계속 업데이트할 수 있습니다. 업데이트는 기존 설치 경로를 임의로 옮기지 않습니다. 위치를 바꾸려면 게임을 종료하고 Setup에서 새 전용 폴더를 선택하세요.

0.327부터 저장 위치는 `설치 폴더\Saves\FourTail\save.json`입니다. 기존 `%LOCALAPPDATA%\CozyNook\FourTail`의 저장·백업은 첫 실행 시 자동 복사되며 원본은 보존합니다. 새 위치에 저장이 있으면 덮어쓰지 않습니다. 업데이트가 교체하는 `current` 폴더 밖에 저장하므로 치즈·구매 아이템·방·설정이 유지됩니다.

게임을 종료한 뒤 `Saves\FourTail` 폴더를 백업하세요. 설치 폴더 전체를 삭제하거나 제거하기 전에는 별도로 백업해 주세요. `.nupkg`와 `releases.win.json`은 자동 업데이트용이며 직접 실행하지 않습니다.

설치 파일·폴더·게시자는 게임 이름으로 표시합니다. GitHub 주소에 나오는 소유 계정명은 유지됩니다. 코드 서명은 아직 적용되지 않았으며 다른 PC·DPI 환경 검증은 계속 필요합니다.

## 오류 제보

[Issues](https://github.com/BaeSean/cozy-nook-releases/issues)에 버전, 모드, 재현 과정과 화면을 남겨 주세요. 개인 정보가 담긴 저장 파일은 공개로 첨부하지 마세요.
