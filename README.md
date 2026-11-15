# dl-model-study
Deep Learning Model 구조 공부

## 환경설정 포맷

* **uv sync**: 기본적으로 **--dev**로 지정된 패키지(예: ipykernel)를 포함하여 모든 의존성이 함께 설치됩니다. 로컬에서 개발할 때는 이 명령어 하나로 끝납니다.

* **uv sync --no-dev**: 나중에 실제 서버에 배포하거나 Docker 컨테이너를 빌드할 때 등, 실행에 꼭 필요한 패키지만 깔끔하게 올리고 싶을 때 개발용 패키지를 제외하고 설치하는 옵션입니다.

```bash
uv init

uv add --dev ipykernel
uv add torch torchvision --index pytorch=https://download.pytorch.org/whl/cu134
```