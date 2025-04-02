# 천재의 서재 - 교과서 기반 문제은행 서비스

<p align="center">
  <img src="./천재의 서재 로고.png" width="300" />
</p>

<p align="center">
  <b>교과서 기반의 단원별 문제를 손쉽게 생성하고 편집할 수 있는 웹 서비스입니다.</b><br>
  선생님과 교육자를 위한 <b>AI 문제 생성</b>, <b>문항 편집</b>, <b>보관 및 다운로드</b> 기능을 제공합니다.
</p>

## 👥 팀 구성원
<a id="section1"></a>
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/hoonee-math">
        <img src="https://github.com/hoonee-math.png" width="100px;" alt="hoonee-math" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>최광훈</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/daineee424">
        <img src="https://github.com/daineee424.png" width="100px;" alt="daineee424" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>정다인</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/blue032">
        <img src="https://github.com/blue032.png" width="100px;" alt="blue032" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>이예진</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/woogamjaa">
        <img src="https://github.com/woogamjaa.png" width="100px;" alt="woogamjaa" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>우민혁</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/my2min0">
        <img src="https://github.com/my2min0.png" width="100px;" alt="my2min0" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>이민영</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/minho0802">
        <img src="https://github.com/minho0802.png" width="100px;" alt="minho0802" style="border-radius:50%; border: 2px solid #00000033;"/>
        <br/>
        <sub><b>김민호</b></sub>
      </a>
    </td>
  </tr>
</table>

## 🛠 기술 스택

### 🎨 Frontend
<div align="left">
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Pinia-76D275?style=for-the-badge&logo=pinia&logoColor=white" />
  <img src="https://img.shields.io/badge/VueRouter-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</div>

### 🧩 Backend
<div align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
</div>

### 🗄️ Database / DevOps
<div align="left">
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
</div>

### 🧑‍💻 개발 환경
<div align="left">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</div>

## 📂 레포지토리

