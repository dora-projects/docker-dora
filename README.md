# docker-dora
通过 docker-compose 快速启动 dora

## 1. 克隆

```bash
git clone https://github.com/dora-projects/docker-dora.git
```

## 2. 修改配置

```
cd docker-dora

# 修改 .env 文件中的配置信息
vi .env
```

## 3. 启动 / 停止

```bash
# start
docker-compose up -d

# stop
docker-compose down
```

4. 访问
浏览 http://localhost:8080 即可看到控制台。
