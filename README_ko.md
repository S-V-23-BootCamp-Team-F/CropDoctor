νκ΅­μ΄ | [English](README.md)

# CropDoctor

![D8771DDC-42B5-42E6-922B-01C0443DB602](https://user-images.githubusercontent.com/97827316/216045573-6e6738bb-f103-407d-a496-f55eb3fd9590.png)
<br>

## π Introduction

μ ν¬ Cropdoctorλ μ¬μ©μμ μλ¬Όμ μ§λ³μ μ§λ¨ν΄μ£Όλ μλΉμ€λ‘ μ§λ³μ λ§λ ν΄κ²°μ±μ μ μν΄λλ¦½λλ€. π©π»βπΎ
<br>
<br>

## π System Architecture

![MacBook Pro 16_ - 1](https://user-images.githubusercontent.com/83527046/215812708-2d8dc494-2d49-4aea-8192-152852902497.png)
<br>

## π TECH STACKS

|Frontend|Backend|Monitoring|Database&Storage|DevOps|AI| 
| :----: | :---: | :-----: | :---------: | :------: | :-----: |
| <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white"><br><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white"><br><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"><br><img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white"><br> | <br><img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white"><br><img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=Gunicorn&logoColor=white"><br><img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"><br><img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"><br><img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"><br><img src="https://img.shields.io/badge/Swagger-85EA2D.svg?style=for-the-badge&logo=Swagger&logoColor=white"> | <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white"><br><img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white"><br><img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=Elasticsearch&logoColor=white"><br><img src="https://img.shields.io/badge/Logstash-005571?style=for-the-badge&logo=Logstash&logoColor=white"><br><img src="https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=Kibana&logoColor=white"><br><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"> |<img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white"><br><img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"><br><img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <br>| <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"><br><img src="https://img.shields.io/badge/Amazon EC2 -FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white"><br><img src="https://img.shields.io/badge/Github Actions-2088FF?style=for-the-badge&logo=Github Actions&logoColor=white"><br> | <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"> <br> <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=YOLO&logoColor=white"> <br>|


<br>

## π» Installation Process

> <b>Docker repository clone </b>

```
git clone --recursive https://github.com/S-V-23-BootCamp-Team-F/docker.git
```

<br>

> <b>Set .env in the backend folder </b>

```
SECRET_KEY = {Django SECRET_KEY}

# AWS S3 μ°λ
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
docker-compose up βbuild
```

## π Submodule Directories

<details>
<summary> FRONTEND </summary>

```sh

π¦frontend
β£ π.github
β£ πdist
β£ πnode_modules
β£ πpublic
β£ πsrc
β β£ πcomponents
β β β£ πCropchart.tsx
β β β£ πDetailModalscreen.tsx
β β β£ πHamnav.tsx
β β β£ πHistorycard.tsx
β β β£ πLoadingPage.tsx
β β β£ πLogInPage.tsx
β β β£ πLongnav.tsx
β β β£ πNavbar.tsx
β β β£ πPeriodchart.tsx
β β β£ πPeriodline.tsx
β β β πSignupPage.tsx
β β£ πfonts
β β£ πimages
β β£ πpages
β β β£ πAbnomalResultPage.tsx
β β β£ πGetStart.tsx
β β β£ πHistoryPage.tsx
β β β£ πMainPage.tsx
β β β£ πNomalResultPage.tsx
β β β πStasticsPage.tsx
β β£ πutils
β β£ πApp.css
β β£ πApp.tsx
β β£ πCookie.ts
β β£ πindex.css
β β£ πmain.tsx
β β£ πmedia.css
β β πvite-env.d.ts
β£ π.dockerignore
β£ π.git
β£ π.gitignore
β£ πDockerfile
β£ πREADME.md
β£ πindex.html
β£ πindex.tsx
β£ πpackage-lock.json
β£ πpackage.json
β£ πpostcss.config.cjs
β£ πtailwind.config.cjs
β£ πtsconfig.json
β£ πtsconfig.node.json
β πvite.config.ts
```

</details>

<details>
<summary> BACKEND </summary>

```sh
π¦backend
β£ π.github
β£ πbackend
β β£ π__init__.py
β β£ πasgi.py
β β£ πcelery.py
β β£ πsettings.py
β β£ πurls.py
β β πwsgi.py
β£ πmembers
β β£ πmigrations
β β£ π__init__.py
β β£ πadmin.py
β β£ πapps.py
β β£ πmodels.py
β β£ πserializer.py
β β£ πtests.py
β β£ πurls.py
β β πviews.py
β£ πplants
β β£ πinference
β β β£ πmodels
β β β β£ πhub
β β β β£ πsegment
β β β β£ π__init__.py
β β β β£ πcommon.py
β β β β£ πexperimental.py
β β β β£ πtf.py
β β β β£ πyolo.py
β β β β£ πyolov5l.yaml
β β β β£ πyolov5m.yaml
β β β β£ πyolov5n.yaml
β β β β£ πyolov5s.yaml
β β β β πyolov5x.yaml
β β β£ πutils
β β β β£ π__init__.py
β β β β£ πactivations.py
β β β β£ πaugmentations.py
β β β β£ πautoanchor.py
β β β β£ πautobatch.py
β β β β£ πcallbacks.py
β β β β£ πdataloaders.py
β β β β£ πdownloads.py
β β β β£ πgeneral.py
β β β β£ πloss.py
β β β β£ πmetrics.py
β β β β£ πplots.py
β β β β£ πtorch_utils.py
β β β β πtriton.py
β β β£ πcucumber.pt
β β β£ πdetect.py
β β β£ πexport.py
β β β£ πgrape.pt
β β β£ πpaprika.pt
β β β£ πpepper.pt
β β β£ πstrawberry.pt
β β β πtomato.pt
β β£ πmigrations
β β£ π__init__.py
β β£ πadmin.py
β β£ πapps.py
β β£ πmodels.py
β β£ πserializer.py
β β£ πstoragess.py
β β£ πtasks.py
β β£ πtests.py
β β£ πurls.py
β β πviews.py
β£ πstatic
β£ π.env
β£ π.git
β£ π.gitignore
β£ πDockerfile
β£ πREADME.md
β£ πmanage.py
β πrequirements.txt
```

</details>
<br>

## Flowchart

![flowchart drawio (5)](https://user-images.githubusercontent.com/84130518/216247660-3d8c62d4-eb9f-4ab0-b6bf-523fa15ee2d9.png)

## π Features

<br>

**νμκ°μ/ λ‘κ·ΈμΈ νμ΄μ§**

<img  src="https://user-images.githubusercontent.com/97827316/215984078-3cbe440e-c4bc-4ae3-9a2b-662ec2dae079.gif">

- JWTν ν°μ μ΄μ©ν νμκ°μ/λ‘κ·ΈμΈ νμ΄μ§μ΄λ€.

<br>

**μ§λ¨/μ§λ¨κ²°κ³Ό νμ΄μ§**

<img src="https://user-images.githubusercontent.com/97827316/215984379-20db97b3-e90c-4857-bb46-c457b61b632c.gif">

- λ³ν΄μλ¬Ό μ΄λ―Έμ§λ₯Ό μ ννμ¬ AIλ‘ μ§λ¨νλ νμ΄μ§μ΄λ©°, λ³ν΄ μλ¬ΌμΌ κ²½μ° μμΈκ³Ό ν΄κ²°μ±λ±μ ν¨κ» μ κ³΅νλ€.

<br>

**νμ€ν λ¦¬/νμ€ν λ¦¬μ­μ **

<img src="https://user-images.githubusercontent.com/97827316/215984492-50f4e265-a738-41a9-8463-532ddb453c68.gif">

- λ‘κ·ΈμΈ μμλ§ μ΄μ©κ°λ₯ν κΈ°λ₯μΌλ‘ μμ μ΄ μ§λ¨ν μλ¬Όμ μΉ΄νκ³ λ¦¬λ³λ‘ λͺ¨μ λ³Ό μ μλ€. <br>
- νμ€ν λ¦¬ μλ¬Όμ μμΈμ λ³΄λ₯Ό νμΈν  μ μκ³  μ΄λ₯Ό μ­μ ν  μ μλ€.

<br>

**ν΅κ³ νμ΄μ§**

![2A005C2A-E092-4315-8DE9-7F42D3C72641](https://user-images.githubusercontent.com/84130518/216145065-275acbcd-2fed-48f2-839c-69294a5dc8e1.gif)

- μ¬ν Cropdoctor μ§λ¨ λ°μ΄ν°λ₯Ό ν λλ‘ ν΅κ³λ₯Ό λνλΈλ€.
- μλ¬Ό λ³ μ§λ³ μ ν΅κ³
  - μλ¬Ό λ³λ‘ μ΄λ€ μ§λ³μ λ§μ΄ κ±Έλ Έλμ§ λ° μ°¨νΈννλ‘ μ λ³΄λ₯Ό μ κ³΅νλ€.
- μ λ³ μ§λ³ μ ν΅κ³
  - μΉ΄νκ³ λ¦¬μμ μ νν μλ¬Όμ μ λ³λ‘ μ§λ³μ΄ νλ¦μ΄ μ΄λ€μ§ μ  κ·Έλνννλ‘ μ λ³΄λ₯Ό μ κ³΅νλ€.


**λ°μν μΉνμ΄μ§**

![αα‘α«αα³αΌαα§αΌ](https://user-images.githubusercontent.com/84130518/216141786-cdafcb67-0af9-49cb-9e2c-005e14bac7b2.gif)


## π₯οΈ Moniterings

<br>

**Kibana Dashboard**

<img src="https://user-images.githubusercontent.com/84130518/216140964-6ae6f082-1a31-4348-8d38-39087ab98a94.png">

<br>

**Grafana Dashboard & Slack Alert**

<img  src="https://user-images.githubusercontent.com/84130518/216139014-d7f93579-66dc-4ec5-8e1e-664fa5258372.png">

<br>

λ§μ½ Storage μ©λμ΄ 85%κ° λμΌλ©΄ Grafanaμμ SlackμΌλ‘ μλμ λ³΄λΈλ€.

<img width="320" src="https://user-images.githubusercontent.com/83527046/216155592-6f85fc7f-b30a-426e-bdc5-86cdeb763663.png">
<br>

## Swagger

Frontendμ Backend ν΅μ μ μν API λ¬Έμνλ Swaggerλ₯Ό μ΄μ©νλ€.
<img width="1245" alt="μ€ν¬λ¦°μ· 2023-02-01 μ€ν 6 03 44 (1)" src="https://user-images.githubusercontent.com/84130518/216385471-3b8f5d95-b9ca-4705-88df-0426ddba2d8d.png">

## AI
AIλ YoloV5λ₯Ό μ¬μ©νμΌλ©°, Precision-Confidence Curveκ³Ό νμ΅ κ³Όμ  λ° μ±λ₯μ λ€μκ³Ό κ°λ€.
![αα³αα΅α·1](https://user-images.githubusercontent.com/84130518/216386440-c240d681-2f4f-4121-b6da-d630e2d30dbd.png)

![results (1)](https://user-images.githubusercontent.com/84130518/216386411-f00c4c4b-2ebb-49bb-a4fd-82dd63aa1094.png)

λ€μ μ¬μ§μ AIκ° μ€μ λ‘ λΆμν μ¬μ§λ€μ΄λ€.
![Group 101111](https://user-images.githubusercontent.com/84130518/216389881-90366a8a-afff-4122-8025-f135ce9fa37a.png)


## π₯ Our Team

<table width="1000">
    <thead>
    </thead>
    <tbody>
    <tr>
        <th>Pictures</th>
         <td width="100" align="center">
            <a href="https://github.com/goldapple-ce">
                <img src="https://user-images.githubusercontent.com/97827316/215991540-bd09f520-794d-4db2-9bde-955470a96957.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/jiyoon0701">
                <img  src="https://user-images.githubusercontent.com/97827316/215991531-8da89dd4-d739-4e37-b5be-2b04c38ec6f3.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/TMInstaller">
                <img src="https://user-images.githubusercontent.com/97827316/215991528-8c8a4e08-16ef-46e2-a996-e3a60b937cc3.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/yura0302">
                <img src="https://user-images.githubusercontent.com/97827316/215991544-021c3e7a-460b-41a3-a030-2dca6bb0ac20.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/fnzl54">
                <img src="https://user-images.githubusercontent.com/97827316/215991516-914ed25d-6759-4478-843c-628a0c6baad1.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/hstla">
                <img src="https://user-images.githubusercontent.com/97827316/215991535-aa0d5aeb-363c-41a7-a114-c1448d58d9f1.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/Mayreeel">
                <img src="https://user-images.githubusercontent.com/97827316/215991527-9226b9b3-34fa-493b-b2af-c61d15cc13cf.png" width="60" height="60">
            </a>
        </td>
    </tr>
    <tr>
        <th>Name</th>
        <td width="100" align="center">κ°μ©λ―Ό</td>
        <td width="100" align="center">μ΄μ§μ€</td>
        <td width="100" align="center">λ°±λμ΄</td>
        <td width="100" align="center">κΉμ λΌ</td>
        <td width="100" align="center">κΆμ°¬μ</td>
        <td width="100" align="center">ν©νμ±</td>
        <td width="100" align="center">μ΄κ·ν</td>
    </tr>
    <tr>
        <th>Position</th>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
            Backend<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
            AI<br>
        </td>
        <td width="150" align="center">
            Backend<br>
            DevOps<br>
        </td>
        <td width="150" align="center">
            Frontend<br>
        </td>
    </tr>
    <tr>
        <th>GitHub</th>
        <td width="100" align="center">
            <a href="https://github.com/goldapple-ce">
                <img src="http://img.shields.io/badge/Kyoungmin1016-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/jiyoon0701">
                <img src="http://img.shields.io/badge/jiyoon0701-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/TMInstaller">
                <img src="http://img.shields.io/badge/TMInstaller-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/yura0302">
                <img src="http://img.shields.io/badge/yura0302-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/fnzl54">
                <img src="http://img.shields.io/badge/fnzl54-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/hstla">
                <img src="http://img.shields.io/badge/hstla-green?style=social&logo=github"/>
            </a>
        </td>
         <td width="100" align="center">
            <a href="https://github.com/Mayreeel">
                <img src="http://img.shields.io/badge/Mayreeel-green?style=social&logo=github"/>
            </a>
        </td>
     </tr>
    </tbody>
</table>
