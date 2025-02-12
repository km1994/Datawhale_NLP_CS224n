# CS224n 组队学习 （上） 任务大纲 

## 项目动机

该项目主要为了 给那些**想入门NLP却没找到比较好的入门教程的 New NLPer** 提供 一个 学习视频索引、课程笔记分享、课后问题解答 的平台 ，以帮助他们入门 NLP。每个人均可将自己的笔记、感悟、作业。

## 项目介绍

自然语言处理( NLP )是信息时代最重要的技术之一，也是人工智能的重要组成部分。NLP的应用无处不在，因为人们几乎用语言交流一切：网络搜索、广告、电子邮件、客户服务、语言翻译、医疗报告等。近年来，深度学习方法在许多不同的NLP任务中获得了非常高的性能，使用了不需要传统的、任务特定的特征工程的单个端到端神经模型。在本课程中，学生将全面了解NLP深度学习的前沿研究。通过讲座、作业和最终项目，学生将学习设计、实现和理解他们自己的神经网络模型的必要技能。

## 基本信息

- 学习名称：NLP组队学习
- 学习周期：16天
- 学习形式：视频学习+实践
- 人群定位：具备一定编程基础，有学习和梳理自然语言处理算法的需求
- 难度等级：中
- 先修组队学习：无
- 后续推荐组队学习：CS224n (中)
- 编程语言：不限

## 课程介绍

- Task 1: Introduction and Word Vectors （3天）
  - 理论部分
    - 介绍NLP研究的对象
    - 如何表示单词的含义
    - Word2Vec方法的基本原理
  - 视频教程
    - [youtube video](https://www.youtube.com/watch?v=8rXD5-xhemo)
    - [bilibili video](https://www.bilibili.com/video/BV1s4411N7fC?p=1) 
  - 资源
    - [slides](Lecture/Lecture1/slides/) 
    - [official notes](Lecture/Lecture1/official_notes/)
  - 优秀作业
    - 鑫海：[https://blog.csdn.net/Rock_y/article/details/106940001](https://blog.csdn.net/Rock_y/article/details/106940001)
    - 芙蕖：[https://blog.csdn.net/weixin_42691585/article/details/106928998](https://blog.csdn.net/weixin_42691585/article/details/106928998)
    - lyman：[https://www.jianshu.com/p/8594cf51bf89](https://www.jianshu.com/p/8594cf51bf89)
    - Bill：[https://billmazengou.github.io/2020/06/23/NLP1-Word-to-Vectors/](https://billmazengou.github.io/2020/06/23/NLP1-Word-to-Vectors/)
    - 浩浩雷：[Lecture/Lecture1/reference/](Lecture/Lecture1/reference/) 
  - [问题解答区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/1)
  
  
- Task 2: Word Vectors and Word Senses （3天）
  - 理论部分
    - 回顾 Word2Vec模型
    - 介绍 count based global matrix factorization 方法
    - 介绍 GloVe 模型
  - 视频教程
    - [youtube video](https://www.youtube.com/watch?v=kEMJRjEdNzM&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=2)
    - [bilibili video](https://www.bilibili.com/video/BV1s4411N7fC?p=2)
  - 资源
    - [slides](Lecture/Lecture2/slides/) 
    - [official notes](Lecture/Lecture2/official_notes/)
  - 优秀作业
    - 鑫海：[https://blog.csdn.net/Rock_y/article/details/106986586](https://blog.csdn.net/Rock_y/article/details/106986586)
    - 芙蕖：[https://blog.csdn.net/weixin_42691585/article/details/106988635](https://blog.csdn.net/weixin_42691585/article/details/106988635)
    - lyman：[https://blog.csdn.net/wuzhongqiang/article/details/106979179](https://blog.csdn.net/wuzhongqiang/article/details/106979179)
    - Raymond：[CS224N Word Vectors 2 and Word Senses](Lecture/Lecture2/reference/) 
  - [问题解答区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/2)
  
- Task 3: Subword Models （3天）
  - 理论部分
    - 回顾 word2vec 和 glove，并介绍其所存在问题
    - 介绍 n-gram 思想
    - 介绍 FastText 模型
  - 视频教程
    - [youtube video](https://www.youtube.com/watch?v=9oTHFx0Gg3Q&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=12)
    - [bilibili video](https://www.bilibili.com/video/BV1s4411N7fC?p=12)
  - 资源
    - [slides](Lecture/Lecture12/slides/) 
    - [official notes](Lecture/Lecture12/official_notes/) 
  - 优秀作业
    - 芙蕖：[https://blog.csdn.net/weixin_42691585/article/details/107009195](https://blog.csdn.net/weixin_42691585/article/details/107009195)
    -  12-Subword Models 读书笔记：[ 12-Subword Models 读书笔记](Lecture/Lecture12/reference/) 
  - [问题解答区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/12)

- Task 4: Contextual Word Embeddings  （3天）
  - 理论部分
    - 回顾 Word2Vec, GloVe, fastText 模型
    - 介绍contextual word representation
    - 介绍 ELMO，GPT与BERT模型
  - 视频教程
    - [youtube video](https://www.youtube.com/watch?v=kEMJRjEdNzM&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z&index=13)
    - [bilibili video](https://www.bilibili.com/video/BV1s4411N7fC?p=13)
  - 资源
    - [slides](Lecture/Lecture13/slides/) 
    - [official notes](Lecture/Lecture14/official_notes/)
  - 优秀作业
    - 荒：[https://chenk.tech/posts/f2fb8471.html](https://chenk.tech/posts/f2fb8471.html)
    - 江湖散人：[浅谈ELMO，GPT，BERT模型](Lecture/Lecture3/reference/) 
  - [问题解答区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/13)

- Task 5: Homework （3天）（组队完成）

可以从以下作业四选一：

1. 英文词向量的探索
   - 练习任务
     - 完成 CS224n 配套作业
   - [作业链接](Assignments/official/homework1/en/)
   - [讨论区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/21)
   
2. 中文词向量的探索
   - 练习任务
     - 特征词转化为 One-hot 矩阵
     - 特征词转化为 tdidf 矩阵
     - 利用 word2vec 进行 词向量训练
     - word2vec 简单应用
     - 利用 one-hot 、TF-idf、word2vec 构建句向量，然后 采用 朴素贝叶斯、条件随机场做分类
   - [作业链接](Assignments/official/homework1/zh/)
   - [讨论区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/21) 
  
3. FastText 探索
  - 练习任务
     - FastText 词向量训练
     - FastText 做分类
  - [作业链接](Assignments/official/homework1/FastText/)
  - [讨论区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/21) 

4. Bert 探索
  - 练习任务
     - Bert 做分类
  - [作业链接](Assignments/official/homework1/Bert/)
  - [讨论区](https://github.com/km1994/Datawhale_NLP_CS224n/issues/21) 

- 优秀作业
  - winter：
    - [fastText_classification](tps://github.com/exuding/NLP/blob/master/fastText_classification.ipynb)
    - [bert_classification](https://github.com/exuding/NLP/blob/master/bert_classification.ipynb)
  - 荒：[NLP项目Pipeline](https://chenk.tech/posts/aefe1ee4.html)
  - 北尘南风：[https://github.com/hu-minghao/my_program/blob/master/NLP-task5%2Bbig%2Bhomework.ipynb](https://github.com/hu-minghao/my_program/blob/master/NLP-task5%2Bbig%2Bhomework.ipynb)

## 致谢

1. [CS224n 课程主页](http://web.stanford.edu/class/cs224n/index.html)
2. [CS224n 中英视频](https://www.bilibili.com/video/BV1s4411N7fC)
  