# 我怎么用 AI 一周做了 39 个开源项目

不是教程，是复盘。

---

## 为什么要做这件事

准备简历的时候发现 GitHub 上项目太少。不是没有，是不够多、不够系统。

决定：用 AI 帮忙，一周内做一套完整的开源项目。

目标：至少 20 个。最后做了 39 个。

## 用的工具

- **Kimi Code** — 主力。写代码、写 README、写文档都用它
- **GitHub CLI** — 批量创建仓库、管理
- **Node.js** — CLI 工具开发
- **Markdown** — 所有内容都是 Markdown

没有用 Cursor（太贵），没有用 Copilot（不好用）。

## 怎么干的

### 第一天：核心工具

做了 4 个 CLI 工具：

```bash
npx vibe-check        # 检查项目 AI 友好度
npx commit-ai         # AI 写 commit message
npx agent-trace       # 追踪 AI Agent 花费
npx git-format        # 格式化 commit
```

**经验**：CLI 工具最容易拿 star，因为用户可以 `npx` 一键体验。

### 第二天：知识库

做了 5 个 awesome 合集：
- awesome-ai-rules — 20 个 AI 编程规则
- awesome-mcp-servers — 9 个 MCP 服务器配置
- awesome-interview-skills — 14 个面试技能
- awesome-skills — 12 个科研技能
- awesome-ai-agents — 12 个 AI Agent 技能

**经验**：awesome list 是最容易做的项目，但也是最容易被忽略的。关键是要有独特的内容，不要只是抄别人的列表。

### 第三天：学习资源

做了 6 个学习资源项目：
- build-your-own-x-cn — 从零构建技术（中文版）
- leetcode-patterns-cn — 算法模式（中文版）
- system-design-interview — 系统设计面试
- awesome-developer-roadmap — 职业路线图
- open-source-llm-guide — 本地部署 LLM
- ai-agent-architectures — AI Agent 架构

**经验**：中文内容有市场，因为很多优质资源只有英文版。

### 第四天：创意工具

做了 7 个视频/创意相关项目：
- awesome-video-prompts — 200+ 视频生成 prompt
- awesome-video-to-text — 视频转文字
- awesome-video-creation — 视频制作
- awesome-video-skills — 视频剪辑
- awesome-creative-skills — 创意技能
- awesome-writing-skills — 写作技能
- awesome-prompts — 285+ AI prompt

**经验**：prompt 合集很受欢迎，但竞争也大。要有自己的分类和整理。

### 第五天：开发者工具

做了 8 个开发者资源项目：
- awesome-dev-tools — 50+ 开发工具
- awesome-devops-skills — DevOps 技能
- awesome-security-skills — 安全技能
- awesome-startup-skills — 创业技能
- github-stars-analysis — Star 趋势分析
- awesome-chinese-developer-tools — 中文开发工具
- awesome-research-figures — 科研绘图
- awesome-interview-skills — 面试技能

### 第六天：收尾

做了剩下的项目：
- my-dotfiles — 我的开发环境配置
- blog — 这个博客
- guizhou-exam-papers — 贵州高考真题（给学生用的）

### 第七天：完善

- 给所有项目加了中英双语 README
- 给核心项目加了 CONTRIBUTING.md
- 给所有项目加了 MIT License
- 写了这篇文章

## 踩过的坑

1. **AI 生成的 README 要人工改**。AI 写的太完美，读起来像营销文案。要改成说人话。
2. **不要一开始就追求完美**。先做出来，再慢慢改。
3. **CLI 工具比 awesome list 更有价值**。因为 CLI 工具是原创的，awesome list 是整理的。
4. **中文内容有优势**。很多优质资源只有英文版，做中文版有市场。
5. **不要做太多相似的项目**。我做了太多 awesome list，有点重复。

## 实际效果

- GitHub star：总共大概 100+（每个项目平均 3-5 个）
- npm 下载：git-format 最高，479/月
- 简历：项目数量够了，但质量还需要提升
- 面试：还没面试，不知道效果

## 我的真实想法

一周做 39 个项目，听起来很厉害，但实际质量参差不齐。有些项目确实有用（vibe-check、agent-trace），有些项目只是凑数（大部分 awesome list）。

如果重来，我会只做 10 个项目，但每个都做到极致。

**数量不重要，质量才重要。** 但如果你和我一样，需要快速建立 GitHub 存在感，这个方法确实有效。

---

*写于 2026 年 8 月。不保证以后还适用。*
