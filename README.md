# PC Remote 수신기 (Windows)

폰의 **PC Remote** 앱으로 Windows PC(노트북)를 제어하기 위한 수신 프로그램입니다.
이 저장소는 **설치 파일 배포용**이며 소스 코드는 포함하지 않습니다.

## 다운로드

[Releases](https://github.com/chzhsea89/pcremote-receiver/releases/latest) 에서 `PcRemote-Receiver-1.0.zip` 을 받으세요.

## 설치 방법

1. zip 파일을 원하는 폴더에 압축 해제합니다.
2. `firewall-allow.bat` 을 **마우스 오른쪽 → 관리자 권한으로 실행** 합니다. (처음 한 번만, 방화벽 허용)
3. `PcRemoteServer.exe` 를 실행합니다. 창에 표시되는 PC 주소(IP)를 확인합니다.
4. 폰과 PC를 **같은 Wi-Fi** 에 연결한 뒤, 폰의 PC Remote 앱에서 그 주소로 연결합니다.

## 참고

- Windows 10 / 11 에서 동작합니다. (.NET Framework 4.x 기본 포함)
- "Windows의 PC 보호" 경고가 뜨면 **추가 정보 → 실행** 을 누르세요. (서명되지 않은 개인 배포 프로그램이라 나오는 안내입니다)
- PC 시작 시 자동 실행하려면 `PcRemoteServer.exe` 바로가기를 `shell:startup` 폴더에 넣으세요.
