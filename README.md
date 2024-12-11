<div align="center" style="font-size: 30px; color: white; background-color: #8090bf">
🏆 삼성 청년 SW 아카데미 11기 공통 우수 프로젝트 🏆
</div>

<div align="center">
<h2> 🧗‍♂️ OnTheRock 🧗‍♂️ </h2>
클라이머들을 위한 SNS 커뮤니티에서 실시간 클라이밍 영상을 공유하고, 클라이머들과 교류해보세요! 🤩
<br/>
클라이밍 커뮤니티를 통해 클라이머들이 연결되고, 지식과 경험을 공유하며, 새로운 도전과 성장을 함께하는 클라이밍 허브 구축을 목표로 하는 플랫폼입니다 🍀

</div>

## 📌 목차

- [개요](#개요)
- [시연 영상 및 자료](#시연-영상-및-자료)
- [프로젝트 구성도](#프로젝트-구성도)
- [주요 화면](#주요-화면)

## 📄 개요

- 🧗‍♂️ 프로젝트 이름: OnTheRock
- 🗓️ 프로젝트 기간: 2024년 7월 8일 - 2024년 8월 16일 (6주)
- 팀원 구성: 백엔드 3명(김수빈, 이찬민, 조승기), 프론트엔드 3명(김광현, 임예원, 정해준)

## 📹 시연 영상 및 자료

- **시연 영상:** [YouTube 링크]()
- **영상 포트폴리오:** [YouTube 링크]()
- **발표 자료:** [MiriCanvas 링크](https://www.miricanvas.com/v/13k5284)
- **배포 링크:** https://ontherock.lol

## 프로젝트 구성도

<details>
<summary style="font-size: 18px;">
👩🏻‍💻 백엔드
</summary>
<div markdown="1">
backend
├── auth
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── auth
│ │ │ ├── application
│ │ │ ├── client
│ │ │ ├── common
│ │ │ ├── domain
│ │ │ │ └── redis
│ │ │ ├── dto
│ │ │ └── presentation
│ │ └── resources
│ └── test
│ └── java
│ └── ontherock
│ └── auth
│ ├── application
│ └── presentation
├── chat
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── chat
│ │ │ ├── application
│ │ │ ├── common
│ │ │ ├── config
│ │ │ ├── domain
│ │ │ ├── dto
│ │ │ ├── exception
│ │ │ └── presentation
│ │ └── resources
│ └── test
│ └── java
│ └── ontherock
│ └── chat
├── contents
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── contents
│ │ │ ├── application
│ │ │ ├── batch
│ │ │ ├── common
│ │ │ ├── config
│ │ │ ├── domain
│ │ │ ├── dto
│ │ │ │ ├── request
│ │ │ │ └── response
│ │ │ └── presentation
│ │ └── resources
│ └── test
│ ├── java
│ │ └── ontherock
│ │ └── contents
│ │ ├── application
│ │ ├── domain
│ │ └── presentation
│ └── resources
├── discovery
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── discoveryservice
│ │ └── resources
│ └── test
│ └── java
│ └── ontherock
│ └── discoveryservice
├── gateway
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── gateway
│ │ └── resources
│ └── test
│ └── java
│ └── ontherock
│ └── gateway
├── message
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── message
│ │ │ ├── application
│ │ │ ├── client
│ │ │ ├── common
│ │ │ ├── domain
│ │ │ ├── dto
│ │ │ └── presentation
│ │ └── resources
│ └── test
│ └── java
│ └── ontherock
│ └── message
│ └── application
├── sender
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── sender
│ │ │ ├── application
│ │ │ ├── common
│ │ │ ├── domain
│ │ │ ├── dto
│ │ │ └── presentation
│ │ └── resources
│ └── test
│ └── java
│ └── ontherock
│ └── sender
│ ├── application
│ ├── config
│ └── domain
├── streaming
│ ├── bin
│ │ ├── main
│ │ │ └── ontherock
│ │ │ └── streaming
│ │ │ ├── application
│ │ │ ├── common
│ │ │ ├── config
│ │ │ ├── dto
│ │ │ │ ├── request
│ │ │ │ └── response
│ │ │ ├── exception
│ │ │ └── presentation
│ │ └── test
│ │ └── ontherock
│ │ └── streaming
│ │ └── application
│ ├── gradle
│ │ └── wrapper
│ └── src
│ ├── main
│ │ ├── java
│ │ │ └── ontherock
│ │ │ └── streaming
│ │ │ ├── application
│ │ │ ├── common
│ │ │ ├── config
│ │ │ ├── dto
│ │ │ │ ├── request
│ │ │ │ └── response
│ │ │ ├── exception
│ │ │ └── presentation
│ │ └── resources
│ └── test
│ └── java
│ └── ontherock
│ └── streaming
│ └── application
└── user
├── gradle
│ └── wrapper
└── src
├── main
│ ├── java
│ │ └── ontherock
│ │ └── user
│ │ ├── application
│ │ ├── client
│ │ ├── common
│ │ ├── domain
│ │ ├── dto
│ │ └── presentation
│ └── resources
└── test
└── java
└── ontherock
└── user
├── application
├── domain
└── presentation

</div>
</details>

<details>
<summary style="font-size: 18px;">
👩🏻‍💻 프론트엔드
</summary>
frontend
└── on-the-rock-app
    └── src
        ├── api
        ├── assets
        ├── components
        │   ├── Mobile
        │   ├── OpenVidu
        │   └── Web
        │       ├── Analyze
        │       ├── Feed
        │       ├── Login
        │       ├── MainPage
        │       ├── NavBar
        │       ├── Streaming
        │       ├── Upload
        │       └── UserProfile
        ├── css
        └── store
</details>

## 주요 화면

| Home       | Alarm      | Login      | Logout     |
| ---------- | ---------- | ---------- | ---------- |
| ![image]() | ![image]() | ![image]() | ![image]() |
|            | 홈         | 알람       | 로그아웃   |
