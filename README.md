# M_Stacking
一个简单的demo，实现了stacking，blending，stacking多层网络搜索。

做了一个简单的对比实验，在15个多分类，20个回归任务，30个二分类数据集上，相同条件下对比了该stacking_demo和GreedyEnsemble算法的性能，实验结果大致如下：

![image](https://user-images.githubusercontent.com/26291393/143535718-368ed384-f96a-47f8-8950-e62d8e5b3087.png)

实验结论如下:
二分类任务下stacking效果提升并不明显，多分类任务下强烈建议使用stacking的技术。

注:GreedyEnsemble参考链接:

"""
    References
    ----------
        Caruana, Rich, et al. "Ensemble selection from libraries of models." Proceedings of the twenty-first international conference on Machine learning. 2004.
    """
