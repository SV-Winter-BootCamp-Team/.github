# 꾸며Zoom
<img src="https://github.com/SV-Winter-BootCamp-TeamD/backend/assets/41982054/5548c201-b987-4d7c-b1ab-16311ac0b6f5" width="300" height="300"/>
<br>
<br>
AI를 활용한 가상 배경 꾸미는 서비스
<br>
<br>
<데모 GIF>

## 📘 Medium

✔️ Introduction → medium링크 붙이기
<br>
<br>

📍System-Architecture
<br>

<img width="1126" alt="111Untitled" src="https://github.com/SV-Winter-BootCamp-TeamD/backend/assets/41982054/e6974ebb-5b4c-4f75-8d1e-5391078258c7">
<br>
<br>
<br>

### ⚒️ Tech Stach
<br>
<br>

|Frontend|Backend|DB|Devops|Monitoring|Etc| 
|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|------|------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
|<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">|<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">|<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">|<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white">|<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white">|<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">|
|<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white">|<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Kibana&logoColor=white">|<img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white">|<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">|<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white">|<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">|
|<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=Three.js&logoColor=white">|<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=Nginx&logoColor=white">|<img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white">||<img src="https://img.shields.io/badge/Elastic Stack-005571?style=for-the-badge&logo=Elastic Stack&logoColor=white">|<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white">|
|<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white">|<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white">||||<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white">|
|<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">|<img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white">||||<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white">|
||<img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=Gunicorn&logoColor=white">|||||







<br>
<br>
<br>

## 🔍 ERD

