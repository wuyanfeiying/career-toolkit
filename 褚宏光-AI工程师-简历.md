# 褚宏光

**男 | 34岁 | 18577332539 | chuhongguang@yeah.net**

**8年工作经验 | 求职意向：AI 工程师（Vibe Coding 全栈方向） | 期望城市：杭州**

---

## 个人优势

1. **从前端到 AI 全栈的完整转型路径**：8年开发经验，近2年深度参与 AI Agent、RAG、MCP 协议等项目的全链路落地，具备前端/后端/AI 应用层的全栈交付能力
2. **Vibe Coding 深度实践者**：日常使用 Claude Code、Cursor、VS Code Copilot 进行 AI 辅助开发，主导多个项目从 0 到 1 的 Vibe Coding 交付，沉淀了 Prompt 工程规范和 AI Coding Pattern
3. **AI 工程落地经验**：参与构建 MCP 协议服务端、7阶段 AI Agent 工作流规划系统、知识卡片 RAG 流水线、Skill 评估框架等核心系统
4. **技术栈**：Node.js / Python / Vue 3 / React / TypeScript / Electron，熟悉 MongoDB / Redis / LangChain / OpenAI API / MCP SDK
5. **AI 内容创作者**：运营多平台自媒体账号，持续输出 AI 工具科普内容（Agent、Skill、OpenClaw 等方向）
6. **软件工程硕士**，具备研究思维和系统性分析能力

---

## 工作经历

### 杭州两叶科技有限公司 — AI 工程师 / 全栈开发

**2023.07 - 至今**

入职初期负责前端开发与项目维护，2025年起全面转型为 AI 全栈工程师，深度使用 Vibe Coding 方式参与公司核心 AI 产品的开发与落地。

**核心职责：**

- 使用 Claude Code / Cursor / Copilot 进行 Vibe Coding，独立完成多个 AI 应用从需求理解到代码实现、测试部署的全流程交付
- 参与 AI Agent 后端服务、知识工程系统、Skill 评估平台等核心产品开发
- 沉淀 Prompt 模板规范、卡片生产 SOP、审计规则等 AI 工作流最佳实践
- 与甲方直接沟通需求，产出 Demo 原型并推进落地

**主要业绩：**

- 落地 MCP 协议（Model Context Protocol）公式执行服务端，支持多公式批量执行与依赖自动解析
- 参与构建 7 阶段工作流规划系统，从 v3.2 迭代至 v3.5，涵盖意图分析、知识召回、DAG 融合、方案生成等完整链路
- 搭建知识卡片生产 + 审计流水线，对接 MongoDB 与向量库，制定 5 类卡片质量审计规则
- 构建 Skill A/B 测试评估框架，实现多模型 Function Calling 测试与训练/测试/验证集分层评估体系
- 使用 Python Numba JIT 优化技术形态识别算法，性能提升 300+ 倍（30秒 → 2.5秒处理 54,000 数据点）

---

### 凌雄技术（深圳）有限公司 — 前端开发工程师

**2020.09 - 2023.03**

公司品牌"小熊U租"，主营 IT 设备租赁服务（已上市）。负责公司多个核心系统的前端开发，涉及 PC 端、移动端及 uni-app 混合开发。

**核心项目：**

- **工作流系统**：负责公司内部审批与工作流程系统，封装"动态表单"业务组件，PC + 移动端双端开发
- **小熊U宝 APP**（uni-app）：独立完成项目框架搭建，含工作台、待办事项、数据总览、工具箱四大模块，获公司年度重点项目奖金
- **多系统免登录方案**：基于 Cookie + Token + Axios 拦截器实现跨系统、钉钉轻应用、第三方 iframe 嵌入的统一免登录

**主要业绩：**

- 开发百宝箱、上门核查、商品查询等功能，获评企业优秀员工
- 公司 2022 年研发重点项目（小熊U宝 APP）如期完成，获项目奖金

---

### 深圳市乐家云计算有限公司 — Web 前端开发

**2018.07 - 2020.08**

负责品牌旗下餐饮小程序"乐凯撒+"的全面开发与维护。

- 使用原生小程序 + OMIX 2.0 进行开发，独立完成积分商城、DIY 拼团、拉新裂变等模块
- 参与小程序全面改版，重构结算页面逻辑，引入状态管理方案
- 拉新裂变功能成功引流，获 2019 年度优秀员工、项目奖金

---

## 项目经历

### AI Agent 后端服务（gpt_server）

**Node.js + Express + OpenAI + LangChain + MCP SDK + MongoDB + Redis**

GPT Agent 后端核心服务，提供 AI 推理、工作流规划、公式执行等能力，服务于量化投研业务场景。

