# 和田十二法 Skill —— 项目创新与创意思考助手

一个面向 Codex 和其他兼容 Agent Skills 规范的创意思考 skill，将“和田十二法”转化为适用于项目开发、功能设计、流程改进和技术方案发散的结构化工作流。

“和田十二法”是一套创新思维方法，包含加、减、扩、缩、变、改、联、学、代、搬、反、定等共12种启发创意的思考角度。

English documentation is available in the [English section](#english).

## 功能

- 使用“加、减、扩、缩、变、改、联、学、代、搬、反、定”十二个方向系统发散。
- 区分已知事实、假设、约束和待验证项。
- 对候选想法进行组合、去重与取舍。
- 输出推荐方向以及可执行的最小验证方案。
- 避免把头脑风暴结果误当作已确认需求或实施授权。

## 适用场景

- 项目开发陷入惯性方案，需要寻找遗漏方向。
- 改进产品功能、用户体验、架构、测试、部署或协作流程。
- 在实施前比较多个替代方案。
- 用户明确要求使用“和田十二法”或进行结构化头脑风暴。

## 安装到 Codex

将本仓库克隆到 Codex 的个人 skills 目录：

```powershell
git clone https://github.com/ddlly/hetian-12-methods.git "$env:USERPROFILE\.codex\skills\hetian-12-methods"
```

最终目录结构应为：

```text
~/.codex/skills/hetian-12-methods/
├── SKILL.md
├── README.md
└── LICENSE
```

安装后，在 Codex 中开始一个新对话。如果未立即识别，重新启动 Codex。

## 使用方法

显式调用：

```text
使用 $hetian-12-methods，为当前项目进行创意发散。
```

也可以直接描述适用任务，Codex 可根据 `SKILL.md` 中的触发条件自动选择该 skill。

## 十二种思考方向

| 方法 | 主要方向 |
|---|---|
| 加一加 | 增加、组合、叠加 |
| 减一减 | 删除、拆除、省略 |
| 扩一扩 | 放大、延伸、增强 |
| 缩一缩 | 缩小、压缩、聚焦 |
| 变一变 | 改变形态、顺序或状态 |
| 改一改 | 修正缺点、改善体验 |
| 联一联 | 连接、关联、联动 |
| 学一学 | 模仿、借鉴、类比 |
| 代一代 | 替换材料、角色、技术或方法 |
| 搬一搬 | 移植、迁移、改变位置或场景 |
| 反一反 | 反向、倒序、角色互换 |
| 定一定 | 设定边界、标准和规则 |

完整操作流程、项目开发提问、输出格式、约束和示例请参阅 [`SKILL.md`](./SKILL.md)。

## 许可证

本项目采用 [MIT License](./LICENSE)。

---

## English

# Hetian Twelve Methods for Project Ideation

A skill for Codex and other Agent Skills-compatible tools. It adapts the Hetian Twelve Methods into a structured workflow for project development, feature design, process improvement, and technical ideation.

## Features

- Explores a problem through twelve transformation directions: add, subtract, expand, shrink, transform, improve, connect, learn, substitute, relocate, reverse, and define.
- Separates known facts, assumptions, constraints, and open questions.
- Combines, deduplicates, and evaluates candidate ideas.
- Produces a focused recommendation and a minimum validation experiment.
- Keeps brainstorming output separate from confirmed requirements and implementation authorization.

## When to Use

- A project is stuck in familiar solution patterns.
- A team wants alternatives for a feature, workflow, architecture, test strategy, or deployment process.
- Multiple options should be explored before implementation.
- The user explicitly requests the Hetian Twelve Methods or a structured brainstorm.

## Install for Codex

Clone this repository into the personal Codex skills directory:

```powershell
git clone https://github.com/ddlly/hetian-12-methods.git "$env:USERPROFILE\.codex\skills\hetian-12-methods"
```

Start a new Codex conversation after installation. Restart Codex if the skill is not detected immediately.

## Usage

Invoke the skill explicitly:

```text
Use $hetian-12-methods to brainstorm improvements for the current project.
```

Codex may also select the skill automatically when a request matches the trigger conditions in `SKILL.md`.

See [`SKILL.md`](./SKILL.md) for the complete workflow, prompts, output format, constraints, and example.

## License

This project is licensed under the [MIT License](./LICENSE).
