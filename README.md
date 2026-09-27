# PersonalSkillsCollection

这个仓库是个人收藏的 AI Agent Skills **来源索引**：记录每个已收集项目的上游 GitHub 仓库、用途和授权信息。它不镜像上游代码；请通过下方链接获取、更新或向原项目贡献。

## 收录项目

| 项目 | 上游 GitHub | 来源 / 维护者 | 简介 | 许可证 |
|---|---|---|---|---|
| Academic Research Skills | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | Edward Cheng-I Wu / 社区项目 | 面向 Claude Code 的学术研究全流程 skills：研究、写作、审阅、修订与定稿。 | 未声明 SPDX |
| arXiv Skills | [ultimatile/arxiv-skills](https://github.com/ultimatile/arxiv-skills) | ultimatile | 用 arXiv API 检索论文，并将论文材料转换为便于阅读、引用和复现的 Markdown。 | MIT |
| Binance Skills Hub | [binance/binance-skills-hub](https://github.com/binance/binance-skills-hub) | Binance | 面向 AI Agent 的加密能力市场，覆盖交易、Web3 钱包、链上数据、DeFi、支付等。 | 未声明 |
| Brave Search Skills | [brave/brave-search-skills](https://github.com/brave/brave-search-skills) | Brave | Brave Search API 的官方 Agent Skills，提供网页、新闻、图像、视频、本地搜索与 LLM context 等能力。 | MIT |
| Claude Trading Skills | [agiprolabs/claude-trading-skills](https://github.com/agiprolabs/claude-trading-skills) | AGIPro | 交易、DeFi 与量化金融 skills，涵盖市场数据、策略、链上分析、组合和风险管理。 | MIT |
| Garden Skills | [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) | ConardLi | 生产级通用 skills 集合，包含网页设计、视频演示、图像生成和本地知识库检索等。 | MIT |
| Khazix Skills | [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) | KKKKhazix（数字生命卡兹克） | 研究分析、写作、AI 资讯与项目知识整理等 Agent Skills。 | MIT |
| PPT Master | [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master) | Hugo He | 将主题或源文档生成原生可编辑 PPTX 的多角色协作工作流，支持图表、动画、旁白与模板。 | MIT |
| Anthropic Skills | [anthropics/skills](https://github.com/anthropics/skills) | Anthropic | Agent Skills 的公开参考仓库，提供示例、规范与模板。 | 未声明 |

## 使用说明

- `catalog.json` 提供与本表一致的机器可读记录，可用作后续网站、脚本或 GitHub Action 的数据源。
- “未声明”表示未在本索引中列出许可证；使用前仍应阅读仓库中的 `LICENSE`、README 与适用条款。
- 上游地址以 GitHub 仓库页面为准；克隆时在地址后加 `.git` 即可。

## 安装到本地 Agent

需要把本集合中的 skills 安装到本机某个或多个 AI Agent 时，请让 Agent 按 [INSTALL_SKILLS.md](INSTALL_SKILLS.md) 执行。该流程会从本仓库的 `catalog.json` 读取上游地址，下载并保留源仓库、扫描可用 Agent、确认各 Agent 的 skills 目录、逐一识别实际的 `SKILL.md` 目录，再复制已确认的 skills。

流程不会默认删除下载的源仓库，也不会覆盖同名 skill；涉及目标 Agent、目标目录或冲突处理时必须先征得用户确认。
