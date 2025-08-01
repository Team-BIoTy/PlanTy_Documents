| [English](./README_en.md) | [Korean](./README.md) |

# 🌱 PlanTy

본 레포지토리는 PlanTy 프로젝트에 대한 설명 및 발표 자료들을 모아 놓은 레포지토리입니다. 

PlanTy 프로젝트는 "캡스톤 디자인" 수업의 일환으로 진행된 프로젝트로, 

LLM과 IoT를 결합한 스마트 식물 관리 어플리케이션을 구현하는 것을 목표로 합니다. 

PlanTy 프로젝트의 코드를 더 자세히 보고 싶다면 아래 내용을 참고하세요. 
- 어플리케이션 코드: [PlanTY_FE](https://github.com/Team-BIoTy/Planty-FE), [PlanTy_BE](https://github.com/Team-BIoTy/Planty-BE?tab=readme-ov-file)
- IoT 코드: [PlanTy_IoT](https://github.com/Team-BIoTy/Planty_IoT)
- LLM 코드: [PlanTy_LLM](https://github.com/Team-BIoTy/Planty_LLM), [PlanTy_Agent](https://github.com/Team-BIoTy/Planty_Agent)

</br>

## 1. 프로젝트 소개
- **프로젝트명**: "PlanTy: LLM과 IoT를 활용한 개인 맞춤형 식물 관리 솔루션"
- **전체 프로젝트 기간**: 2025.01.21 - 2025.06.14
- **참여 인원**: 구선주, 김민지, 민유진, 최예림

</br>

### 프로젝트 설명
- IoT를 기반으로 식물 관리 솔루션을 제공하고, SLM (LLM)을 기반으로 사용자에게 정서적인 교감을 지원하는 종합 솔루션
- IoT 센서를 활용하여 식물의 환경을 탐지하고, 팬, LED, 워터 펌프를 사용하여 식물 관리 자동화
- 모바일 앱을 통해 IoT 센서의 결과를 실시간으로 모니터링하고 제어 방법 선택 가능
- 챗봇은 IoT에서 수집한 데이터를 연결하여 현재 상태를 기반으로 답변
- 챗봇에 페르소나를 부여하여 사용자와 정서적인 교감이 가능하도록 지원 (SLM과 LLM 모델 제공)

</br>

### 개발 기간

<img alt="타임라인" src="./images/timeline.jpg" width="800"/>

</br>

## 2. 개발 환경

<img alt="개발환경" src="./images/environment.jpg" width="800"/>

- **Frontend**: Flutter, Dart
- **Backend**: SpringBoot, Java
- **LLM**: Transformer, LangChain, LangGraph, Python
- **Harware**: ESP32Board, soil humidity sensor, humidity and temperature sensor(DHT), illumination sensros(CDS), water pumps, fans, LEDs, relay modules
- **Database**: ChromaDB, MySQL
- **collaborate**: Notion, Github

</br>

## 3. 프로젝트 결과


</br>

## 4. 역할 분담

### 👩🏻‍💻 구선주 (IoT)
- IoT 장치 설계 및 구현
- 식물 데이터 및 센서 데이터 수집 및 가공
- 장치와 백엔드 시스템 간의 통신 프로토콜 정의 및 구현

</br>

### 👩🏻‍💻 김민지 (어플리케이션)
- 사용자 인터페이스 (UI/UX) 설계 및 Flutter 기반 어플리케이션 개발
- Spring Boot 기반 백엔드 서버 구축 및 API 설계
- IoT 장치 및 SLM 기반 챗봇 서버와의 데이터 연동 로직 구현
- 실시간 데이터 흐름 및 상태 관리 로직 구성
- MySQL 기반 데이터베이스 설계, 연동 및 운영
- 전체 시스템 통합

</br>

### 👩🏻‍💻 민유진 (LLM)
- 식물 정보 및 농업 데이터 수집
- 파운데이션 모델 선정
- 벡터 데이터베이스 및 RAG 최적화
- 에이전트 설계 및 구현
- 프롬프트 엔지니어링
- 프로젝트 발표

</br>

### 👩🏻‍💻 최예림 (LLM)
- 식물 정보 및 농업 데이터 수집
- 파운데이션 모델 선정
- SLM 모델 파인튜닝
- 에이전트 설게 및 구현
- 에이전트 API 구현
- 프로젝트 발표

</br>