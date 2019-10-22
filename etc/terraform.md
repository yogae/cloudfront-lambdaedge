# terraform

## 설치

- [terraform 설치](https://learn.hashicorp.com/terraform/getting-started/install.html)

- brew로 설치

    ```bash
    brew install terraform
    ```

> [tfenv 설치](https://github.com/tfutils/tfenv)

## 사용법

```bash
tf init # terraform 설정 초기화

tf plan # 기존에 반영된 infra와 비교하여 변경사항을 확인

tf apply # infra를 변경

workspace # 환경을 여러개로 분리하여 구성(dev 환경과 prod환경을 분리할 때 주로 사용)
```

## Reference

- [terraform](https://www.terraform.io/docs/configuration/resources.html)