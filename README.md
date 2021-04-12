# AWS_Study

### AWS Technical Essentials
1. AWS Foundational Services

> * EC2
>   + Amazon Elastic Compute Cloud(Amazon EC2)는 Amazon Web Services(AWS) 클라우드에서 확장 가능 컴퓨팅 용량을 제공합니다. Amazon EC2를 사용하면 하드웨어에 선투자할 필요가 없어 더 빠르게 애플리케이션을 개발하고 배포할 수 있습니다. Amazon EC2를 통해 원하는 만큼 가상 서버를 구축하고 보안 및 네트워크 구성과 스토리지 관리가 가능합니다. 또한 Amazon EC2는 요구 사항이나 갑작스러운 인기 증대 등 변동 사항에 따라 신속하게 규모를 확장하거나 축소할 수 있어 서버 트래픽 예측 필요성이 줄어듭니다.
> * VPC
>    + Virtual Private Cloud(VPC) — 사용자의 AWS 계정 전용 가상 네트워크
> * S3
>    + 아마존 S3(Amazon S3, Simple Storage Service)는 아마존 웹 서비스에서 제공하는 온라인 스토리지 웹 서비스이다. 아마존 S3는 웹 서비스 인터페이스를 통해 스토리지를 제공한다.
> * EBS
>    + Amazon Elastic Block Store(EBS)는 대규모로 처리량과 트랜잭션 집약적인 워크로드 모두를 지원하기 위해 Amazon Elastic Compute Cloud(EC2)에서 사용하도록 설계된 사용하기 쉬운 고성능 블록 스토리지 서비스입니다. 관계형 및 비관계형 데이터베이스, 엔터프라이즈 애플리케이션, 컨테이너화된 애플리케이션, 빅 데이터 분석 엔진, 파일 시스템 및 미디어 워크플로와 같은 다양한 워크로드가 Amazon EBS에 널리 배포됩니다.
>    

2. AWS Security

> * IAM
>    + AWS Identity and Access Management(IAM)는 AWS 리소스에 대한 액세스를 안전하게 제어할 수 있는 웹 서비스입니다. IAM을 사용하여 리소스를 사용하도록 인증(로그인) 및 권한 부여(권한 있음)된 대상을 제어합니다.
>    

3. AWS Databases

> * DynamoDB
>    + Amazon DynamoDB는 종합 관리형 NoSQL 데이터베이스 서비스로, 원활한 확장성과 함께 빠르고 예측 가능한 성능을 제공
>    + DynamoDB를 통해 데이터 규모에 관계없이 데이터를 저장 및 검색하고, 어떤 수준의 요청 트래픽이라도 처리할 수 있는 데이터베이스 테이블을 생성할 수 있습니다.
>    

4. AWS Management Tools

> * Auto Scaling
>    + Amazon EC2 Auto Scaling를 통해 애플리케이션의 로드를 처리할 수 있는 정확한 수의 Amazon EC2 인스턴스를 보유하도록 보장할 수 있습니다. Auto Scaling 그룹.이라는 EC2 인스턴스 모음을 생성합니다. 각 Auto Scaling 그룹의 최소 인스턴스 수를 지정할 수 있으며, Amazon EC2 Auto Scaling에서는 그룹의 크기가 이 값 아래로 내려가지 않습니다. 각 Auto Scaling 그룹의 최대 인스턴스 수를 지정할 수 있으며, Amazon EC2 Auto Scaling에서는 그룹의 크기가 이 값을 넘지 않습니다. 원하는 용량을 지정한 경우 그룹을 생성한 다음에는 언제든지 Amazon EC2 Auto Scaling에서 해당 그룹에서 이만큼의 인스턴스를 보유할 수 있습니다. 조정 정책을 지정했다면 Amazon EC2 Auto Scaling에서는 애플리케이션의 늘어나거나 줄어드는 수요에 따라 인스턴스를 시작하거나 종료할 수 있습니다.
> * Elastic Load Balancing
>    + Elastic Load Balancing은(는) 둘 이상의 가용 영역에서 EC2 인스턴스, 컨테이너, IP 주소 등 여러 대상에 걸쳐 수신되는 트래픽을 자동으로 분산합니다. 이는 등록된 대상의 상태를 모니터링하여 정상 상태인 대상으로만 트래픽을 라우팅합니다. 시간이 흐르면서 수신되는 트래픽이 변화함에 따라 Elastic Load Balancing이(가) 로드 밸런서를 확장합니다. 대다수의 워크로드에 맞게 자동으로 조정할 수 있습니다.
> * Cloud Watch
>    + Amazon CloudWatch는 Amazon Web Services(AWS) 리소스와 AWS에서 실시간으로 실행 중인 애플리케이션을 모니터링합니다. CloudWatch를 사용하여 리소스 및 애플리케이션에 대해 측정할 수 있는 변수인 지표를 수집하고 추적할 수 있습니다.
> * Trusted Advisor
>    + AWS Trusted Advisor는 AWS 모범 사례에 따라 리소스를 프로비저닝하는 데 도움이 되도록 실시간 지침을 제공하는 온라인 도구
