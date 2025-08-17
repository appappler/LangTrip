# 🌐 LangTrip - 외국어 이러닝 플랫폼
<img width="733" height="524" alt="프로젝트 대표 이미지" src="https://github.com/user-attachments/assets/e3122149-7951-4333-a8e1-299c0e8d1c14" />

<br/>

## 📑 목차
- [📝 프로젝트 소개](#project-intro)
- [🛠 기술 스택](#tech-stack)
- [💾 ERD](#erd)
- [✨ 주요 기능 소개](#main-features)
- [🎬 시연영상](#demo-video)
- [💁‍♂️ 팀원 소개](#team-members)

---

<h2 id="project-intro">📝 프로젝트 소개</h2>
<strong>Langtrip</strong> 은 외국어 학습에 특화된 이러닝 플랫폼으로, <br>
누구나 강의자가 될 수 있고 쌍방향 후원 및 커뮤니티 소통이 가능한 학습 생태계를 지향합니다.  

기존 이러닝 서비스의 전문가 중심·일방향 강의 제공 방식을 넘어,  
**학습자도 직접 강의를 개설하고 수익을 창출할 수 있는 구조**를 갖추었습니다.  

또한 **후원 기능, 커뮤니티, 질문 게시판**을 통해 학습자 간 자율적인 학습 참여와 지식 공유,  
경제적 보상까지 연결되는 **선순환 기반 외국어 교육 서비스**를 구현했습니다.  

- **개발 기간**: 2024.06.25 ~ 2024.07.29 (7주)  
- **팀 구성**: 8명  
- **아키텍처**: Spring Boot 기반 MVC 구조  

<br/>

<h2 id="tech-stack">🛠 기술 스택</h2>

### Backend
- **Language**: Java (JDK 11)
- **Framework**: Spring Boot, Thymeleaf
- **Authentication & Authorization**: JWT
- **Persistence Layer**: MyBatis
- **Web Server**: NginX
- **WAS**: Apache Tomcat

### Frontend
- **Markup**: HTML5, CSS3
- **Scripting**: JavaScript (AJAX, Axios)
- **Framework**: Bootstrap
- **Library**: jQuery, Chart.js


### Database
- Oracle Database, SQL Developer  

### Development Environment
- **IDE**: Eclipse  
- **OS**: Windows 11  
- **Version Control**: Git / GitHub  

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/mybatis-000000?style=for-the-badge&logo=&logoColor=white"> <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black"> <img src="https://img.shields.io/badge/chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"> <img src="https://img.shields.io/badge/eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

<br/>

<h2 id="erd">💾 ERD</h2>
<img width="4450" height="2457" alt="4조_ERD" src="https://github.com/user-attachments/assets/d17ad19d-07c6-4ba7-bd43-4d73edd1f91e" />


<br/>

<h2 id="main-features">✨ 주요 기능 소개</h2>

### 👥 사용자 기능
- 📚 강의 등록 및 수강 (일반 사용자도 강의 개설 가능)  
- 💖 후원 기능 (다른 사용자에게 후원하거나 후원받기 가능)  
- 🗨 커뮤니티 (강의 추천 게시판 및 자유 소통 공간)  
- 🆘 지원 센터 (FAQ, 공지사항, 1:1 질문 등록)  
- 👤 마이페이지
  - 내 정보 조회, 프로필 사진/비밀번호 변경, 회원 탈퇴  
  - 수강 중인 강의 / 등록한 강의 목록 확인  
  - 내 지갑 (계좌 연동, 정산, 환불 신청)  
  - 내 후원 (후원 내역, 후원받은 내역)  
  - 광고 노출 및 클릭 통계 반영  

### 👨‍💼 관리자 기능
- 📊 7종 통계 대시보드 및 CSV 다운로드 기능 (회원 가입/탈퇴 통계, 광고 클릭 통계)  
- 📝 회원, 강의, 로그, 결제, 후원, 신고, 지원 관리 

<br/>

<h2 id="demo-video">🎬 시연영상</h2>

[![YouTube Video](http://img.youtube.com/vi/rfvgqpy11yg/0.jpg)](https://www.youtube.com/watch?v=rfvgqpy11yg)

<br/>

<h2 id="team-members">💁‍♂️ 팀원 소개</h2>

- **김민진** [팀장 / DBA]  
  - 프로젝트 전체 아키텍처 및 DB 통합  
  - 사용자 마이페이지 메인 프레임 및 Fragment 구조 설계·구현 및 광고 배너 삽입 
  - 내 정보 수정 - 프로필 사진 업로드·이미지 처리, 비밀번호 변경, 회원 탈퇴 기능 구현
  - 관리자 대시보드 회원 통계(Chart.js 7종) 및 CSV 다운로드 기능 개발  
  - 팀 일정·업무 분배 및 최종 프레젠테이션 총괄  

- **김세형** [부팀장]  
  - 관리자 회원가입·이메일인증·로그인·캡차 적용  
  - 사이트 메인 페이지 구성
  - 관리자 로그 관리  
  - 강의 관리 

- **정성재**  
  - 회원가입·로그인·인증 토큰 관리  
  - 소셜 연동 API 구현  
  - 후원금 충전·결제 및 내 지갑·내 후원 기능 구현  

- **심규민**  
  - 강의 등록 및 미디어(영상·이미지) 업로드  
  - 강의 진행률·난이도 설정 및 수강 관리  

- **박선은**  
  - 강의-퀴즈 연동 및 퀴즈 CRUD 구현  
  - 퀴즈 채점 및 결과 저장 로직 처리  

- **최승재**  
  - 커뮤니티 게시글 CRUD 및 추천·개념글 기능  
  - 이미지 업로드 처리  
  - 관리자 댓글·대댓글 관리  

- **이장훈**  
  - 지원센터 FAQ·1:1 문의 등록  
  - 키워드 검색 및 자동 분류 기능 구현  

- **정제균**  
  - 커뮤니티 신고 처리 및 사유 관리  
  - 신고 게시글·댓글 관리  

  
<br/>

---

**© 2025 Donutted Project Team. 본 프로젝트는 교육 목적으로 개발되었습니다.**

> 🙋 README 작성: 김민진
