# wordSeg
主函数为newWordsFind.py
整体思路：
基于PMI和左右信息熵实现中文分词算法，对每天的新闻语料进行分词，不用任何其他的已经存在的分词词库，将满足条件的词语提取出来与已经存在的词库中的词作比较，若是词库中没有，则添加进去。此处将未登录词和新词认为是一样的，没有细分。
