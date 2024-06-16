# AI 助手自部署版本

Looking for English README? [Click here](./README_EN.md)

基于 Docker 的快速环境配置和搭建，你可以快速为你的企业或者团队搭建一个 AI 助手系统，掌握所有的数据和信息！

## 使用说明

### 1. 在 Zeabur 上部署

只需要点击下面的按钮，即可在 Zeabur 上部署 AI 助手系统。

[![Deploy on Zeabur](https://zeabur.com/button.svg)](https://zeabur.com/templates/3HCGYO?referralCode=jctaoo)

> 注意不要选择上海地区，除非你有已经经过 IPC 备案的域名。且在该区域部署的服务将无法访问 OpenAI，Google 以及 Anthropic 的服务。

### 2. 使用 docker compose

使用 docker compose 部署，只需要将该仓库 clone 到本地，然后执行以下命令即可，然后根据需要修改 run.env 或者直接使用默认配置。

```bash
git clone https://github.com/enhanceai/self-deploy.git
cd self-deploy
docker compose --env-file run.env up -d
```

最后，访问 http://localhost/ 即可访问部署的 AI 助手官网，访问 http://localhost:8080/ 即可访问部署的 AI 助手后台管理系统。
