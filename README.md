# 🩵 Knowing - 개발자를 위한 선명한 피드백, 기술 면접 학습 서비스

![Knowing Title](https://github.com/education-project-knowing/.github/assets/77969467/350da596-7aba-4942-baad-5290ecb6e423)

## Knowing 링크 : 출시 예정

</br>

## 👟 프로젝트 진행 기간

2024.07.08(월) ~ 2024.08.30(금) (53일간 진행)  
2024년 여름방학 자율 프로젝트 - Knowing

</br>

## 🌟 Knowing - 배경

개발자가 되기 위해서 꼭 공부해야 하는 것은 바로 기술면접 대비를 위한 Computer Science 지식입니다.

개발자를 꿈꾸는 사람들은 CS를 공부하기 위해 여기저기서 구글링을 하고 책을 사서 읽습니다.

하지만 공부는 항상 하는데 이상하게 머릿속에 잘 남지 않는 경험 다들 한 번씩 있지 않나요?

방대하고 어질러진 CS 지식, **Knowing과 함께 깔끔하게 정리하고 공부해봐요.😊**

</br>

## 🔎 Knowing - 개요

_- CS지식을 정리하고 학습하자 -_

**Knowing** 방대한 CS 정보를 분야별로 제공하고, 분야별 랜덤 퀴즈 서비스를 제공하여 학습에 도움을 줍니다.

데일리 퀴즈는 학습자가 잊지 않고 꾸준히 CS 지식을 학습할 수 있도록 학습자의 도전 의식을 고취시킵니다.

퀴즈를 풀고나면 어느 분야가 취약한지 분석하고, 최적의 공부효율을 위해 틀린 문제 위주로 복습할 수 있는 기능을 제공합니다.

<!--스스로 질문을 추가하여 CS지식을 개별적으로 정리하고 학습할 수 있습니다.-->

</br>

## 💎 주요 기능

---

-   ### 데일리 퀴즈

    -   학습자는 매일 10가지의 랜덤으로 나오는 단답형 문제를 풀 수 있습니다.
    -   랜덤 문제는 첫 번째 시도가 결과로 기록되며(시간, 정답 개수), 학습자의 결과에 따라 랭킹과 개발자 레벨이 나옵니다.
 
<!-- 개발자 레벨은 정답 개수에 따라 바뀔 수 있지만 랭킹은 오직 첫번째 시도에만 기록되어야 하며 랭킹은 한국 시계 기준으로 00시에 초기화되어야 함)-->

        <br/>

-   ### 랜덤 퀴즈

    -   랜덤 퀴즈를 학습하면 선택한 카테고리의 질문이 무작위로 학습자에게 제공됩니다.
    -   랜덤 퀴즈는 모든 문항이 혹은 모르는 문항만 출제되도록 선택할 수 있습니다.
    -   학습자는 스스로 질문에 대해 답변을 해야하며 성공할 시 Yes를 실패 시 No를 체크하여 다음 문제로 넘어갑니다.
    -   Yes로 답한 문항은 즉시 학습 진도의 반영됩니다.
    -   설령 모르는 문제를 Yes로 답변해도 직접 문항의 인지 여부를 조작하거나 퀴즈를 재시도하여 해제할 수 있습니다.
    -   (힌트 키워드를 설정해도 좋을 듯함)
    -   문항 설명 버튼을 클릭하여 문항의 답안을 확인할 수 있습니다.

         <br/>

-   ### 진도 확인

    -   분야 별 학습 진도를 메인 화면에서 확인할 수 있습니다.

          <br/>

-   ### 인지 여부 체크

    -   체크 박스를 통해 각 질문의 인지 상태를 체크할 수 있습니다.
    -   인지 상태는 Yes or No로 나뉘며 인지 상태는 곧바로 분야 별 학습 진도의 영향을 미칩니다. 

          </br>


## ✔ 주요 기술

---

**Backend**

-   Springboot 3.x.x
-   Spring Data JPA
-   Spring Security
-   Spring Validation
-   Spring Web
-   QueryDSL
-   ?WebSocket
-   !Redis
-   MySQL
-   ?fluentd
-   !elasticsearch
-   ?kibana
-   ?metricbeats


**Frontend**

-   React
-   ?Recoil
-   ?MUi
-   ?Unity
-   ?Photon
-   WebGL
-   Webstomp-Client 1.2.6
-   Sock.js-Client 1.5.2
-   sweetalert2 11.3.10
-   Swift
-   Android

**CI/CD**

-   AWS EC2
-   ?NGINX
-   ?SSL
-   !Docker

---

<!--## ✔ 프로젝트 파일 구조

---

### Frontend

```
csafy-frontend
  ├── node_modules
  ├── public
  └── src
      ├── components
      │   ├── atoms
      │   ├── common
      │   ├── companyClassification
      │   ├── Home
      │   └── myPage
      ├── pages
      │   ├── handler
      │   └── StudyPage
      ├── recoils
      └── utils

```

