# 我如何用 AI 做了 39 个开源项目

> 一周时间，39 个开源项目，全部中英双语，全部免费开源。这不是炫耀，这是一份实操指南。

---

## 背景

我是一个贵州大学人工智能专业的本科生，今年刚考上北京理工大学的硕士。在准备简历和作品集的时候，我发现一个问题：

**GitHub 上的项目太少了。**

不是说没有项目，而是没有足够多、足够系统、能展示我能力的项目。于是我决定：用 AI 帮我，在一周内做出一套完整的开源项目矩阵。

## 目标

1. **数量**：至少 20 个项目（最后做了 39 个）
2. **质量**：每个项目都有完整的 README、社区文件、CI/CD
3. **覆盖**：覆盖开发者、研究者、学生、创作者等多个群体
4. **语言**：全部中英双语
5. **风格**：不像 AI 生成的，要像真人写的

## 工具

- **Kimi Code**：主要的 AI 编程助手
- **GitHub CLI**：仓库管理
- **Node.js**：CLI 工具开发
- **Markdown**：所有内容

## 第一天：核心工具类

第一天我做了 4 个核心工具：

### 1. vibe-check
```bash
npx vibe-check
# Score: 83/100 | Grade: A
```
一个检查项目 AI 友好度的 CLI 工具。5 秒出结果，7 个维度评分。

### 2. commit-ai
```bash
npx commit-ai
# feat(auth): add OAuth2 login flow
```
AI 帮你写 commit message，不需要 API key，纯规则驱动。

### 3. agent-trace
追踪 AI Agent 的轨迹：花了多少钱、烧了多少 Token、工具调用是否正常。

### 4. git-format
格式化 git commit 为 conventional commits 格式。

**经验**：CLI 工具是最容易获得 star 的，因为用户可以 `npx` 一键体验。

## 第二天：AI 知识库

第二天我做了 5 个 awesome 合集：

1. **awesome-ai-rules** — 20 个 AI 编程规则
2. **awesome-mcp-servers** — 9 个 MCP 服务器
3. **awesome-ai-agents** — 12 个 AI Agent 架构模式
4. **awesome-ai-alignment** — 12 个 AI 安全对齐技能
5. **awesome-prompts** — 285+ 个 AI 提示词

**经验**：awesome 合集是最快出成果的，但要保证内容质量，不能只是堆砌。

## 第三天：学习资源类

第三天做了 5 个学习资源项目：

1. **awesome-developer-roadmap** — 10 个职业路线图
2. **build-your-own-x-cn** — 从零构建技术（中文版）
3. **system-design-interview** — 系统设计面试指南
4. **leetcode-patterns-cn** — LeetCode 算法模式
5. **awesome-interview-skills** — 14 个面试准备技能

**经验**：学习资源类项目最容易获得收藏，因为面试是刚需。

## 第四天：创意工具类

第四天做了 6 个创意工具项目：

1. **awesome-video-prompts** — 200+ 视频生成 prompt
2. **awesome-video-skills** — 10 个视频制作技能
3. **awesome-video-creation** — 视频制作全流程
4. **awesome-video-to-text** — 视频转文字
5. **awesome-creative-skills** — 10 个创意设计技能
6. **awesome-writing-skills** — 12 个写作技能

**经验**：视频生成是 2026 年最火的话题，prompt 合集特别受欢迎。

## 第五天：专业领域类

第五天做了 5 个专业领域项目：

1. **awesome-skills** — 12 个科研技能
2. **awesome-research-figures** — 科研绘图技能
3. **awesome-devops-skills** — 12 个 DevOps 技能
4. **awesome-security-skills** — 12 个网络安全技能
5. **awesome-startup-skills** — 12 个创业技能

**经验**：专业领域的项目虽然受众小，但用户粘性高。

## 第六天：个人品牌

第六天做了个人品牌相关的项目：

1. **liangzhengtao** — 个人主页 + 简历
2. **awesome-resume-skills** — 简历制作技能
3. **awesome-portfolio-skills** — 个人网页制作技能
4. **paper-grill** — 论文审稿技能

**经验**：个人主页是必须的，它是你所有项目的入口。

## 第七天：打磨和发布

最后一天做了：

1. 给所有项目添加封面图
2. 修复所有 AI 味词汇
3. 确保所有项目中英双语
4. 运行所有测试
5. 推送到 GitHub

## 成果

| 维度 | 数据 |
|------|------|
| 项目数量 | 39 个 |
| 文件数量 | 500+ 个 |
| 代码行数 | 100,000+ 行 |
| 测试数量 | 130+ 个 |
| 语言 | 中英双语 |
| 覆盖群体 | 开发者、研究者、学生、创作者 |

## 经验总结

### 1. AI 是工具，不是替代品

AI 帮我生成了大量内容，但最终的质量把控在我。每一行代码、每一个 README 我都检查过。

### 2. 一致性比完美更重要

所有项目遵循相同的结构：README + LICENSE + CONTRIBUTING + SECURITY + CODE_OF_CONDUCT + CHANGELOG。这让你的 GitHub 看起来很专业。

### 3. 去 AI 味很重要

AI 生成的内容有明显的"味道"：complete、proven patterns、use 这些词用得太多。我花了不少时间把这些替换成更自然的表达。

### 4. 中英双语是加分项

中文母语者做开源项目，中英双语是基本功。这能让你的项目触达更广的受众。

### 5. 交叉引用形成矩阵

每个项目都链接到其他项目，形成一个网络效应。用户发现一个项目，就会发现所有项目。

## 下一步

- 给热门项目提 PR，展示协作能力
- 写更多技术博客
- 做一个真正有用的 VS Code 插件
- 持续更新现有项目

---

**如果你也想用 AI 做开源项目，希望这篇文章对你有帮助。**

**GitHub**: https://github.com/liangzhengtao
