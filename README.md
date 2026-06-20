# argumentative-essay

议论文写作 Reasonix Skill —— 覆盖中英文议论文全场景，从立论到成文一步到位。

## 触发方式

在 Reasonix 中通过 `/argumentative-essay` 或 `run_skill({ name: "argumentative-essay" })` 调用。

典型触发语：写一篇议论文论证某观点、帮我写时评、write an essay arguing that ...、高考/雅思/托福/GRE 作文。

## 覆盖场景

| 场景 | 类型 |
|------|------|
| 中文 | 高考作文、考研政治大题、考研英语作文、公考申论、时评、学术议论、自由议论 |
| 英文 | 雅思 Task 2、托福 Independent Writing、GRE Issue、学术 essay |

## 功能

- **六步流程**：立论 → 谋篇 → 配证 → 选论证方法 → 起草 → 润色，默认一次性走完
- **字数控制**：目标 ±20% 偏差校验，超限自动调整
- **创新强化**：论点/论据/结构/表达四维度自检，防烂大街套路
- **自我改良**：跨会话改进日志，自动积累写作经验
- **自评模块**：参考评分 + 亮点 + 不足 + 创新度 + 改进点对照

## 文件结构

```
SKILL.md                        主文件（含完整工作流指令）
references/
├── structures-cn.md             中文四类结构模板
├── structures-en.md             英文五段式与 Toulmin 模型
├── exam-subtypes.md             各应试类型评分偏好
├── argumentation.md             五种论证方法详解
├── pitfalls.md                  反模式清单
├── self-review.md               评分维度速查表
└── innovation-checklist.md      创新自检清单
```

## 安装

将本仓库克隆到 Reasonix 项目的 `.reasonix/skills/argumentative-essay/` 目录下即可。

## License

MIT
