![logo](https://user-images.githubusercontent.com/66216102/224023729-c3fef6b4-d45a-48a8-8e7c-1be533e18078.png)

<details>
<summary> 👉🏻 Contents  </summary>
  
- [🚀 프로젝트 개요](#🚀-프로젝트-개요)
- [🎮 기술 스택](#🎮-기술-스택)
  - [💻 Back-End](#💻-back-end)
  - [✨ Front-End](#✨-front-end)
  - [🌏 Infra](#🌏-Infra)
  - [🫡 협업툴](#🫡-협업툴)
- [🚀 서비스 소개](#🚀-서비스-소개)
  - [Carpe Diem은 이런 생각에서 시작하였습니다.](#carpe-diem은-이런-생각에서-시작하였습니다)
  - [Carpe Diem은 이런 서비스입니다.](#carpe-diem은-이런-서비스입니다)
- [🚀 주요기능](#🚀-주요기능)
  - [두 가지의 영상 모드](#두-가지의-영상-모드)
  - [소셜 로그인](#소셜-로그인)
  - [인물 등록 - 인물 & 감정 디텍팅](#인물-등록---인물--감정-디텍팅)
  - [영상 녹화 - 비디오 & 앨범](#영상-녹화---비디오--앨범)
  - [친구 기능](#친구-기능)
  - [감정 리포트 제작](#감정-리포트-제작)
- [🚀 전체 프로젝트의 구조](#🚀-전체-프로젝트의-구조)
- [🚀 프로젝트 포스터](#🚀-프로젝트-포스터)

</details>

## 



## 🚀 프로젝트 개요
- *모든 팀원이 풀스택으로 개발에 참여했으며, 주 포지션은 아래와 같습니다.*
<br>

|   Name   | 김다솔 | 김수경 | 이지연 | 주성우 | 홍서희 |
| :------: | --- | --- | --- | --- | --- |
| Profile  | ![김다솔](https://user-images.githubusercontent.com/66216102/224022201-5cecf932-469b-416e-8e43-e62ec1286337.jpeg) | ![김수경](https://user-images.githubusercontent.com/66216102/224022211-d841609e-5e04-4246-95bc-893bb0b95959.jpeg) | ![이지연](https://user-images.githubusercontent.com/66216102/224022216-5b8070a7-afb1-4d60-b21f-2fcd74f54cf8.jpeg) | ![주성우](https://user-images.githubusercontent.com/66216102/224022220-16542f51-9dcd-45a8-a1af-b04422a125cc.jpeg) | ![홍서희](https://user-images.githubusercontent.com/66216102/224022221-e2ce65ca-a78e-4589-9ae3-38eb04af98f3.jpg) |
| Position | Frontend & UI/UX | 팀장 & Backend Develop | Frontend & UI/UX | Backend Develop | Backend Develop |
|   Git    | [@sol2588](https://github.com/sol2588) | [@olive-su](https://github.com/olive-su) | [@ljy6712](https://github.com/ljy6712) | [@nickhealthy](https://github.com/nickhealthy)| [@XxoSio](https://github.com/XxoSio) |

- 프로젝트 기간: 2023년 2월 2일 ~ 2023년 3월 11일
- 서비스 보러가기: [jungle-carpediem.site](https://jungle-carpediem.site/)
- 소개 및 시연 영상: [Youtube](https://youtu.be/m-FIanzrorc)
- 최종 발표 영상 : [Youtube](https://youtu.be/2QMQA4y3c4c)
- 팀 소개 위키: [Carpediem Wiki](https://www.notion.so/kimpp/CARPE-DIEM-WIKI-1647f0a74db346b3b3edddebe390cd48)

<br> 

## 🎮 기술 스택

### ✨ Front-End

<details>
    <summary>⚡️ FE 자세히 살펴보기</summary>
    <ul>
        <li>typescript : 4.9.5 </li>
        <li>react: 18.2.0</li>
        <li>react-webcam: 7.0.1</li>
        <li>redux: 4.2.1</li>
        <li>redux-saga: 1.2.2</li>
        <li>styled-components: 5.3.6</li>
        <li>socket.io-client: 4.6.0</li>
   		  <li>aws-sdk: 3.266</li>
        <li>axios : 0.21.1</li>
        <li>fontawesome : 2.0.2</li>
        <li>vue-awesome-swiper : 4.1.1</li>
        <li>eslint & prettier : 6.7.2</li>
        <li>mui/material : 5.11.7 </li>
        <li>react-oauth/google : 0.7.0</li>
        <li>html2canvas : 1.4.1</li>
        <li>react-images-upload : 1.2.8 </li>
    </ul>
</details>

### 💻 Back-End

<details>
      <summary>⚡️ BE 자세히 살펴보기</summary>
      <ul>
          <li>typescript : 4.9.5 </li>
          <li>Nodejs : 18.14.0</li>
          <li>express: 4.17.17</li>
          <li>eslint: 8.33.0</li>
					<li>dotenv: 16.0.3</li>
        	<li>aws-sdk: 3.266</li>
  	      <li>multer: 8.33.0</li>
          <li>socket.io: 4.6.1</li>
	        <li>passport: 0.6.0</li>
	        <li>passport-google-oauth2: 0.2.0</li>
        	<li>swagger-jsdoc: 6.2.8</li>
        	<li>swagger-ui-express: 4.6.0</li>
          <li>cors: 2.8.5</li>
          <li>mysql: 8.0.28</li>
          <li>sequelize: 6.28.0</li>
          <li>winston: 3.8.2</li>
        	<li>winston-daily-rotate-file: 4.7.1</li>
      </ul>
  </details>
  
### 🌏 Infra

  <details>
      <summary>⚡️ Deploy, CI/CD 자세히 살펴보기 </summary>
      <ul>
          <li>AWS IAM - Access Management</li>
          <li>AWS EC2 - Deploy Server</li>
         	<li>AWS Lambda - Change File extension, Make Thumbnail, Batch</li>
          <li>AWS Cloud Front - CDN</li>
          <li>AWS S3 - File(Image, Video) Server</li>
          <li>AWS RDS - DB Server</li>
	        <li>Nginx - WEB Server</li>
          <li>Github Action</li>
          <li>Docker</li>
      </ul>
  </details>

### 🙌🏻 Collaboration
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat&logo=Jira&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=Slack&logoColor=white"/> <img src="https://img.shields.io/badge/Github-181717?style=flat&logo=Github&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/GoogleDrive-4285F4?style=flat&logo=GoogleDrive&logoColor=white"/>

<br>


## 🚀 서비스 소개

> 아무리 많은 돈과 황금이 있더라도 단 1초의 시간도 살 수 없다. 
> <br> *_어벤져스 토니스타크 대사 中*

우리의 인생은 1분, 1초 모두 놓치기 아까운 소중한 시간들입니다.

<br>

### ☀️ Carpe Diem은 이런 생각에서 시작하였습니다.

- 소중한 추억들은 항상 일상생활에서 일어나는데, 그 순간이 지나서 아까운 경험은 없으셨나요?
- 그 순간을 다시 회상하고 싶진 않으셨나요?
- 영상을 전체 저장해서 그 순간을 찾아내는 것 보단 특정 순간을 바로 보고 싶지 않으셨나요?

<br>

### ☁️ Carpe Diem은 이런 서비스입니다.

- Carpe Diem과 함께라면 오늘 하루를 포착하고, 인생의 모든 소중한 순간을 포착할 수 있습니다.
- 감지된 인물과 감정을 기반으로 개인화된 앨범을 쉽게 제작할 수 있습니다.
- 앨범, 감정 리포트를 친구들과 소중한 경험들을 공유할 수 있습니다.

<br>

**"지금, Carpe Diem을 시작하여 평생 간직할 수 있는 추억을 만들어 보세요!"**

<br>

**"특별한 순간들을 다시 경험해보세요!"**

<br>

## 🚀 주요기능

### 1️⃣ 소셜 로그인

💬 *Google 소셜 로그인으로 별도의 회원가입 없이 간편하게 서비스를 이용할 수 있어요!*

<img src="https://user-images.githubusercontent.com/66216102/224342324-8e5eeca2-bb36-4c3a-aa80-71202f5a1f61.gif" width=800>

<br>

### 2️⃣ 카메라 촬영
💬 *두 가지 촬영 모드로 손쉽게 촬영을 시작해보세요!*

- 웹캠 & 모바일, 두 가지의 촬영 모드를 통해 어디서나 쉽게 촬영을 저장할 수 있습니다.
  - 모바일은 QR 코드를 통해 접근가능합니다.

<br>

### 3️⃣ 얼굴 & 감정 디텍팅
💬 *사용자 등록 이미지를 토대로 정확한 디텍팅을 수행합니다.*

- 초기 서비스 이용 시 인물 등록을 통해 특정인을 구분하여 영상을 녹화하고, 감정 그래프를 통해 실시간으로 감정을 추적할 수 있습니다.
  - '행복해요', '슬퍼요', '화나요', '힘들어요', '두려워요', '놀라워요' 총 6가지의 감정을 추척하고 기록할 수 있습니다.
- 친구 목록 탭에서 등록한 이미지를 변경하여 재등록할 수 있습니다. 재등록된 사진을 기준으로 인물을 인식합니다.

  <table border="0" >
    <tr>
        <td>    <img width="400" src="https://user-images.githubusercontent.com/66216102/224342071-c6dd10d1-6fbb-4c33-bacb-17c24412957e.gif"> </img></td>
        <td>    <img width="400" src="https://user-images.githubusercontent.com/66216102/224342085-7239d891-27d2-47fb-bc89-8f91e3eea993.gif"> </img></td>
   </tr>
</table>

<br>

### 4️⃣ 비디오 확인하기 & 앨범 생성하기
💬 *비디오 탭에서 만들어진 영상들을 모아 앨범 형태로 제작해보세요!*

- 다양한 감정 상태를 통해 자동으로 영상이 녹화되고, 비디오 탭에 저장됩니다.

  - 비디오 탭에서 영상 미리보기, 감정별 필터링이 가능합니다.

- 저장된 영상은 웹캠 & 모바일 탭의 '최근 저장된 영상' 에서 24시간 내 녹화된 영상들을 바로 확인할 수 있습니다.

<img src="https://user-images.githubusercontent.com/67156494/225967456-39f73e83-a702-4f5b-9dac-04c3014030a3.gif" width=800>
<img src="https://user-images.githubusercontent.com/67156494/225971985-b351b366-82c7-440a-87fe-f98648716174.gif" width=800>



<br>

### 5️⃣ 친구
💬 *친구끼리 앨범 공유를 통해 소중한 추억과 감정들을 공유하고, 아낌없는 축하와 격려를 보내주세요!*
- 친구 ID 또는 이메일을 통해 친구를 맺을 수 있습니다.
- 저장된 영상을 앨범으로 저장하여, 친구들과 소중한 추억을 공유할 수 있습니다.


<br>

### 6️⃣ 감정 리포트
💬 *감정 리포트를 통해 나의 감정 상태를 되돌아보세요!*
- 일주일 간의 저장된 영상들을 통해 감정에 대한 통계를 제공합니다. 

<br>

- 다운로드 기능을 통해 리포트를 보관할 수 있습니다.
- 친구끼리 감정 리포트를 이메일로 공유하고 나의 감정 상태를 친구에게 알릴 수 있습니다.

<br>

<img src="https://user-images.githubusercontent.com/66216102/224341609-e8c745e5-508c-4def-8c04-fa2e9cd05f32.gif" width=800>
  
<br>

## 🚀 서비스 아키텍쳐

<img src="https://user-images.githubusercontent.com/66216102/224341403-20838d86-c17e-414b-9093-160c337fc3b5.png" width=800>

<br>

## 🚀 포스터

<img src="https://user-images.githubusercontent.com/66216102/224221024-947782bc-c67c-4f53-a6ad-7957c980d618.png" width=800>
