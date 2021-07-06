# free-for.dev

개발자와 오픈 소스 작성자는 무료 등급(free tier)를 제공하는 방대한 서비스를 보유하고 있지만 정보에 입각한 결정을 내리기 위해 모든 등급(tier)을 찾기가 어려울 수 있습니다.

이것은 소프트웨어(SaaS, PaaS, IaaS 등) 및 개발자를 위한 무료 등급이 있는 기타 제품 목록입니다.

이 특정 목록의 범위는 인프라 개발자(System Administrator, DevOps Practitioners 등)가 유용할 수 있는 것으로 제한됩니다. 우리는 모든 무료 서비스를 좋아하지만 주제를 유지하는 것이 좋습니다. 때때로 약간의 회색 선이므로 약간의 의견이 있습니다. 당신의 기여를 받아들이지 않으면 기분이 상하지 않습니다.

이 목록은 500명 이상이 수행한 풀 요청(pull request), 검토, 아이디어 및 작업의 결과입니다. 풀 요청을 전송하여 더 많은 서비스를 추가하거나 오퍼링이 변경되거나 폐기 된 서비스를 제거하면 도움이 될 수 있습니다.

GitHub 또는 전용 웹 사이트 [free-for.dev](free-for.dev)에서 목록을 찾을 수 있습니다.

*참고:* 이 목록은 자체 호스팅 소프트웨어가 아닌 서비스 제공 서비스에만 해당됩니다. 서비스를 받으려면 무료 평가판(free trial)이 아닌 무료 등급(Free Tier)을 제공해야 합니다. 프리 티어에 시간이 걸리는 경우 최소 1년 이상이어야 합니다.

