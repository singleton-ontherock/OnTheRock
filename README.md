# 🏆 삼성 청년 SW 아카데미 11기 공통 우수 프로젝트 🏆

<div align="center">
<h2> 🧗‍♂️ OnTheRock 🧗‍♂️ </h2>
클라이머들을 위한 SNS 커뮤니티에서 실시간 클라이밍 영상을 공유하고, 클라이머들과 교류해보세요! 🤩
<br/>
클라이밍 커뮤니티를 통해 클라이머들이 연결되고, 지식과 경험을 공유하며, 새로운 도전과 성장을 함께하는 클라이밍 허브 구축을 목표로 하는 플랫폼입니다 🍀

</div>

## 📌 목차

- [개요](#개요)
- [프로젝트 구성도](#프로젝트-구성도)
- [주요 화면](#주요-화면)
- [시연 영상 및 자료](#시연-영상-및-자료)

## 📄 개요

- 🧗‍♂️ 프로젝트 이름: OnTheRock
- 🗓️ 프로젝트 기간: 2024년 7월 8일 - 2024년 8월 16일 (6주)
- 팀원 구성: 백엔드 3명(김수빈, 이찬민, 조승기), 프론트엔드 3명(김광현, 임예원, 정해준)

## 👩🏻‍💻팀원

|                                                                               김광현                                                                               |                                                                               김수빈                                                                               |                                                                               이찬민                                                                               |                                                                              정해준                                                                              |                                                                               임예원                                                                               |                                                                               조승기                                                                               |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                            <img src="https://avatars.githubusercontent.com/lyw000312?v=4" width=150>                                             |                                            <img src="https://avatars.githubusercontent.com/u1qns?v=4" width=150>                                             |                                            <img src="https://avatars.githubusercontent.com/chanmin97?v=4" width=150>                                            |                                           <img src="https://avatars.githubusercontent.com/lyw000312?v=4" width=150>                                           |                                           <img src="https://avatars.githubusercontent.com/wony0321?v=4" width=150>                                           |                                           <img src="https://avatars.githubusercontent.com/seungki-cho?v=4" width=150>                                            |
|                                        **김광현**                                        | <a href="https://github.com/u1qns"><img alt="Github" src="https://img.shields.io/badge/@u1qns-181717?&logo=github&logoColor=white&style=round-square"></a> | <a href="https://github.com/chanmin97"><img alt="Github" src="https://img.shields.io/badge/@chanmin97-181717?&logo=github&logoColor=white&style=round-square"></a> |                                  **정해준**                                  | <a href="https://github.com/lyw000312"><img alt="Github" src="https://img.shields.io/badge/@wony0321-181717?&logo=github&logoColor=white&style=round-square"></a> | <a href="https://github.com/seungki-cho"><img alt="Github" src="https://img.shields.io/badge/@seungki--cho-181717?&logo=github&logoColor=white&style=round-square"></a> |
|                                                                           **프론트엔드**                                                                           |                                                                     **팀장 및 발표자**,</br> **백엔드**                                                                      |                                                                          **백엔드**                                                                         |                                                                          **백엔드**                                                                          |                                                                          **프론트엔드**                                                                          |                                                                      **백엔드**                                                                    |

---


## 🗂️ 프로젝트 구성도

<details>
<summary style="font-size: 18px;">
<h3>📂 백엔드</h3>
</summary>
<div markdown="1">

```
backend
├── 🗂️ auth
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 auth
│   │   │   │           ├── application
│   │   │   │           ├── client
│   │   │   │           ├── common
│   │   │   │           ├── domain
│   │   │   │           │   └── redis
│   │   │   │           ├── dto
│   │   │   │           └── presentation
│   │   └── resources
├── 🗂️ chat
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 chat
│   │   │   │           ├── application
│   │   │   │           ├── common
│   │   │   │           ├── config
│   │   │   │           ├── domain
│   │   │   │           ├── dto
│   │   │   │           └── presentation
│   │   └── resources
├── 🗂️ contents
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 contents
│   │   │   │           ├── application
│   │   │   │           ├── batch
│   │   │   │           ├── common
│   │   │   │           ├── config
│   │   │   │           ├── domain
│   │   │   │           ├── dto
│   │   │   │           │   ├── request
│   │   │   │           │   └── response
│   │   │   │           └── presentation
│   │   └── resources
├── 🗂️ gateway
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 gateway
│   │   │   └── resources
├── 🗂️ message
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 message
│   │   │   │           ├── application
│   │   │   │           ├── client
│   │   │   │           ├── common
│   │   │   │           ├── domain
│   │   │   │           ├── dto
│   │   │   │           └── presentation
│   │   └── resources
├── 🗂️ sender
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 sender
│   │   │   │           ├── application
│   │   │   │           ├── common
│   │   │   │           ├── domain
│   │   │   │           ├── dto
│   │   │   │           └── presentation
│   │   └── resources
├── 🗂️ streaming
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 streaming
│   │   │   │           ├── application
│   │   │   │           ├── common
│   │   │   │           ├── config
│   │   │   │           ├── domain
│   │   │   │           ├── dto
│   │   │   │           │   ├── request
│   │   │   │           │   └── response
│   │   │   │           ├── exception
│   │   │   │           └── presentation
│   │   └── resources
├── 🗂️ user
│   ├── gradle
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── ontherock
│   │   │   │       └── 📂 user
│   │   │   │           ├── application
│   │   │   │           ├── client
│   │   │   │           ├── common
│   │   │   │           ├── domain
│   │   │   │           ├── dto
│   │   │   │           └── presentation
│   │   └── resources

```
</div>
</details>

<details>
<summary>
<h3>📂 프론트엔드</h3>
</summary>
<div markdown="1">

```
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
```
</div>
</details>

## 주요 화면

| Home       | Alarm      | Login      | Logout     |
| ---------- | ---------- | ---------- | ---------- |
| ![image]() | ![image]() | ![image]() | ![image]() |
|            | 홈         | 알람       | 로그아웃   |


---

## 📹 시연 영상 및 자료

- **시연 영상:** [YouTube 링크]()
- **발표 자료:** [MiriCanvas 링크](https://www.miricanvas.com/v/13k5284)
- **배포 링크:** https://ontherock.lol
