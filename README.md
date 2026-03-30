<div align="center">

# hookAgent

<img width="500px" src="./docs/img/Preview.png">

**HookAgent는 AI Agent의 사용자 입력, 추론, 도구 사용을 가로채고 감시하여 나쁜 행동을 탐지하고 제한합니다.**

</div>

- [미리보기 이미지 설명](./docs/img/Description.png)
- [사용자의 수락을 기다리는 에이전트](./docs/img/WatingUserAccept.png)
- [도구 사용을 거절했을때 에이전트](./docs/img/WhenDeny.png)

## 탐지 과정

1. 사용자 입력에 프롬프트 인젝션 내용이 없는가?
2. 사용자 입력에 따른 정당한 추론인가?
3. 정당한 추론에 따른 정당한 도구 사용인가?
4. 도구 사용 결과가 추론에 부합하는가?

## 사용 방법

```bash
python3 app.py
```

## 문서 목록

- [프로젝트 개요](docs/project-overview.md)
- [현재 구현](docs/current-implementation.md)
- [컨트롤 패널](docs/control-panel.md)
- [로드맵](docs/roadmap.md)
