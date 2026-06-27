# 仓库设置备忘 / Repo Setup Memo

建仓库时把下面内容填到 **About**（仓库主页右侧齿轮）。

## Description（描述，二选一）

**EN（推荐）**

```
🧩 Prompt Studio — a single-file, bilingual (中/EN) prompt generator for LLMs, coding/automation agents & image models. 88 templates, a composable prompt dictionary, promptfoo/DSPy export. No install, runs locally.
```

**中文**

```
🧩 多模型 / 多 Agent 提示词生成器：纯前端单文件、中英双语、88 个模板 + 可组合提示词字典，支持 promptfoo/DSPy 导出，本地即用、数据不上传。
```

## Topics（话题标签，最多 20 个）

```
prompt-engineering prompts prompt-generator llm chatgpt claude gemini ai-agents prompt-templates bilingual midjourney stable-diffusion dspy promptfoo single-file
```

可选追加：prompt-library cursor no-build vanilla-js chinese

## Website

开了 GitHub Pages 后，把 About 里的 Website 勾选为 Pages 网址：
https://<你的用户名>.github.io/<仓库名>/

## 发版 / Release

git tag v0.5-beta && git push --tags

然后在 GitHub 的 Releases 页面，把打包好的 zip 作为附件上传。
