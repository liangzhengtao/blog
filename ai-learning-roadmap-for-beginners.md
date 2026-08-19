# 小白从零开始学 AI 路线合集

> 不需要数学天才，不需要顶级硬件，只需要一台电脑和一颗想学的心。

---

## 前言

很多人觉得 AI 很难，需要高深的数学基础、昂贵的硬件设备、顶尖的学历背景。

**这些都是误解。**

我是一个普通本科生，从零开始学 AI，现在能做出 39 个开源项目。这份路线图是我亲身经历的总结，适合所有想入门 AI 的人。

## 第一阶段：基础准备（1-2 周）

### 1.1 Python 基础

**必须掌握：**
- 变量、数据类型、控制流
- 函数、类、模块
- 列表推导式、生成器
- 文件操作、异常处理

**推荐资源：**
- [Python 官方教程](https://docs.python.org/3/tutorial/)
- [Python 100 Days](https://github.com/jackfrued/Python-100-Days)（中文）

**练习项目：**
- 写一个简单的计算器
- 写一个文件整理脚本
- 写一个命令行待办事项应用

### 1.2 数学基础

**必须掌握：**
- 线性代数：向量、矩阵、特征值
- 微积分：导数、偏导数、梯度
- 概率统计：概率分布、贝叶斯定理

**推荐资源：**
- [3Blue1Brown 线性代数](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
- [Khan Academy](https://www.khanacademy.org/)

**不要害怕数学，边学边用，不需要精通。**

### 1.3 Git 和 GitHub

**必须掌握：**
- git init, add, commit, push, pull
- 分支管理
- Pull Request 流程

**推荐资源：**
- [Git 官方教程](https://git-scm.com/book/zh/v2)
- [GitHub Skills](https://skills.github.com/)

## 第二阶段：机器学习基础（2-4 周）

### 2.1 机器学习概念

**必须掌握：**
- 监督学习 vs 无监督学习
- 回归、分类、聚类
- 训练集、验证集、测试集
- 过拟合、欠拟合

**推荐资源：**
- [吴恩达机器学习课程](https://www.coursera.org/learn/machine-learning)（Coursera）
- [StatQuest](https://www.youtube.com/c/joshstarmer)（YouTube）

### 2.2 Scikit-learn 实战

**必须掌握：**
- 数据预标准化
- 线性回归、逻辑回归
- 决策树、随机森林
- 模型评估指标

**练习项目：**
- 房价预测
- 鸢尾花分类
- 手写数字识别

### 2.3 数据处理

**必须掌握：**
- Pandas：数据清洗、分析
- NumPy：数值计算
- Matplotlib/Seaborn：数据可视化

**推荐资源：**
- [Pandas 官方教程](https://pandas.pydata.org/docs/getting_started/index.html)
- [Kaggle Learn](https://www.kaggle.com/learn)

## 第三阶段：深度学习（4-8 周）

### 3.1 神经网络基础

**必须掌握：**
- 神经元、激活函数
- 前向传播、反向传播
- 损失函数、优化器
- 卷积神经网络（CNN）
- 循环神经网络（RNN）

**推荐资源：**
- [吴恩达深度学习课程](https://www.deeplearning.ai/)
- [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

### 3.2 PyTorch 实战

**必须掌握：**
- Tensor 操作
- 自动求导
- 模型定义和训练
- 数据加载

**练习项目：**
- MNIST 手写数字识别
- CIFAR-10 图像分类
- 文本情感分析

### 3.3 计算机视觉

**必须掌握：**
- 图像分类
- 目标检测
- 图像分割
- 迁移学习

**推荐资源：**
- [CS231n](http://cs231n.stanford.edu/)
- [PyTorch 官方教程](https://pytorch.org/tutorials/)

### 3.4 自然语言处理

**必须掌握：**
- 词嵌入（Word2Vec, GloVe）
- RNN、LSTM、GRU
- Transformer 架构
- BERT、GPT 原理

**推荐资源：**
- [CS224n](http://web.stanford.edu/class/cs224n/)
- [Hugging Face Course](https://huggingface.co/course)

## 第四阶段：大语言模型（4-8 周）

### 4.1 LLM 基础

**必须掌握：**
- Transformer 架构详解
- 预训练和微调
- Prompt Engineering
- RAG（检索增强生成）

**推荐资源：**
- [Andrej Karpathy 的视频](https://www.youtube.com/@AndrejKarpathy)
- [LangChain 文档](https://docs.langchain.com/)

### 4.2 实战项目

**必须做：**
- 用 LangChain 搭建 RAG 系统
- 微调一个小型 LLM
- 构建一个 AI Agent
- 部署一个 LLM 应用

**推荐资源：**
- [LLM Course](https://github.com/mlabonne/llm-course)
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM)

### 4.3 MCP 协议

**必须掌握：**
- MCP（Model Context Protocol）概念
- MCP Server 开发
- 工具调用（Tool Use）

**推荐资源：**
- [MCP 官方文档](https://modelcontextprotocol.io/)
- [awesome-mcp-servers](https://github.com/liangzhengtao/awesome-mcp-servers)

## 第五阶段：专业方向（持续学习）

### 5.1 选择你的方向

| 方向 | 技能要求 | 就业前景 |
|------|---------|---------|
| 计算机视觉 | CNN、目标检测、图像处理 | ⭐⭐⭐⭐⭐ |
| 自然语言处理 | Transformer、LLM、NLP | ⭐⭐⭐⭐⭐ |
| 强化学习 | RL、游戏AI、机器人 | ⭐⭐⭐⭐ |
| AI 安全 | 对齐、红队测试、评估 | ⭐⭐⭐⭐⭐ |
| AI Agent | 工具调用、多Agent协作 | ⭐⭐⭐⭐⭐ |

### 5.2 深入学习

**推荐资源：**
- [arXiv](https://arxiv.org/) - 最新论文
- [Papers With Code](https://paperswithcode.com/) - 论文+代码
- [Hugging Face](https://huggingface.co/) - 模型和数据集

## 学习建议

### 1. 动手实践 > 看视频

看 10 小时视频不如写 1 小时代码。每学一个概念，立刻用代码实现。

### 2. 不要追求完美

先跑起来，再优化。一个能运行的 80 分代码比一个跑不起来的 100 分代码有用得多。

### 3. 加入社区

- GitHub：参与开源项目
- Discord：加入 AI 社区
- 知乎/掘金：分享学习心得

### 4. 坚持写博客

把学到的东西写出来，是最好的学习方式。同时也能建立你的个人品牌。

### 5. 不要害怕英文

大部分优质资源都是英文的。用 AI 翻译，慢慢就会习惯。

## 学习时间表

| 阶段 | 时间 | 目标 |
|------|------|------|
| 基础准备 | 1-2 周 | Python + 数学 + Git |
| 机器学习 | 2-4 周 | Scikit-learn + 数据处理 |
| 深度学习 | 4-8 周 | PyTorch + CV/NLP |
| 大语言模型 | 4-8 周 | LLM + RAG + Agent |
| 专业方向 | 持续 | 深入一个方向 |

**总计：3-6 个月可以入门，1 年可以独立做项目。**

## 推荐项目练手

| 难度 | 项目 | 技能 |
|------|------|------|
| ⭐ | MNIST 手写数字识别 | CNN 基础 |
| ⭐⭐ | 图像分类器 | 迁移学习 |
| ⭐⭐ | 文本情感分析 | NLP 基础 |
| ⭐⭐⭐ | RAG 问答系统 | LLM + 向量数据库 |
| ⭐⭐⭐ | AI Agent | 工具调用 + 多步推理 |
| ⭐⭐⭐⭐ | 多模态模型 | CV + NLP 融合 |

## 相关资源

- [awesome-ai-rules](https://github.com/liangzhengtao/awesome-ai-rules) — AI 编程规则
- [awesome-skills](https://github.com/liangzhengtao/awesome-skills) — 科研技能
- [awesome-interview-skills](https://github.com/liangzhengtao/awesome-interview-skills) — 面试准备
- [build-your-own-x-cn](https://github.com/liangzhengtao/build-your-own-x-cn) — 从零构建技术
- [system-design-interview](https://github.com/liangzhengtao/system-design-interview) — 系统设计

---

**这条路不容易，但绝对值得。**

**加油！** 🚀