![스크린샷(144)](https://github.com/SV-Winter-BootCamp-TeamD/frontend/assets/110004440/1aea8da8-f9c4-4218-8667-226f853f108d)
<br>
<br>

## 💡Swagger API
<div align="center">
<img width="1000" alt="Untitled" src="https://github.com/SV-Winter-BootCamp-TeamD/backend/assets/41982054/52718d87-cdd1-40a6-a143-4c6691984400">
</div>

<br>
<br>

## 📊 Monitoring

<img width="1815" alt="Un221titled" src="https://github.com/SV-Winter-BootCamp-TeamD/backend/assets/41982054/90f5c285-008a-4856-a427-ba7c1f7419e3">

<br>
<br>

### ELK Stack

![U33ntitled](https://github.com/SV-Winter-BootCamp-TeamD/backend/assets/41982054/aa862aba-d526-4dee-b891-fb58d346260e)

<br>
<br>

## 🚀 How to Start

Clone Repository

```jsx
https://github.com/SV-Winter-BootCamp-TeamD/backend.git
```

### .env setting in the Settings folder

frontend/.env

```jsx
VITE_BASE_URL = 
VITE_SOCKET_URL = 
```

backend/.env

```jsx
SECRET_KEY=

DATABASE_NAME=
DATABASE_USERNAME=
DATABASE_PASSWORD=
DATABASE_HOST=
DATABASE_PORT=
MYSQL_ROOT_PASSWORD=

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_STORAGE_BUCKET_NAME=
AWS_S3_REGION_NAME=

OPENAI_API_KEY=
PIXABAY_API_KEY=
```

### Run Docker

```jsx
docker compose -f docker.compose.prod.yml up --build
```

📂 Directory Structure
<details>
  <summary>frontend</summary>
    
    ```jsx
    frontend/
    ├── Dockerfile
    ├── README.md
    ├── docker-compose.yml
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── public
    │   ├── animations
    │   │   └── json
    │   │       ├── data.json
    │   │       └── webSocket.json
    │   └── images
    │       ├── png
    │       │   ├── mm1.png
    │       │   ├── mm2.png
    │       │   ├── startImage.png
    │       │   └── websocketImage.png
    │       └── svg
    │           ├── aiImage.svg
    │           ├── aibackground.svg
    │           ├── aisticker.svg
    │           ├── avator.svg
    │           ├── backarrow.svg
    │           ├── background.svg
    │           ├── backgroundupload.svg
    │           ├── brush.svg
    │           ├── download.svg
    │           ├── examples
    │           │   ├── example01.svg
    │           │   ├── example02.svg
    │           │   ├── example03.svg
    │           │   ├── example04.svg
    │           │   ├── example05.svg
    │           │   ├── example06.svg
    │           │   ├── example07.svg
    │           │   ├── example08.svg
    │           │   ├── example09.svg
    │           │   ├── example10.svg
    │           │   ├── example11.svg
    │           │   ├── example12.svg
    │           │   ├── example13.svg
    │           │   ├── example14.svg
    │           │   ├── example15.svg
    │           │   ├── example16.svg
    │           │   ├── example17.svg
    │           │   ├── example18.svg
    │           │   ├── example19.svg
    │           │   ├── example20.svg
    │           │   ├── example21.svg
    │           │   ├── example22.svg
    │           │   ├── example23.svg
    │           │   ├── example24.svg
    │           │   ├── example25.svg
    │           │   ├── example26.svg
    │           │   ├── example27.svg
    │           │   ├── example28.svg
    │           │   ├── example29.svg
    │           │   └── example30.svg
    │           ├── exit.svg
    │           ├── favicon.svg
    │           ├── frontarrow.svg
    │           ├── hamburger.svg
    │           ├── history.svg
    │           ├── home.svg
    │           ├── info.svg
    │           ├── invite.svg
    │           ├── mycanvas.svg
    │           ├── object.svg
    │           ├── onBoarding1.svg
    │           ├── onBoarding2.svg
    │           ├── palette.svg
    │           ├── plus.svg
    │           ├── recommendbackground.svg
    │           ├── startImage.svg
    │           ├── text.svg
    │           ├── trashcan.svg
    │           ├── upload.svg
    │           ├── webSocketImage.svg
    │           ├── x.svg
    │           └── 무제-1.svg
    ├── src
    │   ├── App.tsx
    │   ├── animations
    │   │   └── json
    │   │       ├── startImage.json
    │   │       └── webSocket.json
    │   ├── api
    │   │   └── api.ts
    │   ├── components
    │   │   ├── CanvasPage
    │   │   │   ├── AIBackground
    │   │   │   │   ├── AIBackground.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── AIBackgroundGenerator
    │   │   │   │   ├── AIBackgroundGenerator.tsx
    │   │   │   │   ├── Color.tsx
    │   │   │   │   ├── Input.tsx
    │   │   │   │   ├── Theme.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── AIBackgroundLoading
    │   │   │   │   ├── AIBackgroundLoading.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── AISticker
    │   │   │   │   ├── AISticker.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── AIStickerGenerator
    │   │   │   │   ├── AIStickerGenerator.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── AIStickerLoading
    │   │   │   │   ├── AIStickerLoading.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── Canvas
    │   │   │   │   ├── Canvas.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── History
    │   │   │   │   ├── History.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── Invite
    │   │   │   │   ├── Input.tsx
    │   │   │   │   ├── Invite.tsx
    │   │   │   │   ├── MemberList.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── MenuBar
    │   │   │   │   ├── Button.tsx
    │   │   │   │   ├── MenuBar.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── MenuSection
    │   │   │   │   ├── MenuSection.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── MyCanvas
    │   │   │   │   ├── MyCanvas.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── NavBar
    │   │   │   │   ├── NavBar.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── RecommendBackground
    │   │   │   │   ├── RecommendBackground.tsx
    │   │   │   │   └── index.tsx
    │   │   │   ├── RecommendBackgroundLoading
    │   │   │   │   ├── RecommendBackgroundLoading.tsx
    │   │   │   │   └── index.tsx
    │   │   │   └── UploadBackground
    │   │   │       ├── UploadBackground.tsx
    │   │   │       ├── UploadButton.tsx
    │   │   │       └── index.tsx
    │   │   ├── GenearateButton
    │   │   │   ├── GenerateButton.tsx
    │   │   │   └── index.tsx
    │   │   ├── General
    │   │   │   └── ReGenerateButton
    │   │   │       ├── ReGenerateButton.tsx
    │   │   │       └── index.tsx
    │   │   ├── MainPage
    │   │   │   └── CanvasPreview
    │   │   │       ├── CanvasPreview.tsx
    │   │   │       └── index.tsx
    │   │   ├── OnBoarding
    │   │   │   ├── Desk.gltf
    │   │   │   ├── ImageSlider.tsx
    │   │   │   ├── OnBoardingTemplate.tsx
    │   │   │   ├── PathDrawing.tsx
    │   │   │   ├── ThreeTest.tsx
    │   │   │   ├── background2.png
    │   │   │   └── index.tsx
    │   │   └── SignupPage
    │   │       └── img
    │   │           └── background.png
    │   ├── index.css
    │   ├── main.tsx
    │   ├── pages
    │   │   ├── CanvasPage.tsx
    │   │   ├── LoginPage.tsx
    │   │   ├── MainPage.tsx
    │   │   ├── OnBoardingPage.tsx
    │   │   ├── SideBar.tsx
    │   │   └── SignUpPage.tsx
    │   ├── type.ts
    │   └── vite-env.d.ts
    ├── tailwind.config.js
    ├── tsconfig.json
    ├── tsconfig.node.json
    ├── vite.config.ts
    └── yarn.lock
    ```
</details>

<details>
  <summary><b>backend</b></summary>
     
    ```jsx
    backend
    ├── Dockerfile
    ├── README.md
    ├── alertmanager
    │   └── config.yml
    ├── backend
    │   ├── __init__.py
    │   ├── __pycache__
    │   │   ├── __init__.cpython-310.pyc
    │   │   ├── __init__.cpython-311.pyc
    │   │   ├── asgi.cpython-310.pyc
    │   │   ├── asgi.cpython-311.pyc
    │   │   ├── celery.cpython-310.pyc
    │   │   ├── celery.cpython-311.pyc
    │   │   ├── settings.cpython-310.pyc
    │   │   ├── settings.cpython-311.pyc
    │   │   ├── urls.cpython-310.pyc
    │   │   ├── urls.cpython-311.pyc
    │   │   └── wsgi.cpython-310.pyc
    │   ├── asgi.py
    │   ├── celery.py
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── canvas
    │   ├── __init__.py
    │   ├── __pycache__
    │   │   ├── __init__.cpython-310.pyc
    │   │   ├── __init__.cpython-311.pyc
    │   │   ├── apps.cpython-310.pyc
    │   │   ├── apps.cpython-311.pyc
    │   │   ├── consumers.cpython-310.pyc
    │   │   ├── consumers.cpython-311.pyc
    │   │   ├── models.cpython-310.pyc
    │   │   ├── models.cpython-311.pyc
    │   │   ├── routing.cpython-310.pyc
    │   │   ├── routing.cpython-311.pyc
    │   │   ├── serializers.cpython-310.pyc
    │   │   ├── serializers.cpython-311.pyc
    │   │   ├── tests.cpython-310.pyc
    │   │   ├── tests.cpython-311.pyc
    │   │   ├── urls.cpython-310.pyc
    │   │   ├── urls.cpython-311.pyc
    │   │   ├── views.cpython-310.pyc
    │   │   └── views.cpython-311.pyc
    │   ├── apps.py
    │   ├── consumers.py
    │   ├── models.py
    │   ├── routing.py
    │   ├── serializers.py
    │   ├── tests.py
    │   ├── urls.py
    │   └── views.py
    ├── component
    │   ├── AI_utils.py
    │   ├── __init__.py
    │   ├── __pycache__
    │   │   ├── AI_utils.cpython-310.pyc
    │   │   ├── AI_utils.cpython-311.pyc
    │   │   ├── __init__.cpython-310.pyc
    │   │   ├── __init__.cpython-311.pyc
    │   │   ├── apps.cpython-310.pyc
    │   │   ├── apps.cpython-311.pyc
    │   │   ├── models.cpython-310.pyc
    │   │   ├── models.cpython-311.pyc
    │   │   ├── nukki.cpython-310.pyc
    │   │   ├── nukki.cpython-311.pyc
    │   │   ├── recommend.cpython-310.pyc
    │   │   ├── recommend.cpython-311.pyc
    │   │   ├── s3_utils.cpython-310.pyc
    │   │   ├── s3_utils.cpython-311.pyc
    │   │   ├── serializers.cpython-310.pyc
    │   │   ├── serializers.cpython-311.pyc
    │   │   ├── tasks.cpython-310.pyc
    │   │   ├── tasks.cpython-311.pyc
    │   │   ├── tests.cpython-310.pyc
    │   │   ├── tests.cpython-311.pyc
    │   │   ├── views.cpython-310.pyc
    │   │   └── views.cpython-311.pyc
    │   ├── apps.py
    │   ├── models.py
    │   ├── nukki.py
    │   ├── recommend.py
    │   ├── s3_utils.py
    │   ├── serializers.py
    │   ├── tasks.py
    │   ├── tests.py
    │   └── views.py
    ├── docker-compose.yml
    ├── grafana
    │   ├── alerting
    │   │   └── 1
    │   │       └── __default__.tmpl
    │   ├── csv
    │   ├── grafana.db
    │   ├── plugins
    │   └── png
    ├── manage.py
    ├── nginx
    │   └── log
    │       └── acess.log
    ├── prometheus
    │   ├── alert.yml
    │   └── prometheus.yml
    ├── requirements.txt
    └── user
        ├── __init__.py
        ├── __pycache__
        │   ├── __init__.cpython-310.pyc
        │   ├── __init__.cpython-311.pyc
        │   ├── apps.cpython-310.pyc
        │   ├── apps.cpython-311.pyc
        │   ├── models.cpython-310.pyc
        │   ├── models.cpython-311.pyc
        │   ├── serializers.cpython-310.pyc
        │   ├── serializers.cpython-311.pyc
        │   ├── tests.cpython-310.pyc
        │   ├── tests.cpython-311.pyc
        │   ├── urls.cpython-310.pyc
        │   ├── urls.cpython-311.pyc
        │   ├── views.cpython-310.pyc
        │   └── views.cpython-311.pyc
        ├── apps.py
        ├── authentication.py
        ├── models.py
        ├── serializers.py
        ├── tests.py
        ├── urls.py
        └── views.py
    ```
</details>
 
    

👨‍👩‍👧‍👦 Member
<table>
  <tbody>
    <tr>
      <td align="center"><a href=""><img src="" width="300px;" alt=""/><br /><sub><b>Frontend 팀장 : 백유진</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="" width="300px;" alt=""/><br /><sub><b>Frontend 팀원 : 김영준</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="" width="300px;" alt=""/><br /><sub><b>Backend 팀원 : 조희은</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="" width="300px;" alt=""/><br /><sub><b>Backend 팀원 : 고예진</b></sub></a><br /></td>
      <td align="center"><a href=""><img src="" width="300px;" alt=""/><br /><sub><b>Backend 팀원 : 민정준</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>
