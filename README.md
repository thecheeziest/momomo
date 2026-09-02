# momomo — macOS 플로팅 메모 앱

<p align="center">
  <img src="./icon.png" alt="momomo logo" width="128" />
</p>

<h2 align="center">
  <code>모</code>든 메<code>모</code>를 <code>모</code>찌게!
</h2>

<p align="center">
커스텀 컬러 테마로 멋있게 메모하고,
</p>

<p align="center">
폴더별 메모 생성, 태그 및 상태 기능으로 모든 메모 정리하기
</p>

<p align="center">
전체 화면 모드에서도 떠 있는 플로팅 메모 앱, 모모모!
</p>

## Preview

<p align="center">
  <img src="./docs/images/ex_toolbar.gif" alt="momomo toolbar usage example" height="519" />
  <img src="./docs/images/ex_memo.gif" alt="momomo memo usage example" height="519" />
</p>



## Installation

| 순서 | 작업 |
| --- | --- |
| 1 | **[Releases](https://github.com/thecheeziest/momomo/releases/latest)** 페이지에서 `.dmg` 파일 다운로드 |
| 2 | `.dmg` 파일 더블 클릭, `momomo.app`을 `Applications` 폴더로 드래그 |
| 3 | `Applications` 폴더 또는 Spotlight에서 momomo 실행 |
| 4 | 첫 실행 시 *"인터넷에서 다운로드한 항목입니다"* 창이 뜨면 **열기** 클릭 |

> Apple 개발자 서명 + 공증을 받은 앱이라 별도 터미널 명령 없이 바로 실행됩니다



## How to Use

- 실행 시 트레이(메뉴바)에 아이콘이 표시됩니다
- Dock에 아이콘이 뜨는 앱이 아니기 때문에 트레이 아이콘으로 조작합니다
- `Cmd+Shift+M`으로 앱을 보이게 하거나 숨길 수 있습니다
- 트레이 아이콘 클릭 또는 앱에서 `우 클릭` 후 **가이드**를 누르면 자세한 설명을 볼 수 있습니다
- 트레이에서 `Cmd`를 누른 채 아이콘 위치를 옮겨 두면 편리합니다 `(다른 앱 아이콘에 밀리지 않게 방지)`



## Updating

`momomo`는 이제 앱 안에서 자동으로 업데이트됩니다.

| 순서 | 작업 |
| --- | --- |
| 1 | 새 버전이 나오면 앱이 감지해 **"지금 업데이트할까모?"** 창을 띄웁니다 (트레이 메뉴 → **업데이트 확인**으로 직접 확인도 가능) |
| 2 | **업데이트** 클릭 → 자동으로 내려받아 설치하고 앱이 다시 켜집니다 |
| 3 | 업데이트가 끝나면 바뀐 내용이 패치노트로 표시됩니다 |

> `.dmg` 재다운로드 · 드래그 · 터미널 명령 모두 필요 없습니다
>
> 메모 데이터(`~/Library/Application Support/momomo`)는 업데이트와 무관하게 그대로 유지됩니다
>
> ⚠️ AppCleaner, CleanMyMac 같은 정리 앱으로 지우면 메모 데이터까지 함께 삭제됩니다 — 지울 땐 Finder에서 `momomo.app`만 휴지통으로
>
> v2.2.0 이하에서 올라오는 경우엔 한 번만 Releases에서 최신 `.dmg`를 받아 위 설치 방법대로 교체하면, 이후로는 자동 업데이트됩니다
