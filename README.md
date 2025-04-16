# Hacker News 每日摘要自动推送

本项目通过自动化工具，每天从 [Hacker News](https://news.ycombinator.com/) 拉取热门新闻，生成简明摘要，并附上原文链接。所有内容会每日自动发布为一个新的 GitHub Issue，方便回顾和检索。

## 功能简介

- 每天定时抓取 Hacker News 热门新闻
- 自动生成每条新闻的简明摘要
- 汇总每日报告并附上原文链接
- 每天自动在本仓库创建一个新的 Issue 发布当天摘要

## 示例

> 每天会自动生成类似如下的 Issue：

2025-04-16 Hacker News

```md
# Show HN: My New Automation Tool

一款用于自动化流程的新工具，支持多种第三方服务集成。

[原文链接](https://github.com/gococonut/hacker-news/)
```

你可以在 [Issues](./issues) 页面浏览每日最新新闻摘要。

## 联系反馈

如有建议欢迎在 Issue 区留言交流。
