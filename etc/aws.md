# cloudfront

## edge location

* AWS에서 CloudFront의 cache 서버
* [CloudFront](https://aws.amazon.com/ko/cloudfront/features/?nc=sn&loc=2)

## origin

* 배포를 생성할 때 CloudFront가 엣지 로케이션에 배포할 파일에 대한 요청을 보내는 위치를 지정합니다.

## cache behavior

* 캐시 동작은 웹 사이트에 있는 파일의 지정된 URL 경로 패턴에 대해 다양한 CloudFront 기능을 구성할 수 있도록 합니다.

![behavior](./images/cloudfront-behavior.png)

- [cache 설정](https://docs.aws.amazon.com/ko_kr/AmazonCloudFront/latest/DeveloperGuide/Expiration.html)

## OAI(Origin Access Identity)

## lambd@edge

![lambda@edge](./images/cloudfront-lambdaedge.png)

* viewer request, viewer response 제한 시간 5초
* origin request, origin response 제한 시간 30초
