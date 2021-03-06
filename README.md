Named Entity Recognition
=======================
       
&nbsp;&nbsp;&nbsp;&nbsp;这是我的本科毕业设计项目《基于金融领域知识图谱构建的实体识别算法设计》，主要是将中文实体识别技术应用在
金融领域的知识图谱构建的系统上。

 &nbsp;&nbsp;&nbsp;&nbsp;命名实体识别（Named Entity Recognition，简称NER），又称作“专名识别”，是指识别文本中具有特定意义的实体，
主要包括人名、地名、机构名、专有名词等。

 &nbsp;&nbsp;&nbsp;&nbsp;命名实体识别是信息提取、问答系统、句法分析、机器翻译、面向Semantic Web的元数据标注等应用领域的重要基础
工具，在自然语言处理技术走向实用化的过程中占有重要地位。一般来说，命名实体识别的任务就是识别出待处理文本中
三大类（实体类、时间类和数字类）、七小类（人名、机构名、地名、时间、日期、货币和百分比）命名实体。

Project Layout
--------------



Subdirectories:

- src - 代码
- data - 相关数据集
- papers - 相关论文
- files - 相关报告和资源文件


参考资源
------------------

- 隐马尔科夫模型(HMM, Hidden Markov Model) -  http://www.hankcs.com/ml/hidden-markov-model.html， 这是介绍隐马尔科夫模型一个很好的博客，
将HMM讲解的通俗易懂，还用python实现了一遍加深了理解
- 最大熵模型(ME, Maximum Entropy Model) - http://www.hankcs.com/ml/the-logistic-regression-and-the-maximum-entropy-model.html, 这是一个介绍
最大熵模型一个比较好的博客，还有相关实现可以加深理解
- 条件随机场(CRF, Conditional Random Field) - http://www.hankcs.com/ml/conditional-random-field.html, 这是一个介绍条件随机场的一个比较好的博客，
并有CRF++代码实现的分析，可以加深理解
- <<Neural Architectures for Named Entity Recognition(2016.ACL)>> - https://arxiv.org/pdf/1603.01360.pdf, 这是一篇使用LSTM+CRF来进行NER任务，效果不错，而且网络结构也不复杂；另外
还提出了Transition-based Chunking models.
- 《Named Entity Recognition for Chinese Social Media with Jointly Trained Embeddings》阅读笔记，https://zhuanlan.zhihu.com/p/24160574?refer=xitucheng10
- Sequence Tagging with Tensorflow, https://guillaumegenthial.github.io/sequence-tagging-with-tensorflow.html
- 论文<End-to-end Sequence Labeling via Bi-directional LSTM-CNNs-CRF>使用pytorch的简单实现，https://zhuanlan.zhihu.com/p/30791481
- 机器学习性能评估指标:http://charleshm.github.io/2016/03/Model-Performance/