# Changelog — Prompt Studio

版本更新日志，新版本写在最上方。开发过程与决策见 `DEVLOG.md`，使用说明见 `USAGE.md`。

Version changelog, newest on top. See `DEVLOG.md` for the development story and `USAGE.md` for usage.

## [Unreleased]
- 计划：组合收藏（把常用 chips 存为"配方"）
- 计划：互斥/冲突提示
- 计划：A/B 版本对比

## [0.5 beta] — 2026-06-27
### 新增 / Added
- **提示词字典（可自由组合的片段库）**：每个字段下方挂一排双语 chips，点选即拼入字段、再点取消、自动处理分隔符
  - 通用字段：角色（资历/视角）、上下文（受众·领域/时空·条件/已知信息，含 {数据} 占位）、约束（语气/篇幅/受众/事实性/禁止项）、输出（结构/格式/粒度）
  - 编程约束：开发 / 维护 / 测试规范拆成可勾选项
  - 图像：风格 / 画质 / 光线 / 镜头 / 构图 / 负向 / Midjourney 与 SD 参数
- 字典内容易扩展：改 `index.html` 中的 `DICT` 对象即可

## [0.4 beta] — 2026-06-27
### 新增 / Added
- **新增「🎭 角色库」类目，38 个主流角色**（精选自 awesome-chatgpt-prompts 等）：Linux 终端、JS 控制台、Python 解释器、SQL 终端、Excel 表格、英语口语老师、面试官、旅行向导、广告策划、脱口秀、励志/人生教练、辩手、编剧、小说家、影评人、诗人、说唱、哲学家、数学老师、网络安全专家、招聘官、健身教练、营养师、厨师、房产顾问、法律信息助手、财务分析师、产品经理、项目经理、UX/UI 顾问、简历/求职信、学习计划、演讲稿、社媒经理、创业点子等
- 顶部标题旁新增**版本徽章**；浏览器标签也带版本号
- 搜索框关闭浏览器自动填充，避免历史记录干扰
- 导入功能支持「角色库」自动识别
- 场景模板总数提升至 **88**

### 修复 / Fixed
- 修复导入角色类内容时 DEFROLE 缺键导致的报错

## [0.3 beta] — 2026-06-27
### 新增 / Added
- **我的模板（本地保存 / 收藏）**：一键保存当前类型+字段+层级到浏览器 localStorage，可载入/删除，刷新与重开均不丢失
- **导出 promptfoo**：把当前 prompt 导出为 `promptfooconfig.yaml`，自动把 `{变量}` 转为 `{{变量}}`、生成 providers 与 assert 测试骨架，可直接做回归测试
- **导出 DSPy**：导出 `dspy_task.py`，含 Signature（InputField/OutputField）、ChainOfThought 与完整指令引用

## [0.2 beta] — 2026-06-27
### 新增 / Added
- 新增「提示工程」类目，含 8 个框架级模板：系统提示词构建器、LangGPT 结构化角色、RAG 检索增强、思维链 CoT、Few-shot、DSPy 签名、promptfoo 评估、提示词优化器
- 通用大模型新增中文经典模板：周报生成、小红书文案
- 导入功能支持「提示工程」类目的自动识别
- 模板总数提升至 48+

### 参考来源 / References
awesome-prompt(NeekChaw) · awesome-chatgpt-prompts-zh-CN · LangGPT · DSPy · promptfoo · prompt-optimizer（「系统提示词构建器」为基于通用结构的原创编写，未取材于任何专有/泄露提示词）

## [0.1 beta] — 2026-06-27
首个公开测试版本。First public beta.
### 新增 / Added
- 单文件静态 HTML 框架，纯前端、本地可用、数据不上传
- 四大目标类目：通用大模型、编程类 Agent、自动化 Agent、绘图/多模态
- 40+ 双语场景模板；中 / 英一键切换
- 三档输出层级：简版 / 标准 / 详尽；各类目使用规范说明
- 导入并定制（启发式拆解）+ 生成优化指令（meta-prompt）
- 变量占位符、场景搜索、复制、下载 .md
