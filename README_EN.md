# AI Assistant Self Deployment Version

Looking for Chinese README? [Click here](./README.md)

Based on Docker's fast environment configuration and deployment, you can quickly build an AI assistant system for your enterprise or team to master all data and information!

## Instructions for use

### 1. Deploy on Zeabur

To deploy the AI assistant system on Zeabur, just click the button below.

[![Deploy on Zeabur](https://zeabur.com/button.svg)](https://zeabur.com/templates/3HCGYO?referralCode=jctaoo)

> Note: Do not select the Shanghai region unless you have a domain name that has already been filed with the IPC. Services deployed in this region will not be able to access OpenAI, Google, and Anthropic services.

### 2. Use docker compose

Deploy using docker compose, just clone this repository to your local machine, then execute the following command, and modify run.env as needed or use the default configuration directly.

```bash
git clone https://github.com/enhanceai/self-deploy.git
cd self-deploy
docker compose --env-file run.env up -d
```

Finally, visit http://localhost/ to access the deployed AI assistant website, and visit http://localhost:8080/ to access the deployed AI assistant background management system.
