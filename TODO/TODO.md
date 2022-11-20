# TODO
공부할 내용 정리

---

## Contents

* [Spring](#Spring) 
* [Language](#Language)
* [Deploy](#Deploy)
* [Architecture](#Architecture)
* [Network](#Network)
* [Middle](#Middle)

---

## Spring

* Spring Cloud Config
* Spring Cloud Gateway
  * [blog](https://saramin.github.io/2022-01-20-spring-cloud-gateway-api-gateway)
* Webflux
  * WebClient 학습
* Spring Security
  * 간단한 로그인 기능 구현
  * 나만의 로그인 시스템 만들기

## Language

* Kotlin
  * 언어 패러다임, 구조, 문법 학습

## Deploy

* GitAction
  * gitaction 학습
  * Docker이미지 build해서 registry(DockerHub)에 등록
  * dockerhub에 올린 이미지 pull 받아와서 oci에 배포
* ArgoCD
* GoCD
* Spinnaker
* Harbor
  * 컨테이너 이미지 레지스트리
* K8S Deploy방법
  * 롤링업데이트, blue/green, carary

## Architecture

* Service Mesh Architecture
  * MSA와 같은 아키텍처로 최근 활발히 언급
* Hexagonal(육각형) Architecture
  * 레이어드 아키텍처의 단점을 헤결하기 위한 아키텍처 - [blog](https://happy-coding-day.tistory.com/entry/%ED%97%A5%EC%82%AC%EA%B3%A0%EB%82%A0-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98Hexagonal-Architecture-%EC%BD%94%EB%93%9C%EB%A1%9C-%EC%9D%B4%ED%95%B4%ED%95%B4%EB%B3%B4%EA%B8%B0-%EB%AF%B8%EC%99%84%EC%84%B1)

## Network

* graphql
* Netty
* hadoop
* OSI 7계층, TCP/IP 4계층
  * 각종 프로토콜 학습 (http, ws, 기타 등등)
* gRPC

## Middle

* Kafka
  * 로컬이나 OCI에 올려볼 것
  * **카프카, 데이터플랫폼의 최강자** 책 학습
* RabbitMQ
  * 로컬이나 OCI에 올려볼 것

## ETC

* zookeeper
* Consul : SMA 툴
* Haproxy : SMA 관련된거
* lstio : SMA 네트워크 툴?!
* Ceph : 스토리지 플랫폼
* 코루틴 : 비동기