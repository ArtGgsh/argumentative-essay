# argumentative-essay

议论文写作 AI Skill —— 覆盖中英文议论文全场景，从立论到成文一步到位。

<p align="center">
  <img src="https://img.shields.io/github/stars/ArtGgsh/argumentative-essay?style=flat-square&color=yellow" alt="Stars">
  <img src="https://img.shields.io/github/license/ArtGgsh/argumentative-essay?style=flat-square&color=blue" alt="License">
  <img src="https://img.shields.io/github/last-commit/ArtGgsh/argumentative-essay?style=flat-square&color=green" alt="Last Commit">
  <img src="https://img.shields.io/github/repo-size/ArtGgsh/argumentative-essay?style=flat-square&color=lightgrey" alt="Repo Size">
  <img src="https://img.shields.io/github/directory-file-count/ArtGgsh/argumentative-essay?style=flat-square&color=orange" alt="Files">
</p>

<p align="center">
  <a href="https://star-history.com/#ArtGgsh/argumentative-essay&Date">
    <img src="https://api.star-history.com/svg?repos=ArtGgsh/argumentative-essay&type=Date" alt="Star History Chart" width="500">
  </a>
</p>

---

## 这是什么

一套完整的议论文写作规范与 AI 行为指令。可作为任意 AI 写作助手的 **system prompt**、**skill 文件**、或人工写作参考。核心是一份 240 行的 `SKILL.md`（含九节完整工作流）加 7 份参考资料，覆盖中英文、应试与非应试全场景。

不绑定任何特定 AI 平台——只要 agent 能读 Markdown 就能用。

---

## 一句话安装

将本仓库所有文件放到你的 AI 写作助手的 skill 目录下，或将 `SKILL.md` 作为 system prompt 加载。

```bash
git clone https://github.com/ArtGgsh/argumentative-essay.git
```

---

## 触发方式

当用户发出类似指令时激活：

| 中文 | 英文 |
|------|------|
| 写一篇议论文论证…… | write an essay arguing that ... |
| 驳一下这个观点 | help me write a rebuttal |
| 帮我写一篇时评 | write an opinion piece on ... |
| 高考作文 / 申论 / 雅思大作文 | TOEFL independent writing / GRE issue |

---

## 覆盖场景

| 类别 | 场景 |
|------|------|
| 中文应试 | 高考作文、考研政治大题、考研英语作文、公考申论 |
| 英文应试 | 雅思 Task 2、托福 Independent Writing、GRE Issue |
| 通用写作 | 时评、学术议论、自由议论、立论文、驳论文 |

---

## 功能总览

| 功能 | 说明 |
|------|------|
| 六步流程 | 立论→谋篇→配证→选论证方法→起草→润色，默认一次性走完 |
| 字数控制 | 目标 ±20% 偏差校验，超限自动调整后交付 |
| 创新强化 | 论点/论据/结构/表达四维度自检，烂大街黑名单防套路 |
| 自我改良 | 跨会话 `logs/improvement-log.md`，自动积累写作经验 |
| 自评模块 | 参考评分 + 亮点 + 不足 + 创新度 + 改进点对照 |
| 交互模式 | 默认一次性输出七项；分步模式兜底；三档回退机制 |

---

## 版本演进

| 版本 | 新增 |
|------|------|
| v1 | 六步工作流、四类中文结构、英文五段式与 Toulmin、五种论证方法、反模式清单、五篇样例 |
| v2 | 字数三级确认逻辑、±20% 偏差校验、自评模块（评分+亮点+不足） |
| v3 | 创新四维度自检、烂大街黑名单、创新角度示例库、自我改良日志 |
| v4 | 一次性交互模式（取消三步停等）、分步模式兜底、三档回退机制 |

---

## 文件清单（10 个文件）

```
SKILL.md                        主文件（9 节 240 行，含完整工作流指令）
README.md                       本文件
LICENSE                         MIT
.gitignore
references/
├── structures-cn.md             中文四类结构模板
├── structures-en.md             英文五段式与 Toulmin 模型
├── exam-subtypes.md             各应试类型评分偏好与踩分要点
├── argumentation.md             五种论证方法详解（正反例 + checklist）
├── pitfalls.md                  八大反模式清单与修改范例
├── self-review.md               各应试尺度评分维度速查表
└── innovation-checklist.md      创新自检清单（黑名单 + 替代角度库 + 表达替换表）
```

> `logs/` 目录由 skill 运行时自动创建，不上传仓库。

---

## 如何使用

### 作为 AI Skill

将整个仓库放入你的 AI agent 的 skill 目录，agent 会在用户请求议论文时自动加载 `SKILL.md` 作为行为指令。

### 作为人工参考

直接阅读各文件：
- 想学结构 → `references/structures-cn.md`
- 想学论证 → `references/argumentation.md`
- 想避坑 → `references/pitfalls.md`
- 想自评 → `references/self-review.md`

### 自定义

`references/innovation-checklist.md` 中的黑名单和示例库可按你的领域扩展。`logs/improvement-log.md` 由系统自动维护，记录每次写作的改进轨迹。


## License

MIT
