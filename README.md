# Project Reese — Employee Recognition Experience Prototypes

> 一组围绕「员工嘉奖（Employee Recognition）」体验的高保真原型，演示嘉奖如何在日常工作流中被**发现、发送、庆祝、沉淀**，并跨越 Microsoft 365 多个协作面（Copilot / Outlook / Teams / Viva）。

## 项目背景 Background

**嘉奖应该发生在工作发生的地方。**

员工通常不会主动打开一个独立的嘉奖工具去感谢同事。真正有价值的贡献——尤其是那些「隐形工作」——常常因为流程割裂、时机错过而被遗忘；而当人们想表达感谢时，又会因为「不知道写什么、怕显得套路」而放弃。

本项目探索一种**嵌入式、AI 辅助**的嘉奖体验：系统在员工的日常协作流程（会议、邮件、项目协作）中自然识别嘉奖机会，主动推荐值得认可的贡献者，帮助用户用可编辑的 AI 草稿快速表达真诚的感谢，并将这些认可在正确的团队场景中庆祝、最终沉淀为长期的**职业可见性**与**组织人才洞察**。

### 产品旅程 Journey（4 个阶段）

| 阶段 | 1. Discover Contributions | 2. Send Recognition | 3. Celebrate Recognition | 4. Build Career Visibility |
|---|---|---|---|---|
| 类型 | Discovery 发现 | Creation 创作 | Celebration 庆祝 | Memory 沉淀 |
| 目标 | 识别值得认可的贡献者 | 清晰而有意义地表达感谢 | 让员工被看见，并与团队共享喜悦 | 理解并展示长期影响力 |

完整旅程图见 [`recognition-journey-map.html`](recognition-journey-map.html)（source of truth），中文说明见 [`Recognition_Journey_Map_CN.md`](Recognition_Journey_Map_CN.md)。

## 文档说明 What's in each file

| 文件 | 触点 / 阶段 | 展示内容 |
|---|---|---|
| [`recognition-journey-map.html`](recognition-journey-map.html) | 全局 · 阶段 1–4 | **横向产品旅程图**（最终版本 / source of truth）。展示嘉奖从发现到职业沉淀的 4 个阶段，每阶段含 Current State（挑战 / 机会）与 Future Experience（触发 / 用户动作 / 系统动作 / 关键产出）。底部「Cross-platform Touchpoints」可点击 Cowork / Outlook / Teams 等触点，在内嵌 iframe 中打开对应原型。 |
| [`copilot-recognition-prototype.html`](copilot-recognition-prototype.html) | Copilot / Cowork · 阶段 1–2 | **Microsoft 365 Copilot 嘉奖工作流**。演示 Copilot 在会议回顾 / 任务场景中识别协作贡献者，主动推荐嘉奖机会，并辅助用户发起嘉奖。 |
| [`copilot-recognition-prototype-outlook.html`](copilot-recognition-prototype-outlook.html) | Copilot → Outlook · 阶段 1–2 | Copilot 工作流的**扩展版**，进一步衔接到 Outlook 邮件场景，展示从 Copilot 发现机会到通过邮件上下文完成嘉奖的跨面流转。 |
| [`outlook-recognition-prototype.html`](outlook-recognition-prototype.html) | Outlook · 阶段 1–3 | **Outlook 邮件嘉奖与设置**。展示嘉奖提醒邮件、嘉奖公告邮件、以及从邮件直接打开 Teams 应用进行设置 / 退订（链接指向 Teams 原型的设置页 `?pg=set`）。 |
| [`teams-recognition-prototype.html`](teams-recognition-prototype.html) | Teams · 阶段 1–3 | **Microsoft Teams Recognition Hub**。主嘉奖中心：左侧导航含 Notifications（通知）与 Recognition（嘉奖）；通知中可处理「审批请求」、用可编辑的 AI 草稿卡片撰写并发送嘉奖；含 Settings 页（触发类型、提醒偏好等）。 |
| [`Recognition_Journey_Map_CN.md`](Recognition_Journey_Map_CN.md) | 文档 | 旅程图的**中文说明文档**，与 `recognition-journey-map.html` 保持同步（HTML 为最终版本）。 |

## 如何查看 How to view

所有原型均为**纯静态 HTML/CSS/JS**，无需构建或安装依赖。

- 直接用浏览器打开任意 `.html` 文件即可；
- 推荐从 [`recognition-journey-map.html`](recognition-journey-map.html) 进入，通过底部触点跳转浏览各原型；
- 公开在线版本托管于 [xinjiapang96/Project-Reese](https://github.com/xinjiapang96/Project-Reese)（GitHub Pages）。

## 设计风格 Design

遵循 Microsoft Fluent / Teams 视觉语言：品牌色 `#5b5fc7`，圆角 16px，浅灰背景 `#f6f6f9`，统一的卡片与分隔线规范。