- 落地 MCP 协议公式执行服务端，实现多公式批量执行、自动依赖解析与并发调度
- 参与 7 阶段工作流规划系统开发（意图分析 → 知识召回 → 知识剪裁 → DAG 融合 → 方案生成），从 v3.2 迭代至 v3.5
- 集成 LangChain、OpenAI、Sentry 监控、Celery 异步任务处理等基础设施
- 服务 40+ 功能模块，包括工作流规划、图表渲染、数据爬取、订阅管理等

### 知识卡片工程系统（knowledge_engineer）

**Python 3.10 + MongoDB + 向量库 + Prompt 工程**

以知识卡片为核心的数据与内容工程系统，实现卡片生产、审计、数据刷新、数据库与向量库同步全流程。

- 构建卡片生产 SOP：从公式链梳理 → 向量化 → 数据库同步 → 质量审计的完整流水线
- 开发 5 类卡片审计工具（action 对齐性、数据名一致性、引用真实性、缓存规范、步骤颗粒度）
- 对接 MongoDB 存储与向量库同步，实现卡片内容的检索增强能力
- 制定 Prompt 审计规范，确保卡片质量与一致性

### AI Skill 评估平台（skill-lab）

**Python + OpenAI Function Calling + 多模型评估**

AI Skill 的测试与迭代实验台，用于评估 Skill 改动对投研问答质量的影响。

- 搭建完整的 A/B 测试评估框架，支持单题验证与批量回归两种模式
- 实现训练集 / 测试集 / 验证集三层分离的评估体系，防止过拟合
- 对接多模型（GPT、Kimi 等）进行 Function Calling 测试，输出 Trace 分析报告
- 部署到 ArkClaw 平台供客户使用

### 智能资产评级系统 Demo（quantBuddy_assetRating）

**React 19 + TypeScript + Recharts + TailwindCSS**

与甲方直接沟通需求后，独立产出的智能资产评级系统前端原型。

- 使用 Vibe Coding 方式快速完成 React 19 项目从 0 到 1 的交付
- 实现多维度评级、估值分析（PB/PE/PS）、宏观背景分析、资金流向追踪等金融可视化模块
- 支持自定义评级模板保存与拖拽配置，交付后由前端团队接手迭代

### 跨平台 Agent 桌面应用（electron-agent）

**Electron + Vue 3 + TypeScript + Python + WebSocket**

系统托盘 Agent 应用，支持远程命令执行与 Python 脚本调度。

- 独立完成 Electron 应用架构搭建，支持 MacOS / Windows 双平台
- 实现 WebSocket 双向通信，支持远程 Python 脚本执行与结果回传
- 集成 PyInstaller 打包 Python 环境，解决跨平台依赖问题
- 覆盖 Jest（Electron）、Vitest（Vue）、Pytest（Python）三层测试

### 技术形态识别算法（technical-patterns-lab）

**Python + Numba JIT + 数据分析**

收敛三角形等技术形态检测工具，用于量化投研中的形态识别。

- 使用 Numba JIT 加速核心算法，性能从 30 秒优化至 2.5 秒，提升 300+ 倍
- 实现对称/上升/下降三种收敛三角形的自动检测与突破强度评分
- 支持实时与历史回测双模式，生成每日 Top-N 报告 + K 线可视化

---

## 自媒体运营经历

**AI 工具科普博主 | 2024.12 - 至今**

运营多平台自媒体账号（公众号、知乎、B站、小红书等），持续输出 AI 工具使用教程与科普内容。

- 覆盖方向：AI Agent、Skill开发、OpenClaw、Vibe Coding 等前沿领域
- 自建博客网站（Nuxt 3 SSG + Strapi CMS），搭配多平台自动化发布工具链
- 开发运营数据中心（11 平台账号管理），实现粉丝追踪、内容数据分析、选题管理

---

## 教育经历

### 广西师范大学 — 硕士 · 软件工程

**2015 - 2018**

- 论文专利：非独立同分布环境下的多相关性差分隐私矩阵分解方法
- 研究方向：基于视觉感受野空间属性的视觉计算模型及图像检索（国家自然科学基金项目）

### 梧州学院 — 本科 · 产品设计

**2011 - 2015**

- 三年班级班长，连续两年获"优秀学生干部"

---

## 技术技能

| 领域 | 技术 |
|------|------|
| **AI 工具** | Claude Code、Cursor、VS Code Copilot、Prompt Engineering |
| **后端** | Node.js / Express、Python 3.10+、MongoDB、Redis |
| **前端** | Vue 3 / React 19 / TypeScript / Vite / TailwindCSS |
| **AI 生态** | OpenAI API、LangChain、MCP SDK、Function Calling |
| **桌面/跨端** | Electron、uni-app、原生微信小程序 |
| **工程化** | Git、Webpack / Vite、ESLint / Ruff / Black、Jest / Vitest / Pytest |
| **数据分析** | ECharts、Recharts、Numba JIT、Excel 数据处理 |
