# AWS cli

AWS 명령줄 인터페이스(CLI)는 AWS 서비스를 관리하는 통합 도구입니다. 도구 하나만 다운로드하여 구성하면 여러 AWS 서비스를 명령줄에서 제어하고 스크립트를 통해 자동화할 수 있습니다.

## 사전 준비

- [aws credential 설정](https://docs.aws.amazon.com/ko_kr/cli/latest/userguide/cli-chap-configure.html)
- [aws-cli 설치 및 구성](https://docs.aws.amazon.com/ko_kr/streams/latest/dev/kinesis-tutorial-cli-installation.html)

### 사용 예시

```bash
aws s3 cp <local file path> s3://<bucket-name>/<key> # local에 있는 file을 s3로 복사
```