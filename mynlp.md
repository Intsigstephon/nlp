# 文本分类
1. 本质： 文本相似性度量和计算
2. 常用的方法： TF-IDF, word embedding pooling, textCNN, textRNN, attention network, matchpyramid等深度学习方法；

## bag模型
   所谓的bag of words
   简称词袋模型， 相当于把组成一个句子的所有词丢到一个袋子里面，那么其实是不考虑词语的先后顺序的。
   
   问题种类：
   1） 短文本的分类
      比如对于商品评论， 判断其感性色彩，是正向评价还是反向评价（2分类）， 
      或者依据满意度可以分为多类，比如非常满意、满意、还可以、不满意、非常不满意（5分类）
      
   词袋模型将每个单词看做孤立的， 把句子看做是由无序的单词组成的。 本身具有非常大的局限性
   
   词袋模型的变种包括如下几种：
   * BOW: 
      ![bag of words](https://github.com/Intsigstephon/nlp/raw/master/img/BOW.png)
   * CBOW
      ![cbow model](https://github.com/Intsigstephon/nlp/raw/master/img/CBOW.png)
   * deep CBOW
      ![deep_CBOW model](https://github.com/Intsigstephon/nlp/raw/master/img/deep_CBOW.png)
