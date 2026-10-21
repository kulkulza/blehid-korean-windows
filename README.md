# BleHid 한국어 키·입력 공유 Windows 배포

[다운로드 및 릴리스 설명](https://github.com/kulkulza/blehid-korean-windows/releases)

공식 [windows-ble-hid](https://github.com/abhishek-raj/windows-ble-hid) **v0.6.0**을 기반으로 만든 비공식 수정본입니다. 공식 프로젝트나 공식 배포본은 변경하지 않습니다.

- Galaxy 입력 모드: 물리 한/영 전용키를 Shift+Space HID 입력으로 변환하며, PC 입력 모드의 한/영키 동작을 유지합니다.
- PC ↔ Galaxy 전환: 기본 Ctrl+Space, 설정에서 단축키 변경 가능.
- Bluetooth 텍스트 클립보드: 별도로 받은 Android Companion과 함께 Ctrl+C → 대상 전환 → Ctrl+V.
- Windows x64 / .NET 8 자체 포함 단일 EXE. ZIP 압축을 푼 뒤 **BleHid.App.exe**를 실행하세요. PC에 .NET SDK나 Python 설치가 필요하지 않습니다.
- 이 저장소의 릴리스에는 **Windows 배포 ZIP만** 올립니다. APK는 포함하지 않습니다.

자동 검증은 Windows 테스트 353개와 시작·종료 확인을 통과했습니다. 실제 Galaxy S21(Android 15 / One UI 7.0), 2.4GHz 동글 키보드 및 Bluetooth 클립보드 왕복은 **미검증**입니다. ZIP의 한국어 안내문과 테스트 결과를 확인하세요.

원본 및 의존 라이선스는 ZIP에 포함되어 있습니다. 원본 저작권: Copyright (c) 2026 Abhishek Raj, MIT License.
