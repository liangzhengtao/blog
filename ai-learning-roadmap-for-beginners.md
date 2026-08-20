# AI 学习路线（给非科班的人）

我本科是人工智能专业，但很多东西也是自学的。这份路线图是我实际走过的路，不是 AI 生成的完美计划。

---

## 第一步：Python（1-2 周）

不用精通，会写脚本就行。

**要学的：**
- 变量、循环、函数、类
- 列表推导式
- 文件操作
- pip 安装包

**不用学的：**
- 装饰器、元类（以后再说）
- 网络编程（AI 用不到）

**练习：**
- 写一个文件整理脚本
- 写一个命令行计算器

**资源：**
- [Python 官方教程](https://docs.python.org/3/tutorial/) — 最权威
- [Python 100 Days](https://github.com/jackfrued/Python-100-Days) — 中文，够用

## 第二步：机器学习基础（2-4 周）

不用懂数学推导，会调 API 就行。

**要学的：**
- scikit-learn 基本用法
- 线性回归、逻辑回归、决策树
- 训练集/测试集划分
- 过拟合/欠拟合

**不用学的：**
- 数学推导（以后再补）
- 手写算法（用库就行）

**练习：**
- 用 scikit-learn 做一个房价预测
- 用 scikit-learn 做一个鸢尾花分类

**资源：**
- [scikit-learn 官方文档](https://scikit-learn.org/stable/) — 最实用
- [吴恩达机器学习课程](https://www.coursera.org/learn/machine-learning) — 经典，但有点老

## 第三步：深度学习（4-8 周）

PyTorch 比 TensorFlow 好用，直接学 PyTorch。

**要学的：**
- PyTorch 基本用法
- CNN（图像）
- RNN/LSTM（文本）
- 训练技巧（学习率、batch size、正则化）

**不用学的：**
- 手写反向传播（PyTorch 自动做）
- 太复杂的模型架构（以后再说）

**练习：**
- 用 CNN 做一个 MNIST 手写数字识别
- 用 LSTM 做一个文本生成

**资源：**
- [PyTorch 官方教程](https://pytorch.org/tutorials/) — 最实用
- [李沐深度学习课程](https://courses.d2l.ai/) — 中文，讲得好

## 第四步：大模型（8-12 周）

这是现在最火的方向，也是最难的。

**要学的：**
- Transformer 架构（不用懂数学，理解原理就行）
- Hugging Face 用法
- 微调（LoRA、QLoRA）
- RAG（检索增强生成）

**不用学的：**
- 从零训练大模型（没钱、没卡）
- 太底层的实现（用库就行）

**练习：**
- 用 Hugging Face 做一个文本分类
- 用 LoRA 微调一个模型
- 用 LangChain 做一个 RAG 应用

**资源：**
- [Hugging Face 文档](https://huggingface.co/docs) — 最实用
- [LangChain 文档](https://docs.langchain.com/) — RAG 必学
- [李宏毅深度学习课程](https://speech.ee.ntu.edu.tw/~hylee/ml/2023-spring.php) — 中文，讲得深

## 第五步：做项目（持续）

学了这么多，不做项目等于白学。

**推荐项目：**
- 用 AI 做一个聊天机器人
- 用 AI 做一个代码生成器
- 用 AI 做一个文档问答系统
- 用 AI 做一个图像识别应用

**我的项目：**
- [vibe-check](https://github.com/liangzhengtao/vibe-check) — 检查项目 AI 友好度
- [agent-trace](https://github.com/liangzhengtao/agent-trace) — 追踪 AI Agent 花费
- [awesome-ai-rules](https://github.com/liangzhengtao/awesome-ai-rules) — AI 编程规则

## 我的真实想法

学 AI 不难，但需要时间。不要指望一周就能学会，也不要指望看完教程就能做项目。

**最好的学习方法是：边学边做。**

看一个教程，马上动手做一个项目。遇到问题再回去看教程。这样学得最快。

**不要害怕数学。** 很多 AI 工具已经帮你处理了数学细节，你只需要会调 API 就行。

**不要害怕英文。** 最新的技术文档都是英文的，但你可以用翻译工具。重要的是理解概念，不是背单词。

---

*写于 2026 年 8 月。基于我的实际学习经历，不是 AI 生成的完美计划。*
