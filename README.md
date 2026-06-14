# 💪 곰 ❤️ 토끼 다이어트 챌린지

2026년 9월 20일까지 목표 달성을 위한 커플 다이어트 트래커입니다.

| | 목표 (9/20) |
|---|---|
| 🐻 곰 | **-5.0 kg** |
| 🐰 토끼 | **-5.0 kg** |

> 개인정보 보호를 위해 실제 체중은 저장하지 않고 **감량량(kg)** 만 기록합니다. 시작 몸무게·연결 키는 각 기기 브라우저에만 저장됩니다.

## 📊 페이지

GitHub Pages로 자동 배포됩니다: https://sungjjoo.github.io/diet-challenge/

## ✍️ 몸무게 기록하는 법 (모바일/PC)

페이지의 **"✍️ 오늘 몸무게 기록"** 에서 지금 잰 몸무게를 넣고 **저장하기**를 누르면 끝입니다.
저장 시 실제 체중이 아닌 **감량량만** `data.json`에 커밋되고 그래프가 갱신됩니다.

### 기기 최초 1회 설정

각 기기에서 처음 한 번만 페이지 **⚙️ 설정**에서 아래를 등록합니다.

1. [Fine-grained token 생성](https://github.com/settings/tokens?type=beta) → **Generate new token**
2. Repository access → **Only select repositories** → `diet-challenge`
3. Permissions → **Contents** → **Read and write**
4. 생성된 `github_pat_...` + 각자 **시작 몸무게**를 ⚙️ 설정에 입력 후 저장

## 🤖 자동 커밋

`.github/workflows/daily.yml`이 매일 오전 8시(KST)에 `lastSync`(D-day 기준일)를 자동 갱신·커밋합니다.
