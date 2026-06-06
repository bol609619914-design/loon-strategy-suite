# Loon 策略组增强模板

一套偏日常使用的 Loon 策略组模板，覆盖 AI、流媒体、社交、开发、支付和常见地区节点分组。

[![一键导入 Loon](https://img.shields.io/badge/Loon-一键导入-1677ff?style=for-the-badge)](loon://import?config=https%3A%2F%2Fraw.githubusercontent.com%2Fbol609619914-design%2Floon-strategy-suite%2Fmain%2FLoon_Strategy_Suite.lcf)

## 说明

这是一个公开脱敏版模板，只保留策略组和远程规则。

不会包含：

- 机场订阅
- 私人 token
- MITM 证书
- 本地插件地址
- 任何私人节点信息

## 覆盖内容

- AI：OpenAI、Gemini
- 流媒体：YouTube、Netflix、Disney、Spotify、Emby
- 社交：Telegram、TikTok、Facebook、Instagram、Twitter
- 国内常用：抖音、哔哩哔哩、Apple
- 开发和办公：GitHub、Microsoft
- 支付：PayPal
- 地区组：HK、TW、SG、JP、KR、US

## 文件

- `Loon_Strategy_Suite.lcf`：Loon 策略组和分流规则模板

## 使用方法

1. 点击上面的“一键导入 Loon”按钮。
2. 导入后，在 `[Remote Proxy]` 里添加自己的订阅。
3. 在 Loon 里更新远程规则和远程节点。
4. 根据自己的节点质量，选择每个策略组使用哪个地区或订阅。

## Raw 配置地址

```text
https://raw.githubusercontent.com/bol609619914-design/loon-strategy-suite/main/Loon_Strategy_Suite.lcf
```

## 注意

- 这个模板故意留空了 `[Remote Proxy]`，需要自己添加订阅。
- YouTube 官方 App 去广告无法保证百分百生效，规则和插件只能尽量拦截。
- 如果使用 MITM 类插件，需要在设备上安装并完全信任自己的 Loon CA 证书。

