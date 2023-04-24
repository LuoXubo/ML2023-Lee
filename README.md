# ML2023-Lee

Some codes of machine learning from HUNG-YI LEE.

## ChatGPT 原理剖析

- **ChatGPT is not connected to the internet**. 多数 ChatGPT 的答案在网络上都找不到一模一样的句子，甚至有些是**假的**

- ChatGPT 的原理类似**文字接龙**

- 在多种语言上**预训练**后，只要教某个语言的某个任务，会自动学会其他语言的**同样任务**

- 对 ChatGPT 提出需求**Prompting**

## 机器学习基本概念

机器学习 = 机器自动找函数

找出函数的三步骤

- 选出候选函数额集合（Model: CNN, Transformer, Decision Tree, etc.）
- 设定评价函数好坏的标准（Loss: Supervised learning, Semi-supervised learning, RL, etc.）
- 找到最好的函数 $f^* = arg min_{f \in H} L(f)$
