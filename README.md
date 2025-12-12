# 🏃‍♀️ 같이 달리조 - 러너들을 위한 올인원 플랫폼

> 러너들을 위한 **상품, 날씨,마라톤대회 정보 제공, 커뮤니티**공통 기능과 러닝 크루 활동을 위한 **가입, 일정 생성/관리, 커뮤니티, 채팅, 챗봇** 기능을  
> 하나의 서비스로 제공하는 **러너들을 위한 올인원 플랫폼**입니다. 🏃‍♂️✨  
>
> **러닝 활동의 모든 흐름을 하나의 플렛폼에서 자연스럽게 연결하는 것이 목표입니다.** 😊  
>
> 제작기간 2025.11.03 ~ 2025.12.05

---

| [프로젝트 소개](#%E2%80%8D%EF%B8%8F-같이-달리조---러너들을-위한-올인원-플랫폼) | [사용 기술 스택](#️-사용-기술-스택) | [팀원 & 담당 역할](#-팀원--담당-역할) | [프로젝트 구조](#-프로젝트-구조) | [주요 기능](#️-주요-기능) | [화면 흐름도](#-화면-흐름도) | [기능 개발 (허린)](#-db설계--챗봇--내크루-전반-허린) |

---

## 🛠️ 사용 기술 스택

<table>
  <tr>
    <th>Frontend</th>
    <th>Backend</th>
    <th>Infra / DevOps</th>
    <th>Database</th>
    <th>External API</th>
  </tr>

  <tr>
    <!-- Frontend -->
    <td>
      <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redux%20Toolkit-593D88?style=for-the-badge&logo=redux&logoColor=white"/>
      <img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white"/>
      <img src="https://img.shields.io/badge/Axios-671DDF?style=for-the-badge&logo=axios&logoColor=white"/>
      <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/FullCalendar-0288D1?style=for-the-badge&logo=googlecalendar&logoColor=white"/>
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/><br/>
      <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
      <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white"/>
    </td>
    <!-- Backend -->
    <td>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring%20Data%20JPA-59666C?style=for-the-badge"/><br/>
      <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
      <img src="https://img.shields.io/badge/REST%20API-005571?style=for-the-badge"/><br/>
      <img src="https://img.shields.io/badge/STOMP-000000?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
      <img src="https://img.shields.io/badge/KOMORAN-000000?style=for-the-badge"/><br/>
      <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"/>
    </td>
    <!-- Infra / DevOps -->
    <td>
      <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/><br/>
      <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
    </td>
    <!-- Database -->
    <td>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
    </td>
    <!-- External API -->
    <td>
      <img src="https://img.shields.io/badge/Kakao%20Map-FFCD00?style=for-the-badge&logo=kakao&logoColor=black"/>
      <img src="https://img.shields.io/badge/OpenWeather-0A6EB4?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/DATA.go.kr-0052CC?style=for-the-badge"/>
    </td>
  </tr>
</table>

---

## 👥 팀원 & 담당 역할

| 이름 | 역할 |
|------|------|
| 👨‍💻 **허린** | **서비스 아이디어 제안, DB 설계, 크루 가입, 크루 메인/회원/일정(FullCalendar), 크루 챗봇(KOMORAN+RabbitMQ+WebSocket+STOMP)** | 
| 👩‍💻 박XX (팀장) | JWT, Spring Security, 회원가입/수정/탈퇴, MyPage, OAuth2 로그인, 권한/보안 설계 | 
| 👨‍💻 정XX | 라우터 설계, 게시판 CRUD, 스토어 메인 UI, CI/CD 설계 및 배포, GitHub 관리| 
| 👨‍💻 이XX | Admin 백오피스 CRUD, 관리자 대시보드, 통계/차트 구현 | 
| 👨‍💻 천XX | 장바구니, 결제/Kakao Pay 연동, 주문/배송 상태 관리, 외부 Open API(마라톤/날씨/지도) 연동 | 
| 👨‍💻 유XX | 크루 목록/검색/페이징, 크루 상세/수정, 마이 크루 게시판·댓글, 마이 크루 채팅(WebSocket/STOMP) 구현 |

---

## 📂 프로젝트 구조

FullStackProject/   <br>
 ┣ backendspring/                           ⭐ Spring Boot 백엔드  <br>
 ┃ ┣ src/main/java/org/spring/backendspring/ <br>
 ┃ ┃ ┣ API/                                  <br>
 ┃ ┃ ┣ admin/                                <br>
 ┃ ┃ ┣ board/                                <br>
 ┃ ┃ ┣ cart/                                 <br>
 ┃ ┃ ┣ checkout/                             <br>
 ┃ ┃ ┣ common/                               <br>
 ┃ ┃ ┣ config/                               <br>
 ┃ ┃ ┣ crew/                                 <br>
 ┃ ┃ ┣ event/                                <br>
 ┃ ┃ ┣ item/                                 <br>
 ┃ ┃ ┣ member/                               <br>
 ┃ ┃ ┣ payment/                              <br>
 ┃ ┃ ┣ rabbitmqWebsocket/                    <br>
 ┃ ┃                                         <br>
 ┃ ┣ src/main/resources/                     <br>
 ┃ ┃ ┣ application.yml                       <br>
 ┃ ┃                                         <br>
 ┃ ┣ build.gradle                            <br>
 ┃ ┗ Dockerfile                              <br>
 ┃                                           <br>
 ┣ vite-front/                              ⭐ React 프론트엔드 (Vite 기반) <br>
 ┃ ┣ nginx/                                  <br> 
 ┃ ┗ nginx.conf                              <br>
 ┃ ┣ public/                                 <br>
 ┃ ┣ src/                                    <br>
 ┃ ┃ ┣ apis/                                 <br>
 ┃ ┃ ┣ components/                           <br>
 ┃ ┃ ┃ ┣ common/                             <br>
 ┃ ┃ ┃ ┗ container/                          <br>
 ┃ ┃ ┣ css/                                  <br>
 ┃ ┃ ┣ js/                                   <br>
 ┃ ┃ ┣ layout/                               <br>
 ┃ ┃ ┣ pages/                                <br>
 ┃ ┃ ┣ router/                               <br>
 ┃ ┃ ┣ slice/                                <br>
 ┃ ┃ ┗ store/                                <br>
 ┃ ┣ package.json                            <br>
 ┃ ┗ Dockerfile                              <br>
 ┃                                           <br>
 ┣ .github/workflows/                        <br>
 ┣ docker-compose.yml                        <br>
 ┣ README.md                                 <br>
 ┗ .gitignore   

---

## ⚙️ 주요 기능

### 🔀 화면 흐름도


###  🧩 **DB설계 / 챗봇 / 내크루 전반 (허린)**

<details>
    <summary>🗄️ DB 설계</summary>
        <table>
            <tr>
                <th></th>
            </tr>
            <tr>
                <td></td>
            </tr>
        </table>
</details>
<details>
    <summary>🤖 챗봇</summary>
        <table>
            <tr>
                <th></th>
            </tr>
            <tr>
                <td></td>
            </tr>
        </table>
</details>
<details>
    <summary>🏃‍♂️ 내 크루 전반 </summary>
        <table>
            <tr>
                <th></th>
            </tr>
            <tr>
                <td></td>
            </tr>
        </table>
</details>

####  🔐 회원가입 / 로그인,OAuth2 / 인증,인가 / MyPage (박XX)

<details>
    <summary>🔍 자세히 보기</summary>
        <table>
            <tr>
                <th></th>
                <th></th>
                <th></th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
</details>

####  ⚙️ CI/CD / GitHub / 라우터 / 메인 UI / 게시판 (정XX)

<details>
    <summary>🔍 자세히 보기</summary>
        <table>
            <tr>
                <th></th>
                <th></th>
                <th></th>
                <th></th>
                <th></th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
</details>

####  🛠️ Admin / 대시보드 (이XX)

<details>
    <summary>🔍 자세히 보기</summary>
        <table>
            <tr>
                <th></th>
                <th></th>
            </tr>
            <tr>
                <td></td>
                <td></td>
            </tr>
        </table>
</details>

####  🛒 장바구니 / 결제,KakaoPay / OpenAPI / 주문상태관리  (천XX)

<details>
    <summary>🔍 자세히 보기</summary>
        <table>
            <tr>
                <th></th>
                <th></th>
                <th></th>
                <th></th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
</details>

####  💬 크루 전반 / 내 크루 게시판 /  내 크루 채팅방  (유XX)

<details>
    <summary>🔍 자세히 보기</summary>
        <table>
            <tr>
                <th></th>
                <th></th>
                <th></th>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
            </tr>
        </table>
</details>
