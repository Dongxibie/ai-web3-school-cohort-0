# Week 1 — 工具准备记录

> 日期: 2026-05-18
> 状态: 进行中

## 一、协作工具

| 工具 | 用途 | 状态 |
|------|------|------|
| Telegram | AI × Web3 School 社区沟通、课程通知、同学交流。加入 [t.me/aiweb3school](https://t.me/aiweb3school) | 待加入 |
| WCB 平台 | 课程观看、打卡提交、任务管理。入口: https://web3career.build/zh/programs/AI-Web3-School | 已就绪 |
| GitHub | 学习仓库管理、开源协作、Proof-of-Work 展示。本仓库即为此用途 | ✅ 已就绪 |
| Zoom | Bootcamp 线上会议、Office Hour 参与 | 按需准备 |

### 说明

- 主要协作通过 **WCB 平台 + Telegram 社区** 完成，课程安排和打卡入口均在 WCB 上。
- **GitHub** 作为个人学习记录和开源沉淀的主要载体，由 Claude Code Learning Agent 辅助维护。
- Zoom 等会议工具在 Bootcamp 正式日程确定后按需安装。

## 二、AI 工具

| 工具 | 用途 | 状态 |
|------|------|------|
| **Claude Code** (当前使用) | 作为 Learning Agent 辅助学习：生成每日打卡草稿、维护学习仓库、整理笔记、解释概念、生成代码原型。与 GitHub MCP 工具配合完成文件管理和 Git 操作。 | ✅ 已就绪 |
| **GLM API / 其他 LLM** | 课程中的 Prompt Engineering 实践和模型对比实验 | 待准备 |

### Claude Code 在 Week 1 中的具体任务

1. **每日打卡辅助**：读取 WCB Learning 页面和 Handbook，生成每日学习笔记草稿，包含学习内容、时间、产出
2. **仓库维护**：根据学习进度更新 learning-plan.md、创建 daily/ 笔记、整理 handbook-feedback/
3. **概念解释**：对 Handbook 中不理解的概念提供补充说明
4. **实验辅助**：协助编写代码原型（如 Prompt 测试、Agent 工作流等）

## 三、Web3 工具

| 工具 | 用途 | 状态 |
|------|------|------|
| MetaMask（浏览器插件） | 测试钱包，用于 Web3 基础课程的链上交互练习 | 待安装 |
| Etherscan（区块浏览器） | 查询交易、合约状态，配合 Web3 网络章节学习 | 待使用 |
| Remix IDE | 在线 Solidity 合约编写和测试，适合智能合约入门 | 待使用 |
| Hardhat / Foundry | 本地合约开发框架，用于后续实验和 Hackathon 项目 | 按需准备 |

### 安装计划

1. **MetaMask** — Week 1 学习钱包和网络章节时安装，创建测试账户
2. **Remix IDE** — 学习智能合约章节时直接使用网页版 (remix.ethereum.org)
3. **Etherscan** — 配合网络和交易查询使用，无需安装

## 四、隐私与安全备忘

- 所有 API Key、私钥、助记词 **绝不** 提交到公开仓库
- 测试钱包使用单独创建的测试账户，不与主网资产关联
- `.env` 文件已加入 `.gitignore`（如需要）

## 五、下一步计划

- [ ] 加入 Telegram 社区
- [ ] 安装 MetaMask 并创建测试钱包
- [ ] 熟悉 WCB 平台的课程和打卡入口
- [ ] 准备 GLM 或其他 API Key 用于 AI 实验（存放在本地环境变量）

---

*此文件由 Learning Agent 辅助生成，随工具准备进度更新。*
