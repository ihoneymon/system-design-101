<p>
  <a href="https://blog.bytebytego.com/?utm_source=site"><img src="images/banner.jpg" /> </a>
</p>

<p align="center">
  【
  <a href="https://www.youtube.com/channel/UCZgt6AzoyjslHTC9dz0UoTw">
    👨🏻‍💻 YouTube
  </a> | 
  <a href="https://blog.bytebytego.com/?utm_source=site">
    📮 Newsletter
  </a> 】
</p>

<a href="https://trendshift.io/repositories/3709" target="_blank"><img src="https://trendshift.io/api/badge/repositories/3709" alt="ByteByteGoHq%2Fsystem-design-101 | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

# System Design 101
복잡한 시스템을 시각적 자료와 간단한 용어를 사용해 설명합니다.   
시스템 디자인 면접을 준비 중이거나 단순히 시스템이 표면 아래에서 어떻게 작동하는지 이해하고 싶은 분이라면 이 자료실이 도움이 되길 바랍니다.

# Table of Contents

<!-- TOC toc.levels=2 -->

- [Communication protocols](#communication-protocols)
  - [REST API vs. GraphQL](#rest-api-vs-graphql)
  - [How does gRPC work?](#how-does-grpc-work)
  - [What is a webhook?](#what-is-a-webhook)
  - [How to improve API performance?](#how-to-improve-api-performance)
  - [HTTP 1.0 -\> HTTP 1.1 -\> HTTP 2.0 -\> HTTP 3.0 (QUIC)](#http-10---http-11---http-20---http-30-quic)
  - [SOAP vs REST vs GraphQL vs RPC](#soap-vs-rest-vs-graphql-vs-rpc)
  - [Code First vs. API First](#code-first-vs-api-first)
  - [HTTP status codes](#http-status-codes)
  - [What does API gateway do?](#what-does-api-gateway-do)
  - [How do we design effective and safe APIs?](#how-do-we-design-effective-and-safe-apis)
  - [TCP/IP encapsulation](#tcpip-encapsulation)
  - [Why is Nginx called a “reverse” proxy?](#why-is-nginx-called-a-reverse-proxy)
  - [What are the common load-balancing algorithms?](#what-are-the-common-load-balancing-algorithms)
  - [URL, URI, URN - Do you know the differences?](#url-uri-urn---do-you-know-the-differences)
- [CI/CD](#cicd)
  - [CI/CD Pipeline Explained in Simple Terms](#cicd-pipeline-explained-in-simple-terms)
  - [Netflix Tech Stack (CI/CD Pipeline)](#netflix-tech-stack-cicd-pipeline)
- [Architecture patterns](#architecture-patterns)
  - [MVC, MVP, MVVM, MVVM-C, and VIPER](#mvc-mvp-mvvm-mvvm-c-and-viper)
  - [18 Key Design Patterns Every Developer Should Know](#18-key-design-patterns-every-developer-should-know)
- [Database](#database)
  - [A nice cheat sheet of different databases in cloud services](#a-nice-cheat-sheet-of-different-databases-in-cloud-services)
  - [8 Data Structures That Power Your Databases](#8-data-structures-that-power-your-databases)
  - [How is an SQL statement executed in the database?](#how-is-an-sql-statement-executed-in-the-database)
  - [CAP theorem](#cap-theorem)
  - [Types of Memory and Storage](#types-of-memory-and-storage)
  - [Visualizing a SQL query](#visualizing-a-sql-query)
  - [SQL language](#sql-language)
- [Cache](#cache)
  - [Data is cached everywhere](#data-is-cached-everywhere)
  - [Why is Redis so fast?](#why-is-redis-so-fast)
  - [How can Redis be used?](#how-can-redis-be-used)
  - [Top caching strategies](#top-caching-strategies)
- [Microservice architecture](#microservice-architecture)
  - [What does a typical microservice architecture look like?](#what-does-a-typical-microservice-architecture-look-like)
  - [Microservice Best Practices](#microservice-best-practices)
  - [What tech stack is commonly used for microservices?](#what-tech-stack-is-commonly-used-for-microservices)
  - [Why is Kafka fast](#why-is-kafka-fast)
- [Payment systems](#payment-systems)
  - [How to learn payment systems?](#how-to-learn-payment-systems)
  - [Why is the credit card called “the most profitable product in banks”? How does VISA/Mastercard make money?](#why-is-the-credit-card-called-the-most-profitable-product-in-banks-how-does-visamastercard-make-money)
  - [How does VISA work when we swipe a credit card at a merchant’s shop?](#how-does-visa-work-when-we-swipe-a-credit-card-at-a-merchants-shop)
  - [Payment Systems Around The World Series (Part 1): Unified Payments Interface (UPI) in India](#payment-systems-around-the-world-series-part-1-unified-payments-interface-upi-in-india)
- [DevOps](#devops)
  - [DevOps vs. SRE vs. Platform Engineering. What is the difference?](#devops-vs-sre-vs-platform-engineering-what-is-the-difference)
  - [What is k8s (Kubernetes)?](#what-is-k8s-kubernetes)
  - [Docker vs. Kubernetes. Which one should we use?](#docker-vs-kubernetes-which-one-should-we-use)
  - [How does Docker work?](#how-does-docker-work)
- [GIT](#git)
  - [How Git Commands work](#how-git-commands-work)
  - [How does Git Work?](#how-does-git-work)
  - [Git merge vs. Git rebase](#git-merge-vs-git-rebase)
- [Cloud Services](#cloud-services)
  - [A nice cheat sheet of different cloud services (2023 edition)](#a-nice-cheat-sheet-of-different-cloud-services-2023-edition)
  - [What is cloud native?](#what-is-cloud-native)
- [Developer productivity tools](#developer-productivity-tools)
  - [Visualize JSON files](#visualize-json-files)
  - [Automatically turn code into architecture diagrams](#automatically-turn-code-into-architecture-diagrams)
- [Linux](#linux)
  - [Linux file system explained](#linux-file-system-explained)
  - [18 Most-used Linux Commands You Should Know](#18-most-used-linux-commands-you-should-know)
- [Security](#security)
  - [How does HTTPS work?](#how-does-https-work)
  - [Oauth 2.0 Explained With Simple Terms.](#oauth-20-explained-with-simple-terms)
  - [Top 4 Forms of Authentication Mechanisms](#top-4-forms-of-authentication-mechanisms)
  - [Session, cookie, JWT, token, SSO, and OAuth 2.0 - what are they?](#session-cookie-jwt-token-sso-and-oauth-20---what-are-they)
  - [How to store passwords safely in the database and how to validate a password?](#how-to-store-passwords-safely-in-the-database-and-how-to-validate-a-password)
  - [Explaining JSON Web Token (JWT) to a 10 year old Kid](#explaining-json-web-token-jwt-to-a-10-year-old-kid)
  - [How does Google Authenticator (or other types of 2-factor authenticators) work?](#how-does-google-authenticator-or-other-types-of-2-factor-authenticators-work)
- [Real World Case Studies](#real-world-case-studies)
  - [Netflix's Tech Stack](#netflixs-tech-stack)
  - [Twitter Architecture 2022](#twitter-architecture-2022)
  - [Evolution of Airbnb’s microservice architecture over the past 15 years](#evolution-of-airbnbs-microservice-architecture-over-the-past-15-years)
  - [Monorepo vs. Microrepo.](#monorepo-vs-microrepo)
  - [How will you design the Stack Overflow website?](#how-will-you-design-the-stack-overflow-website)
  - [Why did Amazon Prime Video monitoring move from serverless to monolithic? How can it save 90% cost?](#why-did-amazon-prime-video-monitoring-move-from-serverless-to-monolithic-how-can-it-save-90-cost)
  - [How does Disney Hotstar capture 5 Billion Emojis during a tournament?](#how-does-disney-hotstar-capture-5-billion-emojis-during-a-tournament)
  - [How Discord Stores Trillions Of Messages](#how-discord-stores-trillions-of-messages)
  - [How do video live streamings work on YouTube, TikTok live, or Twitch?](#how-do-video-live-streamings-work-on-youtube-tiktok-live-or-twitch)

<!-- /TOC -->

## Communication protocols
통신 프로토콜

아키텍처 스타일은 애플리케이션 프로그래밍 인터페이스(API)의 여러 구성 요소가 서로 상호 작용하는 방식을 정의합니다. 결과적으로 API 설계 및 구축에 대한 표준 접근 방식을 제공함으로써 효율성, 안정성 및 다른 시스템과의 통합 용이성을 보장합니다. 다음은 가장 많이 사용되는 스타일입니다:

<p>
  <img src="images/api-architecture-styles.png" style="width: 640px">
</p>

- SOAP: 
  - 성숙하고 포괄적인 XML 기반
  - 엔터프라이즈 애플리케이션에 적합 

- RESTful: 
  - 대중적이고 구현하기 쉬운 HTTP 메서드 
  - 웹 서비스에 이상적 

- GraphQL: 
  - 쿼리 언어, 특정 데이터 요청 
  - 네트워크 오버헤드 감소, 응답 속도 향상 

- gRPC: 
  - 최신, 고성능, 프로토콜 버퍼 
  - 마이크로서비스 아키텍처에 적합 

- WebSocket: 
  - 실시간, 양방향, 영구 연결 
  - 지연 시간이 짧은 데이터 교환에 적합 

- Webhook: 
  - 이벤트 중심, HTTP 콜백, 비동기식 
  - 이벤트 발생 시 시스템에 알림


### REST API vs. GraphQL

API 설계와 관련하여 REST와 GraphQL은 각각 고유한 장단점을 가지고 있습니다.

아래 다이어그램은 REST와 GraphQL을 간략하게 비교한 것입니다.

<p>
  <img src="images/graphQL.jpg">
</p>

REST

- CRUD 작업에 GET, POST, PUT, DELETE와 같은 표준 HTTP 메서드를 사용합니다.
- 서로 다른 서비스/애플리케이션 간에 간단하고 균일한 인터페이스가 필요할 때 유용합니다.
- 캐싱 전략은 구현이 간단합니다.
- 단점은 별도의 엔드포인트에서 관련 데이터를 수집하기 위해 여러 번의 왕복이 필요할 수 있다는 것입니다.

GraphQL

- 클라이언트가 필요한 데이터를 정확하게 쿼리할 수 있는 단일 엔드포인트를 제공합니다.
- 클라이언트는 중첩 쿼리에 필요한 정확한 필드를 지정하면 서버는 해당 필드만 포함하는 최적화된 페이로드를 반환합니다.
- 데이터 수정을 위한 뮤테이션과 실시간 알림을 위한 구독을 지원합니다.
- 여러 소스의 데이터를 집계하는 데 적합하며 빠르게 진화하는 프런트엔드 요구 사항에 잘 맞습니다.
- 그러나 복잡성을 클라이언트 측으로 이동시키며, 제대로 보호하지 않으면 악의적인 쿼리를 허용할 수 있습니다.
- 캐싱 전략은 REST보다 더 복잡할 수 있습니다.

REST와 GraphQL 중 최선의 선택은 애플리케이션 및 개발 팀의 특정 요구 사항에 따라 달라집니다. GraphQL은 복잡하거나 자주 변경되는 프론트엔드 요구사항에 적합하며, REST는 단순하고 일관된 계약이 선호되는 애플리케이션에 적합합니다.

두 API 접근 방식 모두 만병통치약은 아닙니다. 올바른 스타일을 선택하려면 요구 사항과 장단점을 신중하게 평가하는 것이 중요합니다. REST와 GraphQL은 모두 데이터를 노출하고 최신 애플리케이션을 구동하는 데 유효한 옵션입니다.


### How does gRPC work?

RPC(원격 프로시저 호출)는 마이크로서비스 아키텍처에서 서비스가 서로 다른 서버에 배포될 때 원격 서비스 간의 통신을 가능하게 하기 때문에 "**원격**"이라고 불립니다. 사용자 입장에서는 로컬 함수 호출처럼 작동합니다.

아래 다이어그램은 **gRPC**의 전체 데이터 흐름을 보여줍니다.

<p>
  <img src="images/grpc.jpg">
</p>

- 1단계: 클라이언트에서 REST 호출이 이루어집니다. 요청 본문은 일반적으로 JSON 형식입니다.
- 2 ~ 4단계: 주문 서비스(gRPC 클라이언트)가 REST 호출을 수신하여 변환한 후 결제 서비스에 RPC 호출을 합니다. gRPC는 **클라이언트 스텁**을 바이너리 형식으로 인코딩하여 저수준 전송 계층으로 보냅니다.
- 5단계: gRPC는 HTTP2를 통해 네트워크를 통해 패킷을 전송합니다. 바이너리 인코딩과 네트워크 최적화로 인해 gRPC는 JSON보다 5배 빠르다고 합니다.
- 6 ~ 8단계: 결제 서비스(gRPC 서버)가 네트워크에서 패킷을 수신하고, 이를 디코딩한 후 서버 애플리케이션을 호출합니다.
- 9 ~ 11단계: 서버 애플리케이션에서 결과를 반환하고 인코딩하여 전송 계층으로 전송합니다.
- 12 ~ 14단계: 주문 서비스가 패킷을 수신하여 디코딩한 후 결과를 클라이언트 애플리케이션으로 보냅니다.

### What is a webhook?
웹훅이란 무엇인가?

아래 다이어그램은 폴링과 웹후크를 비교한 것입니다. 

<p>
  <img src="images/webhook.jpeg" style="width: 680px" />
</p>

이커머스 웹사이트를 운영한다고 가정해 봅시다. 클라이언트는 API 게이트웨이를 통해 주문 서비스로 주문을 보내고, 주문 서비스는 결제 트랜잭션을 위해 결제 서비스로 이동합니다. 그러면 결제 서비스는 외부 결제 서비스 공급업체(PSP)와 통신하여 거래를 완료합니다. 

외부 PSP와의 통신을 처리하는 방법에는 두 가지가 있습니다. 

**1. 짧은 폴링(Short polling)** 

결제 요청을 PSP에 전송한 후 결제 서비스에서 PSP에 결제 상태를 계속 묻습니다. 몇 번의 라운드가 끝나면 PSP가 최종적으로 상태를 반환합니다. 

짧은 폴링에는 두 가지 단점이 있습니다: 
- 상태를 지속적으로 폴링하려면 결제 서비스의 리소스가 필요합니다. 
- 외부 서비스가 결제 서비스와 직접 통신하므로 보안 취약점이 발생할 수 있습니다. 

**2. 웹훅(Webhook)** 

외부 서비스에 웹훅을 등록할 수 있습니다. 이는 요청에 대한 업데이트가 있을 때 특정 URL로 다시 전화하는 것을 의미합니다. PSP가 처리를 완료하면 HTTP 요청을 호출하여 결제 상태를 업데이트합니다.

이렇게 프로그래밍 패러다임이 바뀌면 결제 서비스에서 더 이상 결제 상태를 폴링하는 데 리소스를 낭비할 필요가 없습니다.

PSP가 다시 전화를 걸지 않으면 어떻게 하나요? 매시간 결제 상태를 확인하도록 하우스키핑 작업을 설정할 수 있습니다.

웹후크는 서버가 클라이언트에 HTTP 요청을 전송하기 때문에 리버스 API 또는 푸시 API라고도 불립니다. 웹훅을 사용할 때는 다음 세 가지에 주의해야 합니다:

1. 외부 서비스가 호출할 적절한 API를 설계해야 합니다.
2. 보안을 위해 API 게이트웨이에 적절한 규칙을 설정해야 합니다.
3. 외부 서비스에 올바른 URL을 등록해야 합니다.

### How to improve API performance?
>  API 성능을 개선하려면 어떻게 해야 하나요?

아래 다이어그램은 API 성능을 개선하기 위한 5가지 일반적인 트릭을 보여줍니다.

<p>
  <img src="images/api-performance.jpg">
</p>

페이지 매김(Pagination)
  결과의 크기가 클 때 일반적으로 사용되는 최적화 방법입니다. 서비스 응답성을 개선하기 위해 결과를 클라이언트로 다시 스트리밍합니다.

비동기 로깅(Asynchronous Logging)
> 동기 로깅은 모든 호출에 대해 디스크를 처리하므로 시스템 속도가 느려질 수 있습니다. 비동기 로깅은 로그를 잠금 없는 버퍼로 먼저 전송하고 즉시 반환합니다. 로그는 주기적으로 디스크에 플러시됩니다. 이렇게 하면 I/O 오버헤드가 크게 줄어듭니다.

캐싱(Caching)
> 자주 액세스하는 데이터를 캐시에 캐시할 수 있습니다. 클라이언트는 데이터베이스를 직접 방문하는 대신 캐시를 먼저 쿼리할 수 있습니다. 캐시에 누락이 있는 경우 클라이언트는 데이터베이스에서 쿼리할 수 있습니다. Redis와 같은 캐시는 데이터를 메모리에 저장하므로 데이터 액세스가 데이터베이스보다 훨씬 빠릅니다.

페이로드 압축(Payload Compression)
> 요청과 응답을 gzip 등을 사용하여 압축하여 전송되는 데이터 크기를 훨씬 작게 만들 수 있습니다. 이렇게 하면 업로드 및 다운로드 속도가 빨라집니다.


커넥션 풀(Connection Pool)
> 리소스에 액세스할 때 데이터베이스에서 데이터를 로드해야 하는 경우가 많습니다. 닫혀 있는 데이터베이스 연결을 열면 상당한 오버헤드가 추가됩니다. 따라서 열린 연결 풀을 통해 데이터베이스에 연결해야 합니다. 연결 풀은 연결 수명 주기를 관리합니다.


### HTTP 1.0 -> HTTP 1.1 -> HTTP 2.0 -> HTTP 3.0 (QUIC)

각 세대의 HTTP는 어떤 문제를 해결하나요?

아래 다이어그램은 주요 기능을 보여줍니다.

<p>
  <img src="images/http3.jpg" />
</p>

- HTTP 1.0은 1996년에 완성되어 완전히 문서화되었습니다. 동일한 서버에 대한 모든 요청에는 별도의 TCP 연결이 필요합니다.

- HTTP 1.1은 1997년에 발표되었습니다. TCP 연결은 재사용(영구 연결)을 위해 열어 둘 수 있지만 HOL(헤드 오브 라인) 차단 문제를 해결하지는 못합니다. 

  HOL 차단 - 브라우저에서 허용되는 병렬 요청의 수가 모두 사용되면 후속 요청은 이전 요청이 완료될 때까지 기다려야 합니다.

- HTTP 2.0은 2015년에 발표되었습니다. 이 버전은 요청 다중화를 통해 HOL 문제를 해결하여 애플리케이션 계층에서 HOL 차단을 제거하지만 전송(TCP) 계층에는 여전히 HOL이 존재합니다.

  다이어그램에서 볼 수 있듯이 HTTP 2.0은 서로 다른 HTTP 교환을 동일한 TCP 연결에 다중화할 수 있는 추상화 개념인 HTTP "스트림"을 도입했습니다. 각 스트림을 순서대로 전송할 필요는 없습니다.

- HTTP 3.0 초안은 2020년에 발표되었습니다. HTTP 2.0의 후속 버전으로 제안되었습니다. 기본 전송 프로토콜로 TCP 대신 QUIC을 사용하므로 전송 계층에서 HOL 차단이 제거됩니다. 

QUIC은 UDP를 기반으로 합니다. 전송 계층에서 스트림을 일등 시민으로 도입합니다. QUIC 스트림은 동일한 QUIC 연결을 공유하므로 새 스트림을 생성하기 위해 추가 핸드셰이크나 슬로우 스타트가 필요하지 않으며, 대부분의 경우 한 스트림에 영향을 미치는 패킷 손실이 다른 스트림에 영향을 미치지 않도록 독립적으로 전달됩니다.


### SOAP vs REST vs GraphQL vs RPC

아래 다이어그램은 API 타임라인과 API 스타일을 비교한 것입니다.

시간이 지남에 따라 다양한 API 아키텍처 스타일이 출시됩니다. 각 스타일에는 데이터 교환을 표준화하는 고유한 패턴이 있습니다. 

다이어그램에서 각 스타일의 사용 사례를 확인할 수 있습니다.

<p>
  <img src="images/SOAP vs REST vs GraphQL vs RPC.jpeg" />
</p>


### Code First vs. API First 
> 코드 우선 대 API 우선 

아래 다이어그램은 코드 우선 개발과 API 우선 개발의 차이점을 보여줍니다. API 우선 설계를 고려해야 하는 이유는 무엇일까요?

<p>
  <img src="images/api_first.jpg" style="width: 680px" />
</p>


- 마이크로서비스는 시스템의 복잡성을 증가시키며, 시스템의 다양한 기능을 제공하기 위해 별도의 서비스를 제공합니다. 이러한 아키텍처는 분리와 업무 분리를 용이하게 하지만, 서비스 간의 다양한 커뮤니케이션을 처리해야 합니다. 

코드를 작성하기 전에 시스템의 복잡성을 충분히 고려하고 서비스의 경계를 신중하게 정의하는 것이 좋습니다.

- 별도의 기능 팀은 동일한 언어를 사용해야 하며 전담 기능 팀은 자체 구성 요소와 서비스만 담당합니다. API 설계를 통해 조직이 동일한 언어를 사용하는 것이 좋습니다. 

코드를 작성하기 전에 요청과 응답을 모의하여 API 설계를 검증할 수 있습니다.

- 소프트웨어 품질 및 개발자 생산성 향상 프로젝트 시작 시 불확실성을 대부분 제거했기 때문에 전반적인 개발 프로세스가 더 원활해지고 소프트웨어 품질이 크게 향상됩니다. 

개발자는 갑작스러운 변경 사항을 협상하는 대신 기능 개발에 집중할 수 있기 때문에 이 프로세스에 만족하고 있습니다.

프로젝트 라이프사이클이 끝날 무렵 돌발 상황이 발생할 가능성도 줄어듭니다.

API를 먼저 설계했기 때문에 코드가 개발되는 동안 테스트를 설계할 수 있습니다. 어떻게 보면 API 우선 개발을 사용할 때 TDD(테스트 주도 설계)를 사용하는 것과도 같습니다.
### HTTP status codes
> HTTP 상태 코드

<p>
  <img src="images/http-status-code.jpg" style="width: 540px" />
</p>


HTTP의 응답 코드는 5가지로 나뉩니다: 

- 정보(100-199) 
- 성공(200-299) 
- 리디렉션 (300-399) 
- 클라이언트 오류(400-499) 
- 서버 오류(500-599) 

### What does API gateway do? 
>  API 게이트웨이의 기능은 무엇인가요? 

아래 다이어그램은 자세한 내용을 보여줍니다. 

<p>
  <img src="images/api_gateway.jpg" style="width: 520px" />
</p>

1단계 - 클라이언트가 API 게이트웨이에 HTTP 요청을 보냅니다. 

2단계 - API 게이트웨이가 HTTP 요청의 속성을 파싱하고 유효성을 검사합니다. 

3단계 - API 게이트웨이가 허용 목록/거부 목록 검사를 수행합니다. 

4단계 - API 게이트웨이가 인증 및 권한 부여를 위해 ID 공급자와 통신합니다. 

5단계 - 요청에 속도 제한 규칙이 적용됩니다. 한도를 초과하면 요청이 거부됩니다. 

6단계와 7단계 - 요청이 기본 검사를 통과했으므로 이제 API 게이트웨이는 경로 매칭을 통해 라우팅할 관련 서비스를 찾습니다. 

8단계 - API 게이트웨이가 요청을 적절한 프로토콜로 변환하여 백엔드 마이크로서비스로 보냅니다. 

9~12단계: API 게이트웨이는 오류를 적절히 처리할 수 있으며, 오류를 복구하는 데 시간이 오래 걸리는 경우(회로 차단) 오류를 처리합니다. 또한 로깅과 모니터링을 위해 ELK(Elastic-Logstash-Kibana) 스택을 활용할 수 있습니다. 때때로 API 게이트웨이에 데이터를 캐시하기도 합니다. 

### How do we design effective and safe APIs?
> 효과적이고 안전한 API를 설계하려면 어떻게 해야 할까요?

아래 다이어그램은 쇼핑 카트를 예로 들어 일반적인 API 설계를 보여줍니다. 

<p>
  <img src="images/safe-apis.jpg" />
</p>

API 설계는 단순한 URL 경로 설계가 아니라는 점에 유의하세요. 대부분의 경우 적절한 리소스 이름, 식별자, 경로 패턴을 선택해야 합니다. 적절한 HTTP 헤더 필드를 설계하거나 API 게이트웨이 내에서 효과적인 속도 제한 규칙을 설계하는 것도 마찬가지로 중요합니다. 

### TCP/IP encapsulation 
> TCP/IP 캡슐화

데이터는 네트워크를 통해 어떻게 전송되나요? OSI 모델에 많은 레이어가 필요한 이유는 무엇인가요?

<p>
  <img src="images/osi model.jpeg" />
</p>

아래 다이어그램은 네트워크를 통해 전송할 때 데이터가 어떻게 캡슐화되고 캡슐화가 해제되는지 보여줍니다.

1단계: 장치 A가 HTTP 프로토콜을 통해 네트워크를 통해 장치 B로 데이터를 전송할 때 먼저 애플리케이션 계층에서 HTTP 헤더가 추가됩니다.

2단계: 그런 다음 TCP 또는 UDP 헤더가 데이터에 추가됩니다. 이 헤더는 전송 계층에서 TCP 세그먼트로 캡슐화됩니다. 헤더에는 소스 포트, 대상 포트, 시퀀스 번호가 포함됩니다.

3단계: 그런 다음 네트워크 계층에서 세그먼트가 IP 헤더로 캡슐화됩니다. IP 헤더에는 소스/대상 IP 주소가 포함됩니다.

4단계: 데이터 링크 계층에서 IP 데이터그램에 소스/대상 MAC 주소가 포함된 MAC 헤더가 추가됩니다.

5단계: 캡슐화된 프레임이 물리 계층으로 전송되고 네트워크를 통해 바이너리 비트로 전송됩니다.

6~10단계: 장치 B가 네트워크에서 비트를 수신하면 캡슐화 프로세스의 역처리인 캡슐화 해제 프로세스를 수행합니다. 헤더가 레이어별로 제거되고 결국 디바이스 B가 데이터를 읽을 수 있게 됩니다.

네트워크 모델에 레이어가 필요한 이유는 각 레이어가 고유한 책임에 집중하기 때문입니다. 각 계층은 헤더에 의존하여 처리 명령을 내릴 수 있으며 마지막 계층의 데이터 의미를 알 필요가 없습니다.

### Why is Nginx called a “reverse” proxy?
> Nginx를 "리버스" 프록시라고 부르는 이유는 무엇인가요?

아래 다이어그램은 𝐟𝐨𝐫𝐰𝐚𝐫𝐝 𝐩𝐫𝐨𝐱𝐲 와 𝐫𝐞𝐯𝐞𝐫𝐬𝐞 𝐩𝐫𝐨𝐱𝐲 의 차이점을 보여줍니다.

<p>
  <img src="images/Forward Proxy v.s. Reverse Proxy2x.jpg" style="width: 720px" />
</p>

정방향 프록시는 사용자 디바이스와 인터넷 사이에 있는 서버입니다.

정방향 프록시는 일반적으로 다음과 같은 용도로 사용됩니다: 

1. 클라이언트 보호
2. 브라우징 제한 우회
3. 특정 콘텐츠에 대한 액세스 차단

역방향 프록시는 클라이언트의 요청을 수락하여 웹 서버로 요청을 전달한 후 프록시 서버가 요청을 처리한 것처럼 결과를 클라이언트에 반환하는 서버입니다.

역방향 프록시는 다음과 같은 경우에 유용합니다:

1. 서버 보호
2. 로드 밸런싱
3. 정적 콘텐츠 캐싱
4. SSL 통신 암호화 및 복호화

### What are the common load-balancing algorithms?
> 일반적인 로드 밸런싱 알고리즘은 무엇인가요?

아래 다이어그램은 6가지 일반적인 알고리즘을 보여줍니다. 

<p>
  <img src="images/lb-algorithms.jpg" />
</p>

- 정적 알고리즘 

1. 라운드 로빈
    클라이언트 요청은 순차적으로 다른 서비스 인스턴스로 전송됩니다. 서비스는 일반적으로 상태 비저장 상태여야 합니다. 

3. 스티키 라운드 로빈
  이것은 라운드 로빈 알고리즘을 개선한 것입니다. 앨리스의 첫 번째 요청이 서비스 A로 전송되면 다음 요청도 서비스 A로 전송됩니다. 

4. 가중치 라운드 로빈
  관리자는 각 서비스에 가중치를 지정할 수 있습니다. 가중치가 높은 서비스가 다른 서비스보다 더 많은 요청을 처리합니다. 

6. 해시
  이 알고리즘은 들어오는 요청의 IP 또는 URL에 해시 함수를 적용합니다. 요청은 해시 함수 결과에 따라 관련 인스턴스로 라우팅됩니다. 

- 동적 알고리즘

5. 최소 연결
    동시 연결 수가 가장 적은 서비스 인스턴스로 새 요청이 전송됩니다. 

7. 최소 응답 시간
  응답 시간이 가장 빠른 서비스 인스턴스에 새 요청이 전송됩니다.


### URL, URI, URN - Do you know the differences? 
> URL, URI, URN - 차이점을 알고 계신가요? 

아래 다이어그램은 URL, URI, URN의 비교를 보여줍니다. 

<p>
  <img src="images/url-uri-urn.jpg" />
</p>

- URI 

URI는 유니폼 리소스 식별자의 약자입니다. 웹에서 논리적 또는 물리적 리소스를 식별합니다. URL과 URN은 URI의 하위 유형입니다. URL은 리소스의 위치를 지정하고 URN은 리소스의 이름을 지정합니다. 

URI는 다음 부분으로 구성됩니다: 
scheme:[//authority]path[?query][#fragment] 
> scheme:[//authority]경로[?쿼리][#조각] 

- URL 

URL은 HTTP의 핵심 개념인 Uniform Resource Locator의 약자입니다. 웹에서 고유한 리소스의 주소입니다. FTP 및 JDBC와 같은 다른 프로토콜과 함께 사용할 수 있습니다. 

- URN 

URN은 유니폼 리소스 이름의 약자입니다. urn 스키마를 사용합니다. URN은 리소스를 찾는 데 사용할 수 없습니다. 다이어그램에 제공된 간단한 예는 네임스페이스와 네임스페이스별 문자열로 구성되어 있습니다. 

이 주제에 대해 더 자세히 알고 싶으시다면 [W3C’s clarification](https://www.w3.org/TR/uri-clarification/)을 참조하시기 바랍니다.

## CI/CD

### CI/CD Pipeline Explained in Simple Terms
> 간단한 용어로 설명하는 CI/CD 파이프라인

<p>
  <img src="images/ci-cd-pipeline.jpg" style="width: 680px" />
</p>

섹션 1 - CI/CD를 사용한 SDLC

소프트웨어 개발 수명 주기(SDLC)는 개발, 테스트, 배포, 유지 관리 등 몇 가지 주요 단계로 구성됩니다. CI/CD는 이러한 단계를 자동화하고 통합하여 더 빠르고 안정적인 릴리스를 가능하게 합니다.

코드가 git 리포지토리에 푸시되면 자동화된 빌드 및 테스트 프로세스가 트리거됩니다. 코드의 유효성을 검사하기 위해 엔드투엔드(e2e) 테스트 케이스가 실행됩니다. 테스트가 통과되면 코드를 스테이징/프로덕션에 자동으로 배포할 수 있습니다. 문제가 발견되면 버그 수정을 위해 코드가 개발팀으로 다시 전송됩니다. 이러한 자동화를 통해 개발자에게 빠른 피드백을 제공하고 프로덕션 환경에서 버그가 발생할 위험을 줄일 수 있습니다.

섹션 2 - CI와 CD의 차이점

지속적 통합(CI)은 빌드, 테스트 및 병합 프로세스를 자동화합니다. 코드가 커밋될 때마다 테스트를 실행하여 통합 문제를 조기에 발견합니다. 이를 통해 코드 커밋을 자주 하고 피드백을 빠르게 받을 수 있습니다.

지속적 배포(CD)는 인프라 변경 및 배포와 같은 릴리스 프로세스를 자동화합니다. 자동화된 워크플로를 통해 언제든지 소프트웨어를 안정적으로 릴리스할 수 있습니다. 또한 CD는 프로덕션 배포 전에 필요한 수동 테스트 및 승인 단계를 자동화할 수도 있습니다.

섹션 3 - CI/CD 파이프라인

일반적인 CI/CD 파이프라인에는 여러 단계가 연결되어 있습니다:
- 개발자가 소스 제어에 코드 변경 사항을 커밋합니다.
- CI 서버가 변경 사항을 감지하고 빌드를 트리거합니다.
- 코드가 컴파일되고 테스트(단위, 통합 테스트)됩니다.
- 개발자에게 테스트 결과 보고
- 성공하면 아티팩트가 스테이징 환경에 배포됩니다.
- 릴리스 전에 스테이징에서 추가 테스트 수행 가능
- CD 시스템에서 승인된 변경 사항을 프로덕션에 배포

### Netflix Tech Stack (CI/CD Pipeline)

<p>
  <img src="images/netflix-ci-cd.jpg" style="width: 720px" />
</p>

- 계획: 넷플릭스 엔지니어링은 계획에는 JIRA를, 문서화에는 Confluence를 사용합니다. 
- 코딩: Java는 백엔드 서비스를 위한 기본 프로그래밍 언어이며, 사용 사례에 따라 다른 언어가 사용됩니다.  
- 빌드: 빌드에는 주로 Gradle이 사용되며, 다양한 사용 사례를 지원하기 위해 Gradle 플러그인이 구축됩니다.  
- 패키징: 패키지 및 종속 요소는 릴리스를 위해 Amazon 머신 이미지(AMI)에 패키징됩니다. 
- 테스트: 테스트는 카오스 도구 구축에 중점을 둔 프로덕션 문화를 강조합니다.  
- 배포: Netflix는 카나리아 롤아웃 배포를 위해 자체 구축한 Spinnaker를 사용합니다.  
- 모니터링: 모니터링 메트릭은 Atlas에서 중앙 집중식으로 관리되며, 이상 징후를 감지하는 데 Kayenta를 사용합니다.  
- 인시던트 보고서: 우선순위에 따라 인시던트가 발송되며, 인시던트 처리를 위해 PagerDuty가 사용됩니다. 

## Architecture patterns
> 아키텍처 패턴

### MVC, MVP, MVVM, MVVM-C, and VIPER
이러한 아키텍처 패턴은 iOS 또는 Android 플랫폼에서 앱 개발에 가장 일반적으로 사용되는 패턴 중 하나입니다. 개발자들은 이전 패턴의 한계를 극복하기 위해 이 패턴들을 도입했습니다. 그렇다면 이들은 어떻게 다를까요? 

<p>
  <img src="images/client arch patterns.png" style="width: 720px" />
</p>

- 가장 오래된 패턴인 MVC는 거의 50년 전으로 거슬러 올라갑니다. 
- 모든 패턴에는 콘텐츠를 표시하고 사용자 입력을 수신하는 '뷰'(V)가 있습니다. 
- 대부분의 패턴에는 비즈니스 데이터를 관리하기 위한 "모델"(M)이 포함됩니다. 
- "컨트롤러", "발표자", "뷰-모델"은 뷰와 모델(VIPER 패턴의 "엔티티") 사이를 매개하는 번역자입니다.

### 18 Key Design Patterns Every Developer Should Know
> 모든 개발자가 알아야 할 18가지 핵심 디자인 패턴

패턴은 일반적인 디자인 문제에 대한 재사용 가능한 솔루션으로, 보다 원활하고 효율적인 개발 프로세스를 제공합니다. 패턴은 더 나은 소프트웨어 구조를 구축하기 위한 청사진 역할을 합니다. 다음은 가장 많이 사용되는 패턴 중 일부입니다: 

<p>
  <img src="images/18-oo-patterns.png" />
</p>

- **추상 팩토리(Abstract Factory)**: 패밀리 크리에이터 - 관련 항목의 그룹을 만듭니다. 
- **빌더: 레고 마스터(Builder: Lego Master)** - 생성 및 모양을 분리하여 단계별로 개체를 만듭니다. 
- **프로토타입: 클론 메이커(Prototype: Clone Maker)** - 완전히 준비된 예제의 사본을 만듭니다. 
- **싱글톤: 원 앤 온리(Singleton: One and Only)** - 인스턴스가 하나뿐인 특수 클래스입니다. 
- **어댑터: 범용 플러그(Adapter: Universal Plug)** - 서로 다른 인터페이스를 가진 사물을 연결합니다. 
- **브리지: 함수 커넥터(Bridge: Function Connector)** - 객체의 작동 방식과 객체가 하는 일을 연결합니다. 
- **컴포지트: 트리 빌더(Composite: Tree Builder)** - 단순하고 복잡한 부품으로 나무와 같은 구조를 형성합니다. 
- **데코레이터: 커스터마이저(Decorator: Customizer)** - 코어를 변경하지 않고 개체에 기능을 추가합니다. 
- **파사드: 원스톱 상점(Facade: One-Stop-Shop)** - 단순화된 단일 인터페이스로 전체 시스템을 나타냅니다. 
- **플라이웨이트: 공간 절약(Flyweight: Space Saver)** - 재사용 가능한 작은 항목을 효율적으로 공유합니다. 
- **프록시: 스탠드인 액터(Proxy: Stand-In Actor)** - 다른 객체를 나타내며 액세스 또는 작업을 제어합니다. 
- **책임의 사슬: 요청 릴레이(Chain of Responsibility)** - 요청이 처리될 때까지 일련의 객체 체인을 통해 요청을 전달합니다. 
- **명령: 태스크 래퍼(Command: Task Wrapper)** - 요청을 작업할 준비가 된 객체로 변환합니다. 
- **이터레이터: 컬렉션 탐색기(Iterator: Collection Explorer)** - 컬렉션의 요소에 하나씩 액세스합니다. 
- **중개자: 커뮤니케이션 허브(Mediator: Communication Hub)** - 서로 다른 클래스 간의 상호 작용을 단순화합니다. 
- **메멘토: 타임캡슐(Memento: Time Capsule)** - 객체의 상태를 캡처하고 복원합니다. 
- **관찰자: 뉴스 브로드캐스터(Observer: News Broadcaster)** - 다른 객체의 변경 사항을 클래스에 알립니다. 
- **방문자: 숙련된 손님(Visitor: Skillful Guest)** - 클래스를 변경하지 않고 새로운 작업을 추가합니다.

***

## Database
> 데이터베이스

### A nice cheat sheet of different databases in cloud services
> 클라우드 서비스의 다양한 데이터베이스에 대한 멋진 치트 시트

<p>
  <img src="images/cloud-dbs2.png" />
</p>

프로젝트에 적합한 데이터베이스를 선택하는 것은 복잡한 작업입니다. 각기 다른 사용 사례에 적합한 수많은 데이터베이스 옵션은 의사 결정의 피로를 빠르게 유발할 수 있습니다. 

이 치트 시트가 프로젝트의 요구사항에 맞는 올바른 서비스를 정확히 파악하고 잠재적인 함정을 피하는 데 도움이 되기를 바랍니다. 

참고: Google은 데이터베이스 사용 사례에 대한 문서가 제한되어 있습니다. 사용 가능한 정보를 최대한 살펴보고 최선의 선택에 도달하기 위해 최선을 다했지만, 일부 항목은 더 정확한 정보가 필요할 수 있습니다.  

### 8 Data Structures That Power Your Databases
> 데이터베이스를 강화하는 8가지 데이터 구조

정답은 사용 사례에 따라 달라질 수 있습니다. 데이터는 메모리 또는 디스크에 색인될 수 있습니다. 마찬가지로 데이터 형식도 숫자, 문자열, 지리적 좌표 등 다양합니다. 시스템이 쓰기 중심일 수도 있고 읽기 중심일 수도 있습니다. 이러한 모든 요소는 데이터베이스 인덱스 형식 선택에 영향을 줍니다. 

<p>
  <img src="images/8-ds-db.jpg" />
</p>

다음은 데이터 인덱싱에 가장 많이 사용되는 몇 가지 데이터 구조입니다: 

- **스킵리스트(Skiplist)**: 일반적인 인메모리 인덱스 유형입니다. Redis에서 사용 
- **해시 인덱스(Hash index)**: "Map" 데이터 구조(또는 "Collection")의 매우 일반적인 구현입니다. 
- **SSTable**: 불변의 온디스크 "맵" 구현 
- **LSM 트리**: 스킵리스트 + SSTable. 높은 쓰기 처리량 
- **B-tree**: 디스크 기반 솔루션. 일관된 읽기/쓰기 성능 
- **반전 인덱스(Inverted index)**: 문서 인덱싱에 사용됩니다. Lucene에서 사용 
- **접미사 트리(Suffix tree)**: 문자열 패턴 검색용 
- **R-tree**: 가장 가까운 이웃 찾기와 같은 다차원 검색에 사용됨 

### How is an SQL statement executed in the database?
> 데이터베이스에서 SQL 문은 어떻게 실행되나요?

아래 다이어그램은 그 과정을 보여줍니다. 데이터베이스마다 아키텍처가 다르지만, 이 다이어그램은 몇 가지 일반적인 설계를 보여줍니다.

<p>
  <img src="images/sql execution order in db.jpeg" style="width: 580px" />
</p>


1단계 - SQL 문이 전송 계층 프로토콜(예: TCP)을 통해 데이터베이스로 전송됩니다.

2단계 - SQL 문이 명령 구문 분석기로 전송되어 구문 및 의미 분석을 거친 후 쿼리 트리가 생성됩니다.

3단계 - 쿼리 트리가 옵티마이저로 전송됩니다. 옵티마이저가 실행 계획을 생성합니다. 

4단계 - 실행 계획이 실행자에게 전송됩니다. 실행자는 실행에서 데이터를 검색합니다.

5단계 - 액세스 메서드는 실행에 필요한 데이터 가져오기 로직을 제공하여 스토리지 엔진에서 데이터를 검색합니다. 

6단계 - Access 메서드는 SQL 문이 읽기 전용인지 여부를 결정합니다. 쿼리가 읽기 전용인 경우(SELECT 문), 추가 처리를 위해 버퍼 관리자에게 전달됩니다. 버퍼 관리자는 캐시 또는 데이터 파일에서 데이터를 찾습니다.

7단계 - UPDATE 또는 INSERT 문인 경우 추가 처리를 위해 트랜잭션 관리자에게 전달됩니다.

8단계 - 트랜잭션이 진행되는 동안 데이터는 잠금 모드가 됩니다. 이는 잠금 관리자에 의해 보장됩니다. 또한 트랜잭션의 ACID 속성도 보장합니다. 


###  CAP theorem
> CAP 정리

CAP 정리는 컴퓨터 과학에서 가장 유명한 용어 중 하나이지만, 개발자마다 이해하는 바가 다를 수 있습니다. 이 용어가 무엇이며 왜 혼란스러울 수 있는지 살펴보겠습니다. 

<p>
  <img src="images/cap theorem.jpeg" />
</p>

CAP 정리는 분산화된 시스템이 이 세 가지 보장 중 두 가지 이상을 동시에 제공할 수 없다는 것을 말합니다.

**일관성(Consistency)**: 일관성이란 모든 클라이언트가 어느 노드에 연결하든 동일한 데이터를 동시에 볼 수 있음을 의미합니다.

**가용성(Availability)**: 가용성이란 일부 노드가 다운되더라도 데이터를 요청하는 모든 클라이언트가 응답을 받는 것을 의미합니다.

**파티션 허용 오차(Partition Tolerance)**: 파티션은 두 노드 간의 통신 중단을 나타냅니다. 파티션 허용 오차는 네트워크 파티션에도 불구하고 시스템이 계속 작동함을 의미합니다. 

"3의 2" 공식이 유용할 수 있지만 **이 단순화는 오해의 소지가 있을 수 있습니다**.

1. 데이터베이스를 선택하는 것은 쉽지 않습니다. CAP 정리에만 근거하여 선택을 정당화하는 것만으로는 충분하지 않습니다. 예를 들어, 기업들이 단순히 AP 시스템이라는 이유만으로 채팅 애플리케이션을 위해 Cassandra를 선택하지는 않습니다. 카산드라가 채팅 메시지 저장을 위한 바람직한 옵션이 될 수 있는 여러 가지 좋은 특성들이 있습니다. 더 자세히 살펴볼 필요가 있습니다.

2. "CAP는 설계 공간의 극히 일부만 허용합니다. 즉, 드물게 파티션이 존재할 때 완벽한 가용성과 일관성을 보장합니다." 논문에서 인용: CAP 12년 후: "규칙"이 어떻게 바뀌었는지.

3. 이 정리는 가용성과 일관성이 약 100%라는 것입니다. 보다 현실적인 논의는 네트워크 파티션이 없을 때 지연 시간과 일관성 사이의 절충안입니다. 자세한 내용은 PACELC 정리를 참조하세요.

**CAP 정리가 실제로 유용한가요?**

일련의 트레이드오프에 대한 논의를 시작한다는 점에서 여전히 유용하다고 생각하지만, 이는 이야기의 일부일 뿐입니다. 올바른 데이터베이스를 선택하려면 더 깊이 파고들어야 합니다.

### Types of Memory and Storage
> 메모리 및 스토리지 유형

<p>
  <img src="images/Types_of_Memory_and_Storage.jpeg" style="width: 420px" />
</p>


### Visualizing a SQL query

<p>
  <img src="images/sql-execution-order.jpg" style="width: 580px" />
</p>

SQL 문은 데이터베이스 시스템에서 다음과 같은 여러 단계로 실행됩니다: 

- SQL 구문 분석 및 유효성(validity) 확인 
- SQL을 관계형 대수 등의 내부 표현으로 변환하기(Transforming) 
- 내부 표현을 최적화하고 인덱스 정보를 활용하는 실행 계획 만들기 
- 실행 계획 실행 및 결과 반환 

SQL 실행은 매우 복잡하며 다음과 같은 많은 고려 사항을 포함합니다: 

- 인덱스 및 캐시 사용 
- 테이블 조인 순서 
- 동시성 제어(Concurrency control)
- 트랜잭션 관리(Transaction management)


### SQL language 
> SQL 언어 

1986년, SQL(구조화된 쿼리 언어)이 표준이 되었습니다. 그 후 40년 동안 관계형 데이터베이스 관리 시스템의 주요 언어가 되었습니다. 최신 표준(ANSI SQL 2016)을 읽는 데는 많은 시간이 소요될 수 있습니다. 어떻게 배울 수 있을까요? 

<p>
  <img src="images/how-to-learn-sql.jpg" />
</p>

SQL 언어에는 5가지 구성 요소가 있습니다: 

- DDL: 데이터 정의 언어(예: CREATE, ALTER, DROP) 
- DQL: SELECT와 같은 데이터 쿼리 언어 
- DML: INSERT, UPDATE, DELETE와 같은 데이터 조작 언어 
- DCL: 데이터 제어 언어(예: GRANT, REVOKE) 
- TCL: 커밋, 롤백 등의 트랜잭션 제어 언어 

백엔드 엔지니어의 경우 대부분을 알아야 할 수 있습니다. 데이터 분석가라면 DQL을 잘 이해하고 있어야 할 수도 있습니다. 자신에게 가장 관련성이 높은 주제를 선택하세요. 

## Cache
> 캐시

### Data is cached everywhere
> 데이터는 어디에나 캐시됩니다.

이 다이어그램은 일반적인 아키텍처에서 데이터를 캐시하는 위치를 보여줍니다.

<p>
  <img src="images/where do we cache data.jpeg" style="width: 720px" />
</p>


흐름을 따라 **여러 레이어(multiple layers**가 있습니다.

1. **클라이언트 앱(Client apps)**: HTTP 응답은 브라우저에 의해 캐시될 수 있습니다. HTTP를 통해 데이터를 처음 요청하면 HTTP 헤더에 만료 정책과 함께 반환되며, 데이터를 다시 요청하면 클라이언트 앱은 브라우저 캐시에서 데이터를 먼저 검색하려고 시도합니다.
2. **CDN**: CDN은 정적 웹 리소스를 캐시합니다. 클라이언트는 근처의 CDN 노드에서 데이터를 검색할 수 있습니다.
3. **로드 밸런서(Load Balancer)**: 로드 밸런서는 리소스도 캐시할 수 있습니다.
4. **메시징 인프라(Messaging infra)**: 메시지 브로커가 먼저 디스크에 메시지를 저장한 다음 소비자는 자신의 속도에 맞춰 메시지를 검색합니다. 보존 정책에 따라 데이터는 일정 기간 동안 Kafka 클러스터에 캐시됩니다.
5. **서비스(Services)**: 서비스에는 여러 계층의 캐시가 있습니다. 데이터가 CPU 캐시에 캐시되지 않은 경우, 서비스는 메모리에서 데이터를 검색하려고 시도합니다. 때때로 서비스에는 디스크에 데이터를 저장하는 두 번째 수준의 캐시가 있습니다.
6. **분산 캐시(Distributed Cache)**: Redis와 같은 분산 캐시는 메모리에 여러 서비스에 대한 키-값 쌍을 보유합니다. 데이터베이스보다 훨씬 뛰어난 읽기/쓰기 성능을 제공합니다.
7. **전체 텍스트 검색(Full-text Search)**: 문서 검색이나 로그 검색을 위해 Elastic Search와 같은 전체 텍스트 검색을 사용해야 할 때가 있습니다. 데이터 사본도 검색 엔진에 색인됩니다.
8. **데이터베이스(Database)**: 데이터베이스에도 다양한 수준의 캐시가 있습니다:
- **WAL(Write-ahead Log)**: B 트리 인덱스를 구축하기 전에 데이터가 먼저 WAL에 기록됩니다.
- **버퍼풀(Bufferpool)**: 쿼리 결과를 캐시하기 위해 할당된 메모리 영역
- **구체화된 보기(Materialized View)**: 쿼리 결과를 미리 계산하여 데이터베이스 테이블에 저장하여 쿼리 성능을 향상시킵니다.
- **트랜잭션 로그(Transaction log)**: 모든 트랜잭션 및 데이터베이스 업데이트 기록
- **복제 로그(Replication log)**: 데이터베이스 클러스터의 복제 상태를 기록하는 데 사용됩니다.

### Why is Redis so fast? 
> Redis가 왜 그렇게 빠른가요? 

아래 다이어그램에 표시된 것처럼 3가지 주요 이유가 있습니다.

<p>
  <img src="images/why_redis_fast.jpeg" />
</p>


1. Redis는 RAM 기반 데이터 저장소입니다. RAM 액세스는 임의 디스크 액세스보다 최소 1000배 이상 빠릅니다.
2. Redis는 실행 효율성을 위해 IO 멀티플렉싱과 단일 스레드 실행 루프를 활용합니다.
3. Redis는 몇 가지 효율적인 하위 수준 데이터 구조를 활용합니다.

질문: 또 다른 인기 있는 인메모리 저장소는 Memcached입니다. Redis와 Memcached의 차이점을 알고 계신가요?

이 다이어그램의 스타일이 이전 게시물과 다르다는 것을 눈치채셨을 것입니다. 어떤 것을 선호하시는지 알려주세요.

### How can Redis be used?
> Redis는 어떻게 사용할 수 있나요?

<p>
  <img src="images/top-redis-use-cases.jpg" style="width: 520px" />
</p>


Redis에는 단순한 캐싱 이상의 기능이 있습니다. 

Redis는 다이어그램과 같이 다양한 시나리오에서 사용할 수 있습니다. 

- 세션(Session)

  Redis를 사용하여 여러 서비스 간에 사용자 세션 데이터를 공유할 수 있습니다. 

- 캐시(Cache)

  Redis를 사용하여 객체나 페이지, 특히 핫스팟 데이터를 캐시할 수 있습니다. 

- 분산 잠금(Distributed lock )

  Redis 문자열을 사용하여 분산 서비스 간에 잠금을 획득할 수 있습니다. 

- 카운터(Counter) 

  '좋아요' 수 또는 기사 읽기 횟수를 계산할 수 있습니다. 

- 속도 제한기(Rate limiter)

  특정 사용자 IP에 대해 속도 제한기를 적용할 수 있습니다. 

- 글로벌 ID 생성기(Global ID generator)

  글로벌 ID에 Redis Int를 사용할 수 있습니다. 

- 쇼핑 카트(Shopping cart)

  장바구니의 키-값 쌍을 표현하기 위해 Redis Hash를 사용할 수 있습니다. 

- 사용자 리텐션 계산(Calculate user retention) 

  비트맵을 사용하여 매일 사용자 로그인을 표시하고 사용자 리텐션을 계산할 수 있습니다. 

- 메시지 큐(Message queue)

  메시지 대기열에 리스트를 사용할 수 있습니다. 

- 랭킹(Ranking)

  ZSet을 사용하여 문서를 정렬할 수 있습니다. 


### Top caching strategies
> 상위 캐싱 전략

대규모 시스템을 설계할 때는 일반적으로 캐싱을 신중하게 고려해야 합니다. 
다음은 자주 사용되는 5가지 캐싱 전략입니다. 

<p>
  <img src="images/top_caching_strategy.jpeg" style="width: 680px" />
</p>


***
## Microservice architecture
> 마이크로서비스 아키텍처

### What does a typical microservice architecture look like? 
> 일반적인 마이크로서비스 아키텍처는 어떤 모습일까요? 

<p>
  <img src="images/typical-microservice-arch.jpg" style="width: 520px" />
</p>

아래 다이어그램은 일반적인 마이크로서비스 아키텍처를 보여줍니다. 

- **로드 밸런서(Load Balancer)**: 들어오는 트래픽을 여러 백엔드 서비스에 분산합니다. 
- **CDN(Content Delivery Network, 콘텐츠 전송 네트워크)**: CDN은 더 빠른 전송을 위해 정적 콘텐츠를 보관하는 지리적으로 분산된 서버 그룹입니다. 클라이언트는 먼저 CDN에서 콘텐츠를 찾은 다음 백엔드 서비스로 진행합니다.
- **API 게이트웨이(API Gateway)**: 들어오는 요청을 처리하고 관련 서비스로 라우팅합니다. ID 공급자 및 서비스 검색과 통신합니다.
- **ID 공급자(Identity Provider)**: 사용자에 대한 인증 및 권한 부여를 처리합니다. 
- **서비스 등록 및 검색(Service Registry & Discovery)**: 마이크로서비스 등록 및 검색은 이 컴포넌트에서 이루어지며, API 게이트웨이는 이 컴포넌트에서 대화할 관련 서비스를 찾습니다. 
- **관리(Management)**: 이 구성 요소는 서비스 모니터링을 담당합니다.
- **마이크로서비스(Microservices)**: 마이크로서비스는 서로 다른 도메인에서 설계 및 배포됩니다. 각 도메인에는 자체 데이터베이스가 있습니다. API 게이트웨이는 REST API 또는 기타 프로토콜을 통해 마이크로서비스와 통신하고, 동일한 도메인 내의 마이크로서비스는 RPC(원격 프로시저 호출, Remote Procedure Call)를 사용하여 서로 통신합니다.


마이크로서비스의 장점:

- 신속하게 설계, 배포 및 수평적 확장이 가능합니다.
- 각 도메인은 전담 팀에서 독립적으로 유지 관리할 수 있습니다.
- 각 도메인에서 비즈니스 요구 사항을 사용자 지정할 수 있으며 결과적으로 더 나은 지원을 받을 수 있습니다.

### Microservice Best Practices
> 마이크로서비스 모범 사례

사진 한 장이 천 마디 말보다 낫습니다: 마이크로서비스 개발을 위한 9가지 모범 사례.

<p>
  <img src="images/microservice-best-practices.jpeg" />
</p>

마이크로서비스를 개발할 때는 다음과 같은 모범 사례를 따라야 합니다: 

1. 각 마이크로서비스에 대해 별도의 데이터 저장소 사용 
2. 코드의 완성도를 비슷한 수준으로 유지 
3. 각 마이크로서비스에 대해 별도의 빌드 
4. 각 마이크로서비스에 단일 책임(single responsibility) 할당 
5. 컨테이너 배포 
6. 상태 비저장 서비스(stateless services ) 설계 
7. 도메인 중심 설계(domain-driven design) 채택
8. 마이크로 프론트엔드 설계 
9. 마이크로 서비스 오케스트레이션 

### What tech stack is commonly used for microservices?
> 마이크로서비스에는 일반적으로 어떤 기술 스택이 사용되나요?

아래에서 개발 단계와 프로덕션 단계의 마이크로서비스 기술 스택을 보여주는 다이어그램을 확인할 수 있습니다.

<p>
  <img src="images/microservice-tech.jpeg" />
</p>


▶️ 𝐏𝐫𝐞-𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧

- **API 정의(Define API)** - 프론트엔드와 백엔드 간의 계약을 설정합니다. 이를 위해 Postman 또는 OpenAPI를 사용할 수 있습니다.
- **개발(Development)** - 프론트엔드 개발에는 Node.js 또는 react가, 백엔드 개발에는 자바/파이썬/go가 많이 사용됩니다. 또한 API 정의에 따라 API 게이트웨이의 구성을 변경해야 합니다.
- **지속적 통합(Continuous Integration)** - 자동화된 테스트를 위한 JUnit과 Jenkins. 코드는 Docker 이미지로 패키징되어 마이크로서비스로 배포됩니다.

▶️ 𝐏𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧
- NGinx는 로드 밸런서를 위한 일반적인 선택입니다. Cloudflare는 CDN(콘텐츠 전송 네트워크)을 제공합니다. 
- **API 게이트웨이** - 게이트웨이에 스프링 부트를 사용하고, 서비스 검색에 Eureka/Zookeeper를 사용할 수 있습니다.
- 마이크로서비스는 클라우드에 배포됩니다. AWS, Microsoft Azure 또는 Google GCP 중에서 선택할 수 있습니다.
캐시 및 전체 텍스트 검색 - 키-값 쌍을 캐싱하는 데는 Redis가 일반적으로 선택됩니다. 전체 텍스트 검색에는 Elasticsearch가 사용됩니다.
- **통신(Communications)** - 서비스들이 서로 통신하기 위해 메시징 인프라 Kafka 또는 RPC를 사용할 수 있습니다.
- **지속성(Persistence)** - 관계형 데이터베이스에는 MySQL 또는 PostgreSQL을, 객체 저장소에는 Amazon S3를 사용할 수 있습니다. 필요한 경우 와이드 컬럼 스토어에 Cassandra를 사용할 수도 있습니다.
- **관리 및 모니터링(Management & Monitoring)** - 수많은 마이크로서비스를 관리하기 위해 일반적인 운영 도구로는 Prometheus, Elastic Stack, Kubernetes 등이 있습니다.

### Why is Kafka fast
> Kafka가 빠른 이유

Kafka의 성능에 기여한 많은 설계 결정이 있습니다. 이 글에서는 두 가지에 초점을 맞추겠습니다. 이 두 가지가 가장 큰 비중을 차지했다고 생각합니다.

<p>
  <img src="images/why_is_kafka_fast.jpeg" />
</p>

1. 첫 번째는 순차적 I/O에 대한 카프카의 의존도입니다.
2. 두 번째는 효율성에 중점을 둔 설계 선택, 즉 제로 카피 원칙입니다.
 
이 다이어그램은 생산자와 소비자 간에 데이터가 전송되는 방식과 제로 카피가 무엇을 의미하는지 설명합니다.
 
- 1.1 - 1.3단계: 생산자가 디스크에 데이터 쓰기 

- 2단계: 소비자가 제로 카피 없이 데이터 읽기
  - 2.1 데이터가 디스크에서 OS 캐시로 로드됩니다.
  - 2.2 데이터가 OS 캐시에서 Kafka 애플리케이션으로 복사됩니다.
  - 2.3 Kafka 애플리케이션이 데이터를 소켓 버퍼에 복사합니다. 
  - 2.4 데이터가 소켓 버퍼에서 네트워크 카드로 복사됩니다.
  - 2.5 네트워크 카드가 소비자에게 데이터를 전송합니다.

- 3단계: 소비자(Consumer)가 제로 카피로 데이터 읽기
  - 3.1: 데이터가 디스크에서 OS 캐시로 로드됩니다.
  - 3.2 OS 캐시는 sendfile() 명령을 통해 데이터를 네트워크 카드에 직접 복사합니다.
  - 3.3 네트워크 카드가 소비자에게 데이터를 보냅니다.
 
제로 카피는 애플리케이션 컨텍스트와 커널 컨텍스트 사이에 여러 데이터 복사본을 저장하는 지름길입니다.

***

## Payment systems
> 결제 시스템

### How to learn payment systems?
> 결제 시스템을 배우는 방법

<p>
  <img src="images/learn-payments.jpg" />
</p>

###  Why is the credit card called “the most profitable product in banks”? How does VISA/Mastercard make money? 
> 신용카드를 "은행에서 가장 수익성이 높은 상품"이라고 부르는 이유는 무엇인가요? 비자/마스터카드는 어떻게 수익을 창출하나요? 

아래 도표는 신용카드 결제 흐름의 경제성을 보여줍니다.

<p>
  <img src="images/how does visa makes money.jpg" style="width: 640px" />
</p>

1. 카드 소지자가 제품을 구매하기 위해 판매자에게 $100를 지불합니다.

2. 판매자는 판매량이 많은 신용카드를 사용하여 이익을 얻고 결제 서비스 제공에 대해 발급사와 카드 네트워크에 보상을 해야 합니다. 매입 은행은 "가맹점 할인 수수료"라고 하는 수수료를 판매자와 설정합니다.

매입 은행은 매입 수수료로 0.25달러를 유지하고, 1.75달러는 교환 수수료로 발급 은행에 지불합니다. 판매자 할인 수수료는 교환 수수료를 충당해야 합니다. 

  각 발급 은행이 각 판매자와 수수료를 협상하는 것이 효율적이지 않기 때문에 교환 수수료는 카드 네트워크에서 설정합니다.

5. 카드 네트워크는 각 은행과 네트워크 평가 및 수수료를 설정하며, 은행은 매월 카드 네트워크에 서비스 비용을 지불합니다. 예를 들어 VISA는 모든 스와이프에 대해 0.11%의 평가 수수료와 $0.0195의 사용 수수료를 부과합니다.

6. 카드 소지자가 발급 은행에 서비스 비용을 지불합니다.

발급 은행이 보상을 받아야 하는 이유는 무엇입니까?

- 카드 소지자가 발급사에 대금을 지불하지 않더라도 발급사는 판매자에게 대금을 지불합니다. 
- 카드 소지자가 발급사에 대금을 지불하기 전에 발급사가 판매자에게 대금을 지불합니다.
- 발급사는 고객 계정 관리, 명세서 제공, 사기 탐지, 위험 관리, 청산 및 정산 등 기타 운영 비용이 있습니다. 

### How does VISA work when we swipe a credit card at a merchant’s shop?
> 판매자 상점에서 신용카드를 스와이프할 때 VISA는 어떻게 작동하나요?

<p>
  <img src="images/visa_payment.jpeg" />
</p>


비자, 마스터카드, 아메리칸 익스프레스는 자금 청산 및 정산을 위한 카드 네트워크 역할을 합니다. 카드 매입 은행과 카드 발급 은행은 서로 다를 수 있으며, 종종 서로 다른 경우가 있습니다. 은행이 중개자 없이 하나씩 거래를 정산한다면, 각 은행은 다른 모든 은행과 거래를 정산해야 합니다. 이는 매우 비효율적입니다.   
 
아래 다이어그램은 신용카드 결제 프로세스에서 VISA의 역할을 보여줍니다. 두 가지 흐름이 관련되어 있습니다. 승인 흐름은 고객이 신용카드를 스와이프할 때 발생합니다. 매입 및 정산 흐름은 판매자가 하루가 끝날 때 돈을 받기를 원할 때 발생합니다.
 
- 승인 흐름

0단계: 카드 발급 은행에서 고객에게 신용카드를 발급합니다. 
 
1단계: 카드 소지자가 제품을 구매하고자 하는 경우 판매자의 매장에 있는 POS(Point of Sale) 단말기에서 신용카드를 스와이프합니다.
 
2단계: POS 단말기는 POS 단말기를 제공한 매입 은행으로 거래를 전송합니다.
 
3단계 및 4단계: 매입 은행이 거래를 카드 네트워크(카드 시스템이라고도 함)로 보냅니다. 카드 네트워크는 승인을 위해 거래를 발급 은행으로 보냅니다.
 
4.1단계, 4.2단계 및 4.3단계: 거래가 승인되면 발급 은행에서 자금을 동결합니다. 승인 또는 거부는 매입자 및 POS 단말기로 다시 전송됩니다. 
 
- 매입 및 정산 흐름

1단계 및 2단계: 판매자는 하루가 끝날 때 돈을 받기를 원하므로 POS 단말기에서 '매입'을 누릅니다. 거래가 매입자에게 일괄적으로 전송됩니다. 매입자는 거래가 포함된 배치 파일을 카드 네트워크에 보냅니다.
 
3단계: 카드 네트워크는 여러 매입자로부터 수집된 거래에 대해 청산을 수행하고 청산 파일을 여러 발급 은행으로 보냅니다.
 
4단계: 발급 은행은 청산 파일의 정확성을 확인하고 관련 매입 은행에 자금을 이체합니다.
 
5단계: 매입 은행이 판매자의 은행으로 금액을 이체합니다. 
 
4단계: 카드 네트워크에서 여러 매입 은행의 거래를 청산합니다. 청산은 상호 상계된 거래가 상쇄되는 과정이므로 총 거래 건수가 줄어듭니다.
 
이 과정에서 카드 네트워크는 각 은행과 대화해야 하는 부담을 떠안고 그 대가로 서비스 수수료를 받습니다.


### Payment Systems Around The World Series (Part 1): Unified Payments Interface (UPI) in India
> 전 세계의 결제 시스템 시리즈(1부): 인도의 통합 결제 인터페이스(UPI)

UPI란 무엇인가요? UPI는 인도 국립결제공사에서 개발한 실시간 즉시 결제 시스템입니다.

현재 인도에서 디지털 소매 거래의 60%를 차지합니다.

UPI = payment markup language + standard for interoperable payments
> UPI = 결제 마크업 언어 + 상호 운용 가능한 결제 표준

<p>
  <img src="images/how-does-upi-work.png"  style="width: 600px" />
</p>

***

## DevOps

###  DevOps vs. SRE vs. Platform Engineering. What is the difference?
> 데브옵스 대 SRE 대 플랫폼 엔지니어링. 차이점은 무엇인가요?

데브옵스, SRE 및 플랫폼 엔지니어링의 개념은 서로 다른 시기에 등장했으며 다양한 개인과 조직에 의해 발전해 왔습니다. 

<p>
  <img src="images/devops-sre-platform.jpg" />
</p>

데브옵스라는 개념은 2009년 애자일 컨퍼런스에서 패트릭 드보이스와 앤드류 셰퍼에 의해 소개되었습니다. 이들은 전체 소프트웨어 개발 수명 주기에 대한 협업 문화와 공동 책임을 장려함으로써 소프트웨어 개발과 운영 간의 격차를 해소하고자 했습니다. 

SRE(사이트 안정성 엔지니어링)는 대규모의 복잡한 시스템을 관리할 때 발생하는 운영상의 문제를 해결하기 위해 2000년대 초에 Google이 개척한 개념입니다. Google은 서비스의 안정성과 효율성을 개선하기 위해 Borg 클러스터 관리 시스템 및 Monarch 모니터링 시스템과 같은 SRE 관행과 도구를 개발했습니다. 

플랫폼 엔지니어링은 SRE 엔지니어링의 토대 위에 구축된 보다 최근의 개념입니다. 플랫폼 엔지니어링의 정확한 기원은 명확하지 않지만, 일반적으로 전체 비즈니스 관점을 지원하는 제품 개발을 위한 포괄적인 플랫폼을 제공하는 데 중점을 두고 DevOps 및 SRE 관행을 확장한 것으로 이해됩니다. 

이러한 개념이 서로 다른 시기에 등장했다는 점에 주목할 필요가 있습니다. 이 개념들은 모두 소프트웨어 개발 및 운영에서 협업, 자동화 및 효율성을 개선하는 광범위한 트렌드와 관련이 있습니다. 

### What is k8s (Kubernetes)?
>  K8s(쿠버네티스)란 무엇인가요?

K8s는 컨테이너 오케스트레이션 시스템(container orchestration system)입니다. 컨테이너 배포 및 관리에 사용됩니다. 이 시스템의 설계는 Google의 내부 시스템인 Borg의 영향을 많이 받았습니다.

<p>
  <img src="images/k8s.jpeg" style="width: 680px" />
</p>

k8s 클러스터는 컨테이너화된 애플리케이션을 실행하는 노드라고 하는 일련의 워커 머신으로 구성됩니다. 모든 클러스터에는 하나 이상의 워커 노드가 있습니다.

워커 노드는 애플리케이션 워크로드의 구성 요소인 파드를 호스팅합니다. 컨트롤 플레인은 클러스터의 워커 노드와 파드를 관리한다. 프로덕션 환경에서 컨트롤 플레인은 일반적으로 여러 대의 컴퓨터에서 실행되며, 클러스터는 일반적으로 여러 노드를 실행하여 내결함성과 고가용성을 제공한다.

- 컨트롤 플레인 구성 요소

1. API 서버
  API 서버는 k8s 클러스터의 모든 구성 요소와 통신합니다. 파드의 모든 작업은 API 서버와 통신하여 실행됩니다.

2. 스케줄러
  스케줄러는 파드 워크로드를 감시하고 새로 생성된 파드에 로드를 할당합니다.

3. 컨트롤러 매니저
  컨트롤러 매니저는 노드 컨트롤러, 잡 컨트롤러, 엔드포인트슬라이스 컨트롤러, 서비스어카운트 컨트롤러를 포함한 컨트롤러를 실행한다.

4. Etcd    
  etcd는 모든 클러스터 데이터에 대한 쿠버네티스의 백업 저장소로 사용되는 키-값 저장소이다.

- 노드

1. 파드
  파드는 컨테이너 그룹으로, k8s가 관리하는 가장 작은 단위입니다. 파드에는 파드 내의 모든 컨테이너에 단일 IP 주소가 적용됩니다.

2. Kubelet
  클러스터의 각 노드에서 실행되는 에이전트. 컨테이너가 파드에서 실행되도록 보장한다.

3. 큐브 프록시
  Kube-proxy는 클러스터의 각 노드에서 실행되는 네트워크 프록시이다. 서비스에서 노드로 들어오는 트래픽을 라우팅한다. 작업 요청을 올바른 컨테이너로 전달한다.

### Docker vs. Kubernetes. Which one should we use? 
> 도커와 쿠버네티스. 어떤 것을 사용해야 하나요? 

<p>
  <img src="images/docker-vs-k8s.jpg" style="width: 680px" />
</p>


Docker란 무엇인가요? 

Docker는 격리된 컨테이너에서 애플리케이션을 패키징, 배포 및 실행할 수 있는 오픈 소스 플랫폼입니다. 컨테이너화에 중점을 두어 애플리케이션과 해당 종속성을 캡슐화하는 경량 환경을 제공합니다. 

쿠버네티스란 무엇인가요? 

K8이라고도 하는 Kubernetes는 오픈 소스 컨테이너 오케스트레이션 플랫폼입니다. 노드 클러스터 전반에서 컨테이너화된 애플리케이션의 배포, 확장 및 관리를 자동화하기 위한 프레임워크를 제공합니다. 

둘은 서로 어떻게 다른가요? 

Docker: Docker는 단일 운영 체제 호스트의 개별 컨테이너 수준에서 작동합니다. 

각 호스트를 수동으로 관리해야 하며 여러 관련 컨테이너에 대한 네트워크, 보안 정책 및 스토리지를 설정하는 것이 복잡할 수 있습니다. 

Kubernetes: Kubernetes는 클러스터 수준에서 작동합니다. 여러 호스트에서 여러 컨테이너화된 애플리케이션을 관리하며 로드 밸런싱, 확장, 애플리케이션의 원하는 상태 보장 등의 작업을 자동화합니다. 

간단히 말해, Docker는 컨테이너화 및 개별 호스트에서 컨테이너를 실행하는 데 중점을 두는 반면, Kubernetes는 호스트 클러스터 전체에서 대규모로 컨테이너를 관리하고 오케스트레이션하는 데 특화되어 있습니다. 

### How does Docker work? 
Docker는 어떻게 작동하나요? 

아래 다이어그램은 Docker의 아키텍처와 "docker 빌드", "docker 풀" 
"도커 실행"을 실행할 때 어떻게 작동하는지 보여줍니다. 

<p>
  <img src="images/docker.jpg" style="width: 680px" />
</p>

Docker 아키텍처에는 3가지 구성 요소가 있습니다: 

- 도커 클라이언트 
    
    도커 클라이언트는 도커 데몬과 대화합니다. 

- 도커 호스트 

    Docker 데몬은 Docker API 요청을 수신 대기하고 이미지, 컨테이너, 네트워크, 볼륨과 같은 Docker 개체를 관리합니다. 

- Docker 레지스트리 

    Docker 레지스트리는 Docker 이미지를 저장합니다. Docker Hub는 누구나 사용할 수 있는 공용 레지스트리입니다. 

"docker run" 명령을 예로 들어 보겠습니다. 

  1. Docker가 레지스트리에서 이미지를 가져옵니다. 
  1. 도커가 새 컨테이너를 생성합니다. 
  1. 도커가 컨테이너에 읽기-쓰기 파일 시스템을 할당합니다. 
  1. 도커가 컨테이너를 기본 네트워크에 연결하기 위해 네트워크 인터페이스를 생성합니다. 
  1. 도커가 컨테이너를 시작합니다.

***
## GIT

### How Git Commands work
> Git 명령의 작동 방식

우선 코드가 저장된 위치를 파악하는 것이 중요합니다. 일반적으로 코드가 저장되는 위치는 Github와 같은 원격 서버와 로컬 컴퓨터 두 곳뿐이라고 가정합니다. 하지만 이는 완전히 정확하지 않습니다. Git은 컴퓨터에서 3개의 로컬 저장소를 유지하므로 코드가 네 곳에서 찾을 수 있습니다: 

<p>
  <img src="images/git-commands.png" style="width: 600px" />
</p>


- 작업 디렉터리: 파일을 편집하는 위치 
- 스테이징 영역: 다음 커밋을 위해 파일을 보관하는 임시 위치 
- 로컬 리포지토리: 커밋한 코드가 들어 있는 곳 
- 원격 리포지토리: 코드를 저장하는 원격 서버 

대부분의 Git 명령은 주로 이 네 위치 사이에서 파일을 이동한다. 

### How does Git Work?
> Git은 어떻게 작동하나요?

아래 다이어그램은 Git 워크플로우를 보여줍니다. 

<p>
  <img src="images/git-workflow.jpeg" style="width: 520px" />
</p>


Git은 분산 버전 제어 시스템(a distributed version control system)입니다. 

모든 개발자는 메인 리포지토리의 로컬 복사본을 유지 관리하고 로컬 복사본을 편집하고 커밋합니다. 

작업은 원격 리포지토리와 상호 작용하지 않기 때문에 커밋이 매우 빠릅니다. 

원격 리포지토리에 충돌이 발생하면 로컬 리포지토리에서 파일을 복구할 수 있습니다. 

### Git merge vs. Git rebase
>  Git 병합과 Git 리베이스 비교

어떤 차이점이 있나요?

<p>
  <img src="images/git-merge-git-rebase.jpeg" style="width: 680px" />
</p>


한 Git 브랜치에서 다른 브랜치로 변경 사항을 Merge할 때는 'git merge' 또는 'git rebase'를 사용할 수 있습니다. 아래 다이어그램은 두 명령의 작동 방식을 보여줍니다.

**Git merge**

이렇게 하면 메인 브랜치에 새 커밋 G' 가 생성됩니다. G'는 메인 브랜치와 피처 브랜치의 히스토리를 모두 연결한다.

Git Merge는 **비파괴적**이다. 메인 브랜치나 피처 브랜치 모두 변경되지 않는다.

**Git 리베이스

Git 리베이스는 피처 브랜치 히스토리를 메인 브랜치의 헤드로 이동한다. 피처 브랜치의 각 커밋에 대해 새로운 커밋 E', F', G' 를 생성한다.

리베이스의 장점은 선형적인 **커밋 히스토리**가 있다는 것입니다.

리베이스는 "git 리베이스의 황금률"을 따르지 않으면 위험할 수 있습니다.

**깃 리베이스의 황금률**은 다음과 같다.

퍼블릭 브랜치에서는 절대 사용하지 마세요!

***
## Cloud Services
> 클라우드 서비스

### A nice cheat sheet of different cloud services (2023 edition)
> 다양한 클라우드 서비스에 대한 유용한 치트 시트(2023년판)

<p>
  <img src="images/cloud-compare.jpg" />
</p>


### What is cloud native?
> 클라우드 네이티브란 무엇인가요?

아래는 1980년대 이후 아키텍처와 프로세스의 진화를 보여주는 다이어그램입니다. 

<p>
  <img src="images/cloud-native.jpeg" style="width: 640px" />
</p>

조직은 클라우드 네이티브 기술을 사용하여 퍼블릭, 프라이빗, 하이브리드 클라우드에서 확장 가능한 애플리케이션을 빌드하고 실행할 수 있습니다. 

즉, 애플리케이션이 클라우드 기능을 활용하도록 설계되었으므로 로드에 대한 탄력성이 뛰어나고 확장이 용이합니다. 

클라우드 네이티브에는 4가지 측면이 있습니다: 

1. 개발 프로세스 
  워터폴에서 애자일, 데브옵스로 발전해 왔습니다. 

2. 애플리케이션 아키텍처 
  아키텍처는 모놀리식 서비스에서 마이크로 서비스로 발전했습니다. 각 서비스는 클라우드 컨테이너의 제한된 리소스에 적응할 수 있도록 소규모로 설계되었습니다. 

3. 배포 및 패키징 
  예전에는 애플리케이션을 물리적 서버에 배포했습니다. 그러다가 2000년경에는 지연 시간에 민감하지 않은 애플리케이션은 보통 가상 서버에 배포되었습니다. 클라우드 네이티브 애플리케이션을 사용하면 도커 이미지로 패키징되어 컨테이너에 배포됩니다. 

4. 애플리케이션 인프라 
  애플리케이션은 자체 호스팅 서버가 아닌 클라우드 인프라에 대규모로 배포됩니다. 

## Developer productivity tools
> 개발자 생산성 도구

### Visualize JSON files
> JSON 파일 시각화

중첩된 JSON 파일은 읽기 어렵습니다.

**JsonCrack**은 JSON 파일에서 그래프 다이어그램을 생성하여 읽기 쉽게 만듭니다.

또한 생성 된 다이어그램을 이미지로 다운로드 할 수 있습니다.

<p>
  <img src="images/json-cracker.jpeg" />
</p>


### Automatically turn code into architecture diagrams
> 코드를 아키텍처 다이어그램으로 자동 변환

<p>
  <img src="images/diagrams_as_code.jpeg" style="width: 640px" />
</p>


어떤 기능을 하나요?

- Python 코드로 클라우드 시스템 아키텍처를 그립니다.
- 다이어그램은 Jupyter 노트북 내에서 바로 렌더링할 수도 있습니다.
- 디자인 도구가 필요하지 않습니다. 
- 다음 공급자를 지원합니다: AWS, Azure, GCP, Kubernetes, Alibaba Cloud, Oracle Cloud 등. 
 
[Github repo](https://github.com/mingrammer/diagrams)

*** 

## Linux

### Linux file system explained
>  Linux 파일 시스템 설명

<p>
  <img src="images/linux-file-systems.jpg" style="width: 680px" />
</p>

리눅스 파일 시스템은 개인이 원하는 곳에 집을 짓는 무질서한 마을과 비슷했습니다. 하지만 1994년에 파일 시스템 계층 구조 표준(FHS)이 도입되어 Linux 파일 시스템에 질서가 생겼습니다.

FHS(Filesystem Hierarchy Standard)와 같은 표준을 구현함으로써 소프트웨어는 다양한 Linux 배포판에서 일관된 레이아웃을 보장할 수 있습니다. 하지만 모든 Linux 배포판이 이 표준을 엄격하게 준수하는 것은 아닙니다. 자체 고유 요소를 통합하거나 특정 요구 사항을 충족하는 경우가 많습니다.

### 18 Most-used Linux Commands You Should Know
> 알아야 할 가장 많이 사용되는 리눅스 명령어 18가지

Linux 명령은 운영체제와 상호 작용하기 위한 지침입니다. 파일, 디렉토리, 시스템 프로세스 및 기타 시스템의 여러 측면을 관리하는 데 도움이 됩니다. Linux 기반 시스템을 효율적이고 효과적으로 탐색하고 유지 관리하려면 이러한 명령에 익숙해져야 합니다. 

아래 다이어그램은 자주 사용되는 Linux 명령을 보여줍니다: 

<p>
  <img src="images/18 Most-Used Linux Commands You Should Know-01.jpeg" style="width: 680px" />
</p>

- ls - 파일 및 디렉터리 목록 
- cd - 현재 디렉터리 변경 
- mkdir - 새 디렉토리 만들기 
- rm - 파일 또는 디렉터리 제거 
- cp - 파일 또는 디렉터리 복사 
- mv - 파일 또는 디렉터리 이동 또는 이름 바꾸기 
- chmod - 파일 또는 디렉터리 권한 변경 
- grep - 파일에서 패턴 검색 
- find - 파일 및 디렉터리 검색 
- tar - 타르볼 아카이브 파일 조작 
- vi - 텍스트 편집기를 사용하여 파일 편집 
- cat - 파일 내용 표시 
- top - 프로세스 및 리소스 사용량 표시 
- ps - 프로세스 정보 표시 
- kill - 신호를 보내 프로세스를 종료합니다. 
- du - 파일 공간 사용량 추정 
- ifconfig - 네트워크 인터페이스 구성  
- ping - 호스트 간 네트워크 연결 테스트 

## Security
> 보안

### How does HTTPS work?
> HTTPS는 어떻게 작동하나요?

HTTPS(Hypertext Transfer Protocol Secure)는 하이퍼텍스트 전송 프로토콜(HTTP)의 확장입니다. HTTPS는 전송 계층 보안(TLS)을 사용하여 암호화된 데이터를 전송합니다. 온라인에서 데이터를 탈취당하면 탈취자는 바이너리 코드만 얻게 됩니다. 

<p>
  <img src="images/https.jpg" />
</p>


데이터는 어떻게 암호화되고 해독되나요?

1단계 - 클라이언트(브라우저)와 서버가 TCP 연결을 설정합니다.

2단계 - 클라이언트가 서버에 "클라이언트 헬로"를 보냅니다. 이 메시지에는 필요한 암호화 알고리즘(encryption algorithms, 암호 모음(cipher suites)) 세트와 지원할 수 있는 최신 TLS 버전이 포함되어 있습니다. 서버는 "서버 안녕하세요"로 응답하여 브라우저가 해당 알고리즘과 TLS 버전을 지원할 수 있는지 여부를 알 수 있도록 합니다.

그런 다음 서버는 SSL 인증서(certificate)를 클라이언트에 보냅니다. 인증서에는 공개 키, 호스트 이름, 만료 날짜 등이 포함됩니다. 클라이언트는 인증서의 유효성을 검사합니다. 

3단계 - SSL 인증서의 유효성을 검사한 후 클라이언트는 세션 키를 생성하고 공개 키를 사용하여 암호화합니다. 서버는 암호화된 세션 키를 수신하고 개인 키로 암호를 해독합니다. 

4단계 - 이제 클라이언트와 서버가 모두 동일한 세션 키(대칭 암호화)를 보유하므로 암호화된 데이터는 안전한 양방향 채널로 전송됩니다.

데이터 전송 중에 HTTPS가 대칭 암호화로 전환되는 이유는 무엇인가요? 두 가지 주요 이유가 있습니다:

1. 보안(Security): 비대칭 암호화는 한 방향으로만 진행됩니다. 즉, 서버가 암호화된 데이터를 클라이언트로 다시 보내려고 하면 누구나 공개 키를 사용하여 데이터를 해독할 수 있습니다.

2. 서버 리소스: 비대칭 암호화는 수학적 오버헤드가 상당히 많이 추가됩니다. 긴 세션의 데이터 전송에는 적합하지 않습니다.

### Oauth 2.0 Explained With Simple Terms. 
> 간단한 용어로 설명하는 OAuth 2.0. 

OAuth 2.0은 강력하고 안전한 프레임워크로, 여러 애플리케이션이 민감한 자격 증명을 공유하지 않고도 사용자를 대신하여 서로 안전하게 상호 작용할 수 있도록 합니다. 

<p>
  <img src="images/oAuth2.jpg" />
</p>

OAuth에 관련된 엔티티는 사용자, 서버, ID 공급자(IDP)입니다. 

OAuth 토큰은 무엇을 할 수 있나요? 

OAuth를 사용하면 신원 및 권한을 나타내는 OAuth 토큰을 받게 됩니다. 이 토큰은 몇 가지 중요한 작업을 수행할 수 있습니다: 

싱글 사인온(SSO): OAuth 토큰을 사용하면 한 번의 로그인으로 여러 서비스나 앱에 로그인할 수 있어 더욱 편리하고 안전하게 생활할 수 있습니다. 

시스템 간 인증: OAuth 토큰을 사용하면 다양한 시스템에서 인증 또는 액세스 권한을 공유할 수 있으므로 모든 곳에서 별도로 로그인할 필요가 없습니다. 

사용자 프로필 액세스: OAuth 토큰이 있는 앱은 허용한 사용자 프로필의 특정 부분에 액세스할 수 있지만 모든 것을 볼 수는 없습니다. 

OAuth 2.0은 사용자와 데이터를 안전하게 보호하는 동시에 다양한 애플리케이션과 서비스에서 원활하고 번거로움 없는 온라인 경험을 제공하는 데 중점을 두고 있습니다.

### Top 4 Forms of Authentication Mechanisms 
> 인증 메커니즘의 4가지 형태

<p>
  <img src="images/top4-most-used-auth.jpg" />
</p>

1. SSH 키: 
  암호화 키는 원격 시스템 및 서버에 안전하게 액세스하는 데 사용됩니다. 

2. OAuth 토큰:
  타사 애플리케이션에서 사용자 데이터에 대한 제한된 액세스를 제공하는 토큰 

3. SSL 인증서:  
디지털 인증서는 서버와 클라이언트 간의 안전하고 암호화된 통신을 보장합니다. 

4. 자격 증명: 
  사용자 인증 정보는 다양한 시스템 및 서비스에 대한 액세스 권한을 확인하고 부여하는 데 사용됩니다.

### Session, cookie, JWT, token, SSO, and OAuth 2.0 - what are they?
> 세션, 쿠키, JWT, 토큰, SSO 및 OAuth 2.0이란 무엇인가요?

이러한 용어는 모두 "사용자 신원 관리(user identity management)"와 관련이 있습니다. 웹사이트에 로그인할 때 사용자는 자신이 누구인지 선언합니다(식별, identification). 신원을 확인하고(인증, authentication), 필요한 권한(permissions)을 부여받습니다(권한 부여, authorization). 과거에 많은 솔루션이 제안되었으며 그 목록은 계속 늘어나고 있습니다.

<p>
  <img src="images/session.jpeg" />
</p>

간단한 것부터 복잡한 것까지, 사용자 ID 관리에 대한 저의 이해를 정리해 보았습니다:

- WWW-Authenticate는 가장 기본적인 방법입니다. 브라우저에서 사용자 이름과 비밀번호를 입력하라는 메시지가 표시됩니다. 로그인 수명 주기를 제어할 수 없기 때문에 오늘날에는 거의 사용되지 않습니다.

- 로그인 수명 주기를 보다 세밀하게 제어할 수 있는 방법은 세션 쿠키(session cookie)입니다. 서버는 세션 저장소를 유지하고 브라우저는 세션의 ID를 유지합니다. 쿠키는 일반적으로 브라우저에서만 작동하며 모바일 앱에는 적합하지 않습니다.

- 호환성 문제를 해결하기 위해 토큰을 사용할 수 있습니다. 클라이언트가 토큰을 서버로 전송하면 서버가 토큰의 유효성을 검사합니다. 단점은 토큰을 암호화하고 해독해야 하므로 시간이 오래 걸릴 수 있다는 것입니다.

- JWT는 토큰을 나타내는 표준 방식입니다. 이 정보는 디지털 서명이 되어 있기 때문에 검증되고 신뢰할 수 있습니다. JWT에는 서명이 포함되어 있으므로 서버 측에 세션 정보를 저장할 필요가 없습니다.

- SSO(싱글 사인온)를 사용하면 한 번만 로그인하면 여러 웹사이트에 로그인할 수 있습니다. CAS(중앙 인증 서비스)를 사용하여 사이트 간 정보를 유지합니다.

- OAuth 2.0을 사용하면 한 웹사이트에서 다른 웹사이트의 정보에 액세스할 수 있도록 인증할 수 있습니다.

### How to store passwords safely in the database and how to validate a password? 
> 비밀번호를 데이터베이스에 안전하게 저장하는 방법과 비밀번호의 유효성을 검사하는 방법은 무엇인가요? 

<p>
  <img src="images/salt.jpg" style="width: 720px" />
</p>

 
**하지 말아야 할 것들**

- 비밀번호를 평문(plain text)으로 저장하는 것은 내부 액세스 권한이 있는 모든 사람이 볼 수 있으므로 좋은 생각이 아닙니다.

- 비밀번호 해시를 직접 저장하는 것은 레인보우 테이블과 같은 사전 계산 공격에 노출되기 때문에 충분하지 않습니다. 

- 계산 전 공격을 완화하기 위해 비밀번호에 솔트(Salt) 처리를 합니다. 

**솔트란 무엇인가요?**

OWASP 가이드라인에 따르면 "솔트란 해싱 과정의 일부로 각 비밀번호에 추가되는 무작위로 생성된 고유한 문자열"입니다.
 
**비밀번호와 솔트는 어떻게 저장하나요?

해시 결과는 각 비밀번호마다 고유합니다.
1. 비밀번호는 해시(비밀번호 + 솔트) 형식을 사용하여 데이터베이스에 저장할 수 있습니다.

**비밀번호를 어떻게 검증하나요?**

비밀번호의 유효성을 검사하려면 다음과 같은 과정을 거칠 수 있습니다:

1. 클라이언트가 비밀번호를 입력합니다.
2. 시스템이 데이터베이스에서 해당 솔트를 가져옵니다.
3. 시스템이 비밀번호에 솔트를 추가하고 해시합니다. 해시된 값을 H1이라고 부르겠습니다.
4. 시스템은 H1과 H2를 비교합니다. 여기서 H2는 데이터베이스에 저장된 해시입니다. 둘이 같으면 비밀번호가 유효합니다. 

### Explaining JSON Web Token (JWT) to a 10 year old Kid
> 10세 어린이에게 JSON 웹 토큰(JWT) 설명하기

<p>
  <img src="images/jwt.jpg" />
</p>

JWT라는 특별한 상자가 있다고 상상해 보세요. 이 상자 안에는 헤더, 페이로드, 서명의 세 부분이 있습니다.

헤더는 상자 외부에 있는 라벨과 같습니다. 헤더는 상자의 유형과 보안 방법을 알려줍니다. 일반적으로 중괄호(`{ }`)와 콜론(`:`) 을 사용하여 정보를 구성하는 방법인 JSON이라는 형식으로 작성됩니다.

페이로드는 전송하려는 실제 메시지 또는 정보와 같습니다. 이름, 나이 또는 공유하고자 하는 기타 데이터가 될 수 있습니다. 또한 JSON 형식으로 작성되므로 이해하고 작업하기 쉽습니다.
이제 서명은 JWT를 안전하게 보호하는 역할을 합니다. 서명은 발신자만 만드는 방법을 알고 있는 특별한 도장과 같습니다. 서명은 비밀번호와 같은 비밀 코드를 사용하여 생성됩니다. 이 서명은 발신자 모르게 아무도 JWT의 내용을 변조할 수 없도록 합니다.

JWT를 서버로 보내려면 헤더, 페이로드 및 서명을 상자 안에 넣습니다. 그런 다음 서버로 전송합니다. 서버는 헤더와 페이로드를 쉽게 읽고 사용자가 누구이며 무엇을 하려는지 이해할 수 있습니다.

### How does Google Authenticator (or other types of 2-factor authenticators) work?
> Google 인증(또는 다른 유형의 2단계 인증)은 어떻게 작동하나요?

2단계 인증이 활성화된 경우 일반적으로 Google 인증서는 트위터 계정에 로그인하는 데 사용됩니다. 어떻게 보안을 보장하나요?
 
Google 인증서는 2단계 인증 서비스를 구현하는 소프트웨어 기반 인증 수단입니다. 아래 다이어그램에 자세한 내용이 나와 있습니다. 

<p>
  <img src="images/google_authenticate.jpeg" />
</p>

두 단계가 관련되어 있습니다:

- 1단계 - 사용자가 Google 2단계 인증을 사용하도록 설정합니다. 
- 2단계 - 사용자가 로그인 등에 인증기를 사용합니다.

각 단계를 살펴보겠습니다.
 
**1단계(Stage)**

1단계 및 2단계: Bob이 웹 페이지를 열어 2단계 인증을 활성화합니다. 프런트 엔드에서 비밀 키를 요청합니다. 인증 서비스는 Bob의 비밀 키를 생성하여 데이터베이스에 저장합니다.
 
3단계: 인증 서비스가 프런트엔드에 URI를 반환합니다. URI는 키 발급자, 사용자 이름 및 비밀 키로 구성됩니다. URI는 웹 페이지에 QR 코드 형태로 표시됩니다.
 
4단계: Bob은 Google 인증기를 사용하여 생성된 QR 코드를 스캔합니다. 비밀 키는 인증기에 저장됩니다.

**2단계(Stage)**
1단계 및 2단계: Bob은 Google 2단계 인증을 사용하여 웹사이트에 로그인하려고 합니다. 이를 위해서는 비밀번호가 필요합니다. 30초마다 Google 인증기는 TOTP(시간 기반 일회용 비밀번호) 알고리즘을 사용하여 6자리 비밀번호를 생성합니다. 밥은 비밀번호를 사용하여 웹사이트에 들어갑니다.
 
3단계와 4단계: 프론트엔드에서 인증을 위해 Bob이 입력한 비밀번호를 백엔드로 전송합니다. 인증 서비스는 데이터베이스에서 비밀 키를 읽고 클라이언트와 동일한 TOTP 알고리즘을 사용하여 6자리 비밀번호를 생성합니다.
 
5단계: 인증 서비스는 클라이언트와 서버에서 생성된 두 개의 비밀번호를 비교하여 비교 결과를 프론트엔드에 반환합니다. 밥은 두 비밀번호가 일치하는 경우에만 로그인 프로세스를 진행할 수 있습니다.
 
이 인증 메커니즘은 안전한가요? 

- 다른 사람이 비밀키를 알아낼 수 있나요? 

    비밀 키가 HTTPS를 사용하여 전송되는지 확인해야 합니다. 인증 클라이언트 및 데이터베이스에 비밀 키가 저장되며, 비밀 키가 암호화되어 있는지 확인해야 합니다.

- 해커가 6자리 비밀번호를 추측할 수 있나요?
    
    비밀번호는 6자리로 구성되므로 생성된 비밀번호는 100만 가지 조합이 가능합니다. 또한 비밀번호는 30초마다 변경됩니다. 해커가 30초 안에 비밀번호를 알아내려면 초당 30,000개의 조합을 입력해야 합니다.

***
##  Real World Case Studies
> 실제 사례 연구

### Netflix's Tech Stack
> 넷플릭스의 기술 스택

이 게시물은 여러 넷플릭스 엔지니어링 블로그와 오픈 소스 프로젝트의 연구를 기반으로 작성되었습니다. 부정확한 내용을 발견하시면 언제든지 알려주시기 바랍니다.

<p>
  <img src="images/netflix tech stack.png" style="width: 680px" />
</p>

- **모바일 및 웹**: 넷플릭스는 네이티브 모바일 앱을 구축하기 위해 Swift와 Kotlin을 채택했습니다. 웹 애플리케이션에는 React를 사용합니다.
- **프론트엔드/서버 통신**: 넷플릭스는 GraphQL을 사용합니다.
- **백엔드 서비스**: 넷플릭스는 ZUUL, 유레카, 스프링 부트 프레임워크 및 기타 기술을 사용합니다.
- **데이터베이스**: 넷플릭스는 EV 캐시, 카산드라, 콕로치DB 및 기타 데이터베이스를 활용합니다.
- **메시징/스트리밍**: 넷플릭스는 메시징 및 스트리밍 목적으로 Apache Kafka와 Fink를 사용합니다.
- **비디오 스토리지**: 넷플릭스는 비디오 저장을 위해 S3와 Open Connect를 사용합니다.
- **데이터 처리**: Netflix는 데이터 처리를 위해 Flink와 Spark를 사용하며, 이 데이터는 Tableau를 사용하여 시각화됩니다. 구조화된 데이터 웨어하우스 정보 처리를 위해 Redshift를 사용합니다.
- **CI/CD**: 넷플릭스는 CI/CD 프로세스를 위해 JIRA, Confluence, PagerDuty, Jenkins, Gradle, Chaos Monkey, Spinnaker, Atlas 등 다양한 도구를 사용하고 있습니다.

### Twitter Architecture 2022
> 트위터 아키텍처 2022

네, 이것이 진짜 트위터 아키텍처입니다. 엘론 머스크가 게시하고 가독성을 높이기 위해 트위터에서 다시 그린 것입니다. 

<p>
  <img src="images/twitter-arch.jpeg" />
</p>


### Evolution of Airbnb’s microservice architecture over the past 15 years
> 지난 15년간의 에어비앤비 마이크로서비스 아키텍처의 진화

에어비앤비의 마이크로서비스 아키텍처는 크게 세 가지 단계를 거쳤습니다. 

<p>
  <img src="images/airbnb_arch.jpeg" />
</p>

#### 모노리스(2008~2017년)

에어비앤비는 호스트와 게스트를 위한 단순한 마켓플레이스에서 시작되었습니다. 이 마켓플레이스는 "루비 온 레일즈 애플리케이션인 모놀리스(Ruby on Rails application - the monolith)"로 구축되었습니다. 

도전 과제는 무엇이었을까요?

- 혼란스러운(Confusing) 팀 소유권 + 소유권 없는 코드
- 느린 배포 

#### 마이크로서비스(2017 - 2020)

마이크로서비스는 이러한 문제를 해결하는 것을 목표로 합니다. 마이크로서비스 아키텍처의 주요 서비스는 다음과 같습니다:

- 데이터 가져오기 서비스
- 비즈니스 로직 데이터 서비스
- 워크플로 작성 서비스
- UI 집계 서비스
- 각 서비스에는 하나의 소유 팀이 있습니다.

도전 과제는 무엇이었나요?

수백 개의 서비스와 종속성을 사람이 관리하기 어려웠습니다.

#### 마이크로 서비스 + 매크로 서비스(2020년 - 현재)

현재 에어비앤비는 이 문제를 해결하기 위해 노력하고 있습니다. 마이크로 및 매크로 서비스 하이브리드 모델은 API 통합에 중점을 두고 있습니다.


### Monorepo vs. Microrepo. 
> 모노레포 대 마이크로레포. 

어떤 것이 가장 좋을까요? 회사마다 다른 옵션을 선택하는 이유는 무엇일까요? 

<p>
  <img src="images/monorepo-microrepo.jpg" />
</p>

모노레포는 새로운 것이 아니며 Linux와 Windows 모두 모노레포를 사용하여 만들어졌습니다. 확장성과 빌드 속도를 개선하기 위해 Google은 내부 전용 툴체인을 개발하여 더 빠르게 확장하고 엄격한 코딩 품질 표준을 적용하여 일관성을 유지했습니다. 

Amazon과 Netflix는 마이크로서비스 철학의 주요 홍보대사입니다. 이 접근 방식은 서비스 코드를 별도의 리포지토리로 자연스럽게 분리합니다. 확장 속도는 빠르지만 나중에 거버넌스 문제가 발생할 수 있습니다. 

Monorepo 내에서 각 서비스는 폴더이며, 모든 폴더에는 빌드 구성 및 소유자 권한 제어가 있습니다. 모든 서비스 구성원은 자신의 폴더에 대한 책임이 있습니다. 

반면, Microrepo에서는 각 서비스가 리포지토리에 대한 책임이 있으며, 일반적으로 전체 리포지토리에 대한 빌드 구성 및 권한이 설정됩니다. 

Monorepo에서는 비즈니스에 관계없이 전체 코드베이스에서 종속성이 공유되므로 버전 업그레이드가 있을 때 모든 코드베이스가 해당 버전을 업그레이드합니다. 

Microrepo에서는 종속성이 각 리포지토리 내에서 제어됩니다. 기업은 자체 일정에 따라 버전을 업그레이드할 시기를 선택합니다. 

모노레포에는 체크인에 대한 표준이 있습니다. Google의 코드 검토 프로세스는 높은 기준을 설정하는 것으로 유명하며, 비즈니스에 관계없이 일관된 품질 표준을 보장하는 것으로 잘 알려져 있습니다. 

Microrepo는 자체 표준을 설정하거나 모범 사례를 통합하여 공유 표준을 채택할 수 있습니다. 비즈니스에 맞게 더 빠르게 확장할 수 있지만 코드 품질은 약간 다를 수 있습니다. 
Google 엔지니어는 Bazel을 만들었고 Meta는 Buck을 만들었습니다. Nix, Lerna 등 다른 오픈 소스 도구도 사용할 수 있습니다. 

지난 몇 년 동안 Microrepo는 Java용 Maven과 Gradle, NodeJS용 NPM, C/C++용 CMake 등 더 많은 도구를 지원해 왔습니다. 

### How will you design the Stack Overflow website? 
> 스택 오버플로 웹사이트를 어떻게 디자인하시겠습니까? 

온프레미스 서버와 모놀리스(다음 이미지 하단)라고 답하면 면접에서 떨어질 가능성이 높지만, 실제로는 그렇게 구축됩니다!

<p>
  <img src="images/stackoverflow.jpg" />
</p>


####  **사람들이 생각하는 모습**

면접관은 아마도 그림의 상단 부분과 같은 모습을 기대하고 있을 것입니다.

- 마이크로서비스는 시스템을 작은 구성 요소로 분해하는 데 사용됩니다.
- 각 서비스에는 자체 데이터베이스가 있습니다. 캐시를 많이 사용합니다.
- 서비스가 샤딩됩니다.
- 서비스는 메시지 큐를 통해 비동기적으로 서로 통신합니다.
- 이벤트 소싱과 CQRS를 사용하여 서비스를 구현합니다.
- 최종 일관성, CAP 정리 등과 같은 분산 시스템에 대한 지식을 보여줍니다.

#### **실제 내용**

스택 오버플로는 단 9대의 온프레미스 웹 서버로 모든 트래픽을 처리하며, 모놀리스로 운영됩니다! 자체 서버를 보유하고 있으며 클라우드에서 실행되지 않습니다.

이는 오늘날의 모든 통념과 상반되는 것입니다. 

### Why did Amazon Prime Video monitoring move from serverless to monolithic? How can it save 90% cost?
>  아마존 프라임 비디오 모니터링이 서버리스에서 모놀리식으로 전환된 이유는 무엇인가요? 어떻게 90%의 비용을 절감할 수 있을까요?

아래 다이어그램은 마이그레이션 전과 후의 아키텍처 비교를 보여줍니다. 

<p>
  <img src="images/serverless-to-monolithic.jpeg" />
</p>

Amazon Prime Video 모니터링 서비스란 무엇인가요? 

프라임 비디오 서비스는 수천 개의 라이브 스트림의 품질을 모니터링해야 합니다. 모니터링 도구는 실시간으로 스트림을 자동으로 분석하고 블록 손상, 동영상 정지 및 동기화 문제와 같은 품질 문제를 식별합니다. 이는 고객 만족을 위한 중요한 프로세스입니다. 

미디어 변환기, 결함 검출기, 실시간 알림의 3단계로 구성됩니다. 

- 기존 아키텍처의 문제점은 무엇인가요? 

  기존 아키텍처는 Amazon Lambda를 기반으로 하여 서비스를 빠르게 구축하는 데는 좋았습니다. 하지만 대규모로 아키텍처를 실행할 때는 비용 효율적이지 않았습니다. 가장 비용이 많이 드는 두 가지 작업은 다음과 같습니다: 

1. 오케스트레이션 워크플로우 - AWS 단계 함수는 상태 전환에 따라 사용자에게 요금을 부과하고 오케스트레이션은 매초마다 여러 상태 전환을 수행합니다. 

2. 분산된 구성 요소 간의 데이터 전달 - 중간 데이터는 다음 단계에서 다운로드할 수 있도록 Amazon S3에 저장됩니다. 볼륨이 크면 다운로드 비용이 많이 들 수 있습니다. 

- 모놀리식 아키텍처로 90% 비용 절감 

  모놀리식 아키텍처는 비용 문제를 해결하기 위해 설계되었습니다. 여전히 3개의 구성 요소가 있지만 미디어 컨버터와 결함 감지기가 동일한 프로세스에 배포되어 네트워크를 통해 데이터를 전달하는 비용을 절감할 수 있습니다. 놀랍게도 이러한 배포 아키텍처 변경 방식을 통해 90%의 비용을 절감할 수 있었습니다! 

마이크로서비스가 기술 업계에서 유행처럼 번지고 있는 요즘, 이 사례는 흥미롭고 독특한 사례 연구입니다. 아키텍처의 진화에 대해 더 많은 논의를 하고 장단점에 대해 더 솔직한 토론을 하고 있다는 점이 반갑습니다. 구성 요소를 분산형 마이크로서비스로 분해하려면 비용이 발생합니다. 

- 이에 대해 Amazon 리더들은 어떤 의견을 내놓았나요? 
  
  Amazon CTO Werner Vogels: "**진화 가능한 소프트웨어 시스템(evolvable software systems)**을 구축하는 것은 종교가 아니라 **전략**입니다. 그리고 열린 마음으로 아키텍처를 재검토하는 것은 필수입니다." 

전 Amazon 지속 가능성 부사장 Adrian Cockcroft: "Prime Video 팀은 제가 **서버리스 퍼스트(Serverless First)**라고 부르는 길을 따랐습니다... 저는 **서버리스 온리(Serverless Only)**를 옹호하지 않습니다.". 


### How does Disney Hotstar capture 5 Billion Emojis during a tournament?
> 디즈니 핫스타는 토너먼트 기간 동안 어떻게 50억 개의 이모티콘을 캡처할 수 있을까요?

<p>
  <img src="images/hotstar_emojis.jpeg" style="width: 720px" />
</p>


1. 클라이언트는 표준 HTTP 요청을 통해 이모티콘을 전송합니다. 골랑 서비스는 일반적인 웹 서버라고 생각하면 됩니다. 골랑을 선택한 이유는 동시성을 잘 지원하기 때문입니다. 골랑의 스레드는 가볍습니다.

2. 쓰기량이 매우 많기 때문에 버퍼로 카프카(메시지 큐)를 사용합니다.

3. 이모티콘 데이터는 Spark라는 스트리밍 처리 서비스를 통해 집계됩니다. 이 서비스는 2초마다 데이터를 집계하며, 그 주기는 설정할 수 있습니다. 이 간격에 따라 장단점이 있습니다. 간격이 짧을수록 다른 클라이언트에 이모티콘이 더 빨리 전달되지만 더 많은 컴퓨팅 리소스가 필요하다는 의미이기도 합니다.

4. 집계된 데이터는 다른 카프카에 기록됩니다. 

5. PubSub 소비자(Consumer)는 Kafka에서 집계된 이모티콘 데이터를 가져옵니다. 

6. 6. 이모티콘은 PubSub 인프라를 통해 실시간으로 다른 클라이언트에게 전달됩니다. PubSub 인프라는 흥미롭습니다. Hotstar는 다음과 같은 프로토콜을 고려했습니다: Socketio, NATS, MQTT, gRPC를 고려한 결과 MQTT로 결정했습니다.
 
초당 백만 건의 좋아요를 스트리밍하는 LinkedIn에서도 비슷한 설계를 채택하고 있습니다.

### How Discord Stores Trillions Of Messages 
> Discord가 수조 개의 메시지를 저장하는 방법

아래 다이어그램은 Discord에서 메시지 저장소의 진화를 보여줍니다: 

<p>
  <img src="images/discord-store-messages.jpg" />
</p>


MongoDB ➡️ Cassandra ➡️ ScyllaDB 
몽고DB ➡️ 카산드라 ➡️ 실라DB 

2015년, Discord의 첫 번째 버전은 단일 MongoDB 복제본 위에 구축되었습니다. 2015년 11월경, MongoDB는 1억 개의 메시지를 저장했고 RAM은 더 이상 데이터와 인덱스를 보관할 수 없었습니다. 지연 시간은 예측할 수 없게 되었습니다. 메시지 스토리지를 다른 데이터베이스로 옮겨야 했습니다. 카산드라가 선택되었습니다. 

2017년, Discord에는 12개의 Cassandra 노드가 있었고 수십억 개의 메시지가 저장되어 있었습니다. 

2022년 초에는 177개의 노드에 수조 개의 메시지가 저장되었습니다. 이 시점에서는 지연 시간을 예측할 수 없었고 유지보수 운영 비용이 너무 많이 들었습니다. 

이 문제에는 몇 가지 이유가 있습니다: 

- Cassandra는 내부 데이터 구조에 LSM 트리를 사용합니다. 읽기가 쓰기보다 비용이 더 많이 듭니다. 수백 명의 사용자가 있는 서버에서 동시 읽기가 많이 발생하여 핫스팟이 발생할 수 있습니다. 
- SSTable 압축과 같이 클러스터를 유지 관리하면 성능에 영향을 미칩니다. 
- 가비지 수집 일시 중지로 인해 지연 시간이 크게 급증할 수 있습니다. 

ScyllaDB는 C++로 작성된 카산드라 호환 데이터베이스입니다. Discord는 모놀리식 API, Rust로 작성된 데이터 서비스, ScyllaDB 기반 스토리지를 갖추도록 아키텍처를 재설계했습니다. 

ScyllaDB의 p99 읽기 레이턴시는 15ms인 반면, Cassandra는 40-125ms입니다. p99 쓰기 레이턴시는 5ms인데 비해 Cassandra는 5-70ms입니다. 

### How do video live streamings work on YouTube, TikTok live, or Twitch?
> 동영상 라이브 스트리밍은 YouTube, TikTok 라이브 또는 Twitch에서 어떻게 작동하나요?

라이브 스트리밍은 비디오 콘텐츠가 인터넷을 통해 실시간으로 전송되기 때문에 일반 스트리밍과 다르며, 일반적으로 몇 초의 지연 시간만 발생합니다.
 
아래 다이어그램은 이를 가능하게 하는 백그라운드에서 어떤 일이 일어나는지 설명합니다

<p>
  <img src="images/live_streaming_updated.jpg" style="width: 640px" />
</p>

 
1단계: 마이크와 카메라로 원시 비디오 데이터를 캡처합니다. 데이터가 서버 측으로 전송됩니다.
 
2단계: 비디오 데이터가 압축 및 인코딩됩니다. 예를 들어, 압축 알고리즘은 배경과 기타 비디오 요소를 분리합니다. 압축 후 비디오는 H.264와 같은 표준으로 인코딩됩니다. 이 단계를 거치면 비디오 데이터의 크기가 훨씬 작아집니다.
 
3단계: 인코딩된 데이터는 보통 몇 초 길이의 작은 세그먼트로 나뉘므로 다운로드 또는 스트리밍에 걸리는 시간이 훨씬 짧아집니다.
 
4단계: 분할된 데이터가 스트리밍 서버로 전송됩니다. 스트리밍 서버는 다양한 디바이스와 네트워크 조건을 지원해야 합니다. 이를 '적응형 비트레이트 스트리밍'이라고 합니다. 즉, 2단계와 3단계에서 서로 다른 비트레이트로 여러 개의 파일을 생성해야 합니다.
 
5단계: 라이브 스트리밍 데이터는 CDN(콘텐츠 전송 네트워크)이 지원하는 엣지 서버로 푸시됩니다. 수백만 명의 시청자가 가까운 엣지 서버에서 동영상을 시청할 수 있습니다. CDN은 데이터 전송 지연 시간을 크게 줄여줍니다. 
 
6단계: 시청자의 디바이스가 비디오 데이터를 디코딩 및 압축 해제하고 비디오 플레이어에서 비디오를 재생합니다.
 
7단계와 8단계: 재생을 위해 비디오를 저장해야 하는 경우 인코딩된 데이터가 스토리지 서버로 전송되고, 시청자는 나중에 이 서버에서 재생을 요청할 수 있습니다.
 
라이브 스트리밍을 위한 표준 프로토콜은 다음과 같습니다:

- **RTMP(실시간 메시징 프로토콜, Real-Time Messaging Protocol)**: 이 프로토콜은 원래 플래시 플레이어와 서버 간에 데이터를 전송하기 위해 Macromedia에서 개발했습니다. 현재는 인터넷을 통한 비디오 데이터 스트리밍에 사용됩니다. Skype와 같은 화상 회의 애플리케이션은 지연 시간을 줄이기 위해 RTC(실시간 통신) 프로토콜을 사용합니다.
- **HLS(HTTP 라이브 스트리밍, HTTP Live Streaming)**: H.264 또는 H.265 인코딩이 필요합니다. Apple 장치는 HLS 형식만 허용합니다.
- **DASH(HTTP를 통한 동적 적응형 스트리밍, Dynamic Adaptive Streaming over HTTP)**: DASH는 Apple 디바이스를 지원하지 않습니다.
- HLS와 DASH는 모두 적응형 비트레이트 스트리밍을 지원합니다.

## License

<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc-nd/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-ND 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1"></a></p>
