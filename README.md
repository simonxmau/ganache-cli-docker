# README

为 `ganache-cli` 建立 `docker-compose`，快速运行的一个项目。

## 运行

- 默认在 `docker-compose.yml` 中配置了几个参数，请自行修改
- 默认占用 `8545` 端口
- 在运行之间请先建立 `db` 目录在工作目录下，用于持久化数据

```shell
docker-compose up -d
```
## 参数

请参考 https://hub.docker.com/r/trufflesuite/ganache-cli/