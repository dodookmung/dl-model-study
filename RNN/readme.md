# RNN 모델 구조 학습

## 환경설정

가상환경 동기화: 
```bash
uv sync
```

끝

<br><br>

### 만약 안된다면 Custom
CUDA 버전에 맞는 torch 설치
```bash
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu134

#uv
uv add --dev ipykernel
uv add torch torchvision --index pytorch=https://download.pytorch.org/whl/cu134
```


## References

RNN의 역사와 발전 과정을 전체적으로 조망하고 싶을 때 참고하기 좋은 아카이브 리뷰 논문입니다.

* **Neural Networks (RNNs): A gentle Introduction and Overview (2019)** [arXiv:1912.05911 PDF 다운로드](https://arxiv.org/pdf/1912.05911)
* **저자:** Robin M. Schmidt