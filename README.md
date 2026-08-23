# portfolio-design

화면을 **시안을 다른 세 가지**로 만들고, 기준을 세워 하나를 고르게 해 드립니다.

---

## 설치

### 🍎 맥 · 리눅스 — 터미널에 붙여넣기

```bash
git clone https://github.com/soodiumstudio/portfolio-design.git ~/.claude/skills/portfolio-design
```

### 🪟 윈도우 — PowerShell 에 붙여넣기

> **PowerShell** 을 여세요. 시작 메뉴에서 "PowerShell" 을 검색하면 나옵니다.
> **cmd 창은 안 됩니다.** cmd 에서는 `~` 가 폴더 이름으로 잘못 인식됩니다.

```powershell
git clone https://github.com/soodiumstudio/portfolio-design.git "$env:USERPROFILE\.claude\skills\portfolio-design"
```

### 둘 다 끝나면

**Claude Code를 완전히 껐다 켜세요.** 그래야 스킬이 잡힙니다.

> 💡 `/plugin install` 은 쓰지 않습니다. 환경에 따라 그 명령이 아예 없습니다.
> 스킬은 스킬 폴더에 넣으면 그대로 인식됩니다.

## 쓰는 법

Claude Code 입력창에 (터미널 아니고, **채팅창**입니다):

    /portfolio-design

만들고 싶은 걸 한 줄로 적으셔도 되고, 그냥 실행하셔도 됩니다.

## 실행하면 이렇게 진행됩니다

1. **진행률이 계속 보입니다.** `▓▓▓▓░░░░░░ 40%` 처럼요. 얼마나 남았는지 알 수 있습니다.
2. **결과는 볼 수 있는 웹 페이지로 나옵니다.** 링크를 눌러서 보시면 됩니다.
   그대로 캡처해서 포트폴리오에 넣으셔도 됩니다.

## 무엇이 나오나요

- **화면 안 세 개** — 접근이 서로 다른
- **비교표** — 어떤 기준으로 골랐는지
- **포기한 것 정리** — 포트폴리오 한 페이지가 그대로 나옵니다

## 이건 못 합니다

- 실제로 작동하는 앱 — 그림까지입니다
- 사용자가 진짜 좋아할지 — 그건 써 보게 해야 압니다

## 자주 막히는 곳

| 이럴 때 | 이렇게 하세요 |
|---|---|
| `/portfolio-design` 이 안 보여요 | Claude Code를 완전히 껐다 켜세요 |
| 지난주 결과가 안 보여요 | 폴더를 잘못 여셨습니다. 매주 같은 폴더를 여세요 |
| 중간에 멈춘 것 같아요 | 진행률 막대를 보세요. 조사·채점 구간은 몇 분 걸립니다 |
| 윈도우인데 명령이 안 먹어요 | **PowerShell** 을 쓰세요. cmd 창에서는 `~` 가 안 됩니다 |
| 화면이 안 만들어져요 | `node` 가 필요합니다. [nodejs.org](https://nodejs.org) 에서 LTS 를 설치하세요 |

## 업데이트

```bash
cd ~/.claude/skills/portfolio-design && git pull
```
윈도우는
```powershell
cd "$env:USERPROFILE\.claude\skills\portfolio-design"; git pull
```
