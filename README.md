# my-skills

내가 만든 Skill을 모아 두는 개인 플러그인 저장소입니다. 이 저장소를 템플릿으로 내 GitHub 계정에 복사해서 씁니다.

## 구조

```text
.claude-plugin/plugin.json       플러그인 이름과 설명
.claude-plugin/marketplace.json  이 저장소를 설치할 수 있게 하는 목록
skills/<스킬 이름>/SKILL.md       스킬 하나
evals/<사례 이름>/prompt.md       스킬이 의도대로 도는지 볼 입력
evals/<사례 이름>/graders/        잘 됐는지 판단하는 기준
```

## 들어 있는 스킬

- `witsttcpw`: 막혔을 때 작동할 수 있는 가장 단순한 것부터 만들게 합니다. 이름은 What Is The Simplest Thing That Could Possibly Work의 머리글자입니다.

## Claude에게 보낼 문장

- 설치: `이 저장소를 Claude Code 플러그인으로 설치해줘`
- 스킬 더하기: `skill-creator로 skills/ 아래에 새 스킬을 만들어줘`
- 확인: `claude plugin eval로 이 플러그인의 evals를 돌리고 결과를 알려줘`
