# Openclaw
官网：https://github.com/openclaw/openclaw

手册：docs.openclaw.ai

## 安装

### Node.js安装

教程1：https://www.runoob.com/nodejs/nodejs-install-setup.html

教程2：https://help.aliyun.com/zh/sdk/developer-reference/install-node-js-in-windows?spm=a2c4g.11186623.J_XmGx2FZCDAeIy2ZCWL7sW.35.47a72f356PhMlN&scm=20140722.S_help@@%E6%96%87%E6%A1%A3@@2793304._.RL_%E5%9C%A8windows%E5%AE%89%E8%A3%85node-LOC_2024NSHelpLink-OR_ser-PAR1_212c8ba317753874005025981d0dea-V_4-P0_0-P1_0

官网：`https://nodejs.org/en/download`

配置npm国内镜像仓库

### Git安装
官网：git-scm.com

### Openclaw安装
网址：https://docs.openclaw.ai/install

api配置

-  `openclaw onboard`

-  `UI -> config -> Raw`

-  `env setting`


## kimi api setting

### kimi code

```python
"kimi": {
        "baseUrl": "https://api.kimi.com/coding/",
        "apiKey": "API_KEY",
        "api": "anthropic-messages",
        "models": [
          {
            "id": "kimi-code",
            "name": "Kimi Code",
            "reasoning": true,
            "input": [
              "text",
              "image"
            ],
            "cost": {
              "input": 0,
              "output": 0,
              "cacheRead": 0,
              "cacheWrite": 0
            },
            "contextWindow": 262144,
            "maxTokens": 32768
          }
        ]
      }
```


### kimi api

```python
"moonshot": {
        "baseUrl": "https://api.moonshot.cn/v1",
        "api": "openai-completions",
        "models": [
          {
            "id": "kimi-k2.5",
            "name": "Kimi K2.5",
            "reasoning": false,
            "input": [
              "text",
              "image"
            ],
            "cost": {
              "input": 0,
              "output": 0,
              "cacheRead": 0,
              "cacheWrite": 0
            },
            "contextWindow": 262144,
            "maxTokens": 262144
          }
        ]
      }
  ```

---
# Claude Code

## 网址

### Anthropic
网址：anthropic.com

### Claude
网址：claude.com

### Claude Code
网址：code.claude.com

手册：code.claude.com/docs

### Claude api
网址：platform.claude.com

手册：platform.claude.com/docs

## 安装

### Node.js安装

教程1：https://www.runoob.com/nodejs/nodejs-install-setup.html

教程2：https://help.aliyun.com/zh/sdk/developer-reference/install-node-js-in-windows?spm=a2c4g.11186623.J_XmGx2FZCDAeIy2ZCWL7sW.35.47a72f356PhMlN&scm=20140722.S_help@@%E6%96%87%E6%A1%A3@@2793304._.RL_%E5%9C%A8windows%E5%AE%89%E8%A3%85node-LOC_2024NSHelpLink-OR_ser-PAR1_212c8ba317753874005025981d0dea-V_4-P0_0-P1_0

官网：`https://nodejs.org/en/download`

配置npm国内镜像仓库

### Git安装
官网：git-scm.com

### Claude Code安装
`npm install -g @anthropic-ai/claude-code`

### 配置Api
#### Linux
`export ANTHROPIC_AUTH_TOKEN="API_KEY"`

`export ANTHROPIC_BASE_URL="xxx"`

---
# Kimi

## Kimi
网址：kimi.com

## Kimi Code
网址：kimi.com/code

手册：kimi.com/code/docs

配置Claude Code：kimi.com/code/docs/more/third-party-agents

## Kimi api
网址：platform.kimi.com

手册：platform.kimi.com/docs

配置Claude Code：platform.kimi.com/docs/guide/agent-suppor

---
# 星火Api
网址：https://my.feishu.cn/wiki/Tlz7wcsb0iMJbgkYCiccV7bKnbd

配置Claude Code：https://yoo7f1r4m4.feishu.cn/wiki/AYvFw9op3iEGAPkfgvMcugDinld

---
# 网络问题
修改http和https为clash 7890端口
#### Linux
`export http_proxy=http://127.0.0.1:7890`

`export https_proxy=http://127.0.0.1:7890`

#### Windows
`$env:HTTP_PROXY="http://127.0.0.1:7890"`

`$env:HTTPS_PROXY="http://127.0.0.1:7890"`
