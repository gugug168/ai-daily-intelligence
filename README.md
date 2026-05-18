# 🤖 AI每日情报

> 每天早上 06:00 自动推送的 AI 科技动态深度解读早报

[![飞书](https://img.shields.io/badge/飞书-推送-blue)](https://github.com/gugug168/ai-daily-intelligence)

## 这是什么

「AI每日情报」是一份每天自动生成的 AI 科技 Newsletter。

**产品结构：**
- 📰 **今日必读** — 3条最重要新闻，附深度解读
- 💡 **值得深入** — 2个值得花时间了解的话题
- 🛠️ **好东西** — 3个工具/项目/资源
- 🔮 **明日关注** — 明天值得注意的事件预判

**数据来源（28个）：**
- 🤖 AI公司官方：OpenAI、Anthropic、Google DeepMind、xAI、Meta AI、Cohere、Mistral、Groq、Perplexity、MiniMax
- 💬 技术社区：Hacker News、GitHub Trending、V2EX
- 📝 高质量博客：Troy Hunt、Simon Willison、Matklad、Gary Marcus、Dwarkesh Patel 等15位独立博主
- 📰 中国科技：36Kr、量子位、虎嗅、腾讯科技
- 📊 学术：arXiv cs.AI、HuggingFace Papers

## 订阅

**早鸟价：¥99/年**（原价 ¥199/年）

微信搜索「知识星球」→ 搜索「AI每日情报」→ 加入

## 最新内容

最新简报发布在 [Issues](/../../issues) 中，每期都可在 Issues 中评论讨论。

## 技术架构

- 采集：`~/.hermes/skills/media/news-aggregator-skill/scripts/fetch_news.py`
- 生成：MiniMax M2.7 API
- 推送：每天 06:00 自动推送至飞书/知识星球
- 源码：[@HermesAgent](https://github.com/gugug168) 全自动运行

## 关于作者

by [Hermes Agent](https://github.com/gugug168) — macOS 上的 AI 个人助理
