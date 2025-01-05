# Fear and Greed Index

[Alternative.me](https://alternative.me/crypto/fear-and-greed-index/)에서 제공하는 공포탐욕 지수를 API를 통해 가져오는 Python 스크립트입니다. 공포탐욕 지수는 암호화폐 시장의 투자 심리를 측정하는 데 유용한 지표입니다.

## 주요 기능

- `Alternative.me` API를 사용하여 최신 공포탐욕 지수를 가져옵니다.
- 공포탐욕 지수 값, 현재 상태(예: "Extreme Fear", "Greed"), 타임스탬프를 반환합니다.
- 간단한 Python 스크립트로, 암호화폐 투자 전략을 지원하는 데 유용합니다.

## 사용 방법

### 1. 의존성 설치

이 스크립트는 `requests` 라이브러리를 사용합니다. 먼저 아래 명령어를 실행하여 필요한 라이브러리를 설치하세요:

```bash
pip install requests
