# Web3 示例项目

本仓库包含了一系列涵盖前端、智能合约和后端的 Web3 示例代码，旨在帮助开发者快速学习和应用到实际项目中。我们提供了多种常用场景的示例代码。

## 在线预览

预览地址：[https://webnext.cloud](https://webnext.cloud)

## 社区交流

如果你对 Web3 感兴趣，想从事 Web3 开发或探讨相关话题，请添加 Web3 布道师 Noah 的微信：「LZQ20130415」，将邀请你加入高质量的 Web3 交流群。

## 环境准备

由于部分服务可能需要翻墙访问，或依赖于需要翻墙的服务（如 Google 验证码），建议确保你的网络环境可以科学上网。

以下是几个可靠的科学上网工具推荐：

- <https://letsvpn.world/?hl=zh>：价格较高，一个账号支持 2 个设备
- <https://ghelper.app/>：价格较低，一个账号支持十几个设备

请注意，以上工具仅供学习使用。若利用这些工具从事违法犯罪行为，我们概不承担任何法律责任。

## 本地运行

### 前端

前端代码位于 `frontend` 目录下。在运行之前，请确保完成以下准备工作：

1. 将 `.env.example` 文件重命名为 `.env`，并补充完整配置信息。
2. 至少在 [alchemy](https://www.alchemy.com/) 上申请一个 API Key。

接下来，安装依赖并启动项目：

```bash
npm i
npm run dev
```

### 智能合约

智能合约代码位于 `contract` 目录下。在运行之前，请确保完成以下准备工作：

1. 将 `.env.example` 文件重命名为 `.env`，并补充完整配置信息。
2. 至少在 [infura](https://www.infura.io/) 上申请一个 Project Key。

然后，你可以使用 `truffle` 进行智能合约开发。

## 学习资源

我们整理了一份学习资源列表，供你参考：

[精选资源](/docs/awesome.md)

如果你有新的资源推荐，或发现资源过期、质量不佳，请提 issue 通知我们。
