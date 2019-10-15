# team-view &middot; [![GitHub stars](https://img.shields.io/github/stars/zhanglingup/team-view.svg?style=flat&label=Star)](https://github.com/zhanglingup/team-view/stargazers) [![GitHub forks](https://img.shields.io/github/forks/zhanglingup/team-view.svg?style=flat&label=Fork)](https://github.com/zhanglingup/team-view/fork) [![GitHub watchers](https://img.shields.io/github/watchers/zhanglingup/team-view.svg?style=flat&label=Watch)](https://github.com/zhanglingup/team-view/watchers)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/zhanglingup/team-view/blob/master/LICENSE) [![NPM version](https://img.shields.io/npm/v/team-view.svg?style=flat)](https://npmjs.com/package/team-view)
[![NPM downloads](https://img.shields.io/npm/dm/team-view.svg?style=flat)](https://npmjs.com/package/team-view)
[![CircleCI](https://img.shields.io/circleci/project/github/nuxt/team-view/master.svg?style=flat)](https://circleci.com/gh/nuxt/team-view/master)

基于Jira的技术团队可视化管理工具

## 需求痛点
在 Confluence 中虽然可抽取 Jira 数据按照我们的需要生成表格，但存在以下不足：
- 灵活性不足，没法按照我们的需求去生成报表，只有预设字段、预设模板☆☆☆
- 缺少对于数据报表的分析☆☆☆
- 周报等需要每周重复生成，重复机械的工作量导致资源浪费☆☆
- 页面不美观☆

## 功能概览
- 任务量排名、分析
- 实时任务量分析
- 技术贡献度：技术任务、突出贡献、技术分享等
- 周报生成模板+自动填写（按周、月、年查询）
- 代码提交量报表/榜单
- 团队成员信息详情页面（基本信息、技术擅长，项目经历，获奖情况，OKR设置与达成情况分析）

## 技术选型
- 前端：Vue2.x + Nuxt + ElementUI
- 后端：Egg.js，后期用Nest.js重构，有空可加入Java、Go版本实现
- 桌面端：Electron
- 移动端：暂不支持

## 如何部署

## 如何使用
- Web
```bash
cd web
npm run dev
npm run build
npm run start
```

## 二次开发
