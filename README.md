# lenny-podcast-skill

基于 **Lenny's Podcast** 播客转录文稿提炼的产品管理方法论导师。

## 什么是 Lenny's Podcast

[Lenny's Podcast](https://www.youtube.com/@LennysPodcast) 是产品管理领域的知名播客，邀请世界顶级产品领袖分享实战经验。每期节目嘉宾包括：

- Sean Ellis（Growth Hacking 术语发明者）
- Marty Cagan（《INSPIRED》《EMPOWERED》作者）
- Bob Moesta（Jobs-to-be-Done 框架联合创始人）
- Casey Winters（Pinterest/Airbnb/Eventbrite 增长负责人）
- Brian Chesky（Airbnb 联合创始人）
- Ben Horowitz（a16z 创始人）
- ...以及更多顶级公司的产品领袖

## 关于这个 Skill

这是一个 **苏格拉底式导师 Skill**——不是直接给答案，而是通过多轮对话了解你的具体情况后，再匹配最相关的方法论。

**核心原则**：先了解背景，再给建议。

## 功能

### 1. 多轮追问了解背景
Skill 会根据你的问题，通过 2-3 轮追问了解具体情况，再给出可操作的建议。

### 2. 顶级专家方法论
整合了以下专家的核心方法：

| 专家 | 核心方法论 |
|------|-----------|
| Sean Ellis | PMF 测试、ICE 优先级框架 |
| Marty Cagan | Empowered Product Teams、产品管理 vs 项目管理 |
| Bob Moesta | Jobs-to-be-Done 用户访谈法 |
| Casey Winters | 不可扩展增长策略 |
| Hamilton Helmer | 7 Powers 竞争壁垒框架 |

### 3. 可操作的下一步
每个建议都包含具体的行动清单，可立即执行。

## 使用方式

在 Claude Code 或其他Agent 中输入：

```
lenny 我的留存很差怎么办
lenny 如何找到创业方向
lenny 产品市场契合怎么做
lenny 团队协作有问题
```

## 对话示例

**问**：lenny 我的留存很差怎么办

**Skill 追问**：
1. 你现在的 DAU 或 MAU 大约是多少？
2. 你有没有做过任何用户访谈或调研？
3. 用户流失集中在哪个阶段？

**你回答后**，Skill 会继续追问或给出具体方法论建议。

## 数据来源

- Lenny's Podcast 转录存档（269 期节目）

## 安装

将 `SKILL.md` 放到 Agent 的 Skill 目录：

```bash
mkdir -p ~/.claude/skills/lenny-podcast-skill
```

## 许可

本 Skill 仅整理和引用 Lenny's Podcast 的公开内容，所有方法和观点归原嘉宾所有。
