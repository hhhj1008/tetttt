<div align="center">
  <img src="https://user-images.githubusercontent.com/110225060/216814005-d3edebfb-d0a8-43ce-9dcb-9b6a3c6d13e5.png" width=200/>

## 🐰 [덕마니](https://www.deokman.site/) 받아!

</div>

---

<br>

## **덕마니는 어떤 사이트 인가요?**

“_덕마니_”는 2023년 계묘년을 맞이하여 새해 소원을 작성하고 응원하는 서비스로 소원 작성 시 자주 사용되는 키워드의 순위도 확인할 수 있습니다. 사용자가 작성한 소원과 응원은 사용자의 로컬 스토리지에 저장되며, 캐시가 초기화될 때는 해당 정보를 볼 수 없습니다.

<br>

## **개발 기간 및 인원**

<br>

### 개발 기간

2022.12.20 - 2023.01.20 (1개월)

### 개발 인원

프론트 엔드(3명), 백엔드(2명)

<br>

## **기술 스택**

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Node.js-39933?style=for-the-badge&logo=Node.js&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Mongoose-68BC71?style=for-the-badge&logo=MongoDB&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/RESTful API-2478CC?style=for-the-badge&logo=RESTful API&logoColor=white"/>&nbsp;

<br>

## **데이터베이스 스키마**

![덕마니 소원](https://user-images.githubusercontent.com/110225060/216817622-a9b8905c-56ce-404e-80b4-019ce80f580a.png)

![덕마니 키워드](https://user-images.githubusercontent.com/110225060/216817619-a3b865bd-2d69-4027-806a-d22841b7486e.png)

<br>

## **프로젝트 구조**

```
📦 deokman
 ┗ 📂src
  ┣ 📂batch
  ┣ 📂common
  ┣ 📂controllers
  ┣ 📂middleware
  ┣ 📂models
  ┣ 📂routes
  ┣ 📂schema
  ┣ 📂services
  ┣ 📜app.js
  ┗ 📜server.js
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┗ ⚙️.env
```

<br>

## **프로젝트 실행 방법**

### 1. 레포지토리 clone

```
git clone https://github.com/hhhj1008/newYearProject.git
```

### 2. Node.js 패키지 설치

```
npm i
```

### 3. 파이썬 패키지 설치

(선행 사항으로 파이썬이 설치되어 있어야 합니다.)

```
pip install JPype1
pip install konlpy
```

### 4. 4. .env 환경변수 설정

```
PORT = {Port 번호}
DB_URI = {데이터베이스 URL}
ex) mongodb://{id}:{password}@{ip address}:{port}/{db name}
```

### 4. 프로젝트 실행

```
node .\src\server.js
nodemon ./src/server.js         // 개발 모드로 실행
```

<br>

**기능의 동작은 [API 명세서](https://documenter.getpostman.com/view/22723440/2s8Z6zzrw1#08c2d24d-0bb8-4d68-8c3d-faf1e4da49a7) 참조**

<br>

## **개발자 정보**

<br>

<div align="center">
  <img src="https://user-images.githubusercontent.com/110225060/216816108-82e39553-7327-4893-958c-1779941b5f19.png" width=300/>

  <br>

### 백엔드

**[전준영](https://github.com/Jyoung706)**
**[김현정](https://github.com/hhhj1008)**

### 프론트엔드

**[박찬영](https://github.com/Poylib)**
**[박유빈](https://github.com/daydreamplace)**
**[정예원](https://github.com/ioni19)**

</div>
