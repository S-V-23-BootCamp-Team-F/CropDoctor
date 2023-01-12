# Docker 사용법
## DockerFile 및 Docker-compose 경로 


 ```sh
├─📦docker
│  ├─📂backend
│  │    📂backend
│  │    📂members
│  │    📂plants
│  ├─📜.env
│  ├─📜Dockerfile
│  ├─📜requirements.txt
│  ├─📂nginx
│  │    📜Dockerfile
│  │    📜default.conf
│  ├─📂frontend
│  │    📜Dockerfile
│  ├─📜.gitmodules
│  ├─📜docker-compose.yml 
│  │  README.md
```

## Docker-compose Build 하기!
### 1. docker repo git clone 하기
```
git clone https://github.com/S-V-23-BootCamp-Team-F/docker.git
```

### 2. 디렉터리 경로 이동
```
cd docker
```

### 3. 업데이트하기
```
git submodule foreach 'git pull'
```

### 5. backend 디렉터리 경로 이동 후 .env 파일 확인
- backend 폴더에 .env 파일이 존재해야 함.

```
cd backend
```
### 6. admin css, js 추가
```
python manage.py collectstatic          
```

### 7. docker 디렉터리 경로 이동
```
cd ..          
```

### 8. docker-compose.yml 실행
- backend, nginx, frontend dockerfile을 한번에 실행
```
docker-compose up --build
```

### 9. 컨테이너 삭제
```
docker-compose down --volumes
```

test
