# Titanic-Survival-Analysis-and-Mining
## 泰坦尼克号事故乘客幸存率数据分析,可视化及决策树模型

### 本项目的基本框架：
- 定义问题
- 收集数据
- 数据清洗
- 探索性数据分析
- 使用决策树算法拟合模型
- 评价模型的性能

## 1.定义问题
1. 背景知识：1912年4月15号英国皇家邮轮泰坦尼克号与冰山相撞沉没。当时船上有1316名乘客和892名船员共计2208人，事故发生后幸存718人，约2/3的人在海难中丧生。按性别划分，男性1738人，女性470人；其中男性存活374人，女性存活344人。更详尽的人员资料请见下面的数据探索部分。

2. 我们感兴趣的问题：
  - 是否有明显的因素决定乘客是否存活？幸存与否与性别有没有关系？和年龄的关系呢？舱位等级是否有影响？诸如此类的问题。
  - 能否建立一个模型，能对乘客的存活率作一个相对准确的预测？

## 2.收集数据
Kaggle平台已经备有较为完整的乘客信息文档，并且出于机器学习的目的，Kaggle官方已经将数据分割为训练集和测试集两个文档。该数据集共记录1309名乘客的信息，包括姓名，性别，年龄等重要信息。

## 3.数据清洗
数据的来源多种多样，有的是人工收集的数据，有的是传感器发回的数据。因此数据的质量是无法保证的。例如数据中缺失值，或者年龄为200岁，诸如此类的麻烦都是我们在作数据分析与挖掘之前先处理掉的事务。同时，数据清洗有一个前提，那就是了解这些数据，数据类型怎样？是独立变量还是依赖其他变量？...

## 4. 数据分析
- 探索所有特征与幸存率的相关性
- 针对这种相关性是否在统计学上成立进行**拟合优度检验**
- 使用可视化技术展示以上相关性

## 5.模型拟合(决策树算法)

## 6.评价模型性能
- Accuracy
- Precision\Recall\F1 score

