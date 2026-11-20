# [SFC] 천지창조 한글패치

슈퍼패미컴 **천지창조**(天地創造) 한글패치입니다. 슈퍼패미컴 실기에서 구동하는 것을 목표로 작업했습니다.

- 블로그 소개글: https://dwyn.tistory.com/13
- 최신 버전 다운로드: [Releases](../../releases/latest)
- 버그 제보: [Issues → 버그 제보](../../issues/new/choose)
- 후원: https://litt.ly/dwyn

## 작업 사항 및 변경 이력

주요 작업 사항, 추가 기능, 변경 이력 등 자세한 내용은 **[블로그](https://dwyn.tistory.com/13)** 글을 참조해 주세요.

본 한글패치의 정보를 공유하실 때는 블로그 패치 글로 링크를 걸어 주세요.

## 적용 방법

1. [Releases](../../releases/latest)에서 패치 파일을 받습니다.
2. 직접 가지고 계신 원본 ROM에 패치를 적용합니다.
   - 웹에서 적용: [ROM Patcher JS](https://www.marcrobledo.com/RomPatcher.js/)
   - PC 프로그램: Delta Patcher 등
3. 패치된 ROM을 에뮬레이터나 플래시카트로 실행합니다.

### 체크섬 확인

패치는 **일본판 원본 ROM**(4,194,304바이트, 헤더 없음)에 적용해야 합니다. 패치 후 ROM은 6,291,456바이트로 커집니다.

| 구분 | CRC32 | MD5 | SHA1 |
|---|---|---|---|
| 원본 ROM (일본판) | `3CC7FDF4` | `5BEC2D7ECF3117B479C69CADA8EBAFA4` | `F787672E766A43A73D9BD310FCB3C2CAC024B227` |
| 패치 후 (v0.93, 6,291,456바이트) | `6F7E643E` | `829049FD7B092C18709130C1908F23A6` | `2E8B4621DABC6EF0F5F1FEBB9D8E3CECC00936A7` |

- 원본 파일 이름: `Tenchi Souzou (Japan).sfc` (512바이트 헤더가 붙은 .smc 파일은 헤더를 지운 뒤 적용해 주세요)
- ROM Patcher JS에 ROM 파일을 넣으면 CRC32, MD5, SHA1이 바로 표시됩니다.
- 6MB 확장 롬(ExHiROM)이라 최신 에뮬레이터, MiSTer, FXPak 같은 플래시카트에서 구동됩니다.

> 이 저장소에는 패치 파일만 있습니다. ROM 파일이나 패치를 적용한 ROM은 배포하지 않으며, 요청에도 응하지 않습니다.
