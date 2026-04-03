# BREAKOUT

벽돌깨기 아케이드 게임. 단일 HTML 파일, 외부 의존성 없음.

## 플레이

**[▶ 플레이하기](https://on1659.github.io/breakout)**

## 게임 규칙

- 마우스 또는 터치로 패들 이동
- 클릭/탭으로 볼 발사
- 모든 벽돌을 부수면 다음 레벨
- 라이프 3개, 바닥에 떨어지면 -1

## 레벨 시스템

| 레벨 | 변화 |
|------|------|
| 1~2 | 기본 (벽돌 HP 1) |
| 3~4 | 상단 벽돌 HP 2, 패들 축소 |
| 5~10 | 최상단 HP 3, 볼 가속 |

## 스택

- HTML + CSS + Canvas API
- 폰트: JetBrains Mono (Google Fonts)
- 빌드 도구 없음, 번들러 없음

## 배포

```bash
# GitHub Pages
git add index.html
git commit -m "feat: breakout game"
git push
# Settings → Pages → main branch
```

## 라이선스

MIT
