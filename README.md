# CropDoctor

![D8771DDC-42B5-42E6-922B-01C0443DB602](https://user-images.githubusercontent.com/83527046/215812755-bda68906-ce2e-41de-b671-4f2a555b3777.png)

<br>

## 🍀 Introduction

저희 Cropdoctor는 사용자의 작물의 질병을 진단해주는 서비스로 질병에 맞는 해결책을 제시해드립니다. 👩🏻‍🌾 

<br>

## 📌 System Architecture
![MacBook Pro 16_ - 1](https://user-images.githubusercontent.com/83527046/215812708-2d8dc494-2d49-4aea-8192-152852902497.png)


## 📚 TECH STACKS

|Frontend|Backend|Monitoring|DevOps|
|:------:|:------:|:---:|:---:| 
|<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white"><br><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"><br><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"><br><img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white"><br>|<img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=Gunicorn&logoColor=white"><br><img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"><br><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"><br><img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"><br><img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white"><br><img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"><br><img src="https://img.shields.io/badge/Swagger-85EA2D.svg?style=for-the-badge&logo=Swagger&logoColor=white">|<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white"><br><img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white"><br><img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=Elasticsearch&logoColor=white"><br><img src="https://img.shields.io/badge/Logstash-005571?style=for-the-badge&logo=Logstash&logoColor=white"><br><img src="https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=Kibana&logoColor=white"><br><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">|<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"><br><img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white"><br><img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white"><br><img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"><br><img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"><br><img src="https://img.shields.io/badge/Github Actions-2088FF?style=for-the-badge&logo=Github Actions&logoColor=white">|

<br>

## 💻 Installation Process
> <b>Docker repository clone </b>

```
git clone --recursive https://github.com/S-V-23-BootCamp-Team-F/docker.git
```

<br>

> <b>Set .env in the backend folder </b>

```
SECRET_KEY = {Django SECRET_KEY}

# AWS S3 연동
AWS_ACCESS_KEY = {AWS_ACCESS_KEY}
AWS_SECRET_KEY = {AWS_SECRET_KEY}
AWS_REGION = {AWS_REGION}

# S3 Storages
S3_BUCKET_NAME = {S3_BUCKET_NAME}

MYSQL_NAME = {MYSQL_NAME}
MYSQL_USER = {MYSQL_USER}
MYSQL_PASSWORD = {MYSQL_PASSWORD}
MYSQL_HOST = {MYSQL_HOST}
```
<br>


> <b>Run Docker-compose </b>

```
docker-compose up —build
```

## 🗂 Submodule Directories
<details>
<summary> FRONTEND </summary>

 ```sh
 
📦frontend
 ┣ 📂.github
 ┣ 📂dist
 ┣ 📂node_modules
 ┣ 📂public
 ┣ 📂src
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📜Cropchart.tsx
 ┃ ┃ ┣ 📜DetailModalscreen.tsx
 ┃ ┃ ┣ 📜Hamnav.tsx
 ┃ ┃ ┣ 📜Historycard.tsx
 ┃ ┃ ┣ 📜LoadingPage.tsx
 ┃ ┃ ┣ 📜LogInPage.tsx
 ┃ ┃ ┣ 📜Longnav.tsx
 ┃ ┃ ┣ 📜Navbar.tsx
 ┃ ┃ ┣ 📜Periodchart.tsx
 ┃ ┃ ┣ 📜Periodline.tsx
 ┃ ┃ ┗ 📜SignupPage.tsx
 ┃ ┣ 📂fonts
 ┃ ┣ 📂images
 ┃ ┣ 📂pages
 ┃ ┃ ┣ 📜AbnomalResultPage.tsx
 ┃ ┃ ┣ 📜GetStart.tsx
 ┃ ┃ ┣ 📜HistoryPage.tsx
 ┃ ┃ ┣ 📜MainPage.tsx
 ┃ ┃ ┣ 📜NomalResultPage.tsx
 ┃ ┃ ┗ 📜StasticsPage.tsx
 ┃ ┣ 📂utils
 ┃ ┣ 📜App.css
 ┃ ┣ 📜App.tsx
 ┃ ┣ 📜Cookie.ts
 ┃ ┣ 📜index.css
 ┃ ┣ 📜main.tsx
 ┃ ┣ 📜media.css
 ┃ ┗ 📜vite-env.d.ts
 ┣ 📜.dockerignore
 ┣ 📜.git
 ┣ 📜.gitignore
 ┣ 📜Dockerfile
 ┣ 📜README.md
 ┣ 📜index.html
 ┣ 📜index.tsx
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┣ 📜postcss.config.cjs
 ┣ 📜tailwind.config.cjs
 ┣ 📜tsconfig.json
 ┣ 📜tsconfig.node.json
 ┗ 📜vite.config.ts
```

</details>


<details>
<summary> BACKEND </summary>

 ```sh
📦backend
 ┣ 📂.github
 ┣ 📂backend
 ┃ ┣ 📜__init__.py
 ┃ ┣ 📜asgi.py
 ┃ ┣ 📜celery.py
 ┃ ┣ 📜settings.py
 ┃ ┣ 📜urls.py
 ┃ ┗ 📜wsgi.py
 ┣ 📂members
 ┃ ┣ 📂migrations
 ┃ ┣ 📜__init__.py
 ┃ ┣ 📜admin.py
 ┃ ┣ 📜apps.py
 ┃ ┣ 📜models.py
 ┃ ┣ 📜serializer.py
 ┃ ┣ 📜tests.py
 ┃ ┣ 📜urls.py
 ┃ ┗ 📜views.py
 ┣ 📂plants
 ┃ ┣ 📂inference
 ┃ ┃ ┣ 📂models
 ┃ ┃ ┃ ┣ 📂hub
 ┃ ┃ ┃ ┣ 📂segment
 ┃ ┃ ┃ ┣ 📜__init__.py
 ┃ ┃ ┃ ┣ 📜common.py
 ┃ ┃ ┃ ┣ 📜experimental.py
 ┃ ┃ ┃ ┣ 📜tf.py
 ┃ ┃ ┃ ┣ 📜yolo.py
 ┃ ┃ ┃ ┣ 📜yolov5l.yaml
 ┃ ┃ ┃ ┣ 📜yolov5m.yaml
 ┃ ┃ ┃ ┣ 📜yolov5n.yaml
 ┃ ┃ ┃ ┣ 📜yolov5s.yaml
 ┃ ┃ ┃ ┗ 📜yolov5x.yaml
 ┃ ┃ ┣ 📂utils
 ┃ ┃ ┃ ┣ 📜__init__.py
 ┃ ┃ ┃ ┣ 📜activations.py
 ┃ ┃ ┃ ┣ 📜augmentations.py
 ┃ ┃ ┃ ┣ 📜autoanchor.py
 ┃ ┃ ┃ ┣ 📜autobatch.py
 ┃ ┃ ┃ ┣ 📜callbacks.py
 ┃ ┃ ┃ ┣ 📜dataloaders.py
 ┃ ┃ ┃ ┣ 📜downloads.py
 ┃ ┃ ┃ ┣ 📜general.py
 ┃ ┃ ┃ ┣ 📜loss.py
 ┃ ┃ ┃ ┣ 📜metrics.py
 ┃ ┃ ┃ ┣ 📜plots.py
 ┃ ┃ ┃ ┣ 📜torch_utils.py
 ┃ ┃ ┃ ┗ 📜triton.py
 ┃ ┃ ┣ 📜cucumber.pt
 ┃ ┃ ┣ 📜detect.py
 ┃ ┃ ┣ 📜export.py
 ┃ ┃ ┣ 📜grape.pt
 ┃ ┃ ┣ 📜paprika.pt
 ┃ ┃ ┣ 📜pepper.pt
 ┃ ┃ ┣ 📜strawberry.pt
 ┃ ┃ ┗ 📜tomato.pt
 ┃ ┣ 📂migrations
 ┃ ┣ 📜__init__.py
 ┃ ┣ 📜admin.py
 ┃ ┣ 📜apps.py
 ┃ ┣ 📜models.py
 ┃ ┣ 📜serializer.py
 ┃ ┣ 📜storagess.py
 ┃ ┣ 📜tasks.py
 ┃ ┣ 📜tests.py
 ┃ ┣ 📜urls.py
 ┃ ┗ 📜views.py
 ┣ 📂static
 ┣ 📜.env
 ┣ 📜.git
 ┣ 📜.gitignore
 ┣ 📜Dockerfile
 ┣ 📜README.md
 ┣ 📜manage.py
 ┗ 📜requirements.txt
```

</details>

<br><br>
