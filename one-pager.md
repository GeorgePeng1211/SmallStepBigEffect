# Liner：关播后的主播社交匹配

**赛道方向：** Reshape the business value of LIVE and Gaming with AI.

**100 字项目介绍：** Liner 是关播后的“主播版 Tinder”。主播结束直播后，在 LIVE Center 结算页进入 AI 匹配卡池，看到基于观众重叠、互动记录、内容标签和开播时间生成的同频创作者推荐。v3.0 新增“TA 喜欢了你”分支和 LIVE Event 邀约：AI 不只帮主播认识谁，还直接生成破冰文案和连麦直播邀请，把弱关系推进到私聊与 Cohost。

## Problem

成长型主播缺少低成本的创作者关系入口。关注、弹幕互动、观众重叠、同公会等信号无法自动变成“谁适合一起播、第一句话怎么说、下一场直播约什么主题”。

## Solution

Liner 在关播后的 LIVE Summary 页面露出跳动火焰入口。点击后进入 AI Match Deck：卡片展示 15s 高光、关系证据、共同/互补特质和推荐理由。主播可左滑跳过、右滑 Match、点 Super 直接触发 Super Match。匹配后进入可编辑的“打个招呼吧”面板，并可勾选附加 LIVE Event 邀约。若对方已喜欢你，则进入 Received 页查看 TA 的留言和 Event，选择接受或先聊天。

## Business Value

核心指标：Liner 入口点击率、Match 成功率、私聊创建率、LIVE Event 发送/接受率、Cohost 发起率、匹配后次日开播率。

## Core Flow

1. 主播关播，进入 LIVE Center 风格结算页。
2. 点击 Liner Fire，进入 AI 匹配卡池。
3. 浏览主播卡片：高光、关系标签、AI 理由、共同/互补特质。
4. 左滑跳过、右滑 Match、点 Super 直接进入 Super Match。
5. Match 成功页编辑 AI 破冰文案，可附加 LIVE Event 邀约。
6. 若“TA 喜欢了你”，右滑后查看并接受 TA 的留言和 Event。
7. Chat 页展示双方消息和 Event 卡片，并支持聊天内继续发起或接受邀约。

## 评审维度回应

| 维度 | 权重 | 回应 |
| --- | --- | --- |
| 业务价值 | 30% | 解决 LIVE 主播关系弱、Cohost 发起难的问题，v3.0 把 Match 直接推进到 LIVE Event 邀约。 |
| 创新性 | 20% | 从推荐人升级为生成社交动作：AI 同时做匹配解释、破冰、邀约主题和双向接受链路。 |
| 完成度 | 20% | 已有完整移动端可操作流程，覆盖普通 Match、Super Match、对方已喜欢你、Event 发送/接受和私聊。 |
| 可落地性 | 20% | 所需信号来自现有 LIVE 数据资产，MVP 可先用规则排序 + LLM 文案生成 + Event 卡片验证。 |
| 产品体验 | 10% | 关播时机自然，卡片解释清晰；收到邀请的分支减少从 Match 到 Cohost 的断点。 |

## Build Log

- 下载并解压 Inspire Prototype v3.0 导出包。
- 阅读 readme、route、PRD 和 changelog，确认 v3.0 核心变化。
- 基于导出包实现静态 mobile demo，覆盖 Matched 编辑面板、Received 页和 Chat Event 卡。
