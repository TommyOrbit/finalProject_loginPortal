# 登入入口網站

>此登入入口網站有兩個功能：註冊與登入。

[![Spec](https://img.shields.io/badge/HackMD-專案說明-blue?logo=markdown)](https://hackmd.io/r9stiuf5RTKZpri67_r3hw)

## Usage
下載專案後，進入專案目錄，在目錄底下執行以下指令：
```
docker compose up -d --build
```
## Start the application
mac:
```
open http://localhost:5600
```
windows:
```
start http://localhost:5600
```

## Environment variables
.env from backend:
```
SECRET_KEY=
ALGORITHM=

ACCESS_TOKEN_EXPIRE_MINUTES=
REFRESH_TOKEN_EXPIRE_DAYS=

DATABASE=

HOST=127.0.0.1
PORT=8000
```
.env.local from frontend:
```
BACKEND_URL=http://backend:4000
NODE_ENV=development   
```