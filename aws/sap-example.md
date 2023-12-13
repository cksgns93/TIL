
미사용 데이터 암호화
EC2 인스턴스에 연결된 EBS 데이터 볼륨에 데이터를 저장하는 동안 암호화

EBS 저장하기 전 내부 데이터 암호화, 파일 시스템 수준, 타사 볼륨 암호화 도구 구현


3개월 100개 -> 3GB
24개월 100,000 -> 72TB
확장성 DynamoDB


IDS/IPS는 트래픽이 인스턴스에 도달하기 전에 트래픽을 분석해야 함


AWS Key Management Service 관리형 키와 함께 Amazon S3 서버 측 암호화
고객에 제공한 키와 함께, 자체 마스터 키
(EC2 키쌍은 SSH를 통해 인증하는 데 사용 됨)


S3 -> Glacier option

EMR - 빅 데이터 프레임워크 실행을 간소화하여 방대한 양의 데이터를 처리하고AWS 분석하는 관리형 클러스터 플랫폼
WAF(Web Application Firewall)

Amazon Kinesis - 실시간 데이터 분석 처리 시스템 (데이터 스트림을 간편하게 캡처, 처리 및 저장할 수 있음)


Route53

A레코드 : 도메인 주소와 서버의 IP주소를 직접 매핑
(IP를 바로 찾아갈 수 있지만 바뀌면 대응해줘야함)
CNAME : Canonical 도메인 주소를 또 다른 도메인 주소로 매핑
(유연하게 대처할 수 있음)

AMI Amazon Machine Image


AWS Direct Connect
사무실 환경과 같은 장소에서 AWS와 전용 네트워크 연결

BGP
Border Gateway Protocol
BGP 경로를 기존 라우팅 인프라에 재배포


인 메모리 캐시는 관계형 데이터베이스보다 수평으로 배포하는 것이 더 쉽기 때문에 확장하기가 더 쉬움
캐싱 계층은 사용량이 갑자기 급증할 경우 요청 버퍼를 제공

RTO(복구 시간 목표)
RPO(복구 지점 목표)
DR (Disaster Recovery)



RDS 백업이나 스냅샷은 S3에 기록된다.
Glacier Standard 검색은 시간이 소요됨
인스턴스 스토어 볼륨은 일시적

하나의 서브넷은 하나의 routing table을 가질 수 있음


AWS IT 인프라
SOC 1/SSAE 16/ISAE 3402(이전 SAS 70 Type II), SOC 2 및 SOC 3
FISMA, DIACAP 및 FedRAMP
PCI DSS 레벨 1, ISO 27001, ITAR 및 FIPS 140-2
HIPAA, CSA(Cloud Security Alliance) 및 MPAA(미국영화협회)


Auto Scaling - 사용자 프라이빗 키에서 계산된 HMAC-SHA1 서명

elasticity 탄력성

EBS Elastic Block Store
RAID 0, RAID 1, RAID 5, RAID 6,
RAID 0  디스


솔리드 스테이트 드라이브(SSD)으로 지원되는 프로비저닝된 IOPS 볼륨은 짧은 지연 시간이 필요한 중요한 IOPS 집약적이고 처리량 집약적인 워크로드를 위해 설계된 최고 성능의 Elastic Block Store(EBS) 스토리지 볼륨

EBS 최적화 처리량은 활용 가능한 총 IOPS를 제한합니다. 더 큰 처리량을 제공하는 EBSOptimized 인스턴스를 사용

S3는 장기 저장에 좋다

Amazon Kinesis 24시간 부터 최대 7일까지 데이터 보존 늘릴 수 있음,

Amazon CloudTrail - 표준화된 보안 로깅 서비스
CloudSearch - 검색 솔루션을 효율적인 비용으로 간단하게 설정, 관리 및 확장할 수 있음

CloudFront는 캐시에서 콘텐츠를 제공하기 전에 뷰어 요청과 관련된 Lambda 함수를 트리거하여 매개변수를 정규화할 수 있음

여러 User가 복수 계정에서 서로 다른 Role을 손쉽게 이동하면서 관리해야 할 경우를 위해 지난 해 교차 계정 접근 제어(Cross-Account Access) 기능

Storage Gateway

Route 53 가중치 라운드 로빈

가중치 기반 리소스 레코드, 지연 시간 별칭 리소스 레코드 세트에서 "Evaluate Target Health"를 "Yes"

SQS는 14일 동안만 저장
SES (Simple Email Service) 이메일 서비스 공급자

Amazon RDS - AWS Security Token Service "AssumeRole" 

EMR의 빅 데이터 워크로드는 내결함성 특성으로 인해 중단되더라도 계속해서 처리할 수 있다.

RRS (Reduced Redundancy Storage)

Amazon Elastic Map Reduce

AWS Key Management Service

Amazon Data Lifecycle Manager를 사용하여 EBS 스냅샷 및 EBS-backed AMI의 생성, 보존 및 삭제를 자동화할 수 있습니다.


고객 개인 정보를 유지하고 비용을 최소한으로 유지


IAM & R53은 글로벌 서비스

IAM 역할은 계정에 생성할 수 있는, 특정 권한을 지닌 IAM 자격 증명입니다.

교차 계정 액세스

최종적 일관성 SQS


vCenter용 EC2 VM Import Connector

웹 identity 패더레이션
웹 자격 증명 연동을 사용하여 필요할 때 동적으로 임시 AWS 보안 자격 증명을 요청하도록 앱을 구축



 웹 서버 앞에 역방향 프록시 레이어를 구현하고 각 역방향 프록시 서버에 IDS/IPS 에이전트를 구성

CloudFormation
WS 리소스를 모델링하고 설정하여 리소스 관리 시간을 줄이고 AWS에서 실행되는 애플리케이션에 더 많은 시간을 사용하도록 해 주는 서비스

Shield DDoS 방어 기능은 Route 53에 대한 CloudFront 트래픽을 지속적으로 검사

Elastic Transcoder

Cloud watch - rds,elb,route53


VPC 간의 연결
VPC Peering, VGW, DGW, TGW

BGP (Border Gateway Protocol) - 인터넷에서 데이터를 전송하는 데 가장 적합한 네트워크 경로를 결정하는 일련의 규칙

CIDR 블록 Classless Inter-Domain Routing(CIDR)은 인터넷상의 데이터 라우팅 효율성을 향상시키는 IP 주소 할당 방법

SWF - 완전한 관리가 가능한 클라우드 워크플로 웹 서비스로서, 복잡한 사용자 지정 코딩 워크플로 솔루션과 자동화 소프트웨어를 대체

EIP (Elastic IP)

TLS/SSL
보안 소켓 계층(Secure Sockets Layer, SSL) 인증서는 종종 디지털 인증서로 불리며, 브라우저(사용자의 컴퓨터)와 서버(웹사이트) 사이의 암호화된 연결을 수립하는 데 사용