# argumentative-essay

议论文写作 AI Skill · Argumentative Essay AI Skill · 논술문 작성 AI 스킬 · 議論文作成 AI スキル

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

<p align="center">
  <b><a href="#中文">🇨🇳 中文</a> | <a href="#english">🇺🇸 English</a> | <a href="#한국어">🇰🇷 한국어</a> | <a href="#日本語">🇯🇵 日本語</a></b>
</p>

---

## 🇨🇳 中文

### 这是什么

一套完整的议论文写作规范与 AI 行为指令。可作为任意 AI 写作助手的 **system prompt**、**skill 文件**或人工写作参考。核心是一份 240 行的 `SKILL.md`（含九节完整工作流）加 7 份参考资料，覆盖中英文、应试与非应试全场景。

不绑定任何特定 AI 平台——只要 agent 能读 Markdown 就能用。

### 安装

```bash
git clone https://github.com/ArtGgsh/argumentative-essay.git
```

将 `SKILL.md` 加载为 system prompt 或放入 skill 目录即可。

### 触发方式

| 中文 | 英文 |
|------|------|
| 写一篇议论文论证…… | write an essay arguing that ... |
| 驳一下这个观点 | help me write a rebuttal |
| 帮我写一篇时评 | write an opinion piece on ... |
| 高考作文 / 申论 / 雅思大作文 | TOEFL / GRE issue |

### 覆盖场景

| 类别 | 场景 |
|------|------|
| 中文应试 | 高考作文、考研政治大题、考研英语作文、公考申论 |
| 英文应试 | 雅思 Task 2、托福 Independent Writing、GRE Issue |
| 通用写作 | 时评、学术议论、自由议论、立论文、驳论文 |

### 功能

| 功能 | 说明 |
|------|------|
| 六步流程 | 立论→谋篇→配证→选论证方法→起草→润色，默认一次性走完 |
| 字数控制 | 目标 ±20% 偏差校验，超限自动调整 |
| 创新强化 | 论点/论据/结构/表达四维度自检，防烂大街套路 |
| 自我改良 | 跨会话改进日志，自动积累写作经验 |
| 自评模块 | 参考评分 + 亮点 + 不足 + 创新度 + 改进点对照 |
| 交互模式 | 默认一次性输出七项；分步模式兜底；三档回退 |

### 版本演进

| 版本 | 新增 |
|------|------|
| v1 | 六步工作流、四类中文结构、英文五段式/Toulmin、五种论证方法、反模式清单 |
| v2 | 字数三级确认逻辑、±20% 偏差校验、自评模块 |
| v3 | 创新四维度自检、烂大街黑名单、创新角度示例库、自我改良日志 |
| v4 | 一次性交互模式、分步模式兜底、三档回退机制 |

### 文件清单

```
SKILL.md                        主文件（9 节 240 行）
README.md                       本文件
LICENSE                         MIT
.gitignore
references/
├── structures-cn.md             中文四类结构模板
├── structures-en.md             英文五段式与 Toulmin 模型
├── exam-subtypes.md             各应试类型评分偏好
├── argumentation.md             五种论证方法详解
├── pitfalls.md                  八大反模式清单
├── self-review.md               评分维度速查表
└── innovation-checklist.md      创新自检清单
```

> `logs/` 目录由 skill 运行时自动创建。

### 使用方式

- **作为 AI Skill**：将仓库放入 AI agent 的 skill 目录
- **作为人工参考**：直接阅读对应 reference 文件
- **自定义**：`innovation-checklist.md` 可按领域扩展

---

## 🇺🇸 English

### What Is This

A comprehensive argumentative essay writing specification and AI behavior instruction set. Works as a **system prompt**, **skill file**, or human writing reference for any AI writing assistant. The core is a 240-line `SKILL.md` (9-section full workflow) plus 7 reference files, covering Chinese and English, exam and non-exam scenarios.

Platform-agnostic — any agent that reads Markdown can use it.

### Install

```bash
git clone https://github.com/ArtGgsh/argumentative-essay.git
```

Load `SKILL.md` as a system prompt or place it in your agent's skill directory.

### Triggers

| Chinese | English |
|---------|---------|
| 写一篇议论文论证…… | write an essay arguing that ... |
| 驳一下这个观点 | help me write a rebuttal |
| 帮我写一篇时评 | write an opinion piece on ... |
| 高考作文 / 申论 | TOEFL independent writing / GRE issue |

### Scenarios

| Category | Types |
|----------|-------|
| Chinese Exams | Gaokao, Postgraduate Politics, Postgraduate English, Civil Service Essay |
| English Exams | IELTS Task 2, TOEFL Independent Writing, GRE Issue |
| General Writing | Commentary, Academic, Free-form, Persuasive, Rebuttal |

