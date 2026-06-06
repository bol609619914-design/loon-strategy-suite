# Loon Strategy Suite

一个偏日常使用的 Loon 策略组模板，覆盖 AI、流媒体、社交、开发、支付和常见地区节点分组。

> This repository is a sanitized public template. It does not include proxy subscriptions, private tokens, MITM certificates, or local-only plugin URLs.

## Highlights

- AI: OpenAI, Gemini
- Media: YouTube, Netflix, Disney, Spotify, Emby
- Social: Telegram, TikTok, Facebook, Instagram, Twitter
- China services: Douyin, Bilibili, Apple
- Dev and productivity: GitHub, Microsoft
- Payment: PayPal
- Regions: HK, TW, SG, JP, KR, US

## Files

- `Loon_Strategy_Suite.lcf`: public Loon strategy/rule template.

## How To Use

1. Add your own proxy subscriptions under `[Remote Proxy]`.
2. Keep or adjust the strategy groups under `[Proxy Group]`.
3. Import/update remote rules in Loon.
4. Choose preferred nodes in each policy group.

## Notes

- The template intentionally leaves `[Remote Proxy]` empty.
- YouTube ad blocking is not guaranteed in the official YouTube app. Rules and plugins can help, but app-side ads may still appear.
- If using MITM-based plugins, install and fully trust your own Loon CA certificate on the device.