### Backend

```
backend-flask
backend
  ├── auth-service
  │   ├── api
  │   ├── clinet
  │   ├── config
  │   ├── dto
  │   ├── entity
  │   ├── exception
  │   ├── info
  │   ├── error
  │   ├── repository
  │   ├── service
  │   └── util
  ├── chat-service
  │   ├── api
  │   ├── clinet
  │   ├── config
  │   ├── dto
  │   ├── error
  │   ├── repository
  │   └── service
  ├── cs-service
  │   ├── api
  │   ├── clinet
  │   ├── controller
  │   ├── dto
  │   ├── entity
  │   ├── repository
  │   ├── scheduler
  │   └── service
  ├── pay-service
  │   ├── client
  │   ├── controller
  │   ├── dto
  │   └── service
  ├── user-service
  │   ├── api
  │   ├── clinet
  │   ├── config
  │   ├── dto
  │   ├── entity
  │   ├── exception
  │   ├── info
  │   ├── repository
  │   ├── service
  │   └── util
  ├── eureka
  └── gateway
      └── config
```-->

## ✔ 협업 툴

---

-   Github
-   Notion
-   !JIRA
-   Figma
-   Webex
-   Code With Me

## ✔ 협업 환경

---

-   Github
    -   코드 버전 관리
    -   이슈 발행, 해결을 위한 토론
    -   MR시, 팀원이 코드리뷰를 진행하고 피드백 게시
-   JIRA
    -   매주 목표량을 설정하여 Sprint 진행
    -   업무의 할당량을 정하여 Story Point를 설정하고, In-Progress -> Done 순으로 작업
    -   소멸 차트를 통해 프로젝트 진행도 확인
-   회의
    -   매주 수요일 강남 스터디카페 오후 회의 진행, 전날 목표 달성량과 당일 할 업무 브리핑
    -   게더 타운 도입 논의
    -   빠른 소통과 신속한 대응 가능
-   Notion
    -   회의가 있을때마다 회의록을 기록하여 보관
    -   회의가 길어지지 않도록 다음날 제시할 안건을 미리 기록
    -   기술확보 시, 다른 팀원들도 추후 따라할 수 있도록 보기 쉽게 작업 순서대로 정리
    -   컨벤션 정리
    -   간트차트 관리
    -   스토리보드, 스퀀스다이어그램, 기능명세서 등 모두가 공유해야 하는 문서 관리
-   Slack
    -   현재 작업 상황 공유
    -   기능 수정 공지
    -   투표 진행
-   Figma
    -   목업 제작, 와이어프레임제작, 디자인 작업 공유
    -   Figjam으로 라이브 작업 및 회의 진행
  

## ✔ 팀원 역할 분배

---



## ✔ 프로젝트 산출물

---

-   [기능명세서](docs/기능명세서.md)
-   [디자인&컨셉기획](docs/디자인&컨셉기획.md)
-   [비지니스모델](docs/비지니스모델.md)
-   [시스템구성도](docs/시스템구성도.md)
-   [와이어프레임](docs/와이어프레임.md)
-   [컨벤션](docs/컨벤션.md)
-   [ERD](docs/ERD.md)
-   [시스템기술서](docs/시스템_기술서)

## ✔ 프로젝트 결과물

-   [포팅메뉴얼](exec/CSAFY_포팅_메뉴얼.docx)
-   [중간발표자료](ppt/CSAFY중간발표.pptx)
-   [최종발표자료](ppt/CSAFY최종발표.pptx)

## 🎵 Knowing 서비스 화면

---

### 메인화면

-   Knowing에서 제공하는 서비스를 한 눈에 볼 수 있도록 메인화면을 구성하였습니다.
-   분야 별 학습진도를 확인할 수 있습니다.


<br>

### 데일리 퀴즈

-   매일 10가지의 문제가 출제됩니다.

<br>

### 랜덤 퀴즈

-   학습자가 선택한 분야 별로 순서가 무작위인 문제가 출제됩니다.

<br>

### 문항 답변

-   문항에 대한 답변을 확인할 수 있습니다.

<br>

### 용어 백과사전

-   궁금한 CS 용어를 검색해서 찾아볼 수 있습니다.

<br>


### 학습분석데이터

-   지금까지 시청한 강의, 풀었던 문제, 그리고 치룬 시험의 결과 데이터를 한 눈에 파악할 수 있도록 그래프와 함께 제공됩니다.


<br>

### 후원하기

-   원활하고 쾌적한 서버 환경을 위해 개발자를 후원합니다.


<br>

### 모바일 환경

-   모바일 환경은 아직 제공되지 않습니다.(추후 도입 예정)


<br>


### Knowing 데일리 퀴즈 결과를 카카오톡에 공유하자

-  다른 개발자와 나의 수준을 데일리 퀴즈로 가볍게 비교해보자
-  경쟁심으로 인한 학습 열정은 취업에 도움이 된다! 