### Features

| Feature | Description |
|---------|-------------|
| 6-Step Workflow | Thesis → Structure → Evidence → Methods → Drafting → Polish, one-shot by default |
| Word Count Control | ±20% deviation check, auto-adjust before delivery |
| Innovation Check | 4 dimensions: angle, evidence, structure, expression + cliché blacklist |
| Self-Improvement | Cross-session improvement log, auto-accumulates writing experience |
| Self-Evaluation | Score + strengths + weaknesses + innovation rating + improvement checklist |
| Interaction Mode | One-shot 7-item output by default; step-by-step fallback; 3-tier rollback |

### Version History

| Version | Additions |
|---------|-----------|
| v1 | 6-step workflow, 4 CN structure templates, EN 5-paragraph & Toulmin, 5 argumentation methods, anti-patterns |
| v2 | 3-tier word count confirmation, ±20% check, self-evaluation module |
| v3 | 4-dimension innovation check, cliché blacklist, alternative angle library, improvement log |
| v4 | One-shot interaction mode, step-by-step fallback, 3-tier rollback mechanism |

### File Manifest

```
SKILL.md                        Main file (9 sections, 240 lines)
README.md                       This file
LICENSE                         MIT
.gitignore
references/
├── structures-cn.md             CN structure templates
├── structures-en.md             EN 5-paragraph & Toulmin model
├── exam-subtypes.md             Exam scoring preferences
├── argumentation.md             5 argumentation methods
├── pitfalls.md                  8 anti-patterns with fixes
├── self-review.md               Scoring dimension quick reference
└── innovation-checklist.md      Innovation self-check library
```

> `logs/` is auto-created at runtime.

### Usage

- **As AI Skill**: Place repo in your agent's skill directory
- **As Human Reference**: Read the relevant reference file directly
- **Customize**: Extend `innovation-checklist.md` for your domain

---

## 🇰🇷 한국어

### 소개

중국어 및 영어 논술문 작성을 위한 종합적인 AI 행동 지침입니다. 모든 AI 글쓰기 도우미의 **system prompt**, **skill 파일** 또는 개인 참고용으로 사용할 수 있습니다. 핵심은 240줄의 `SKILL.md`(9개 섹션의 전체 워크플로우)와 7개의 참고 자료로, 시험 및 비시험 시나리오를 모두 다룹니다.

특정 AI 플랫폼에 종속되지 않으며 Markdown을 읽을 수 있는 모든 에이전트에서 사용 가능합니다.

### 설치

```bash
git clone https://github.com/ArtGgsh/argumentative-essay.git
```

`SKILL.md`를 system prompt로 로드하거나 skill 디렉토리에 넣으세요.

### 트리거

| 중국어 | 영어 |
|--------|------|
| 写一篇议论文论证…… | write an essay arguing that ... |
| 驳一下这个观点 | help me write a rebuttal |
| 帮我写一篇时评 | write an opinion piece on ... |
| 高考作文 / 申论 | TOEFL / GRE issue |

### 대상 시나리오

| 구분 | 유형 |
|------|------|
| 중국어 시험 | 까오카오(高考), 대학원 정치, 대학원 영어, 공무원 시험 논술 |
| 영어 시험 | IELTS Task 2, TOEFL Independent Writing, GRE Issue |
| 일반 작성 | 시사 평론, 학술 논술, 자유 논술, 주장문, 반박문 |

### 기능

| 기능 | 설명 |
|------|------|
| 6단계 워크플로우 | 논점→구조→증거→방법→초안→수정, 기본적으로 원샷 완료 |
| 글자 수 제어 | 목표 ±20% 편차 확인, 초과 시 자동 조정 |
| 혁신성 점검 | 논점/증거/구조/표현 4가지 차원 자가 점검 + 진부한 표현 블랙리스트 |
| 자기 개선 | 세션 간 개선 로그, 작성 경험 자동 축적 |
| 자체 평가 | 점수 + 강점 + 약점 + 혁신도 + 개선 체크리스트 |
| 상호작용 모드 | 기본 원샷 7항목 출력; 단계별 폴백; 3단계 롤백 |

### 버전 히스토리

| 버전 | 추가 사항 |
|------|-----------|
| v1 | 6단계 워크플로우, 중국어 구조 템플릿 4종, 영어 5문단/Toulmin, 논증 방법 5종, 안티패턴 |
| v2 | 글자 수 3단계 확인, ±20% 편차 확인, 자체 평가 모듈 |
| v3 | 혁신 4차원 점검, 진부한 표현 블랙리스트, 대안 각도 라이브러리, 개선 로그 |
| v4 | 원샷 상호작용 모드, 단계별 폴백, 3단계 롤백 |

