# 独立开发第一周行动计划

> 这个 7 天计划帮你从零开始，用最少的时间验证一个产品想法。
> 核心原则：先验证需求，再写代码。

## Day 1：找方向

**目标：** 选出 3 个你有兴趣且有真实付费需求的方向。

- [ ] 打开 [Idea Miner](https://idea-miner.com/en/) 查看本月热门需求榜单
- [ ] 按技术栈筛选（React/Python/Flutter/AI/LLM 等），找到你能做的
- [ ] 按增长率排序，标注增长 +100% 以上的方向
- [ ] 按预算排序，标注中位预算 $500+ 的方向
- [ ] 从交集里选出 3 个你最有兴趣的方向
- [ ] 记录到 `ideas.md`，每个方向写一句话描述

**不要做的事：**
- ❌ 不要纠结选哪个"最好"
- ❌ 不要开始想技术实现
- ❌ 不要写代码

## Day 2：读真实需求

**目标：** 从一手需求里读懂用户真正的痛点。

- [ ] 去 [Upwork](https://www.upwork.com/) 搜索你选的 3 个方向的关键词
- [ ] 每个方向至少读 20 个真实任务描述
- [ ] 记录：
  - 用户用什么词描述问题（这是你的营销文案关键词）
  - 他们尝试过什么烂方案（这是你的切入点）
  - 预算范围（这是你的定价参考）
  - 反复出现的具体需求点
- [ ] 同样去 [Freelancer](https://www.freelancer.com/) 看一遍

**关键问题：**
- 这些任务描述里有没有一个共同的、反复出现的"痛点短语"？
- 有没有客户在为多个项目重复付费（说明有持续需求）？

## Day 3：用户访谈

**目标：** 用 The Mom Test 方法，和 5 个目标用户聊，验证需求。

- [ ] 找到 5 个目标用户（Twitter、Reddit、微信群、朋友圈、现有客户）
- [ ] 用 The Mom Test 原则访谈：
  - 聊他们的生活/工作，不是你的想法
  - 问他们过去怎么解决这个问题的
  - 问他们最不满意的地方
  - **不要**问"你会用吗"（他们会礼貌地说会）
- [ ] 记录关键反馈，分类：
  - 真正的痛点（他们愿意付钱解决的）
  - 伪需求（他们说想要但不会为之行动）
  - 惊喜发现（你没想到的需求）

**推荐阅读：** [The Mom Test](http://momtestbook.com/)（1 小时读完，改变你做产品的方式）

## Day 4：选 Starter Kit 开始搭 MVP

**目标：** 用成熟模板开始，不要从零写。

- [ ] 在 [Starter Kits 列表](../README.md#-starter-kits--boilerplates) 选一个合适的模板
  - 全栈 React：ShipFast / Next.js Base
  - Python/Django：Django SaaS Boilerplate
  - Laravel：Laravel Spark
- [ ] 部署一个最简版本：
  - 能跑起来
  - 有 landing page
  - 能收邮箱（不用做完整支付）
- [ ] 不用纠结设计，能用就行

**核心原则：**
> 如果你对第一个版本不感到羞愧，说明你上线太晚了。
> — Reid Hoffman

## Day 5：开始 Build in Public

**目标：** 在 Twitter/X 开始公开构建，建立第一批受众。

- [ ] 完善你的 Twitter 个人资料：
  - 头像用真人照片
  - 简介写清楚你在做什么
  - Pinned tweet 放你的项目介绍
- [ ] 发第一条 #buildinpublic 推文：
  ```
  Day 1 of building [产品名]: [一句话说你在做什么]
  
  为什么做这个：[一句话痛点]
  今天完成：[具体进展]
  目标：一句话目标
  
  #buildinpublic #indiedev
  ```
- [ ] 关注 50 个同领域独立开发者
- [ ] 在 10 条相关推文下留下有价值的评论（不是"加油"这种）

## Day 6：加入社区，建立日志

**目标：** 在更多平台建立存在感。

- [ ] 注册 [Makerlog](https://getmakerlog.com/) 或 [WIP](https://wip.co/)，开始每日打卡
- [ ] 加入相关社区：
  - 海外：Indie Hackers、Reddit r/SideProject
  - 国内：w2solo、V2EX、即刻"独立开发"圈子
- [ ] 发一条介绍帖，坦诚说你刚开始做，欢迎交流
- [ ] 回答 3 个你能回答的问题，提供价值

## Day 7：发布 Landing Page 收集邮箱

**目标：** 上线 landing page，开始收集潜在用户邮箱。

- [ ] Landing Page 必须包含：
  - 一句话说清楚你解决什么问题
  - 产品截图/demo（即使是粗糙的）
  - 邮箱订阅表单（用 Buttondown / Substack / ConvertKit）
  - 明确的"什么时候上线"承诺
- [ ] 在你已经建立存在的平台分享：
  - Twitter/X（配截图）
  - Indie Hackers（简短介绍 + 求反馈）
  - Reddit r/SideProject（Showoff Saturday）
  - 国内社区（V2EX、即刻、w2solo）
- [ ] 不要发 Product Hunt（等产品真正能用再发）

**目标不是收集 1000 个邮箱。目标是验证有 10 个陌生人愿意留下邮箱等你的产品。**

---

## 完成 7 天后

如果你走到了这里：
- ✅ 你有了一个经过真实数据和真实用户验证的方向
- ✅ 你有了一个能跑的 MVP
- ✅ 你有了第一批关注者
- ✅ 你有了潜在用户邮箱列表

**下一步：** 联系留下邮箱的人，和他们 1 对 1 聊，根据反馈迭代。然后在合适的时机发 Product Hunt。

---

## 推荐资源

- 📖 [Zero to Sold](https://zerotosold.com/) — Arvid Kahl 的完整创业指南
- 🐦 [Follow @levelsio](https://twitter.com/levelsio) — Build in Public 教父
- 🐦 [Follow @marc_louvion](https://twitter.com/marc_louvion) — 每两周一个产品的实战派
- 📊 [Idea Miner](https://idea-miner.com/en/) — 找下一个产品方向
- 📚 [本列表的完整资源](../README.md)
