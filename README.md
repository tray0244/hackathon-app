# hackathon-app

Pre-SKALA 해커톤 학습 사이트의 실습에 쓰는 FastAPI 예제 앱이다.

## API

| 메서드 | 경로 | 응답 |
|---|---|---|
| GET | `/` | `{"message": "hello hackathon"}` |
| GET | `/health` | `{"status": "ok"}` |

## 실행 방법

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```