### 파일 구성

```
SKILL.md                        메인 파일 (9개 섹션, 240줄)
README.md                       이 파일
LICENSE                         MIT
.gitignore
references/
├── structures-cn.md             중국어 구조 템플릿
├── structures-en.md             영어 5문단 & Toulmin 모델
├── exam-subtypes.md             시험별 채점 기준
├── argumentation.md             5가지 논증 방법
├── pitfalls.md                  8가지 안티패턴과 수정 예시
├── self-review.md               채점 기준 요약표
└── innovation-checklist.md      혁신성 자가 점검 라이브러리
```

> `logs/` 디렉토리는 런타임에 자동 생성됩니다.

### 사용법

- **AI Skill로**: 저장소를 AI 에이전트의 skill 디렉토리에 배치
- **개인 참고용으로**: 해당 reference 파일을 직접 읽기
- **커스터마이즈**: `innovation-checklist.md`를 자신의 분야에 맞게 확장

---

## 🇯🇵 日本語

### 概要

中国語・英語の議論文作成のための包括的な AI 行動指針です。あらゆる AI ライティングアシスタントの **system prompt**、**skill ファイル**、または個人の参考資料として使用できます。中核は 240 行の `SKILL.md`（9 セクションの完全ワークフロー）と 7 つの参考ファイルで、試験・非試験の両シナリオをカバーします。

特定の AI プラットフォームに依存せず、Markdown を読めるエージェントであれば使用可能です。

### インストール

```bash
git clone https://github.com/ArtGgsh/argumentative-essay.git
```

`SKILL.md` を system prompt としてロードするか、skill ディレクトリに配置してください。

### トリガー

| 中国語 | 英語 |
|--------|------|
| 写一篇议论文论证…… | write an essay arguing that ... |
| 驳一下这个观点 | help me write a rebuttal |
| 帮我写一篇时评 | write an opinion piece on ... |
| 高考作文 / 申论 | TOEFL independent writing / GRE issue |

### 対象シナリオ

| 区分 | タイプ |
|------|--------|
| 中国語試験 | 高考作文、大学院政治、大学院英語、公務員試験論文 |
| 英語試験 | IELTS Task 2、TOEFL Independent Writing、GRE Issue |
| 一般作文 | 時評、学術論文、自由論文、主張文、反論文 |

### 機能

| 機能 | 説明 |
|------|------|
| 6ステップワークフロー | 論点→構成→証拠→手法→起草→推敲、デフォルトで一括実行 |
| 文字数制御 | 目標 ±20% 偏差チェック、超過時は自動調整 |
| 革新性チェック | 論点・証拠・構成・表現の4次元自己チェック＋陳腐表現ブラックリスト |
| 自己改善 | セッション間改善ログ、執筆経験を自動蓄積 |
| 自己評価 | スコア＋強み＋弱点＋革新性＋改善チェックリスト |
| 対話モード | デフォルト一括7項目出力・ステップバイステップフォールバック・3段階ロールバック |

### バージョン履歴

| バージョン | 追加内容 |
|------------|----------|
| v1 | 6ステップWF、中国語構造4種、英語5段落/Toulmin、論証方法5種、アンチパターン |
| v2 | 文字数3段階確認、±20%偏差チェック、自己評価モジュール |
| v3 | 革新性4次元チェック、陳腐表現ブラックリスト、代替角度ライブラリ、改善ログ |
| v4 | 一括対話モード、ステップバイステップフォールバック、3段階ロールバック |

### ファイル構成

```
SKILL.md                        メインファイル（9セクション、240行）
README.md                       このファイル
LICENSE                         MIT
.gitignore
references/
├── structures-cn.md             中国語構造テンプレート
├── structures-en.md             英語5段落 & Toulmin モデル
├── exam-subtypes.md             試験別採点基準
├── argumentation.md             5つの論証方法
├── pitfalls.md                  8つのアンチパターンと修正例
├── self-review.md               採点基準クイックリファレンス
└── innovation-checklist.md      革新性自己チェックライブラリ
```

> `logs/` ディレクトリは実行時に自動生成されます。

### 使い方

- **AI Skill として**: リポジトリを AI エージェントの skill ディレクトリに配置
- **個人参考として**: 該当する reference ファイルを直接読む
- **カスタマイズ**: `innovation-checklist.md` を自分の分野に合わせて拡張


## License

MIT
