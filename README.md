# Claude Code Changelog

Claude Code release notes from Anthropic's official CHANGELOG, synced once a day, in a calendar-style page with Chinese translation, RSS, JSON and an embeddable card.

**Page:** https://gaoxiaoyu1228.github.io/claude-code-changelog/

> Source: Anthropic's official [CHANGELOG.md](https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md) and npm release data, synced daily. Original text © Anthropic; Chinese text is AI-translated, English is authoritative. Dates and times are UTC, based on npm publish time.
>
> Curated by @ Xiaoyu Gao · [gaoxiaoyu1228/claude-code-changelog](https://github.com/gaoxiaoyu1228/claude-code-changelog)

## Get updates

| Way | What you get | Address |
|---|---|---|
| RSS | One item per version in any reader, or an RSS bot in Slack / Teams | [`feed.xml`](https://gaoxiaoyu1228.github.io/claude-code-changelog/feed.xml) · [`feed.zh.xml`](https://gaoxiaoyu1228.github.io/claude-code-changelog/feed.zh.xml) |
| Card | An image that always shows the latest version | see below |
| Agents | The last 7 release days as JSON | [`latest.json`](https://gaoxiaoyu1228.github.io/claude-code-changelog/latest.json) · [`llms.txt`](https://gaoxiaoyu1228.github.io/claude-code-changelog/llms.txt) |
| Webhook | A message in your own Slack / Discord / Feishu / WeCom / DingTalk group | copy [`templates/notify-webhook.yml`](templates/notify-webhook.yml) into your repo |
| Full data | Every entry since 2025-03 | [`data/all.json`](https://gaoxiaoyu1228.github.io/claude-code-changelog/data/all.json) · [`changelog.csv`](https://gaoxiaoyu1228.github.io/claude-code-changelog/changelog.csv) |

Embed the card:

```markdown
![Claude Code latest](https://gaoxiaoyu1228.github.io/claude-code-changelog/latest.svg)
```

![Claude Code latest](latest.svg)

## Data format

`latest.json`

```json
{
  "generated": "2026-11-07T10:00:00Z",
  "latest": { "version": "2.1.319", "date": "2026-11-06", "published": "…", "url": "…#v2.1.319", "counts": { "new": 18, "fixed": 90 } },
  "releases": [ { "version": "2.1.319", "counts": { … }, "entries": [ { "type": "new", "en": "…", "zh": "…" } ] } ]
}
```

`type` is one of `new`, `improved`, `fixed`, `removed`, `other`.

## Links to a version

Every version has a stable link: `…/claude-code-changelog/#v2.1.319`.

---

## 中文说明

Claude Code 版本更新记录，来源 Anthropic 官方 CHANGELOG，每天同步一次。日期和时间均为 UTC（国际标准时间）。网页默认英文，右上角可切换中文；其他语言请用浏览器自带的翻译。

| 方式 | 效果 | 地址 |
|---|---|---|
| RSS | 每个版本一条，放进阅读器或 Slack、飞书的 RSS 机器人 | `feed.zh.xml`（中文）/ `feed.xml`（英文） |
| 最新版本卡片 | 贴进 README 或 Notion，图片每天自动变成最新版本 | `latest.zh.svg` / `latest.svg` |
| 给 Agent 用 | 最近 7 个发布日的整理结果（JSON） | `latest.json`，字段说明见 `llms.txt` |
| Webhook | 推到你自己的群机器人 | 把 `templates/notify-webhook.yml` 复制到你自己的仓库，填上地址；地址只存在你那里 |

内容来自 Anthropic 官方 CHANGELOG.md 与 npm 发布记录，每日自动同步；原文版权归 Anthropic，中文为 AI 翻译，以英文原文为准。

整理：@ Xiaoyu Gao · [gaoxiaoyu1228/claude-code-changelog](https://github.com/gaoxiaoyu1228/claude-code-changelog)
