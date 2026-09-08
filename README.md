# 🎬 AI-Drama-Skill

**A professional AI short-drama creation skill** · 专业 AI 短剧创作能力扩展包

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](VERSION.md)

> AI-Drama-Skill 是一套专业短剧创作能力扩展包，让 AI 具备影视短剧领域的专业能力——从
> 一个故事想法，发展成为完整的商业短剧项目。
>
> AI-Drama-Skill is a professional short-drama production extension pack that equips AI
> assistants with industry-grade capabilities — taking a story idea and developing it into a
> complete commercial short-drama project through a structured multi-agent pipeline.

---

## ✨ Features / 核心能力

| Capability | 能力 | Description |
|---|---|---|
| Story Development | 故事开发 | 从创意到完整故事框架的搭建 |
| Character Design | 人物设计 | 人物关系、人物弧线与角色模型设计 |
| Script Writing | 剧本创作 | 场景、对白、动作、情绪的剧本生成 |
| Quality Review | 质量审核 | 剧情、逻辑、节奏、情感的多维 QA 审核 |
| Market Analysis | 市场分析 | 受众、趋势、竞品与市场机会分析 |
| Business Analysis | 商业分析 | 变现模式、商业价值与成本收益分析 |

## 🏗 Architecture / 架构

AI-Drama-Skill 采用**多智能体 + 工作流 + 知识库**的模块化架构：

| Module | Responsibility / 职责 |
|---|---|
| `agents/` | 专业任务执行智能体（故事、人物、剧本、QA、营销等 20+ Agent） |
| `workflows/` | 任务编排与生产流水线（11 条工作流） |
| `knowledge/` | 行业经验与创作规则（题材、结构、情绪、变现等） |
| `templates/` | 标准输出模板（剧本、大纲、角色、商业模板） |
| `memory/` | 项目记忆与连续性格局（项目、角色、世界观、决策日志） |
| `router/` | 意图识别与智能体调度（意图映射、工作流映射） |
| `orchestration/` | 多智能体协作（角色权限、会议协议、冲突解决） |
| `quality_assurance/` | 质量保障（逻辑、节奏、情感、商业多维校验） |
| `evaluation/` | 评分体系（故事、角色、情感、商业四维评分） |
| `feedback/` | 反馈闭环（失败诊断、成功模式、学习工作流） |
| `research/` | 市场研究（受众、竞品、趋势 Agent） |
| `ip_universe/` | IP 宇宙（世界观、角色生命周期、季番规划、衍生开发） |
| `multimodal/` | 多模态生产（分镜、运镜、视觉、音频、视频规划） |
| `deployment/` | 部署与发布（安装、初始化、导入导出、版本发布） |

## 🎯 Production Pipeline / 生产流水线

```
市场分析 → 项目定位 → IP设计 → 人物设计 → 100集结构设计 → 分集规划 → 剧本创作 → 质量优化
Market Analysis → Project Positioning → IP Design → Character Design →
100-Episode Structure → Episode Planning → Script Writing → Quality Optimization
```

## 📜 Creation Principles / 创作原则

1. **前 30 秒必须有钩子** — The first 30 seconds must contain a hook
2. **每集必须有冲突** — Every episode must contain conflict
3. **每 3-5 集必须升级** — Escalation every 3–5 episodes
4. **每 10 集必须大高潮** — A major climax every 10 episodes
5. **结尾必须推动下一集** — Every ending must drive the next episode

## 🚀 Quick Start / 快速开始

### As an AI Skill（作为 AI 技能加载）

1. 加载 `SKILL.md`（必须读取 `CORE_RULES.md`）
2. 根据任务调用 `agents/`、`workflows/`、`knowledge/` 中的对应模块
3. 参考 `STARTUP.md` 完成系统启动与恢复

### Key Entry Files / 关键入口文件

| File | Purpose / 用途 |
|---|---|
| `SKILL.md` | 技能入口，描述能力与加载规则 |
| `CORE_RULES.md` | 核心工作流（8 步生产流程）与输出标准 |
| `manifest.yaml` | 技能清单（能力、组件、版本） |
| `capability.yaml` | 能力定义与关联智能体 |
| `router/agent_route.yaml` | 智能体路由配置 |
| `orchestration/agent_hierarchy.yaml` | 智能体协作层级 |

## 📁 Project Structure / 目录结构

```
AI-Drama-Skill/
├── agents/            # 专业任务智能体（20+）
├── automation/        # 自动化（调度、触发规则、任务队列）
├── commands/          # 常用指令（新建项目、写剧集、评审、改写）
├── config/            # 系统与工作流配置
├── deployment/        # 安装、初始化、导入导出、版本发布
├── evaluation/        # 四维评分体系
├── feedback/          # 反馈闭环与学习
├── interface/         # 输入输出接口规范
├── ip_universe/       # IP 宇宙与衍生
├── knowledge/         # 行业知识库（题材/结构/情绪/商业）
├── knowledge_graph/   # 知识图谱（角色/情感/情节/题材）
├── memory/            # 项目记忆体系
├── memory_v2/         # 记忆引擎（创作/失败/市场/策略记忆）
├── multimodal/        # 多模态生产规划
├── orchestration/     # 多智能体协作
├── quality_assurance/ # 质量保障
├── research/          # 市场研究
├── router/            # 意图路由
├── schemas/           # 数据结构定义
├── templates/         # 标准输出模板
└── workflows/         # 生产工作流
```

## 🗓 Changelog / 更新记录

See [CHANGELOG.md](CHANGELOG.md) · 当前版本 **v1.0.0**（Stable，2026-08-18）

## 🤝 Contributing / 贡献

欢迎提交 Issue 与 Pull Request，共同完善这套短剧创作能力包。

## 📄 License / 许可

本项目基于 [MIT License](LICENSE) 开源。

---

*Made for the AI short-drama community · 为 AI 短剧创作社区而作*