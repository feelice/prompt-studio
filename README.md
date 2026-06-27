# 🧩 Prompt Studio — v0.5 beta

**中文** · [English](README.en.md)

> 多模型 / 多 Agent 提示词生成器 · 纯前端单文件 · 中英双语 · 88 模板 + 可组合字典 · 本地即用，数据不上传

面向多模型 / 多 Agent 的 Prompt 生成器。纯前端单文件，**双击 `index.html` 即可在浏览器本地使用**：无需安装、无需联网、数据不上传。

A multi-model / multi-agent prompt generator. A single static HTML file — just open `index.html`. No install, no network, nothing leaves your machine.

---

## 功能 / Features

- **六大类目**：通用大模型、🎭 角色库、编程类 Agent、自动化 Agent、绘图/多模态、提示工程
- **88 个双语模板**，借鉴 GitHub 高星仓库（含 38 个主流角色）
- **提示词字典**：每个字段下方挂双语可点 chips（语气/篇幅/格式、图像风格·光线·镜头·参数、编程开发/维护/测试规范…），点选即自由组合
- **中英一键切换**：界面、模板、字典、输出、使用规范全部双语
- **三档输出**：简版 / 标准 / 详尽
- **导入并定制**：粘贴自然语言或粗糙 prompt → 自动拆解为结构化定制版；或生成「优化指令」交给 AI 精修
- **我的模板**：本地保存 / 收藏（localStorage），刷新不丢
- **导出工程格式**：promptfoo YAML 测试配置、DSPy 代码片段
- 变量占位符、场景搜索、一键复制、下载 .md、使用规范说明、版本徽章

---

## 快速开始 / Quick Start

1. 解压本压缩包，双击 `index.html`（用现代浏览器打开）。
2. 选目标类型 → 选场景模板（或用「导入并定制」）→ 用字段下方 chips 自由组合 → 填 `{变量}` → 选层级 → 生成。
3. 复制 / 下载结果，或导出 promptfoo / DSPy。

> 顶部标题旁的版本徽章会显示当前版本（应为 **v0.5 beta**），可据此判断是否最新。

---

## 文档 / Docs

- **`USAGE.md`** — 详细使用说明：全局 vs. 特定项目用法，开发/维护/测试应遵循的规范要求
- **`CHANGELOG.md`** — 版本更新日志（各版本变更清单）
- **`DEVLOG.md`** — 开发日志（开发过程、关键决策、问题与修复）
- **`NOTICE.md`** — 版权与署名说明（原创性声明、来源许可）
- **`LICENSE`** — MIT 许可证

---

## 扩展 / Extending

内容集中在 `index.html` 的 `<script>` 中，改数据即可扩展，无需改逻辑：

- `CATS` — 类目与字段定义
- `TPL` — 场景模板（按类目分组，每条双语）
- `DICT` — 提示词字典片段库
- `SPECS` — 各类目使用规范
- `I18N` — 界面文案

---

## 样本来源 / Sources

- f/awesome-chatgpt-prompts · CHENJIAMIAN/awesome-chatgpt-prompts-zh-CN · NeekChaw/awesome-prompt
- PatrickJS/awesome-cursorrules（CC0）
- langGPTai/LangGPT · stanfordnlp/DSPy · promptfoo · prompt-optimizer
- altryne/awesome-ai-art-image-synthesis

---

纯静态单文件 · 数据保存在本地浏览器，不上传。