| 구분 | 링크 | 
|------|------|
| 🖥️ Frontend | [2nd_GenieQ_FrontEnd](https://github.com/ChunJae-Full-Stack-FinalProject/2nd_GenieQ_FrontEnd) 
| 🛠️ Backend  | [2nd_GenieQ_BackEnd](https://github.com/ChunJae-Full-Stack-FinalProject/2nd_GenieQ_BackEnd) 
<details>
<summary>🖥️ 프론트엔드 구조 보기</summary>
<pre><code>
├─📁 src/
│  ├─📁 assets/
│  │  ├─📁 css/
│  │  │  ├─📄 common.css
│  │  │  ├─📄 font.css
│  │  │  └─📄 reset.css
│  │  │
│  │  ├─📁 js/
│  │  │  ├─📄 common.js
│  │  │  └─📄 jquery-ui.js
│  │  │
│  │  ├─📁 json/
│  │  │  ├─📄 books.json
│  │  │  ├─📄 count.json
│  │  │  └─📄 schoolDistrict.json
│  │  │
│  │  ├─📁 policy/
│  │  │
│  │  ├─📁 scss/
│  │  │  ├─📄 _mixin.scss
│  │  │  ├─📄 _setting.scss
│  │  │  └─📄 common.scss
│  │  │
│  │  ├─📄 base.css
│  │  └─📄 main.css
│  │
│  ├─📁 components/
│  │  ├─📁 auth/
│  │  │  ├─📄 Login.vue
│  │  │  ├─📄 PasswordSearch.vue
│  │  │  ├─📄 SearchSchool.vue
│  │  │  ├─📄 SignUp.vue
│  │  │  └─📄 TempPasswordNotice.vue
│  │  │
│  │  ├─📁 common/
│  │  │  ├─📁 button/
│  │  │  │  └─📄 BaseButton.vue
│  │  │  │
│  │  │  ├─📁 modal/
│  │  │  │  ├─📁 auth/
│  │  │  │  │  ├─📄 PrivacyModal.vue
│  │  │  │  │  └─📄 TermsModal.vue
│  │  │  │  │
│  │  │  │  ├─📄 BaseModal.vue
│  │  │  │  └─📄 LoadingModal.vue
│  │  │  │
│  │  │  ├─📄 Footer.vue
│  │  │  ├─📄 Header.vue
│  │  │  └─📄 Loading.vue
│  │  │
│  │  ├─📁 paper/
│  │  │  └─📄 PaperListComponent.vue
│  │  │
│  │  └─📁 subject/
│  │     └─📄 SubjectListComponent.vue
│  │
│  ├─📁 composables/
│  │  └─📄 useParentAuth.js
│  │
│  ├─📁 plugins/
│  │  └─📄 axios.js
│  │
│  ├─📁 router/
│  │  └─📄 index.js
│  │
│  ├─📁 stores/
│  │  ├─📄 auth.js
│  │  ├─📄 paper.js
│  │  └─📄 subject.js
│  │
│  ├─📁 views/
│  │  ├─📁 paper/
│  │  │  ├─📄 PaperPopup.vue
│  │  │  ├─📄 PaperSave.vue
│  │  │  ├─📄 PaperSaveComplete.vue
│  │  │  └─📄 PaperSummary.vue
│  │  │
│  │  └─📄 HomeView.vue
│  │
│  ├─📄 App.vue
│  └─📄 main.js
│
├─📄 .env.development
├─📄 .env.production
├─📄 index.html
├─📄 jsconfig.json
├─📄 package-lock.json
├─📄 package.json
└─📄 vite.config.js
</code></pre>
</details>

<details>
<summary>🛠️ 백엔드 구조 보기</summary>
<pre><code>
└─📁 main/
   ├─📁 java/
   │  └─📁 com/
   │     └─📁 cj/
   │        └─📁 genius/
   │           ├─📁 answer/
   │           │  ├─📁 controller/
   │           │  │  └─📄 AnswerController.java
   │           │  │
   │           │  ├─📁 dto/
   │           │  │  ├─📁 request/
   │           │  │  │  └─📄 AnswerRequestDto.java
   │           │  │  │
   │           │  │  └─📁 response/
   │           │  │     ├─📄 Answer.java
   │           │  │     └─📄 AnswerResponseDto.java
   │           │  │
   │           │  ├─📁 entity/
   │           │  │  └─📄 AnswerEntity.java
   │           │  │
   │           │  ├─📁 repository/
   │           │  │  └─📄 AnswerRepository.java
   │           │  │
   │           │  └─📁 service/
   │           │     ├─📄 AnswerService.java
   │           │     └─📄 AnswerServiceImpl.java
   │           │
   │           ├─📁 common/
   │           │  └─📁 config/
   │           │     ├─📄 IsSameUser.java
   │           │     ├─📄 JwtAuthenticationFilter.java
   │           │     ├─📄 JwtTokenProvider.java
   │           │     ├─📄 SecurityConfig.java
   │           │     ├─📄 SwaggerConfig.java
   │           │     └─📄 WebMvcConfig.java
   │           │
   │           ├─📁 exam/
   │           │  ├─📁 controller/
   │           │  │  └─📄 ExamController.java
   │           │  │
   │           │  ├─📁 dto/
   │           │  │  ├─📁 request/
   │           │  │  │  ├─📄 ExamDeleteEachRequestDto.java
   │           │  │  │  ├─📄 ExamDeleteListRequestDto.java
   │           │  │  │  ├─📄 ExamInsertRequestDto.java
   │           │  │  │  ├─📄 ExamSelectAllRequestDto.java
   │           │  │  │  └─📄 ExamSelectEachRequestDto.java
   │           │  │  │
   │           │  │  ├─📁 response/
   │           │  │  │  ├─📄 ExamSelectAllResponseDto.java
   │           │  │  │  ├─📄 ExamSelectEachResponseDto.java
   │           │  │  │  └─📄 ExamSelectResponseDto.java
   │           │  │  │
   │           │  │  └─📄 Exam.java
   │           │  │
   │           │  ├─📁 entity/
   │           │  │  └─📄 ExamEntity.java
   │           │  │
   │           │  ├─📁 repository/
   │           │  │  └─📄 ExamRepository.java
   │           │  │
   │           │  └─📁 service/
   │           │     ├─📄 ExamService.java
   │           │     └─📄 ExamServiceImpl.java
   │           │
   │           ├─📁 member/
   │           │  ├─📁 controller/
   │           │  │  └─📄 MemberController.java
   │           │  │
   │           │  ├─📁 dto/
   │           │  │  ├─📁 request/
   │           │  │  │  ├─📄 FindPasswordRequestDto.java
   │           │  │  │  ├─📄 LoginRequestDto.java
   │           │  │  │  ├─📄 SignUpRequestDto.java
   │           │  │  │  └─📄 WithdrawRequestDto.java
   │           │  │  │
   │           │  │  ├─📁 response/
   │           │  │  │  ├─📄 FindEntireResponseDto.java
   │           │  │  │  └─📄 LoginMemberResponseDto.java
   │           │  │  │
   │           │  │  ├─📄 Member.java
   │           │  │  └─📄 TokenResponseDto.java
   │           │  │
   │           │  ├─📁 entity/
   │           │  │  └─📄 MemberEntity.java
   │           │  │
   │           │  ├─📁 repository/
   │           │  │  └─📄 MemberRepository.java
   │           │  │
   │           │  └─📁 service/
   │           │     ├─📄 AuthService.java
   │           │     ├─📄 AuthServiceImpl.java
   │           │     └─📄 CustomUserDetailsService.java
   │           │
   │           ├─📁 pdf/
   │           │  ├─📁 config/
   │           │  │  └─📄 AppConfig.java
   │           │  │
   │           │  ├─📁 controller/
   │           │  │  └─📄 PdfController.java
   │           │  │
   │           │  ├─📁 dto/
   │           │  │  ├─📄 ExamRequestDto.java
   │           │  │  ├─📄 ExamResponseDto.java
   │           │  │  ├─📄 ItemDetailDto.java
   │           │  │  └─📄 QuestionDto.java
   │           │  │
   │           │  ├─📁 repository/
   │           │  │  ├─📄 PdfRepository.java
   │           │  │  └─📄 PdfRepositoryImpl.java
   │           │  │
   │           │  └─📁 service/
   │           │     ├─📄 ExamItemService.java
   │           │     └─📄 ExamPdfService.java
   │           │
   │           ├─📁 question/
   │           │  ├─📁 controller/
   │           │  │  └─📄 QuestionController.java
   │           │  │
   │           │  ├─📁 dto/
   │           │  │  ├─📁 request/
   │           │  │  │  └─📄 QuestionInsertRequestDto.java
   │           │  │  │
   │           │  │  └─📁 response/
   │           │  │     └─📄 QuestionResponseDto.java
   │           │  │
   │           │  ├─📁 entity/
   │           │  │  └─📄 QuestionEntity.java
   │           │  │
   │           │  ├─📁 repository/
   │           │  │  └─📄 QuestionRepository.java
   │           │  │
   │           │  └─📁 service/
   │           │     ├─📄 QuestionService.java
   │           │     └─📄 QuestionServiceImpl.java
   │           │
   │           ├─📁 result/
   │           │  ├─📁 controller/
   │           │  │  └─📄 ResultController.java
   │           │  │
   │           │  ├─📁 dto/
   │           │  │  ├─📁 request/
   │           │  │  │  └─📄 ResultRequestDto.java
   │           │  │  │
   │           │  │  └─📁 response/
   │           │  │     ├─📄 Result.java
   │           │  │     └─📄 ResultResponseDto.java
   │           │  │
   │           │  ├─📁 entity/
   │           │  │  └─📄 ResultEntity.java
   │           │  │
   │           │  ├─📁 repository/
   │           │  │  └─📄 ResultRepository.java
   │           │  │
   │           │  └─📁 service/
   │           │     ├─📄 ResultService.java
   │           │     └─📄 ResultServiceImpl.java
   │           │
   │           ├─📁 school/
   │           │  ├─📁 controller/
   │           │  │  └─📄 SchoolController.java
   │           │  │
   │           │  ├─📁 dto/
   │           │  │  ├─📁 request/
   │           │  │  │  └─📄 SchoolRequestDto.java
   │           │  │  │
   │           │  │  └─📁 response/
   │           │  │     ├─📄 School.java
   │           │  │     └─📄 SchoolResponseDto.java
   │           │  │
   │           │  ├─📁 entity/
   │           │  │  └─📄 SchoolEntity.java
   │           │  │
   │           │  ├─📁 repository/
   │           │  │  └─📄 SchoolRepository.java
   │           │  │
   │           │  └─📁 service/
   │           │     ├─📄 SchoolService.java
   │           │     └─📄 SchoolServiceImpl.java
   │           │
   │           ├─📁 test/
   │           │  ├─📄 TestController.java
   │           │  └─📄 TestCustomUserDetailsService.java
   │           │
   │           └─📄 GeniusApplication.java
   │
   ├─📁 resources/
   │  ├─📁 fonts/
   │  │
   │  ├─📁 images/
   │  │  ├─📄 genius_library_logo.png
   │  │  ├─📄 genius_library_logo_two_rows.png
   │  │  └─📄 logo_row_no_margin.png
   │  │
   │  ├─📁 initdata/
   │  │
   │  ├─📄 application-private.properties
   │  ├─📄 application-private.properties.template
   │  ├─📄 application.properties
   │  └─📄 datasource.properties
   │
</code></pre>
</details>

## ✨ 주요 기능

### 📝 문제 생성 및 편집 
교과서 단원별로 제공되는 문제를 선택하여, 시험지를 자유롭게 구성하고 편집할 수 있습니다. 
<img src="./generate.gif" width="100%" alt="시험지 생성 시연" />

### 📄 시험지 다운로드
완성된 시험지는 PDF, Word, TXT 형식으로 다운로드할 수 있어 수업에 바로 활용할 수 있습니다.
<img src="./exam.gif" width="100%" alt="시험지 다운로드 시연" />

## 🗂 ERD 설계도

천재의 서재 데이터베이스 구조를 시각적으로 표현한 ERD입니다.

<img src="./erd.png" alt="ERD 설계도" width="100%" />
