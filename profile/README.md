## Hi there 👋 We are "Port"

# Voilio ✨
영상기반의 포트폴리오 웹서비스

## VERSION 2. BY
| Name    | 정길연   |  김인철   |  양소연  |  김미영    |  김주언  |
| ------- | -------| ---------| ----- | -------- | -------- | 
| Profile | <img width="200px" src="https://avatars.githubusercontent.com/u/52391627?v=4">    | <img width="200px" src="https://avatars.githubusercontent.com/u/82080962?v=4" />  | <img width="200px" src="https://avatars.githubusercontent.com/u/125855539?v=4"/>    | <img width="200px" src="https://avatars.githubusercontent.com/u/96506175?v=4"/>  | <img width="200px" src="https://avatars.githubusercontent.com/u/91904079?v=4"/>  |
| Role    | Team Leader, Backend | Backend | Frontend   | Frontend | Backend |
| gitHub  | [gilyeon00](https://github.com/gilyeon00) | [kimich1218](https://github.com/kimich1218)   | [Xoeon](https://github.com/Xoeon)    |  [miyoung12](https://github.com/miyoung12) | [wndjs803](https://github.com/wndjs803) |

---

## 💡Tech Stack

<br>

<p align="center">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">

</p>  
<p align="center">
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white">
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=SpringSecurity&logoColor=white">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white">
  </p>
<p align="center">
<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white"/>
<img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> 
<img src="https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=GitKraken&logoColor=white"> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> 
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white">
<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white">

</p>

```
- Backend : Spring Boot
- Frontend : React
- Web Server: Nginx
- DevOps : Docker
- Database: MySQL
- API Documentation : Swagger
- Deployment : AWS EC2
- VCS: Git
```

## 💻 System Architecture
![아키텍처(1029ver)](https://github.com/techeer-sv/Voilio/assets/52391627/36732ad5-9f26-4515-9b3a-319e61976503)


## 🚀 How to Start

### 1. Clone Repository 

```
git clone --recursive https://github.com/techeer-sv/Voilio.git
```


### 2. Env Settings

- Add /Voilio/.env file

```bash
# === Database ===
MYSQL_ROOT_PASSWORD=
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_DATABASE=
SPRING_DATASOURCE_PASSWORD=
```

- Add /Voilio/backend/src/resources/application-secret.yml

```bash
# === S3Bucket ===
spring:
  config:
    activate:
      on-profile: secret

cloud:
  aws:
    credentials:
      accessKey: 
      secretKey: 
    s3:
      bucket: 
    region:
      static: 
    stack:
      auto: false
```

### 3. Run Docker

```
$ docker-compose up --build   
# build images and run containers
```

---

## VERSION 1. BY
| Name    | 정길연   |  강용민   | 김인철  |  백한결    |
| ------- | -------| ---------| ----- | -------- | 
| Profile | <img width="200px" src="https://avatars.githubusercontent.com/u/52391627?v=4">    | <img width="200px" src="https://avatars.githubusercontent.com/u/84130518?v=4" />  | <img width="200px" src="https://avatars.githubusercontent.com/u/82080962?v=4"/>    | <img width="200px" src="https://avatars.githubusercontent.com/u/76465887?v=4"/>  |
| Role    | Team Leader, Backend, Frontend | Backend, Frontend | Backend   | Backend |
| gitHub  | [gilyeon00](https://github.com/gilyeon00) | [goldapple-ce](https://github.com/goldapple-ce)   | [kimich1218](https://github.com/kimich1218)    |  [snake7667](https://github.com/snake7667) |