Table of Contents
=================

   * [Major Cloud Providers' Always-Free Limits](#major-cloud-providers)
   * [Analytics, Events and Statistics](#analytics-events-and-statistics)
   * [APIs, Data and ML](#apis-data-and-ml)
   * [Artifact Repos](#artifact-repos)
   * [Automated Browser Testing](#automated-browser-testing)
   * [BaaS](#baas)
   * [CDN and Protection](#cdn-and-protection)
   * [CI / CD](#ci--cd)
   * [Code Quality](#code-quality)
   * [Code Search and Browsing](#code-search-and-browsing)
   * [Crash and Exception Handling](#crash-and-exception-handling)
   * [Data Visualization on Maps](#data-visualization-on-maps)
   * [DBaaS](#dbaas)
   * [Design and UI](#design-and-ui)
   * [DNS](#dns)
   * [Docker Related](#docker-related)
   * [Email](#email)
   * [IaaS](#iaas)
   * [IDE and Code Editing](#ide-and-code-editing)
   * [International Mobile Number Verification API and SDK](#international-mobile-number-verification-api-and-sdk)
   * [Issue Tracking and Project Management](#issue-tracking-and-project-management)
   * [Log Management](#log-management)
   * [Management Systems](#management-system)
   * [Miscellaneous](#miscellaneous)
   * [Monitoring](#monitoring)
   * [Other Free Resources](#other-free-resources)
   * [PaaS](#paas)
   * [Package Build System](#package-build-system)
   * [Payment / Billing Integration](#payment--billing-integration)
   * [Search](#search)
   * [Security and PKI](#security-and-pki)
   * [Source Code Repos](#source-code-repos)
   * [Storage and Media Processing](#storage-and-media-processing)
   * [STUN, WebRTC, Web Socket Servers and Other Routers](#stun-webrtc-web-socket-servers-and-other-routers)
   * [Tools for Teams and Collaboration](#tools-for-teams-and-collaboration)
   * [Translation Management](#translation-management)
   * [Vagrant Related](#vagrant-related)
   * [Visitor Session Recording](#visitor-session-recording)
   * [Web Hosting](#web-hosting)
   
## 주요 클라우드 제공 업체

### [Google Cloud Platform](https://cloud.google.com)
- App Engine - 하루 28 개의 프런트 엔드 인스턴스 시간, 하루에 9 개의 백엔드 인스턴스 시간
- Cloud Firestore - 1GB 스토리지, 50,000 읽기, 20,000 쓰기, 하루 20,000 삭제
- Compute Engine - 1 개의 비선 점형 f1-micro, 30GB HDD, 5GB 스냅 샷 스토리지 (특정 지역으로 제한됨)
- 클라우드 스토리지 - 5GB, 1GB 네트워크 송신
- Cloud Pub / Sub - 매월 10GB의 메시지
- 클라우드 기능 - 한 달에 2 백만 건의 호출 (백그라운드 및 HTTP 호출 모두 포함)
- Google Kubernetes Engine - 모든 규모의 클러스터에 대한 클러스터 관리 수수료가 없습니다. 각 사용자 노드는 표준 Compute Engine 요금으로 청구됩니다
- BigQuery - 매월 1TB의 쿼리, 매월 10GB의 스토리지
- 클라우드 빌드 - 하루 120 분
- 클라우드 소스 리포지토리 - 최대 5 명의 사용자, 50GB 스토리지, 50GB 송신
- 자세한 전체 목록 - https://cloud.google.com/free/docs/gcp-free-tier#always-free-usage-limits

###  [Amazon Web Services](https://aws.amazon.com)
- Amazon DynamoDB - 25GB NoSQL DB
- Amazon Lambda - 매월 1 백만 건의 요청
- Amazon SNS - 한 달에 1 백만 건의 게시
- Amazon Cloudwatch - 10 개의 사용자 지정 지표 및 10 개의 경보
- Amazon Glacier - 10GB 장기 객체 스토리지
- Amazon SQS - 100 만 개의 메시징 대기열 요청
- Amazon CodeBuild - 매월 100 분의 빌드 시간
- Amazon Code Commit - 한 달에 5 명의 활성 사용자
- Amazon Code Pipeline - 한 달에 1 개의 활성 파이프 라인
- 전체 상세 목록 - https://aws.amazon.com/free/?awsf.Free%20Tier%20Types=categories%23alwaysfree

### [Microsoft Azure](https://azure.microsoft.com)
- 앱 서비스 - 10 개의 웹, 모바일 또는 API 앱
- 기능 - 한달에 백만 건의 요청
- DevTest Labs - 빠르고 쉬운 린 개발 테스트 환경을 가능하게합니다.
- Active Directory - 500,000 개의 개체
- Active Directory B2C - 월간 저장된 사용자 50,000 명
- Azure DevOps - 5 명의 활성 사용자
- Microsoft IoT Hub - 매일 8,000 개의 메시지
- 로드 밸런서 - 1 개의 무료 공개로드 밸런싱 IP (VIP)
- 알림 허브 - 백만 개의 푸시 알림
- 대역폭 - 월 5GB 송신
- Visual Studio 코드
- 자세한 전체 목록 - https://azure.microsoft.com/en-us/free/

### [Oracle Cloud](https://www.oracle.com/cloud/)
- 컴퓨팅 - 2 VM. 표준. E2.1. 마이크로 1GB RAM
- 블록 볼륨 - 2 개 볼륨, 총 100GB (계산에 사용)
- 객체 저장 - 10 기가 바이트
- 로드 밸런서 - 10 Mbps 의 인스턴스 1 개
- 데이터베이스 - 2개의 DB, 각 20GB
- 모니터링 - 5억 건의 수집 데이터 포인트, 10 억 건의 검색 데이터 포인트
- 대역폭 - 매월 10TB 송신
- 알림 - 한 달에 백만 개의 배달 옵션, 한 달에 1000 개의 이메일 전송
- 자세한 전체 목록-https://www.oracle.com/cloud/free/

### [IBM Cloud](https://www.ibm.com/cloud/free/)
- Kubernetes - 1 개의 작업자 노드가있는 무료 클러스터
- 클라우드 기능 - 한 달에 5 백만 건의 실행
- 오브젝트 스토리지 - 월 25GB
- Cloudant 데이터베이스 - 1GB의 데이터 저장
- DB2 데이터베이스 - 100MB의 데이터 스토리지
- API Connect - 매월 50,000 개의 API 호출
- 가용성 모니터링 - 한 달에 3 백만 개의 데이터 포인트
- 로그 분석-일일 로그 500MB
- 자세한 전체 목록 - https://www.ibm.com/cloud/free/

## 소스 코드 저장소
- [github.com](https://github.com/) — CI/CD 용 파이프 라인이있는 무제한 공용 리포지토리 및 무제한 개인 리포지토리 (최대 3 명)
- [bitbucket.org](https://bitbucket.org/) — CI/CD 용 파이프 라인을 가진 최대 5 명의 사용자를 위한 무제한 공용 및 개인 Git 리포지토리
- [gitlab.com](https://about.gitlab.com/) — 무제한 공동 작업자 및 리포 당 10GB의 공간이 있는 무제한 공개 및 비공개 Git 리포지토리
- [chiselapp.com](http://chiselapp.com/) - 무제한 공공 및 민간 fossil 저장소
- [Azure DevOps](https://azure.microsoft.com/services/devops/) — 최대 5 명의 사용자/팀을 위한 무제한 개인 저장소 (Git 및 TFS)
- [plasticscm.com](https://plasticscm.com/) - 개인, OSS 및 비영리 단체를위한 무료
- [codebasehq.com](https://www.codebasehq.com/) - 1백메가바이트 공간과 2 사용자와 하나 개의 무료 프로젝트
- [NotABug](https://notabug.org) — NotABug.org는 Git 기반의 무료 라이센스 프로젝트를 위한 무료 소프트웨어 코드 협업 플랫폼입니다
- [perforce.com](https://www.perforce.com/products/helix-teamhub) — 무료 1GB 클라우드 및 Git, Mercurial 또는 SVN 리포지토리.
- [projectlocker.com](https://projectlocker.com) - 하나 개 무료 전용 프로젝트 (망할 놈의 서브 버전) 50 메가 바이트 공간
- [ionicframework.com](https://ionicframework.com/appflow) - Ionic으로 응용 프로그램을 개발하기 위한 Repo 및 도구, 또한 이온 Repo가 있습니다
- [gitea.com](https://www.gitea.com/) - 무제한 공공 및 민간 힘내 REPOS
- [codeberg.org](https://codeberg.org/) - 무제한 공개 및 비공개 Git 저장소

## API, 데이터 및 ML
- [algorithmia.com](https://algorithmia.com/) — 무료로 제공되는 호스트 알고리즘. 알고리즘 실행에 대한 월별 무료 수당이 포함됩니다. 이제 CLI 지원
- [ApiFlash](https://apiflash.com) — Aws Lambda 및 Chrome 기반 스크린 샷 API. 전체 페이지, 캡처 타이밍, 뷰포트 크기 등을 처리합니다.
- [Apify](https://www.apify.com/) — 웹 스크래핑 및 자동화 플랫폼으로 웹 사이트 데이터를 추출하는 API를 만들 수 있습니다. 월간 크롤링 횟수가 10 일이고 데이터 보존 기간이 7 일인 무료 계층
- [Beeceptor](https://beeceptor.com) - 몇 초 만에 휴식 API를 조롱하고 가짜 API 응답 등을 할 수 있습니다. 하루에 50 건의 무료 요청, 공개 대시 보드, 개방형 엔드 포인트 (대시 보드에 링크 된 사람은 누구나 요청 및 응답을 볼 수 있음).
- [Bearer.sh](https://www.bearer.sh)-몇 분 안에 API 통합이 실시간으로 모니터링됩니다. 범용 API 클라이언트를 사용하면 2 분 안에 API를 호출하고 간단한 대시 보드에서 모든 통합을 모니터링 할 수 있습니다.
- [bigml.com](https://bigml.com/) — 호스팅 된 머신 러닝 알고리즘. 개발을위한 무제한 무료 작업, 16MB 데이터 / 작업 제한
- [Clarifai](https://www.clarifai.com) — 맞춤형 얼굴 인식 및 감지를위한 이미지 API. AI 모델을 훈련시킬 수 있습니다. 무료 요금제는 한 달에 5000 건입니다.
- [Colaboratory](https://colab.research.google.com) — Nvidia Tesla K80 GPU를 갖춘 무료 웹 기반 Python 노트북 환경.
- [Diggernaut](https://www.diggernaut.com/) — 웹 사이트를 데이터 세트로 전환하거나 API와 같이 작업하기위한 클라우드 기반 웹 스크래핑 및 데이터 추출 플랫폼. 무료 요금제에는 월 5K 페이지 요청이 포함됩니다.
- [dominodatalab.com](https://www.dominodatalab.com) — Python, R, Spark, Hadoop, Matlab 및 기타를 지원하는 데이터 과학
- [dreamfactory.com](https://dreamfactory.com/) — 모바일, 웹 및 IoT 애플리케이션을 위한 오픈 소스 REST API 백엔드. 모든 SQL / NoSQL 데이터베이스, 파일 스토리지 시스템 또는 외부 서비스를 연결하면 실시간 문서, 사용자 관리 등을 통해 포괄적 인 REST API 플랫폼을 즉시 생성 할 수 있습니다.
- [FraudLabs Pro](https://www.fraudlabspro.com) — 신용 카드 결제 사기에 대한 주문 거래를 선별합니다. 이 REST API는 주문의 입력 매개 변수를 기반으로 가능한 모든 사기 특성을 감지합니다. 무료 마이크로 요금제에는 한 달에 500 건의 거래가 있습니다.
- [FreeGeoIP.app](https://freegeoip.app/)-완전 무료 Geo IP 정보 (JSON, CSV, XML). 등록 불필요, 시간당 15000 쿼리 속도 제한.
- [IP Geolocation](https://ipgeolocation.io/) — IP Geolocation API-월 30k 요청 (1k / day) 제한이있는 개발자를위한 무료 플랜입니다.
- [IP2Location](https://www.ip2location.com) — Freemium IP 지리적 위치 서비스입니다. LITE 데이터베이스는 무료로 다운로드 할 수 있습니다. 서버에서 데이터베이스를 가져오고 로컬 쿼리를 수행하여 도시, 좌표 및 ISP 정보를 결정하십시오.
- [IPinfo](https://ipinfo.io/) — 빠르고 정확하며 무료 (최대 100k / 월) IP 주소 데이터 API. 지리적 위치, 회사, 이동 통신사, IP 범위, 도메인, 남용 연락처 등에 대한 세부 정보가 포함 된 API를 제공합니다. 모든 유료 API는 무료로 시험 사용할 수 있습니다.
- [IPList](https://www.iplist.cc) — Geo IP 정보, 주소, 호스트 이름 및 ASN 세부 정보와 같은 모든 IP 주소에 대한 조회 세부 정보. 개인 및 비즈니스 사용자에게는 무료입니다.
- [IPTrace](https://iptrace.io) — 비즈니스에 안정적이고 유용한 IP 위치 정보를 제공하는 매우 간단한 API입니다.
- [konghq.com/](https://konghq.com/) — API 마켓 플레이스 및 프라이빗 및 퍼블릭 API를위한 강력한 도구. 프리 티어를 사용하면 모니터링, 경고 및 지원과 같은 일부 기능이 제한됩니다
- [MailboxValidator](https://www.mailboxvalidator.com) — 유효한 이메일을 확인하기 위해 실제 메일 서버 연결을 사용하는 이메일 확인 서비스. 무료 API 계획은 한 달에 300 번의 검증을받습니다.
- [monkeylearn.com](https://monkeylearn.com/) — 기계 학습을 통한 텍스트 분석, 월 300 회 무료 쿼리
- [OCR.Space](https://ocr.space/) — 텍스트를 반환하는 이미지 및 pdf 파일을 파싱하는 JSON 형식의 OCR API입니다. 한 달에 25,000 건의 요청이 무료입니다.
- [parsehub.com](https://parsehub.com/) — 동적 사이트에서 데이터를 추출하고 동적 웹 사이트를 API로 전환합니다 (5 개의 프로젝트 무료)
- [Pixela](https://pixe.la/)-무료 데이 스트림 데이터베이스 서비스. 모든 작업은 API에 의해 수행됩니다. 히트 맵 및 선 그래프를 사용한 시각화도 가능합니다.
- [Postman](https://postman.com) — API 개발을위한 협업 플랫폼 인 Postman을 사용하여 워크 플로우를 단순화하고 더 나은 API를 더 빠르게 만듭니다. Postman 앱을 영원히 무료로 사용하십시오. 우편 배달부 클라우드 기능도 특정 제한 사항으로 영원히 무료입니다.
- [ProxyCrawl](https://proxycrawl.com/) — 프록시, 인프라 또는 브라우저없이 웹 사이트를 크롤링하고 긁습니다. 보안 문자를 해결하고 차단되지 않도록합니다. 처음 1000 개의 통화는 무료입니다.
- [RequestBin.com](https://requestbin.com) — HTTP 요청을 보낼 수있는 무료 엔드 포인트를 만듭니다. 해당 엔드 포인트로 전송된 모든 HTTP 요청은 연관된 페이로드 및 헤더와 함께 기록됨.

## Artifact 보관소
- [bintray.com](https://bintray.com/) — JFrog Bintray는 무료로 오픈 소스 프로젝트를 호스팅하고 Docker, Maven, NuGet, npm, Debian, RPM, Conan, Vagrant, Opkg, yum 및 또한 지원합니다 가장 포괄적 인 Maven 아티팩트 인 [JCenter](https://bintray.com/bintray/jcenter)의 홈입니다.
- [central.sonatype.org](https://central.sonatype.org) — Apache Maven, SBT 및 기타 빌드 시스템의 기본 아티팩트 저장소입니다.
- [packagecloud.io](https://packagecloud.io) — Maven, RPM, DEB, PyPi 및 RubyGem 패키지 (프리 티어 포함)에 사용하기 쉬운 리포지토리 호스팅.
- [cloudsmith.io](https://cloudsmith.io) — Java / Maven, RedHat, Debian, Python, Ruby, Vagrant + more를위한 단순하고 안전한 중앙 집중식 저장소 서비스입니다. 프리 티어 + 오픈 소스 무료.
- [jitpack.io](https://jitpack.io/) — GitHub의 JVM 및 Android 프로젝트를위한 Maven 저장소이며, 공개 프로젝트는 무료입니다.

## 팀과 협업을 위한 도구
- [scinote.net](https://scinote.net) — 과학적 데이터 관리 및 팀 협업. 무제한의 사용자, 백업 및 1GB의 저장 공간을 갖춘 하나의 팀
- [whereby.com](https://whereby.com/) — 한 번의 클릭으로 비디오 대화 무료 제공 (이전 명칭은 appear.in)
- [meet.jit.si](https://meet.jit.si/) — 한 번의 클릭으로 비디오 대화, 화면 공유, 무료
- [flowdock.com](https://www.flowdock.com/) — 채팅 및받은 편지함, 최대 5 명까지 팀 무료
- [slack.com](https://slack.com/) — 일부 기능 제한이있는 무제한 사용자에게는 무료
- [twist.com](https://twist.com) — 대화가 체계적이고 주제별로 유지되는 비동기식 팀 커뮤니케이션 앱입니다. 무료 및 무제한 요금제 이용 가능. 자격이되는 팀에게 할인이 제공됩니다.
- [gitter.im](https://gitter.im/) — GitHub를위한 채팅. 무제한 공용 및 개인 실, 최대 25 명까지 팀 무료
- [Discord](https://discordapp.com/) — 공개 / 개인 실 및 VoIP 서비스와 채팅합니다. 무제한 사용자에게는 무료입니다.
- [hangouts.google.com](https://hangouts.google.com/) — 무료로 모든 대화를위한 한 곳에서 Google 계정이 필요합니다.
- [seafile.com](https://www.seafile.com/) — 개인 또는 클라우드 스토리지, 파일 공유, 동기화, 토론. 개인용 버전이 가득 찼습니다. 클라우드 버전은 1GB입니다.
- [yammer.com](https://www.yammer.com/) — 개인 소셜 네트워크 독립형 또는 MS Office 365 용. 관리 도구 및 사용자 관리 기능이 약간 적은 무료
- [helpmonks.com](https://helpmonks.com/) — 팀을위한 공유받은 편지함, 오픈 소스 및 비영리 단체 용 무료
- [typetalk.com](https://www.typetalk.com/) — 웹 또는 모바일에서 인스턴트 메시징을 통해 팀과 아이디어를 공유하고 토론
- [talky.io](https://talky.io/) — 무료 그룹 영상 채팅. 익명. 피어 투 피어. 플러그인, 가입 또는 결제 불필요
- [helplightning.com](https://www.helplightning.com/) — 증강 현실 비디오를 통해 도움말. 분석, 암호화, 지원없이 무료
- [evernote.com](https://evernote.com/) — 정보 구성 도구입니다. 메모를 공유하고 다른 사람들과 협력
- [cally.com](https://cally.com/) — 회의를위한 완벽한 시간과 날짜를 찾으십시오. 사용하기 쉽고 소규모 및 대규모 그룹에 적합합니다.
- [doodle.com](https://doodle.com/) — 실제로 사용할 예약 도구입니다. 회의 날짜가 두 배 더 빠릅니다.
- [zoom.us](https://zoom.us/) — 보안 비디오 및 웹 회의, 추가 기능 제공. 40 분 무료
- [ideascale.com](https://ideascale.com/) — 고객이 한 커뮤니티에서 25 명의 회원에게 아이디어를 제출하고 투표 할 수 있도록 허용
- [wistia.com](https://wistia.com/) — 방문자 분석, 25 개의 비디오 및 Wistia 브랜드 플레이어를 이해하는 데 도움이되는 뷰어 분석, HD 비디오 전달 및 마케팅 도구를 갖춘 비디오 호스팅
- [flock.com](https://flock.com) — 팀이보다 빠르게 커뮤니케이션 할 수 있습니다. 무료 무제한 메시지, 채널, 사용자, 앱 및 통합
- [Igloo](https://www.igloosoftware.com/) — 문서, 블로그 및 캘린더 등을 공유하기위한 내부 포털. 최대 10 명의 사용자에게 무료로 제공됩니다.
- [riot.im](https://about.riot.im/) — Matrix에 구축 된 분산 커뮤니케이션 도구입니다. 그룹 채팅, 다이렉트 메시징, 암호화 된 파일 전송, 음성 및 화상 채팅 및 다른 서비스와의 쉬운 통합.
- [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teams는 대화 기반의 디지털 허브로서 대화, 콘텐츠 및 응용 프로그램을 한 곳에서 한 곳에서 하나로 통합 할 수 있습니다. 최대 300 명의 사용자에게 무료로 제공됩니다.
- [featurepeek.com](https://featurepeek.com)-팀 공동 작업 도구가 내장 된 클라우드 제공 업체에 구애받지 않는 프런트 엔드 기능 환경. 정적 및 Dockerized 프런트 엔드와 함께 작동합니다. 공용 리포지토리에는 무료입니다.
- [스펙트럼](https://spectrum.chat/)-무료로 공개 또는 비공개 커뮤니티를 만듭니다.

## 코드 품질
* [codescene.io](https://codescene.io/)-CodeScene은 개발자가 코드를 사용하는 방식에 따라 기술적 부채의 우선 순위를 정하고 팀 연결 및 시스템 마스터리와 같은 조직적 요소를 시각화합니다. 오픈 소스 무료.
* [hiberly.com](https://hiberly.com)-개발자를위한 기술 부채 툴킷-각 병합 후 엔지니어의 피드백을 얻은 후이를 집계하여 코드베이스의 기술 부채를 수량화하고 강조 표시합니다. 최대 12 개월 동안 회고전에서 무료로 사용할 수 있습니다.
* [tachikoma.io](https://tachikoma.io/) — Ruby, Node.js, Perl 프로젝트에 대한 종속성 업데이트, 무료 오픈 소스
* [codeclimate.com](https://codeclimate.com/) — 자동화 된 코드 검토, 오픈 소스 및 무제한 조직 소유 개인 저장소 (최대 4 명의 공동 작업자)에 대해 무료입니다. 학생 및 기관에도 무료입니다.
* [houndci.com](https://houndci.com/) — GitHub에 대한 의견은 오픈 소스에서 무료로 코드 품질에 대해 커밋합니다.
* [coveralls.io](https://coveralls.io/) — 오픈 소스에 대해 무료로 테스트 범위 보고서를 표시합니다
* [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 지속적인 검사 플랫폼, 오픈 소스 무료
* [codecov.io](https://codecov.io/) — 코드 범위 도구 (SaaS), 무료 오픈 소스 및 무료 개인 저장소 1 개
* [insight.sensiolabs.com](https://insight.sensiolabs.com/) — PHP / Symfony 프로젝트의 코드 품질, 오픈 소스 무료
* [codacy.com](https://www.codacy.com/) — PHP, Python, Ruby, Java, JavaScript, Scala, CSS 및 CoffeeScript에 대한 자동화 된 코드 검토, 무제한 공용 및 개인 리포지토리 무료
* [gocover.io](https://gocover.io/) — [Go](https://golang.org/) 패키지의 코드 적용
* [goreportcard.com](https://goreportcard.com/) — Go Source for Code 프로젝트, 오픈 소스 무료
* [scan.coverity.com](https://scan.coverity.com/) — Java, C / C ++, C # 및 JavaScript에 대한 정적 코드 분석, 무료 오픈 소스
* [webceo.com](https://www.webceo.com/) — SEO 도구이지만 코드 확인 및 다양한 유형의 조언
* [zoompf.com](https://zoompf.com/) — 웹 사이트의 성능, 상세 분석 수정
* [gtmetrix.com](https://gtmetrix.com/) — 웹 사이트 최적화를위한 보고서 및 철저한 권장 사항
* [browserling.com](https://www.browserling.com/) — 실시간 대화 형 크로스 브라우저 테스트, Vista에서 1024 x 768 해상도로 MS IE 9를 사용하여 3 분 세션 만 무료
* [shields.io](https://shields.io) — 오픈 소스 프로젝트를 위한 품질 메타 데이터 배지
* [beanstalkapp.com](https://beanstalkapp.com/) — 코드 작성, 검토 및 배포를 위한 완벽한 워크 플로), 100MB의 스토리지가 있는 1 명의 사용자 및 1 개의 저장소 무료 계정
* [testanywhere.co](https://testanywhere.co/) — 웹 사이트 또는 웹앱을 지속적으로 자동 테스트하고 초기 단계에서 버그를 발견하며 월 1,000 회 무료 테스트
* [gerrithub.io](https://review.gerrithub.io/) — GitHub 리포지토리에 대한 Gerrit 코드 검토 무료
* [reviewable.io](https://reviewable.io/) — GitHub 리포지토리의 코드 검토, 공개 또는 개인 리포지토리 무료
* [sonarcloud.io](https://sonarcloud.io) — Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy 및 기타 언어를위한 자동화 된 소스 코드 분석 오픈 소스 무료
* [golangci.com](https://golangci.com) — GitHub 풀 요청에 대한 자동화 된 Go (golang) 코드 검토 서비스입니다.
* [lgtm.com](https://lgtm.com) — Java, Python, JavaScript, TypeScript, C#, C 및 C++에 대한 지속적인 보안 분석, 무료 오픈 소스
* [deepscan.io](https://deepscan.io) — JavaScript 코드에서 런타임 오류를 자동으로 찾아주는 고급 정적 분석 (무료 소스)


## 코드 검색 및 브라우징
* [codota.com](https://www.codota.com/) — Codota는 전 세계의 모든 코드에서 얻은 통찰력을 제공함으로써 개발자가 더 나은 소프트웨어를 더 빠르게 만들 수 있도록 도와줍니다. 사용 가능한 플러그인.
* [libraries.io](https://libraries.io/) — 32 개의 서로 다른 패키지 관리자에 대한 검색 및 종속성 업데이트 알림, 무료 오픈 소스
* [sourcegraph.com](https://about.sourcegraph.com/) — Java, Go, Python, Node.js 등, 코드 검색 / 상호 참조, 오픈 소스 무료
* [searchcode.com](https://searchcode.com/) — 포괄적 인 텍스트 기반 코드 검색, 무료 오픈 소스

## CI / CD
* [ligurio / awesome-ci](https://github.com/ligurio/awesome-ci) — 지속적인 통합 서비스 비교
* [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — Linux, macOS 및 Windows 용 오픈 소스를위한 무제한 분으로 10 개의 무료 병렬 작업
* [codefresh.io](https://codefresh.io) — 무료 플랜 : 빌드 1 개, 환경 1 개, 공유 서버, 무제한 공용 저장소
* [codeship.com](https://codeship.com/) — 100 건의 개인 빌드 / 월, 5 개의 프라이빗 프로젝트, 오픈 소스 무제한
* [circleci.com](https://circleci.com/) — 하나의 동시 빌드에 대해 무료
* [stackahoy.io](https://stackahoy.io) — 100 % 무료입니다. 무제한 배포, 분기 및 빌드
* [travis-ci.org](https://travis-ci.org/) — 공개 GitHub 리포지토리 무료
* [semaphoreci.com](https://semaphoreci.com/) — 오픈 소스 무료, 매월 100 건의 개인 빌드
* [shippable.com](https://app.shippable.com/) — 매월 150 개의 개인 빌드, 1 개의 빌드 컨테이너, 개인 및 공용 저장소에 대해 무료
* [appveyor.com](https://www.appveyor.com/) — Windows 용 CD 서비스, 오픈 소스 용 무료
* [deployhq.com](https://www.deployhq.com/) — 매일 10 번 배포하는 프로젝트 1 개 (월 30 회 빌드 분)
* [styleci.io](https://styleci.io/) — 공개 GitHub 리포지토리 만
* [buddybuild.com](https://www.buddybuild.com/) — 하나의 원활한 반복 시스템에서 iOS 및 Android 앱에 대한 피드백을 구축, 배포 및 수집
* [gitlab.com](https://about.gitlab.com/product/continuous-integration/) — GitLab의 CI 서비스를 사용하여 Git 리포지토리에서 직접 파이프 라인을 만듭니다. 2,000 분 / 월
* [buddy.works](https://buddy.works/) — 5 개의 무료 프로젝트와 1 개의 동시 실행 (월별 120 회 실행)이 포함 된 CI / CD
* [bitrise.io](https://www.bitrise.io/) — 기본 또는 하이브리드 모바일 앱용 CI / CD. 200 회의 무료 빌드 / 월 10 분의 빌드 시간과 두 명의 팀원. OSS 프로젝트는 45 분의 빌드 시간, +1의 동시성 및 무제한 팀 규모를 갖습니다.

## 테스팅
* [gridlastic.com](https://www.gridlastic.com/) — 최대 4 개의 동시 셀레늄 노드 동시 동시 계획 / 10 그리드 시작 / 4,000 테스트 분 / 월
* [saucelabs.com](https://saucelabs.com/) — 크로스 브라우저 테스트, 셀레늄 테스트 및 모바일 테스트, [오픈 소스 무료](https://saucelabs.com/open-source)
* [crossbrowsertesting.com](https://crossbrowsertesting.com)-클라우드에서 수동, 비주얼 및 Selenium 브라우저 테스트-[무료 공개 소스](https://crossbrowsertesting.com/open-source)
* [browserstack.com](https://www.browserstack.com/) — 수동 및 자동 브라우저 테스트, [오픈 소스 무료](https://www.browserstack.com/open-source?ref=pricing)
* [everystep-automation.com](https://www.everystep-automation.com/) — 웹 브라우저에서 수행 된 모든 단계를 기록 및 재생하고 적은 옵션으로 무료로 스크립트를 생성합니다.
* [Applitools.com](https://applitools.com/) — 웹, 기본 모바일 및 데스크탑 앱을위한 스마트 한 시각적 검증. 거의 모든 자동화 솔루션 (예 : Selenium 및 Karma) 및 원격 러너 (Sauce Labs, Browser Stack)와 통합됩니다. 오픈 소스 무료. 주당 검사 점이 제한된 단일 사용자를위한 프리 티어입니다.
* [checkbot.io](https://www.checkbot.io/) — 웹 사이트가 50 개 이상의 SEO, 속도 및 보안 모범 사례를 따르는 지 테스트하는 브라우저 확장 프로그램입니다. 소규모 웹 사이트를위한 프리 티어
* [testingbot.com](https://testingbot.com/) — 셀레늄 브라우저 및 장치 테스트, [오픈 소스 무료](https://testingbot.com/open-source)
* [tesults.com](https://www.tesults.com) — 테스트 결과보고 및 테스트 사례 관리. 널리 사용되는 테스트 프레임 워크와 통합됩니다. 오픈 소스 소프트웨어 개발자, 개인, 교육자 및 소규모 팀은 기본 무료 프로젝트 외에 할인 및 무료 서비스를 요청할 수 있습니다.
* [cypress.io](https://www.cypress.io/)-브라우저에서 실행되는 모든 항목에 대한 빠르고 쉽고 안정적인 테스트입니다. Cypress Test Runner는 항상 무료이며 오픈 소스이며 제한 및 제한이 없습니다. Cypress Dashboard는 최대 5 명의 사용자를위한 오픈 소스 프로젝트에 무료로 제공됩니다.

## 보안 및 PKI
* [pyup.io](https://pyup.io) — 보안 취약점에 대한 모니터링 Python 종속성 및 자동 업데이트. 하나의 개인 프로젝트에는 무료이며 오픈 소스에는 무제한 프로젝트가 있습니다.
* [threatconnect.com](https://threatconnect.com) — 위협 인텔리전스 : 사이버 위협 인텔리전스에 대해 배우기 시작한 개별 연구원, 분석가 및 조직을 위해 설계되었습니다. 최대 3 명의 사용자 무료
* [crypteron.com](https://www.crypteron.com/) — 클라우드 우선 개발자 친화적 인 보안 플랫폼으로 .NET 및 Java 응용 프로그램에서 데이터 유출 방지
* [snyk.io](https://snyk.io) — 오픈 소스 종속성에서 알려진 보안 취약점을 찾아서 수정할 수 있습니다. 오픈 소스 프로젝트에 대한 무제한 테스트 및 치료. 개인 프로젝트에 대해 매월 200 회의 테스트로 제한됩니다.
* [letsencrypt.org](https://letsencrypt.org/) — 모든 주요 브라우저에서 신뢰할 수있는 인증서가있는 무료 SSL 인증 기관
* [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) — 오픈 소스 용 무료 SSL 인증서
* [Okta](https://developer.okta.com/) — 사용자 관리, 인증 및 권한 부여. 최대 1000 명의 월간 활성 사용자에게 무료입니다.
* [auth0.com](https://auth0.com/) — 개발 SSO를 위해 무료로 호스팅됩니다. 비공개 소스 프로젝트를위한 최대 2 개의 소셜 아이덴티티 공급자.
* [ringcaptcha.com](https://ringcaptcha.com/) — 무료로 제공되는 전화 번호를 ID로 사용하는 도구
* [ssllabs.com](https://www.ssllabs.com/ssltest/) — 모든 SSL 웹 서버 구성에 대한 심층 분석
* [qualys.com](https://www.qualys.com/forms/freescan/owasp/) — 웹앱 취약점 찾기, OWASP 위험 감사
* [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 네트워크에서 손상된 시스템을 발견합니다.
* [duo.com](https://duo.com/) — 웹 사이트 또는 앱에 대한 2 단계 인증 (2FA). 무료 10 명의 사용자, 모든 인증 방법, 무제한, 통합, 하드웨어 토큰
* [tinfoilsecurity.com](https://www.tinfoilsecurity.com/) — 자동화 된 취약성 검색. 무료 계획은 매주 XSS 스캔을 허용합니다
* [ponycheckup.com](https://www.ponycheckup.com/) — Django 웹 사이트를위한 자동화된 보안 점검 도구
* [foxpass.com](https://www.foxpass.com/) — 호스팅 된 LDAP 및 RADIUS. 서버, VPN 및 무선 네트워크에 사용자별로 쉽게 로그인 할 수 있습니다. 10 명 무료
* [opswat.com](https://www.opswat.com/) — 컴퓨터, 장치, 응용 프로그램, 구성 등의 보안 모니터링 ... 무료 25 명의 사용자와 30 일의 기록
* [bitninja.io](https://bitninja.io/) — 블랙리스트를 통한 봇넷 보호, 무료 계획은 각 공격에 대한 제한된 정보만 보고합니다
* [onelogin.com](https://www.onelogin.com/) — IDaaS (Identity as a Service), 싱글 사인온 아이덴티티 공급자, Cloud SSO IdP, 3 개의 회사 앱 및 5 개의 개인 앱, 무제한 사용자
* [logintc.com](https://www.logintc.com/) — 푸시 알림을 통한 2 단계 인증 (2FA), 10 명의 사용자에게는 무료, VPN, 웹 사이트 및 SSH
* [report-uri.io](https://report-uri.io/) — CSP 및 HPKP 위반보고
* [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services (AWS) 보안 및 규정 준수 감사 및 모니터링
* [Pwned Pwned?](https://haveibeenpwned.com) — 위반에 대한 정보를 가져 오기위한 REST API입니다.
* [Internet.nl](https://internet.nl) — IPv6, DNSSEC, HTTPS, DMARC, STARTTLS 및 DANE와 같은 최신 인터넷 표준 테스트
* [Mozilla Observatory](https://observatory.mozilla.org/) — 사이트의 보안 취약점을 찾아 수정합니다.
* [Shieldfy](https://shieldfy.io) — 개발자를위한 웹 응용 프로그램 방화벽 및 취약성 탐지, 매월 최대 100k 요청 무료 계획.
* [Sqreen](https://www.sqreen.com/) — 웹 응용 프로그램 및 API에 대한 응용 프로그램 보안 모니터링 및 보호 (RASP, WAF 등). 1 개의 앱과 3 백만 개의 요청에 대해 무료입니다.
* [Sucuri SiteCheck](https://sitecheck.sucuri.net)-무료 웹 사이트 보안 검사 및 맬웨어 스캐너

## 관리 시스템
* [bitnami.com](https://bitnami.com/) — 준비된 앱을 IaaS에 배포합니다. 1 개의 AWS 마이크로 인스턴스 무료 관리
* [jamf.com](https://www.jamf.com/) — iPad, iPhone 및 Mac의 장치 관리, 3 개의 장치 무료
* [moss.sh](https://moss.sh)-개발자가 웹 앱 및 서버를 배포하고 관리 할 수 있도록 도와줍니다. 한 달에 최대 25 개의 git 배포 무료

## 로그 관리
* [bugfender.com](https://bugfender.com/) — 24 시간 보존으로 최대 하루에 최대 100k 로그 라인 확보
* [humio.com](https://www.humio.com/) — 7 일 보존으로 최대 2GB / 일 무료
* [logentries.com](https://logentries.com/) — 7 일 보존으로 최대 5GB / 월까지 무료
* [loggly.com](https://www.loggly.com/) — 단일 사용자에게는 무료입니다. lite 옵션 참조
* [logz.io](https://logz.io/) — 최대 3GB / 일, 3 일 보존
* [papertrailapp.com](https://papertrailapp.com/) — 48 시간 검색, 7 일 보관, 100MB / 월
* [rollbar.com](https://rollbar.com) — 최대 5000 개의 이벤트 / 월, 30 일 보존
* [sematext.com](https://sematext.com/logsene) — 최대 500MB / 일, 7 일 보존
* [sumologic.com](https://www.sumologic.com/) — 최대 500MB / 일, 7 일 보존
* [splunk.com](https://www.splunk.com)-단일 사용자에게 무료, 500MB / 일

## 번역 관리
* [lingohub.com](https://lingohub.com/) — 최대 3 명의 사용자 무료, 오픈 소스의 경우 항상 무료
* [webtranslateit.com](https://webtranslateit.com/) — 최대 500 개의 문자열 무료
* [transifex.com](https://www.transifex.com/) — 무료 공개 소스
* [oneskyapp.com](https://www.oneskyapp.com/) — 최대 5 명의 사용자를위한 한정판 무료, 오픈 소스 무료
* [crowdin.com](https://crowdin.com/) — 오픈 소스를위한 무제한 프로젝트, 무제한 문자열 및 공동 작업자
* [Loco](https://localise.biz/) — 최대 2000 개의 번역, 무제한 번역기, 10 개 언어 / 프로젝트, 1000 개의 번역 가능한 자산 / 프로젝트 무료

## 모니터링
* [instrumentalapp.com](https://instrumentalapp.com)-최대 500 개의 지표와 3 시간의 데이터 가시성으로 아름답고 사용하기 쉬운 응용 프로그램 및 서버 모니터링
* [gitential.com](https://gitential.com) — 소프트웨어 개발 분석 플랫폼. 무료 : 무제한 공용 저장소, 무제한 사용자, 개인 저장소에 대한 무료 평가판. 기업용 온 프레미스 버전.
* [cloudsploit.com](https://cloudsploit.com) — AWS 보안 및 구성 모니터링. 무료 : 주문형 검색 무제한, 무제한 사용자, 무제한 저장 계정. 구독 : 자동 스캔, API 액세스 등
* [elastic.co](https://www.elastic.co/solutions/apm) — JS 개발자를위한 즉각적인 성능 통찰력. 24 시간 데이터 보존 무료
* [appneta.com](https://www.appneta.com/) — 1 시간의 데이터 보존 무료
* [thousandeyes.com](https://www.thousandeyes.com/) — 네트워크 및 사용자 경험 모니터링. 주요 웹 서비스의 3 개 위치 및 20 개의 데이터 피드 무료
* [datadoghq.com](https://www.datadoghq.com/) — 최대 5 개의 노드에 대해 무료
* [freshworks.com](https://www.freshworks.com/website-monitoring/) — 무료로 전 세계 위치 10 개 및 공개 상태 페이지 5 개로 1 분 간격으로 50 개의 URL을 모니터링합니다.
* [nodequery.com](https://nodequery.com/) — 최대 10 대의 서버까지 무료 기본 서버 모니터
* [circonus.com](https://www.circonus.com/) — 20 개 메트릭에 대해 무료
* [uptimerobot.com](https://uptimerobot.com/) — 웹 사이트 모니터링, 50 개의 모니터 무료
* [sitemonki.com](https://sitemonki.com/) — 웹 사이트, 도메인, Cron & SSL 모니터링, 각 카테고리에서 5 개의 모니터 무료 제공
* [statuscake.com](https://www.statuscake.com/) — 웹 사이트 모니터링, 무제한 테스트 무료로 제한 사항
* [bmc.com](https://www.bmc.com/truesightpulse/) — 최대 10 대의 서버에 대해 1 초 무료 제공
* [ghostinspector.com](https://ghostinspector.com/) — 무료 웹 사이트 및 웹 응용 프로그램 모니터링. 단일 사용자, 매월 100 회 테스트 실행
* [sematext.com](https://sematext.com/) — 24 시간 통계, 무제한 서버 수, 10 개의 사용자 정의 지표, 500,000 개의 사용자 정의 지표 데이터 포인트, 무제한 대시 보드, 사용자 등 무료
* [stathat.com](https://www.stathat.com/) — 10 가지 통계로 무료 시작, 만료 없음
* [skylight.io](https://www.skylight.io/) — 처음 100,000 개의 요청에 대해 무료입니다 (레일 전용)
* [appdynamics.com](https://www.appdynamics.com/) — 24 시간 동안 무료로 제공되며, 애플리케이션 성능 관리 에이전트는 Java, .NET, PHP 및 Node.js로 제한됩니다.
* [deadmanssnitch.com](https://deadmanssnitch.com/) — 크론 작업 모니터링. 1 개의 무료 스니치 (모니터)
* [librato.com](https://www.librato.com/) — 60 초 해상도에서 최대 100 개의 메트릭을 무료로 제공
* [freeboard.io](https://freeboard.io/) — 공개 프로젝트의 경우 무료입니다. 사물 인터넷 (IoT) 프로젝트를위한 대시 보드
* [loader.io](https://loader.io/) — 제한이있는 무료로드 테스트 도구
* [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 성능 모니터링 API, Ping, DNS 등 확인
* [blackfire.io](https://blackfire.io/) — Blackfire는 SaaS 제공 애플리케이션 성능 솔루션입니다. 무료 해커 플랜 (PHP 만 해당)
* [apimetrics.io](https://apimetrics.io/) — 자동화 된 API 성능 모니터링, 테스트 및 분석. 무료 계획, 수동으로 API 호출 및 West Coast 서버에서 실행
* [healthchecks.io](https://healthchecks.io) — cron 작업 및 백그라운드 작업을 모니터링합니다. 최대 20 개의 수표를 무료로 제공합니다.
* [appbeat.io](https://appbeat.io) — 웹 사이트 모니터링, 3 개의 모니터가 무료입니다. 매우 안정적이고 저렴한 모니터 서비스를 제공합니다.
* [assertible.com](https://assertible.com) — 자동화 된 API 테스트 및 모니터링. 팀과 개인을위한 무료 요금제.
* [opsgenie.com](https://www.opsgenie.com/) — 상시 작동 서비스를위한 강력한 경고 및 통화 관리. 최대 5 명의 사용자를 확보하십시오.
* [paessler.com](https://www.paessler.com/) — 경고, 강력한 시각화 기능 및 기본보고를 포함한 강력한 인프라 및 네트워크 모니터링 솔루션. 최대 100 개의 센서를 확보하십시오.
* [pingbreak.com](https://pingbreak.com/) — 최신 가동 시간 모니터링 서비스. 무제한 URL을 확인하고 Discord, Slack 또는 이메일을 통해 다운 타임 알림을 받으십시오.
* [pagertree.com](https://pagertree.com/)-경고 및 통화 관리를위한 간단한 인터페이스. 최대 5 명의 사용자를 확보하십시오.

## 충돌 및 예외 처리
* [rollbar.com](https://rollbar.com/) — 예외 및 오류 모니터링, 5,000 오류 / 월의 무료 요금제, 무제한 사용자, 30 일 보존
* [bugsnag.com](https://www.bugsnag.com/) — 최초 평가판 이후 월별 최대 2,000 개의 오류에 대해 무료
* [sentry.io](https://sentry.io/) — Sentry는 앱 예외를 실시간으로 추적하고 작은 무료 요금제를 가지고 있습니다. 매월 5k 오류 무료 / 사용자 1 명, 자체 호스팅 된 경우 무제한 사용
* [honeybadger.io](https://www.honeybadger.io)-예외, 가동 시간 및 cron 모니터링이 너무 훌륭하여 사이트에 더 많은 오류가 있었으면합니다. Honeybadger는 솔로 개발자 및 오픈 소스 프로젝트 (12,000 오류 / 월)에 대해 무료입니다.

## 검색
* [algolia.com](https://www.algolia.com/) — 호스팅 검색 유형 (인스턴트). 무료 해커는 최대 10,000 개의 문서와 100,000 개의 작업을 계획합니다. 커뮤니티 / 오픈 소스 프로젝트에 사용할 수있는 더 큰 무료 플랜
* [swiftype.com](https://swiftype.com/) — 호스팅 검색 솔루션 (API 및 크롤러). 최대 1,000 개의 문서가있는 단일 검색 엔진에 대해 무료입니다. 오픈 소스를위한 프리미엄 레벨 무료 업그레이드
* [bonsai.io](https://bonsai.io/) — 무료 1GB 메모리 및 1GB 스토리지
* [searchly.com](http://www.searchly.com/) — 무료 2 인덱스 및 5 MB 저장

## 이메일
* [mailinator.com](https://www.mailinator.com/) — 원하는 모든 받은 편지함을 사용할 수 있는 무료 공개 이메일 시스템
* [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) — 개발자를위한 이메일 검증 및 검증 API, 월 2,000 건의 무료 API 요청
* [sparkpost.com](https://www.sparkpost.com/) — 처음 500 개 이메일 / 월 무료
* [mailgun.com](https://www.mailgun.com/) — 매월 처음 10,000 개의 이메일과 100 개의 이메일 주소 확인이 무료입니다.
* [tinyletter.com](https://tinyletter.com/) — 5,000 가입자 / 월 무료
* [mailchimp.com](https://mailchimp.com/) — 가입자 2,000 명과 월 12,000 이메일
* [sendgrid.com](https://sendgrid.com/) — 하루에 100 개 이메일 및 2,000 개 연락처 무료
* [phplist.com](https://phplist.com/) — 호스팅 된 버전에서 월 300 회 이메일 허용
* [MailerLite.com](https://www.mailerlite.com)-가입자 1,000 명 / 월, 무제한 이메일 무료
* [mailjet.com](https://www.mailjet.com/) — 6,000 개 이메일 / 월 무료
* [sendinblue.com](https://www.sendinblue.com/) — 9,000 개 이메일 / 월 무료
* [mailtrap.io](https://mailtrap.io/) — 개발 용 가짜 SMTP 서버,받은 편지함 1 개, 메시지 50 개, 팀원 없음, 초당 2 개 이메일, 초당 전달 규칙 없음
* [zoho.com](https://www.zoho.com/mail/) — 최대 5 명의 사용자를위한 무료 이메일 관리 및 협업
* [Yandex.Connect](https://connect.yandex.com/pdd/) — 최대 1,000 명의 사용자를 위한 무료 이메일 및 DNS 호스팅
* [moosend.com](https://moosend.com/) — 메일 링리스트 관리 서비스. 스타트 업을위한 6 개월 무료 계정
* [debugmail.io](https://debugmail.io/) — 개발자를 위해 사용하기 쉬운 테스트 메일 서버
* [mailboxlayer.com](https://mailboxlayer.com/) — 개발자를위한 이메일 유효성 검사 및 확인 JSON API. 월 1,000 회 무료 API 요청
* [mailcatcher.me](https://mailcatcher.me/) — 메일을 잡아 웹 인터페이스를 통해 제공합니다
* [yopmail.fr](http://www.yopmail.fr/en/) — 일회용 이메일 주소
* [kickbox.io](https://kickbox.io/) — 100 개의 이메일을 무료로 실시간 API 확인 가능
* [inumbo.com](http://inumbo.com/) — SMTP 기반 스팸 필터, 10 명의 사용자에게 무료
* [biz.mail.ru](https://biz.mail.ru/) — DNS 호스팅을 통해 사용자 지정 도메인 당 25GB 씩 5,000 개의 사서함
* [sendpulse.com](https://sendpulse.com) — 시간당 50 개 이메일, 처음 12,000 개 이메일 / 월 무료
* [pepipost.com](https://pepipost.com) — 첫 달에 30k 이메일, 그 다음 100 일 이메일 / 무료
* [elasticemail.com](https://elasticemail.com) — 하루에 100 개의 무료 이메일. API를 통해 $ 0.09의 이메일 1,000 개 (가상 결제)
* [mail-tester.com](https://www.mail-tester.com) — 이메일의 dns / spf / dkim / dmarc 설정이 올바른지 테스트합니다. 매월 20 일 무료입니다.
* [migadu.com](https://www.migadu.com/) — 이메일 호스팅 (웹 메일, SMTP, IMAP 등) — 무료 플랜은 하루에 10 개의 발신 메일로 제한됩니다
* [socketlabs.com](https://www.socketlabs.com)-첫 달에는 40k 개의 이메일이 무료이고 그 다음에 첫 번째 2000 개의 이메일이 무료입니다.
* [postmarkapp.com](https://postmarkapp.com/)-100 개 이메일 / 월 무료, 무제한 DMARC 주간 요약
* [testmail.app](https://testmail.app/)-무제한 사서함과 GraphQL API로 엔드 투 엔드 이메일 테스트를 자동화합니다. 이메일 100 개 / 월 무료, 오픈 소스 무제한 무료.
* [trashmail.com](https://www.trashmail.com)-전달 및 자동 주소 만료 기능이 있는 무료 일회용 이메일 주소
* [발신자](https://www.sender.net) 최대 15,000 개 이메일 / 월-가입자 최대 2,500 명
* [Buttondown](https://buttondown.email/) — 뉴스 레터 서비스. 최대 1,000 명의 가입자 무료
* [Substack](https://substack.com) — 무제한 무료 뉴스 레터 서비스. 청구할 때 지불을 시작하십시오.


## CDN 및 보호
* [PageCDN.com](https://pagecdn.com/)-모든 사람을위한 무료 공개 CDN 및 오픈 소스 / 비영리를위한 무료 비공개 CDN을 제공합니다.
* [cloudflare.com](https://www.cloudflare.com/) — 기본 서비스는 무료이며 블로그에 적합하며 무료 SSL 인증서 서비스와 5 개의 방화벽 규칙도 제공합니다.
* [bootstrapcdn.com](https://www.bootstrapcdn.com/) — 부트 스트랩, 부트 워치 및 fontawesome.io 용 CDN
* [cdnjs.com](https://cdnjs.com/) — JavaScript 라이브러리, CSS 라이브러리, SWF, 이미지 등을위한 CDN
* [jsdelivr.com](https://www.jsdelivr.com/) — 개발자 및 웹 마스터를위한 OSS (JS, CSS, 글꼴)의 CDN, PR을 허용하여 더 추가
* [raw.githack.com](https://raw.githack.com/) — Clouflare를 사용하여 파일을 간단히 호스팅하는 **rawgit.com**의 현대적인 대체품
* [developers.google.com](https://developers.google.com/speed/libraries/) — Google 호스팅 라이브러리는 가장 인기있는 오픈 소스 JavaScript 라이브러리를위한 콘텐츠 배포 네트워크입니다.
* [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN은 jQuery와 같은 널리 사용되는 타사 JavaScript 라이브러리를 호스트하고이를 쉽게 추가 할 수 있습니다. 웹 애플리케이션
* [toranproxy.com](https://toranproxy.com/) — Packagist 및 GitHub 용 프록시. CD를 절대로 실패하지 마십시오. 개인용 무료, 개발자 1 명, 지원 없음
* [웹 지원 혁명](https://w.tools/) — 무료 CDN, 백업, 방화벽, 바이러스 백신 및 모니터링.
* [section.io](https://www.section.io/) — 완전한 Varnish Cache 솔루션을 시작하고 관리하는 간단한 방법입니다. 한 사이트에서 영원히 무료로 제공
* [netdepot.com](https://www.netdepot.com/cdn/) — 처음 100GB 무료 / 월
* [speeder.io](https://speeder.io/) — KeyCDN을 사용합니다. 자동 이미지 최적화 및 무료 CDN 부스트. 무료이며 서버 변경이 필요하지 않습니다
* [jare.io](http://www.jare.io) — 이미지 CDN. AWS CloudFront 사용
* [unpkg.com](https://unpkg.com/) — npm의 모든 내용에 대한 CDN
* [staticaly.com](https://staticaly.com/) — Git 리포지토리 (GitHub, GitLab, Bitbucket), WordPress 관련 자산 및 이미지 용 CDN
* [bitmitigate.com](https://bitmitigate.com/website-suite.html) — 무료 CDN, DDoS 보호 및 SSL 인증서
* [ddos-guard.net](https://ddos-guard.net/store/web) — 무료 CDN, DDoS 보호 및 SSL 인증서
* [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 무료 DDos 보호 및 SSL 인증서 

## PaaS
* [engineyard.com](https://www.engineyard.com/) — Engine Yard는 500 시간의 무료 시간을 제공합니다
* [appharbor.com](https://appharbor.com/) — 1 명의 무료 작업자를 제공하는 .Net PaaS
* [heroku.com](https://www.heroku.com/) — 단일 프로세스 앱을 위해 무료로 클라우드에 앱을 호스팅
* [firebase.google.com](https://firebase.google.com) — 실시간 앱 구축, 무료 요금제는 최대 100 개의 연결, 10GB 데이터 전송, 1GB 데이터 저장소, 1GB 호스팅 저장소 및 10 GB 호스팅 전송
* [outsystems.com](https://www.outsystems.com/) — 온 프레미스 또는 클라우드를위한 엔터프라이즈 웹 개발 PaaS, 무료 "개인 환경"제공으로 무제한 코드 및 최대 1GB 데이터베이스 허용
* [scn.sap.com](https://scn.sap.com/docs/DOC-56411) — SAP의 인 메모리 Platform-as-a-Service 오퍼링. 무료 개발자 계정에는 1GB 구조화, 1GB 비 구조화, 1GB의 Git 데이터가 제공되며 HTML5, Java 및 HANA XS 앱을 실행할 수 있습니다
* [mendix.com](https://www.mendix.com/) — 엔터프라이즈를위한 신속한 응용 프로그램 개발, 각각 10 명의 사용자, 100MB의 파일 및 100MB의 데이터베이스 저장소를 지원하는 무제한 무료 샌드 박스 환경
* [pythonanywhere.com](https://www.pythonanywhere.com/) — Cloud Python 앱 호스팅입니다. 초보자 계정은 무료이며 your-username.pythonanywhere.com 도메인의 Python 웹 애플리케이션 1 개, 512MB 개인 파일 스토리지, 하나의 MySQL 데이터베이스
* [configure.it](https://www.configure.it/) — 모바일 앱 개발 플랫폼, 2 개 프로젝트 무료, 기능 제한, 리소스 제한 없음
* [zeit.co/now](https://zeit.co/now) — 여러 언어 (정적 사이트 포함) 및 단일 명령 배포를 지원하는 서버리스 플랫폼. 프리 티어에는 SSL, 20GB 대역폭, 100 개의 배포가 포함됩니다.
* [sandstorm.io](https://sandstorm.io/) — Sandstorm은 개인 및 개인 클라우드를위한 오픈 소스 운영 체제입니다. 200MB의 스토리지와 5 개의 곡물을 무료로 제공하는 무료 요금제
* [gearhost.com](https://www.gearhost.com/pricing) — .NET 및 PHP 앱용 플랫폼. 제한된 리소스를 가진 공유 서버에서 256MB의 RAM 무료 제공
* [glitch.com](https://glitch.com/) — 코드 공유 및 실시간 협업과 같은 기능을 갖춘 무료 무제한 공개 / 개인 호스팅
* [gigalixir.com](https://gigalixir.com/)-Gigalixir는 Elixir / Phoenix 앱에 대해 잠자 지 않고 프리 티어 PostgreSQL 데이터베이스를 2 개의 연결, 10, 000 개의 행 및 백업없이 제한된 1 개의 무료 인스턴스를 제공합니다.
* [workers.dev](https://workers.dev)-Cloudflare의 글로벌 네트워크에서 서버리스 코드를 무료로 배포하십시오. workers.dev 하위 도메인으로 하루에 100,000 건의 무료 요청이 가능합니다.
* [pipedream.com](https://pipedream.com)-개발자를 위해 구축 된 통합 플랫폼입니다. 트리거를 기반으로 워크 플로우를 개발하십시오. 워크 플로는 코드이며 [무료](https://docs.pipedream.com/pricing/)를 실행할 수 있습니다. 관리할 서버 또는 클라우드 리소스가 없습니다.


## BaaS
* [back4app.com](https://www.back4app.com)-Back4App은 Parse Platform 기반의 사용하기 쉽고 유연하며 확장 가능한 백엔드입니다.
* [blockspring.com](https://www.blockspring.com/) — 클라우드 기능. 500 만 회 / 월 무료
* [progress.com](https://www.progress.com/kinvey) — 모바일 백엔드, 시작 계획에는 초당 1GB의 데이터 저장 용량으로 무제한 요청이 있습니다. 엔터프라이즈 애플리케이션 지원
* [backendless.com](https://backendless.com/) — 1GB의 파일 저장 공간이없는 모바일 및 웹 Baas, 50000 / 월의 푸시 알림 및 테이블에 1000 개의 데이터 개체가 있습니다.
* [hasura.io](https://hasura.io/) — 단일 노드 클러스터에 대해 무료로 앱 백엔드를 빠르게 구축 및 배포하는 플랫폼.
* [pusher.com](https://pusher.com/beams) — 월간 활성 사용자 2000 명에 대한 무료 무제한 푸시 알림. iOS 및 Android 장치 용 단일 API
* [quickblox.com](https://quickblox.com/) — 인스턴트 메시징, 비디오 및 음성 통화 및 푸시 알림을위한 통신 백엔드
* [pushbots.com](https://pushbots.com/) — 푸시 알림 서비스. 최대 150 만 회 / 월 무료
* [onesignal.com](https://onesignal.com/) — 무제한 무료 푸시 알림
* [getstream.io](https://getstream.io/) — 주당 몇 시간이 아닌 몇 시간 내에 확장 가능한 뉴스 피드 및 활동 스트림을 작성하며 매월 3 백만 개의 피드 업데이트가 무료입니다.
* [tyk.io](https://tyk.io/) — 인증, 할당량, 모니터링 및 분석을 통한 API 관리. 무료 클라우드 오퍼링
* [iron.io](https://www.iron.io/) — 프리 티어 및 1 개월 무료 평가판을 사용한 비동기 작업 처리 (AWS Lambda와 같은)
* [nstack.com](https://nstack.com/) — AWS Lambda와 같은 비동기 작업 처리 10 개의 무료 개인 서비스 및 무제한의 무료 공공 서비스
* [pubnub.com](https://www.pubnub.com/) — 최대 백만 건의 메시지 / 월 및 100 개의 활성 일일 장치에 대한 무료 푸시 알림
* [pushtechnology.com](https://www.pushtechnology.com/) — 브라우저, 스마트 폰 및 모든 사람을위한 실시간 메시징. 100 개의 동시 연결 무료 10GB 데이터 / 월
* [zapier.com](https://zapier.com/) — 사용하는 앱을 연결하여 작업을 자동화합니다. 15 분마다 5 회, 한 달에 100 회
* [stackstorm.com](https://stackstorm.com/) — 흐름, 액세스 제어, LDAP 등이없는 앱, 서비스 및 워크 플로우를위한 이벤트 중심 자동화 ...
* [simperium.com](https://simperium.com/) — 멀티 플랫폼, 구조화 된 데이터의 무제한 전송 및 저장, 즉 어디서나 데이터를 즉각적으로 자동으로 이동합니다. 월 2,500 명의 사용자
* [pushcrew.com](https://pushcrew.com/) — 푸시 알림 서비스. 최대 2000 명의 가입자에게 무제한 알림
* [streamdata.io](https://streamdata.io/) — 모든 REST API를 이벤트 중심 스트리밍 API로 바꿉니다. 최대 1 백만 개의 메시지와 10 개의 동시 연결 무료 계획
* [posthook.io](https://posthook.io/) — 작업 예약 서비스. 특정 시간에 대한 요청을 예약 할 수 있습니다. 500 건의 예약 요청 / 월 무료.
* [paraio.com](https://paraio.com) — 유연한 인증, 전체 텍스트 검색 및 캐싱을 갖춘 백엔드 서비스 API. 앱 1 개, 앱 1GB에 대해서는 무료입니다.
* [remotemysql.com](https://remotemysql.com) — 원격 MySQL 데이터베이스 호스팅, 설치가 즉시 완료되며 관리를 위해 phpMyAdmin을 사용하고, 100Mb 데이터, 무료 백업, 쿼리 제한 없음 및 99 % 가동 시간을 위해 무료입니다.
* [ably.com](https://www.ably.com)-실시간 메시징, 푸시 알림 및 이벤트 중심 API 생성을위한 API. 무료 요금제에는 3m 메시지 / 모, 100 개의 동시 연결, 100 개의 동시 채널이 있습니다.


## 웹 호스팅
* [pages.github.com](https://pages.github.com/) — GitHub 리포지토리에서 직접 정적 사이트 호스팅
* [sourceforge.net](https://sourceforge.net/) — 무료로 오픈 소스 소프트웨어를 찾아서 생성 및 게시
* [devport.co](http://devport.co/) — GitHub 프로젝트, 앱 및 웹 사이트를 개인 개발자 포트폴리오로 전환
* [netlify.com](https://www.netlify.com/) — 100GB 데이터 및 100GB / 월 대역폭에 대해 무료로 정적 사이트 또는 앱을 빌드, 배포 및 호스팅
* [sanity.io](https://www.sanity.io/) – React로 빌드 된 사용자 정의 가능한 MIT 라이센스 편집기로 구조화 된 컨텐츠를위한 호스팅 된 백엔드. 무제한 프로젝트. 프로젝트 당 3 명의 사용자, 2 개의 데이터 세트, 500k API CDN 요청, 5GB 자산 무료
* [pantheon.io](https://pantheon.io/) — Drupal 및 WordPress 호스팅, 자동화 된 DevOps 및 확장 가능한 인프라. 개발자 및 대행사 무료
* [acquia.com](https://www.acquia.com/) — Drupal 사이트 호스팅. 개발자를위한 프리 티어. 무료 개발 도구 (예 : Acquia Dev Desktop)도 사용 가능
* [readthedocs.org](https://readthedocs.org/) — 버전 관리, PDF 생성 등을 포함한 무료 문서 호스팅
* [bubble.is](https://bubble.is/) — 코드없이 웹 및 모바일 앱을 빌드 할 수있는 비주얼 프로그래밍, 무료 방문자 / 월, 앱 2 개
* [contentful.com](https://www.contentful.com/) — 헤드리스 CMS. 클라우드의 컨텐츠 관리 및 제공 API. 10 명의 사용자, 5000 개의 레코드, 24 개의 컨텐츠 유형, 2 개의 로케일을 포함하는 하나의 사용 가능한 마이크로 공간이 제공됩니다.
* [tilda.cc](https://tilda.cc/) — 사이트 1 개, 페이지 50 개, 저장 용량 50MB, 170 개 이상의 사용 가능한 기본 미리 정의 된 블록 만, 글꼴 없음, 파비콘 없음 및 사용자 정의 도메인 없음
* [surge.sh](https://surge.sh/) — 프론트 엔드 개발자를위한 정적 웹 게시. 맞춤 도메인 지원을 제공하는 무제한 사이트
* [neocities.org](https://neocities.org) — 200GB 대역폭의 정적 1GB 무료 스토리지.
* [txti.es](http://txti.es/) — 마크 다운을 사용하여 웹 페이지를 빠르게 만듭니다.
* [kuber.host](https://kuber.host/) — 무료 플랜으로 호스팅하는 Kubernetes
* [cloudno.de](https://cloudno.de/) — Node.js 앱용 무료 클라우드 호스팅.
* [heliohost.org](https://www.heliohost.org) — 모든 사람을위한 커뮤니티 기반 무료 호스팅.
* [render.com](https://render.com) — 모든 앱 및 웹앱 무료 SSL, 글로벌 CDN, 개인 네트워크 및 Git의 자동 배포를 정적 웹 페이지 용으로 무료로 구축하고 실행할 수있는 통합 플랫폼입니다.
* [Infinity Free](https://infinityfree.net/) — 무제한 디스크 공간과 대역폭으로 완전 무료 웹 사이트 호스팅.
* [000WebHost](https://www.000webhost.com/) — PHP, MySQL, cPanel을 통한 무료 웹 사이트 호스팅 및 광고 없음!
* [Free Host](https://profreehost.com/) — 무제한 디스크 공간 및 대역폭을 갖춘 무료 웹 호스팅.
* [무료 호스팅](http://freehostingnoads.net/) — 무료 호스팅 PHP 5, Perl, CGI, MySQL, FTP, 파일 관리자, POP 이메일, 무료 하위 도메인, 무료 도메인 호스팅, DNS 영역 편집기, 웹 사이트 통계, 무료 온라인 지원 및 기타 무료 호스트가 제공하지 않는 더 많은 기능.

## DNS
* [freedns.afraid.org](https://freedns.afraid.org/) — 무료 DNS 호스팅
* [dns.he.net](https://dns.he.net/) — 동적 DNS 지원을 통한 무료 DNS 호스팅 서비스
* [luadns.com](https://www.luadns.com/) — 무료 DNS 호스팅, 3 개의 도메인, 합리적인 제한이있는 모든 기능
* [Yandex.Connect](https://connect.yandex.com/pdd/) — 최대 1,000 명의 사용자를위한 무료 이메일 및 DNS 호스팅
* [selectel.com](https://selectel.com/services/dns/) — 무료 DNS 호스팅, 애니 캐스트, 10 개 지역
* [cloudns.net](https://www.cloudns.net/) — 50 개의 레코드가있는 최대 1 개의 도메인을 호스팅하는 무료 DNS
* [ns1.com](https://ns1.com/) — 데이터 기반 DNS, 자동 트래픽 관리, 500k 무료 쿼리
* [zonewatcher.com](https://zonewatcher.com) — 자동 백업 및 DNS 변경 모니터링. 1 개의 도메인 무료
* [namecheap.com](https://www.namecheap.com/domains/freedns/) — 무료 DNS. 도메인 수 제한 없음
* [dynu.com](https://www.dynu.com/) — 무료 동적 DNS 서비스
* [noip](https://www.noip.com/) — 30 일마다 확인을 통해 최대 3 개의 호스트 이름을 무료로 제공하는 동적 DNS 서비스
* [freenom.com](https://freenom.com/) — 무료 도메인 제공 업체. FQDN을 무료로 받으십시오.
* [duckdns.org](https://www.duckdns.org/) — 프리 티어에서 최대 5 개의 도메인이있는 무료 DDNS. 다양한 설정을위한 구성 안내서 포함.
* [1984.is](https://www.1984.is/product/freedns/) — API를 통한 무료 DNS 서비스 및 기타 많은 무료 DNS 기능이 포함되어 있습니다.
* [Cloudflare](https://www.cloudflare.com/)-무료 DNS. 무제한 도메인 수.
* [biz.mail.ru](https://biz.mail.ru) — 최대 5,000 명의 사용자를위한 무료 이메일 및 DNS 호스팅
* [pointhq.com](https://pointhq.com/developer) — Heroku에서 무료 DNS 호스팅.
* [dnspod.com](https://www.dnspod.com/) — 무료 DNS 호스팅.
* [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — 무료 DNS 호스팅.
* [zoneedit.com](https://www.zoneedit.com/free-dns/) — 동적 DNS 지원을 통한 무료 DNS 호스팅.
* [zilore.com](https://zilore.com/ru/dns) — 무료 DNS 호스팅.

## IaaS
* [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2 클라우드 스토리지. 무제한 10 시간 동안 무료 10GB (Amazon S3 유사) 객체 스토리지
* [www.terraform.io](https://www.terraform.io/)-Terraform 클라우드. 최대 5 명의 사용자를위한 무료 원격 상태 관리 및 팀 협업.

## DBaaS
* [redislabs.com](https://redislabs.com/redis-cloud) — 서비스로서의 Redis, 30MB 및 30 개의 동시 연결 무료
* [redsmin.com](https://www.redsmin.com/) — Redis, 1 Redis 인스턴스 무료 온라인 실시간 모니터링 및 관리 서비스
* [graphstory.com](https://graphstory.com/) — GraphStory는 Neo4j (그래프 데이터베이스)를 서비스로 제공합니다
* [elephantsql.com](https://www.elephantsql.com/) — 서비스로서 PostgreSQL, 20MB 무료
* [heroku.com](https://www.heroku.com/) — PostgreSQL은 서비스로, 최대 10,000 개의 행과 20 개의 연결은 무료입니다 ( "addon"으로 제공됨). 그렇지 않으면 비어있는 앱 및 외부에서 액세스)
* [graphenedb.com](https://www.graphenedb.com/) — 서비스로서 Neo4j, 최대 1,000 개의 노드 및 10,000 개의 관계 무료
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)-프리 티어에서 512MB 제공
* [scalingo.com](https://scalingo.com/) — 주로 PaaS이지만 512MB의 프리 티어 MySQL, PostgreSQL 또는 MongoDB를 제공합니다.
* [skyvia.com](https://skyvia.com/) — Cloud Data Platform, 프리 티어 제공 및 베타 기간 동안 모든 요금제 무료 제공
* [airtable.com](https://airtable.com/) — 스프레드 시트처럼 보이지만 관계형 데이터베이스, 무제한 기준, 1,200 행 /베이스 및 1,000 건의 API 요청 / 월
* [FaunaDB](https://fauna.com/) — 기본 GraphQL, 다중 모델 액세스 및 최대 5GB의 일일 무료 계층이있는 서버리스 클라우드 데이터베이스

## STUN, WebRTC, 웹 소켓 서버 및 기타 라우터
* [scaledrone.com](https://www.scaledrone.com/) — 푸시 메시징 서비스. 최대 20 개의 동시 연결 및 100,000 개의 메시지 / 일 무료
* [pusher.com](https://pusher.com/) — 실시간 메시징 서비스. 최대 100 개의 동시 연결 및 200,000 개의 메시지 / 일 무료
* [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302) — Google STUN
* [stun:global.stun.twilio.com : 3478? transport = udp](stun:global.stun.twilio.com:3478?transport=udp) — Twilio STUN
* [segment.com](https://segment.com/) — 이벤트를 다른 타사 서비스로 번역하고 라우팅하는 허브. 100,000 이벤트 / 월 무료
* [ngrok.com](https://ngrok.com/) — 터널을 통해 로컬로 실행중인 서버를 공개 URL에 노출합니다.
* [cloudamqp.com](https://www.cloudamqp.com/) — 서비스로서의 RabbitMQ. 작은 여우 원숭이 계획 : 최대 백만 메시지 / 월, 최대 20 개의 동시 연결, 최대 100 개의 큐, 최대 10,000 개의 큐 메시지, 다른 AZ의 여러 노드
* [serveo.net](https://serveo.net/) — SSH 터널을 사용하여 서보 하위 도메인의 공용 인터넷에 로컬 포트를 빠르게 노출합니다. HTTP를 통해 요청을 재생하는 SSH GUI가 포함되어 있습니다.
* [ZeroTier](https://www.zerotier.com) — 서비스로서 FOSS 관리 가상 이더넷. 무료 요금제로 100 개 클라이언트의 무제한 종단 간 암호화 네트워크. 데스크탑 / 모바일 / NA 용 클라이언트; 개인 네트워크에서 사용자 지정 라우팅 규칙 구성 및 새 클라이언트 노드 승인을위한 웹 인터페이스.
* [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi는 LAN과 같은 네트워크를 무료 계획으로 분산 된 팀으로 안전하게 확장 할 수있는 호스팅 된 VPN 서비스입니다. 최대 5 명까지 무제한 네트워크를 사용할 수 있습니다.
* [webhookrelay.com](https://webhookrelay.com) — 모든 웹 후크를 공용 또는 내부 (예 : localhost) 대상으로 관리, 디버그, 팬 아웃 및 프록시합니다. 또한 공개 HTTP 엔드 포인트 (`https://yoursubdomain.webrelay.io <----> http : // localhost : 8080`)를 가져와 터널을 통해 개인 네트워크에서 실행중인 서버를 노출하십시오.

## 이슈 트래킹 및 프로젝트 관리
* [todoist.com](https://todoist.com/) — 공동 작업 및 개별 작업 관리 무료, 프리미엄 및 팀 계획을 사용할 수 있습니다. 자격이있는 사용자에게 제공되는 할인.
* [bitrix24.com](https://www.bitrix24.com/) — 무료 인트라넷 및 프로젝트 관리 도구
* [pivotaltracker.com](https://www.pivotaltracker.com/) — 무제한 공개 프로젝트 및 3 명의 총 활성 사용자 (읽기-쓰기) 및 무제한 수동적 사용자 (읽기 전용)가있는 2 개의 비공개 프로젝트에 대해 무료입니다.
* [kanbantool.com](https://kanbantool.com/) — Kanban 보드 기반 프로젝트 관리. 더 많은 옵션이있는 무료 유료 플랜
* [kanbanflow.com](https://kanbanflow.com/) — 보드 기반 프로젝트 관리. 더 많은 옵션이있는 무료 프리미엄 버전
* [zenhub.io](https://www.zenhub.io/) — GitHub 내부의 유일한 프로젝트 관리 솔루션입니다. 공공 리포지토리, OSS 및 비영리 단체에 무료
* [trello.com](https://trello.com/) — 보드 기반 프로젝트 관리. 무제한 개인 보드, 10 개의 팀 보드.
* [clickup.com](https://clickup.com/) — 프로젝트 관리. 클라우드 스토리지가있는 무료 프리미엄 버전. 모바일 애플리케이션 및 Git 통합 가능
* [LeanBoard](https://www.leanboard.io) — GitHub 문제에 대한 스티커 메모가있는 협업 화이트 보드 (예제 매핑 및 기타 기술에 유용)
* [huboard.com](https://huboard.com/) — GitHub 문제에 대한 즉각적인 프로젝트 관리, 오픈 소스 무료
* [taiga.io](https://taiga.io/) — 스타트 업 및 민첩한 개발자를위한 프로젝트 관리 플랫폼, 무료 오픈 소스
* [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — FOSS 프로젝트, 개인 프로젝트 (3 명의 사용자는 무료)를위한 무료 호스팅 YouTrack (InCloud). 시간 추적 및 민첩한 보드 포함
* [github.com](https://github.com/) — Git 스토리지 기능 외에도 GitHub는 기본적인 문제 추적 기능을 제공합니다
* [asana.com](https://asana.com/) — 공동 작업자와의 비공개 프로젝트 무료
* [acunote.com](https://www.acunote.com/) — 최대 5 명의 팀원을위한 무료 프로젝트 관리 및 SCRUM 소프트웨어
* [gliffy.com](https://www.gliffy.com/) — 온라인 다이어그램 : 플로차트, UML, 와이어 프레임 등 ... Jira 및 Confluence 용 플러그인 5 개의 다이어그램과 2MB의 여유 공간
* [cacoo.com](https://cacoo.com/) — 실시간 온라인 다이어그램 : 플로차트, UML, 네트워크. 최대 무료 15 명 /도, 25 매
* [draw.io](https://www.draw.io/) — Google 드라이브, OneDrive 또는 Dropbox에 로컬로 저장된 온라인 다이어그램. 모든 기능 및 스토리지 수준에 대해 무료
* [Azure DevOps](https://azure.microsoft.com/services/devops/) — 무제한 무료 개인 코드 리포지토리; 버그, 작업 항목, 피드백 등을 추적
* [testlio.com](https://testlio.com/) — 문제 추적, 테스트 관리 및 베타 테스트 플랫폼. 개인용 무료
* [vivifyscrum.com](https://www.vivifyscrum.com/) — 애자일 프로젝트 관리를위한 무료 도구입니다. 스크럼 호환
* [targetprocess.com](https://www.targetprocess.com/) — Kanban 및 Scrum에서 거의 모든 운영 프로세스에 이르는 시각적 프로젝트 관리. 무제한 사용자, 최대 1,000 개의 데이터 엔터티 무료 {[자세히](https://www.targetprocess.com/pricing/)}
* [taskulu.com](https://taskulu.com/) — 역할 기반 프로젝트 관리. 최대 5 명의 사용자를 확보하십시오. GitHub / Trello / Dropbox / Google Drive와 통합
* [contriber.com](https://www.contriber.com/) — 사용자 정의 가능한 프로젝트 관리 플랫폼, 무료 시작 계획, 5 개의 작업 공간
* [planitpoker.com](https://www.planitpoker.com/) — 무료 온라인 플래닝 포커 (예상 도구)
* [ubertesters.com](https://ubertesters.com/) — 테스트 플랫폼, 통합 및 크라우드 테스터, 2 개 프로젝트, 5 명
* [plan.io](https://plan.io/) — 리포지토리 호스팅 및 mor 옵션을 사용한 프로젝트 관리. 10 명의 고객과 500MB의 스토리지를 보유한 2 명의 사용자에게 무료
* [taskade.com](https://www.taskade.com/) — 팀을위한 실시간 공동 작업 목록 및 개요
* [zenkit.com](https://zenkit.com) — 프로젝트 관리 및 협업 도구. 최대 5 명의 회원, 5GB의 첨부 파일을 무료로 제공합니다.
* [Instabug](https://instabug.com) — 모바일 앱을위한 포괄적 인 버그보고 및 인앱 피드백 SDK. 최대 1 개의 앱과 1 개의 멤버까지 무료 플랜.
* [Office 365 Developer](https://developer.microsoft.com/en-us/office/dev-program) — 개발 / 테스트를위한 1 년 무료 Office 365 E3 구독.
* [senseitool.com](https://www.senseitool.com/) — 민첩한 회고 도구-무료.
* [Gitlab](https://gitlab.com)-프로젝트에 대한 기본 이슈 추적 기능을 제공합니다.
* [Clubhouse](https://clubhouse.io/)-프로젝트 관리 플랫폼. 최대 10 명의 사용자에게 무료
* [Ora](https://ora.pm/)-민첩한 작업 관리 및 팀 협업. 최대 3 명의 사용자에게는 무료이며 파일은 10MB로 제한됩니다.


## 저장 및 미디어 처리
* [redbooth.com](https://redbooth.com) — P2P 파일 동기화, 최대 2 명의 사용자 무료
* [cloudinary.com](https://cloudinary.com/) — 루비, 파이썬, 자바, PHP, Objective-C 등을위한 라이브러리가 포함 된 이미지 업로드, 강력한 조작, 사이트 및 앱의 저장 및 제공. 영구 프리 티어는 월 7,500 개 이미지, 2GB 스토리지, 5GB 대역폭을 포함합니다.
* [piio.co](https://piio.co/) — 모든 웹 사이트에 대한 반응 형 이미지 최적화 및 전달. 개발자 및 개인 웹 사이트 무료 계획. 무료 CDN, WebP 및 Lazy Loading을 기본 제공합니다.
* [gumlet.com](https://www.gumlet.com/) — 이미지 크기 조정 서비스입니다. 또한 이미지를 최적화하고 CDN을 통한 전달을 수행합니다. 프리 티어에는 1 년 동안 매월 1GB의 대역폭과 무제한의 이미지 처리가 포함됩니다.
* [plot.ly](https://plot.ly/) — 데이터를 그래프로 만들고 공유합니다. 프리 티어에는 무제한 공개 파일과 10 개의 비공개 파일이 포함됩니다
* [transloadit.com](https://transloadit.com/) — 파일, 비디오, 오디오, 이미지 및 문서의 인코딩을 처리합니다. 오픈 소스 및 기타 수행자에게는 무료입니다. 상용 애플리케이션은 테스트 구동을 위해 1GB를 무료로 제공
* [podio.com](https://podio.com/) — 최대 5 명으로 구성된 팀과 함께 Podio를 사용하고 사용자 관리를 제외하고 기본 계획의 기능을 시험해 볼 수 있습니다
* [shrinkray.io](https://shrinkray.io/) — GitHub 저장소의 무료 이미지 최적화
* [kraken.io](https://kraken.io/) — 서비스로 웹 사이트 성능을위한 이미지 최적화, 최대 1MB 파일 크기의 무료 요금제
* [placeholder.com](https://placeholder.com/) — 빠르고 간단한 이미지 자리 표시 자 서비스
* [placekitten.com](https://placekitten.com/) — 자리 표시 자로 사용할 새끼 고양이의 사진을 가져 오는 빠르고 간단한 서비스
* [embed.ly](https://embed.ly/) — 웹 페이지에 미디어를 포함하고 반응형 이미지 크기를 조정하며 웹 페이지에서 요소를 추출하기위한 API를 제공합니다. 초당 15 개의 요청으로 최대 5,000 개의 URL을 무료로 제공합니다.
* [otixo.com](https://www.otixo.com/) — 모든 클라우드 저장소 파일을 한 곳에서 암호화, 공유, 복사 및 이동합니다. 기본 계획은 최대 250MB의 무제한 파일 전송을 제공합니다. 파일 크기 및 5 개의 암호화 된 파일 허용
* [tinypng.com](https://tinypng.com/) — PNG 및 JPEG 이미지를 압축 및 크기 조정하는 API로 매월 500 회 압축 제공
* [filestack.com](https://www.filestack.com/) — 파일 선택기, 변환 및 전달, 250 개 파일, 500 개 변환 및 3GB 대역폭 무료
* [packagecloud.io](https://packagecloud.io/) — YUM, APT, RubyGem 및 PyPI 용 호스트 패키지 리포지토리. 제한된 무료 요금제, 오픈 소스 요금제 요청 가능
* [image-charts.com](https://www.image-charts.com/) — 워터 마크가 포함 된 무제한 이미지 차트 생성
* [jsonbin.io](https://jsonbin.io/) — 무료 JSON 데이터 스토리지 서비스로 소규모 웹 앱, 웹 사이트, 모바일 앱에 이상적입니다.

## 디자인과 UI
* [landen.co](https://www.landen.co) — 스타트 업을위한 멋진 웹 사이트 및 방문 페이지를 생성, 편집 및 게시합니다. 코드없이 모두. 프리 티어를 사용하면 하나의 웹 사이트를 만들 수 있으며 웹에서 완전히 사용자 정의하고 게시 할 수 있습니다.
* [pixlr.com](https://pixlr.com/) — 상용 수준의 무료 온라인 브라우저 편집기
* [imagebin.ca](https://imagebin.ca/) — 이미지 용 Pastebin
* [cloudconvert.com](https://cloudconvert.com/) — 무엇이든 변환하십시오. 비디오를 GIF로 포함한 208 지원 형식
* [resizeappicon.com](https://resizeappicon.com/) — 앱 아이콘의 크기를 조정하고 관리하는 간단한 서비스
* [vectr.com](https://vectr.com/) — 웹 + 데스크탑 용 무료 디자인 앱
* [clevebrush.com](https://www.cleverbrush.com/) — 무료 그래픽 디자인 / 사진 콜라주 앱, 또한 컴포넌트로 유료 통합 기능을 제공합니다
* [walkme.com](https://www.walkme.com/) — Enterprise Class Guidance and Engagement Platform, 무료 플랜 3 도보 최대 5 걸음 / 걸음
* [marvelapp.com](https://marvelapp.com/) — 설계, 프로토 타이핑 및 협업, 한 명의 사용자와 한 명의 프로젝트로 제한되는 무료 플랜.
* [Zeplin](https://zeplin.io/) — 디자이너 및 개발자 공동 작업 플랫폼. 디자인, 자산 및 스타일 가이드를 보여줍니다. 1 개 프로젝트 무료.
* [figma.com](https://www.figma.com) — 팀을위한 온라인 협업 디자인 도구; 프리 티어에는 최대 2 명의 편집자와 3 개의 프로젝트가있는 무제한 파일 및 뷰어가 포함됩니다.
* [designer.io](https://www.designer.io/) — UI, 일러스트레이션 등을위한 디자인 도구입니다. 기본 앱이 있습니다. 비어 있는
* [photopea.com](https://www.photopea.com) — PSD, XCF 및 스케치 형식 (Adobe Photoshop, Gimp 및 Sketch App)을 지원하는 Adobe Photoshop UI가 포함 된 무료 고급 온라인 디자인 편집기입니다.
* [pexels.com](https://www.pexels.com/)-상업용 무료 사진. 키워드별로 사진을 검색 할 수있는 무료 API가 있습니다.
* [unsplash.com](https://unsplash.com/)-상업용 및 비상업적 용도의 무료 재고 사진 (무엇을 원하든 라이센스)
* [whimsical.com](https://whimsical.com/)-협업 플로차트, 와이어 프레임, 스티커 메모 및 마인드 맵. 최대 4 개의 무료 보드를 만듭니다.
* [lensdump.com](https://lensdump.com/)-무료 클라우드 이미지 호스팅
* [Adobe XD](https://www.adobe.com/products/xd.html)-스케치와 유사한 와이어 프레임 및 프로토 타이핑 도구입니다. 무료 플랜 커버 : 1 개의 활성 공유 디자인 사양, Adobe Fonts Free (제한된 글꼴 세트), 2GB의 클라우드 스토리지

## 지도상의 데이터 시각화
* [opencagedata.com](https://opencagedata.com) — OpenStreetMap 및 기타 오픈 지오 소스를 집계하는 지오 코딩 API입니다. 하루 2,500 건의 무료 쿼리
* [graphhopper.com](https://www.graphhopper.com/) 라우팅, 경로 최적화, 거리 매트릭스, 지오 코딩,지도 일치를 위해 개발자를위한 무료 패키지가 제공됩니다.
* [datamaps.world](https://datamaps.world/) — 자유 계층으로 지리 공간 데이터를 시각화 할 수있는 도구를 제공하는 단순하면서도 강력한 플랫폼입니다.
* [Foursquare](https://developer.foursquare.com/)-Places API 및 Pilgrim SDK의 위치 검색, 장소 검색 및 상황 인식 콘텐츠입니다.
* [geocod.io](https://www.geocod.io/) — API 또는 CSV 업로드를 통한 지오 코딩. 하루 2,500 건의 무료 쿼리
* [gogeo.io](https://gogeo.io/) — 사용하기 쉬운 API 및 빅 데이터 지원을 제공하는지도 및 지리 공간 서비스
* [carto.com](https://carto.com/) — 데이터 및 공개 데이터에서지도 및 지형 공간 API를 만듭니다.
* [giscloud.com](https://www.giscloud.com/) — 온라인으로 지리 데이터를 시각화, 분석 및 공유
* [mapbox.com](https://www.mapbox.com/) —지도 데이터를 표시하기위한지도, 지리 공간 서비스 및 SDK
* [osmnames](https://osmnames.org/) — 지오 코딩, 관련 Wikipedia 페이지의 인기도에 따라 순위가 지정된 검색 결과
* [maptiler.com](https://www.maptiler.com/cloud/) —지도 시각화를위한 벡터지도,지도 서비스 및 SDK. 주간 업데이트 및 4 가지 맵 스타일의 무료 벡터 타일.
* [here](https://developer.here.com/) —지도 및 위치 인식 앱을위한 API 및 SDK. 한 달에 2 만 건의 거래가 무료로 제공됩니다
* [stadiamaps.com](https://stadiamaps.com/) —지도 타일, 라우팅, 탐색 및 기타 지리 공간 API. 비상업적 사용 및 테스트를위한 하루 2,500 건의 무료지도보기 및 API 요청.
* [developers.arcgis.com](https://developers.arcgis.com) — 웹, 데스크톱 및 모바일에서지도, 지리 공간 데이터 저장, 분석, 지오 코딩, 라우팅 등을위한 API 및 SDK입니다. 1,000,000 무료 기본 맵 + 지오 코드 트랜잭션, 한 달에 40GB 무료 타일 + 데이터 스토리지

## 패키지 빌드 시스템
* [build.opensuse.org](https://build.opensuse.org/) — 여러 배포판 (SUSE, EL, Fedora, Debian 등)을위한 패키지 빌드 서비스
* [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Fedora 및 EL을위한 모의 기반 RPM 빌드 서비스
* [help.launchpad.net](https://help.launchpad.net/Packaging) — 우분투 및 데비안 빌드 서비스 

## IDE 및 코드 편집
* [codenvy.com](https://codenvy.com/은) - IDE 및 브라우저, 협력, 힘내 / SVN의 통합 자동화 개발자의 작업 영역 (구축하고 사용자 정의 도커 기반 주자에 응용 프로그램을 실행 무료 계층이 포함됩니다 : 3 GB RAM, 여러 컴퓨터를 동시에 실행할 수있는 기능), Google Apps에 사전 통합 된 배포
* [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — 수천 개의 확장 기능을 갖춘 모든 기능을 갖춘 IDE, 플랫폼 간 앱 개발 (iOS 및 Android 용 Microsoft 확장 프로그램 다운로드 가능), 데스크톱 , 웹 및 클라우드 개발, 다국어 지원 (C#, C++, JavaScript, Python, PHP 등)
* [ide.goorm.io](https://ide.goorm.io) goormIDE는 클라우드의 완전한 IDE입니다. 다중 언어 지원, 모든 기능을 갖춘 웹 기반 터미널을 통한 Linux 기반 컨테이너, 포트 포워딩, 사용자 정의 URL, 실시간 협업 및 채팅, 공유 링크, Git / Subversion 지원. 더 많은 기능이 있습니다 (프리 티어에는 컨테이너 당 1GB RAM 및 10GB 스토리지, 5 컨테이너 슬롯 포함)
* [cocalc.com](https://cocalc.com/) — (구 cloud.sagemath.com의 SageMathCloud) — 클라우드에서의 공동 계산. Python, LaTeX, Jupyter Notebooks, SageMath, scikitlearn 등 수학, 과학, 데이터 과학, 사전 설치를위한 내장 된 협업 및 많은 무료 소프트웨어를 사용하여 전체 우분투에 대한 브라우저 액세스
* [wakatime.com](https://wakatime.com/) — 텍스트 편집기 플러그인을 사용하여 코딩 활동에 대한 정량화 된 자체 메트릭스, 무료 플랜
* [apiary.io](https://apiary.io/) - 인스턴트 API 모의와 공동 디자인 API 및 생성 된 문서 (무제한 API 청사진 하나 개의 관리자 계정 무제한 사용자에 대한 무료 및 문서 호스팅)
* [mockable.io](https://www.mockable.io/) — Mockable은 RESTful API 또는 SOAP 웹 서비스를 모방하기위한 간단한 구성 가능한 서비스입니다. 이 온라인 서비스를 통해 REST API 또는 SOAP 엔드 포인트를 빠르게 정의하고 JSON 또는 XML 데이터를 리턴 할 수 있습니다.
* [fakejson.com](https://fakejson.com/) — FakeJSON을 사용하면 API를 사용하여 가짜 데이터를 빠르게 생성 할 수 있습니다. 원하는 것과 원하는 방법을 설명하는 API 요청을하십시오. API는 JSON으로 모두 반환합니다. 아이디어에 대한 시장 프로세스로 이동하여 아이디어를 만들 때까지 속일 수 있습니다.
* [JSONPlaceholder](http://jsonplaceholder.typicode.com/) 일부 가짜 API 데이터를 JSON 형식으로 반환하는 일부 REST API 엔드 포인트입니다. 서버를 로컬로 실행하려는 경우 소스 코드도 사용할 수 있습니다.
* [jetbrains.com](https://jetbrains.com/products.html) — 생산성 도구, IDE 및 배포 도구. 학생, 교사, 오픈 소스 및 사용자 그룹을위한 무료 라이센스
* [codepen.io](https://codepen.io/) — CodePen은 웹 프런트 엔드를 위한 놀이터입니다.
* [repl.it](https://repl.it/) — 다양한 프로그램 언어를위한 클라우드 코딩 환경
* [codesandbox.io](https://codesandbox.io/) — React, Vue, Angular, Preact 등을위한 온라인 놀이터
* [stackblitz.com](https://stackblitz.com/) — 각도 및 반응을위한 온라인 VS 코드 IDE
* [cacher.io](https://www.cacher.io) — 100 개 이상의 프로그래밍 언어를 지원하는 레이블이있는 코드 스 니펫 구성
* [Coder](https://coder.com) — Visual Studio Code를 중심으로 전체 개발 환경을 구축하는 플랫폼입니다. 프리 티어에서는 2GB의 프로젝트와 2GB의 컨테이너 공간과 5 시간의 빠른 시간을 확보 할 수 있습니다 (사용 가능한 경우 컨테이너를 동적으로 확장).
* [gitpod.io](https://www.gitpod.io) — GitHub 프로젝트를위한 즉각적이고 코딩 가능한 즉시 개발 환경. 오픈 소스 무료.
* [Katacoda](https://katacoda.com) — 개발자가 배우고 회사의 채택을 늘리도록 도와주는 소프트웨어 엔지니어를위한 대화형 학습 및 교육 플랫폼.
* [JDoodle] https://www.jdoodle.com) — 하루에 최대 200 크레딧을 컴파일하는 REST API 코드 무료 계획으로 60 개 이상의 프로그래밍 언어를위한 온라인 컴파일러 및 편집기.
* [Atom](https://atom.io/)-Atom은 Electron 기반의 해킹 가능한 텍스트 편집기입니다.


## 분석, 이벤트 및 통계
* [analytics.google.com](https://analytics.google.com/) — Google 웹 로그 분석
* [www.heatlyanalytics.com](https://www.heatlyanalytics.com) — UI / UX를 이해하기위한 무료 히트 맵 도구입니다.
* [heap.io](https://heap.io) — iOS 또는 웹 앱의 모든 사용자 동작을 자동으로 캡처합니다. 월 최대 5,000 회 방문 무료
* [sematext.com](https://sematext.com/cloud/) — 최대 50K 작업 / 월, 1 일 데이터 보존, 무제한 대시 보드, 사용자 등 무료
* [usabilityhub.com](https://usabilityhub.com/) — 실제 사람들의 디자인과 모형을 테스트하고 방문자를 추적합니다. 한 명의 사용자에게 무료, 무제한 테스트
* [mixpanel.com](https://mixpanel.com/) — 사이트에 배지가있는 25,000 포인트 또는 200,000 포인트 무료
* [amplitude.com](https://amplitude.com/) — 월간 백만 건의 이벤트, 최대 2 개의 앱
* [keen.io](https://keen.io/) — 데이터 수집, 분석 및 시각화를위한 사용자 정의 분석. 50,000 이벤트 / 월 무료
* [metrica.yandex.com](https://metrica.yandex.com/) — 무제한 무료 분석
* [hotjar.com](https://www.hotjar.com/) — 사이트 당 : 하루 2,000 페이지 조회수, 3 개의 히트 맵, 3 개월 동안 저장된 데이터 ...
* [imprace.com](https://imprace.com/) — 이탈률을 높이기위한 제안으로 방문 페이지 분석. 무료 방문 페이지 / 도메인 5 개
* [optimizely.com](https://www.optimizely.com) — A / B 테스트 솔루션, 무료 시작 계획, 1 개의 웹 사이트, 1 개의 iOS 및 1 개의 Android 앱
* [expensify.com](https://www.expensify.com/) — 비용보고, 무료 개인보고 승인 워크 플로
* [Moesif](https://www.moesif.com) — REST 및 GraphQL에 대한 API 분석. (최대 500,000 API 호출 무료)
* [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) — 무제한 무료 분석
* [getinsights.io](https://getinsights.io)-프라이버시 중심, 쿠키가없는 분석, 최대 5k 이벤트 / 월 무료. 

## 방문자 세션 기록
* [inspectlet.com](https://www.inspectlet.com/) — 1 개의 웹 사이트에 대해 100 회 / 월 무료
* [mousestats.com](https://www.mousestats.com/) — 1 개의 웹 사이트에 대해 100 회 / 월 무료
* [hotjar.com](https://www.hotjar.com/) — 사이트 당 : 하루 2,000 페이지 조회수, 3 개의 히트 맵, 3 개월 동안 저장된 데이터 ...
* [usersurge.com](https://www.usersurge.com/) — 개인을위한 한 달에 250K 세션.
* [smartlook.com](https://www.smartlook.com/) — 웹 및 모바일 앱 (1,500 회 / 월), 3 개의 히트 맵, 1 개의 퍼널, 1 개월의 데이터 기록을위한 무료 패키지
* [mouseflow.com](https://mouseflow.com/) — 1 개의 웹 사이트에 대해 100 회 / 월 무료 

## 국제 휴대폰 번호 확인 API 및 SDK
* [cognalys.com](https://cognalys.com/) — SMS 게이트웨이를 사용하는 것보다 혁신적이고 안정적인 방법을 통해 프리미엄 휴대폰 번호 확인. 무료 10 회 시도 및 15 회 검증 / 일
* [numverify.com](https://numverify.com/) — 전 세계 전화 번호 확인 및 조회 JSON API. 한 달에 250 번의 API 요청
* [veriphone.io](https://veriphone.io/) — 무료이며 빠르고 안정적인 JSON API의 글로벌 전화 번호 확인. 월별 1000 건의 요청

## 결제 / 청구 통합
* [currencylayer.com](https://currencylayer.com/) — 비즈니스를위한 안정적인 환율 및 환율 변환, 월별 API 요청 1,000 건
* [vatlayer.com](https://vatlayer.com/) — 즉각적인 부가가치세 번호 확인 및 EU 부가가치세 API, 월 100 회 무료 API 요청
* [fraudlabspro.com](https://www.fraudlabspro.com) — 판매자가 지불 사기 및 지불 거절을 방지하도록 도와줍니다. 한 달에 500 번의 쿼리로 제공되는 무료 마이크로 요금제.
* [exchangerate-api.com](https://www.exchangerate-api.com)-사용하기 쉬운 통화 변환 JSON API. 요청 제한이없는 프리 티어
* [currencystack.io](https://currencystack.io/) — 154 통화에 대한 생산 준비 실시간 환율.
* [mailpop.in](https://mailpop.in)-상황에 맞는 정보로 Stripe 알림을 최대한 활용하십시오.

## 도커 관련
* [Docker Hub](https://hub.docker.com) — Docker 이미지를 빌드하고 저장하기위한 하나의 무료 개인 저장소 및 무제한 공용 저장소
* [quay.io](https://quay.io/) — 무제한 무료 공용 저장소를 사용하여 컨테이너 이미지를 빌드하고 저장합니다
* [canister.io](https://canister.io/) — 개발자를위한 20 개의 무료 개인 저장소, 팀이 Docker 이미지를 빌드하고 저장할 수있는 30 개의 무료 개인 저장소
* [Whales](https://github.com/Gueils/whales) — 무료로 애플리케이션을 자동으로 고정하는 도구입니다.
* [PWD](https://labs.play-with-docker.com/) — Docker와 함께 재생합니다. Docker를 배울 수있는 간단하고 대화 형의 재미있는 놀이터
* [Gitlab](https://gitlab.com)-리포 컨테이너 별 레지스트리. 10GB 제한 

## Vagrant 관련
* [app.vagrantup.com](https://app.vagrantup.com)-HashiCorp Vagrant Cloud. 방랑 상자 호스팅.
* [vagrantbox.es](https://www.vagrantbox.es/) — 대체 공개 상자 색인

## 여러가지 잡다한
* [docsapp.io](https://www.docsapp.io/) — 오픈 소스를 위해 무료로 문서를 게시하는 가장 쉬운 방법
* [fullcontact.com](https://www.fullcontact.com/developer/pricing/) — 앱에 소셜 프로필을 추가하여 사용자가 연락처에 대해 더 많이 알도록 도와줍니다. 한 달에 500 개의 무료 Person API 일치
* [formlets.com](https://formlets.com/) — 온라인 양식, 무제한 단일 페이지 양식 / 월, 100 건의 제출 / 월, 이메일 알림
* [superfeedr.com](https://superfeedr.com/) — 실시간 PubSubHubbub 호환 피드, 내보내기, 분석. 적은 사용자 정의로 무료
* [screenshotlayer.com](https://screenshotlayer.com/) — 모든 웹 사이트의 사용자 지정 가능한 스냅 샷을 캡처합니다. 월 100 회 무료 스냅 샷
* [screenshotmachine.com](https://www.screenshotmachine.com/) — 홈페이지뿐만 아니라 전체 길이 캡처를 포함하여 100 스냅 샷 / 월, png, gif 및 jpg 캡처
* [readme.com](https://readme.com/) — 오픈 소스를 위해 무료로 제공되는 멋진 문서 : [여기](https://readme.readme.io/docs/open-source)를 참조하십시오.
* [formaholic.com](https://formaholic.com) — 간단한 양식 끝점. 정적 사이트에 적합
* [http2.pro](https://http2.pro) — HTTP / 2 프로토콜 준비 테스트 및 클라이언트 HTTP / 2 지원 감지 API.
* [Formspree.io](https://formspree.io/) — HTTP POST 요청을 사용하여 이메일을 보냅니다. 프리 티어는 한 달에 1000 건으로 제한되며 API 호출에 이메일 주소를 공개해야합니다.
* [Formcarry.com](https://formcarry.com)-HTTP POST Form endpoint, Free plan은 한 달에 100 건의 제출을 ​​허용합니다.
* [Typeform.com](https://www.typeform.com/) — 웹 사이트에 아름답게 디자인 된 양식을 포함시킵니다. 무료 계획은 양식당 10 개의 필드와 한 달에 100 개의 응답 만 허용합니다.
* [SurveyMonkey.com](https://www.surveymonkey.com) — 온라인 설문 조사를 만듭니다. 결과를 온라인으로 분석하십시오. 무료 플랜은 설문 당 10 개의 질문과 100 개의 응답 만 허용합니다.
* [Filly](https://fill.ly) — 이전에 앱에서 수행 한 수동 작업을 재사용하여 웹 개발 워크 플로를 향상시킵니다. 팀 협업 향상을위한 양식 작성기.
* [ReqBin](https://www.reqbin.com/) — 온라인 HTTP 요청 게시. 많이 사용되는 요청 방법에는 GET, POST, PUT, DELETE 및 HEAD가 있습니다. 헤더 및 토큰 인증을 지원합니다. 요청을 저장하기위한 기본 로그인 시스템을 교육합니다.

## 기타 무료 자료

* [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) — 개발자를 위한 무료 및 오픈 소스 소프트웨어 허브
* [getawesomeness](https://getawesomeness.herokuapp.com) — GitHub에서 놀라운 기능을 모두 검색합니다.
* [education.github.com](https://education.github.com/pack) — 학생을 위한 무료 서비스 모음. 등록 필요
* [Framacloud](https://degooglisons-internet.org/en/list/) — 프랑스 비영리 단체 [Framasoft](https://framasoft.org/en) 의 무료 / Libre 오픈 소스 소프트웨어 및 SaaS 목록.
    
출처 : https://github.com/j2doll/free-for-dev.kr
