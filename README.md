<div align="center">
  <img src="https://user-images.githubusercontent.com/110225060/197337903-82af5ddd-444f-443b-a16a-b48b56ef2bf1.png" width=200/>


  ### 이거사조팀의 **holaworld** 클론 코딩 프로젝트
</div>

---

<br>

## **프로젝트 개요**
```
부트 캠프에서의 첫 프로젝트인 만큼, 웹 개발의 기본적인 기능을 경험하고자 선정한 사이트입니다.

게시글과 댓글의 작성, 읽기, 수정, 삭제 등 기본 기능을 포함하여 node.js를 이용한RESTful API 
개발 과정을 경험할 수 있던 프로젝트입니다.
```

<br>

## **개발 기간 및 인원**

<br>

### 개발 기간
2022.08.29 ~ 2022.09.08 (2주)

### 개발 인원
프론트 엔드(4명), 백엔드(2명)

<br>

## **기술 스택**
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Node.js-39933?style=for-the-badge&logo=Node.js&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/TypeORM-262627?style=for-the-badge&logo=TypeORM&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/RESTful API-2478CC?style=for-the-badge&logo=RESTful API&logoColor=white"/>&nbsp;

<br>

## **DB 모델링**
![](https://user-images.githubusercontent.com/110225060/197342659-41c8fe87-7d62-4e41-a043-8bddd7b9c064.png)

<br>

## **프로젝트 구조**
```
📦/
 ┣ 📂controllers
 ┣ 📂db
 ┣ 📂middleware
 ┣ 📂models
 ┣ 📂routes
 ┣ 📂services
 ┣ 📜app.js.js
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┗ 📜server.js
```


<br>

## **프로젝트 실행 방법**
### 1. 레포지토리 clone
```
git clone https://github.com/hhhj1008/justcode-6-1st-this.4team-back.git
```

### 2. 프로젝트 폴더 선택 후 아래의 명령어 실행
```
npm i
```

### 3. 데이터베이스 스키마 설정
dbmate 설치 관련은 [참조](https://github.com/amacneil/dbmate)
```
dbmate up
```

### 4. .env 환경변수 설정
```
DATABASE_URL={dbmate 연동 URL} 
ex) mysql://{user}:{password}@{host}:{port}/{dbname}
TYPEORM_CONNECTION = 사용할 데이터베이스 종류
TYPEORM_HOST = host              
TYPEORM_PORT = port                   
TYPEORM_USERNAME = user               
TYPEORM_PASSWORD = password         
TYPEORM_DATABASE = dbname
```

### 5. 프로젝트 실행
```
npm start
```

<br>

## **프로젝트 시연 영상**
[![프로젝트 시연 영상](http://img.youtube.com/vi/xo1gqoUQRx0/0.jpg)](https://youtu.be/xo1gqoUQRx0?t=0s)

<br>

## **API 명세서**
### 📌[API 명세서 ](https://documenter.getpostman.com/view/22723177/VUxNR7mw#dd4ed3cb-7fdc-4575-8732-19c22d916e9b)

<br>

## **역할 및 알게 된 점**

### 역할
1. 회원 가입 및 로그인
2. 사용자 정보 불러오기 및 수정
3. 게시글 세부페이지 불러오기
4. 게시글 목록 불러오기 (필터링, 페이지네이션)

<br>

### 알게 된 점
- `RESTful API` 구조 및 원칙 이해
- `jwt` 를 사용한 인증/인가 방식 활용
- `node.js` 로 백엔드 서버 구축 경험

<br>
