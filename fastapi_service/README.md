# FastAPI 服务

这是一个基本的FastAPI服务示例。

## 功能特点

- 基本的健康检查端点
- CORS支持
- Docker支持

## 本地运行

1. 安装依赖：
```bash
pip install -r requirements.txt
```

2. 运行服务：
```bash
python main.py
```

## Docker运行

1. 构建镜像：
```bash
docker build -t fastapi-service .
```

2. 运行容器：
```bash
docker run -p 8000:8000 fastapi-service
```

## API端点

- GET /: 欢迎信息
- GET /health: 健康检查 