---
title: crabar 지원 · Support
---

# crabar 지원

crabar는 메뉴바에 CPU와 메모리(RAM) 사용량을 작게 보여 주는 Mac 앱입니다.

## 사용법

앱을 실행하면 Dock 아이콘 없이 화면 오른쪽 위 메뉴바에 CPU·RAM 아이콘이 나타납니다. 아이콘을 클릭하면 메뉴가 열립니다.

- **CPU · 메모리 수치**: CPU 사용률과 코어 수, 사용 중인 메모리와 전체 메모리
- **갱신 주기**: 1초, 1.5초, 2초, 3초, 5초 중에서 고릅니다. 기본은 1.5초입니다.
- **표시 방식**: 게이지(막대) 또는 그래프(최근 사용량)
- **애니메이션**: 사용량이 높을수록 아이콘의 핀이 빠르게 흐르는 효과를 켜고 끕니다.
- **로그인 시 자동 실행**: 켜면 Mac에 로그인할 때 crabar가 자동으로 실행됩니다. 기본은 꺼져 있습니다.
- **활성 상태 보기 열기**: 어떤 앱이 CPU나 메모리를 많이 쓰는지 볼 수 있습니다.
- **종료**: crabar를 끕니다.

## 자주 묻는 질문

**메뉴바에 아이콘이 보이지 않아요.**
메뉴바에 아이콘이 많거나 노치가 있는 Mac에서는 공간이 모자라 일부 아이콘이 가려질 수 있습니다. 다른 메뉴바 아이콘을 줄이거나, 다른 앱 창을 클릭해 메뉴바 항목이 적은 앱으로 바꿔 보세요.

**메모리 사용량은 어떻게 계산하나요?**
활성 상태 보기의 '사용된 메모리'와 같은 방식(앱 메모리 + 와이어드 메모리 + 압축된 메모리)입니다. 파일 캐시는 빼고 계산하므로, 사용량이 높게 보여도 macOS가 필요할 때 바로 비울 수 있는 메모리는 포함되지 않습니다.

**crabar를 어떻게 끄나요?**
메뉴바 아이콘을 클릭하고 '종료'를 고르세요(메뉴가 열린 상태에서 ⌘Q도 됩니다). 다음 로그인 때 다시 실행되지 않게 하려면 '로그인 시 자동 실행'을 끄세요.

**배터리를 많이 쓰지 않나요?**
crabar는 몇 초에 한 번 시스템 통계를 읽을 뿐이라 부담이 적습니다. 더 줄이고 싶다면 갱신 주기를 길게 하거나 애니메이션을 끄세요.

## 문의

버그 신고나 기능 제안은 [GitHub 이슈](https://github.com/hoofam/docs/issues/new?title=%5Bcrabar%5D%20)로 남겨 주세요. macOS 버전과 Mac 모델을 함께 적어 주시면 도움이 됩니다.

[개인정보 처리방침](privacy)

---

# crabar Support

crabar is a Mac app that shows CPU and memory (RAM) usage in the menu bar.

## How to use

When you launch crabar, CPU and RAM icons appear in the menu bar at the top right of the screen (there is no Dock icon). Click the icons to open the menu.

- **CPU and memory details**: CPU usage and core count, memory in use and total memory
- **Refresh interval**: Choose 1, 1.5, 2, 3, or 5 seconds. The default is 1.5 seconds.
- **Display style**: Gauge (bar) or graph (recent usage)
- **Animation**: Turns on or off the effect where the icon's pins flow faster as usage rises.
- **Launch at login**: When on, crabar starts automatically when you log in. Off by default.
- **Open Activity Monitor**: See which apps are using the most CPU or memory.
- **Quit**: Quits crabar.

## FAQ

**I can't see the icon in the menu bar.**
On a crowded menu bar, or on a Mac with a notch, some icons may be hidden for lack of space. Try removing other menu bar icons, or switch to an app with fewer menus.

**How is memory usage calculated?**
The same way as "Memory Used" in Activity Monitor (app memory + wired memory + compressed memory). File cache is excluded, so memory that macOS can free immediately is not counted.

**How do I quit crabar?**
Click the menu bar icon and choose Quit (or press ⌘Q while the menu is open). To keep it from starting the next time you log in, turn off Launch at login.

**Does it drain the battery?**
crabar only reads system statistics once every few seconds, so its overhead is small. To reduce it further, choose a longer refresh interval or turn off the animation.

## Contact

Please report bugs or suggest features via [GitHub Issues](https://github.com/hoofam/docs/issues/new?title=%5Bcrabar%5D%20). Including your macOS version and Mac model helps.

[Privacy Policy](privacy)
