# Machine-Learning-Workshop
### Week 1: 機器學習基石Overview `泰瑋` 
> 1. https://hackmd.io/6YkQWaLARNWOMQmMxEnLHg

### Week 2: Linear Regression `宛誼` (6/21)
- 機器學習基石
> 1. https://www.youtube.com/watch?v=qGzjYrLV-4Y&index=34&list=PLXVfgk9fNX2I7tB6oIINGBmW50rrmFTqf
> 2. https://www.youtube.com/watch?v=2LfdSCdcg1g&index=35&list=PLXVfgk9fNX2I7tB6oIINGBmW50rrmFTqf
> 3. https://www.youtube.com/watch?v=lj2jK1FSwgo&index=36&list=PLXVfgk9fNX2I7tB6oIINGBmW50rrmFTqf
> 4. https://www.youtube.com/watch?v=tF1HTirYbtc&index=37&list=PLXVfgk9fNX2I7tB6oIINGBmW50rrmFTqf

- Scikit-learn
> http://scikit-learn.org/stable/modules/linear_model.html#linear-model
> 1. Ordinary Least Squares
> 2. Ridge Regression
> 3. Lasso

- 投影片＆Ｃode
> 1. [Link to PPT](https://github.com/KPIxLILU/Machine-Learning-Workshop/blob/master/Week2.Linear%20Regression.pdf)
> 2. [Link to Demo Code](https://github.com/mayritaspring/Data-Science/blob/master/Linear%20Regression/Linear%20Regression.ipynb)([Data](https://archive.ics.uci.edu/ml/datasets/Las+Vegas+Strip))
> 3. [Link to Demo Code_fran's review](https://github.com/sunchigg/JrML/blob/master/Linear_Regression_DEMO_reivew.ipynb)

### Week 3: Logistic Regression `Rex`(6/25)
> 1. [Link to PDF](https://github.com/KPIxLILU/Machine-Learning-Workshop/blob/master/Week3.Logistic%20Regression.pdf)
> 2. [Link to Demo Code](https://github.com/sunchigg/JrML/blob/master/Rex/Logistic.ipynb)([Data](https://github.com/sunchigg/JrML/blob/master/Rex/rex_22.csv))


### Week 4: Classification And Regression Tree (CART) `信賢`(7/2)
-[[資料分析&機器學習] 第3.5講 : 決策樹(Decision Tree)以及隨機森林(Random Forest)介紹)](https://medium.com/@yehjames/%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90-%E6%A9%9F%E5%99%A8%E5%AD%B8%E7%BF%92-%E7%AC%AC3-5%E8%AC%9B-%E6%B1%BA%E7%AD%96%E6%A8%B9-decision-tree-%E4%BB%A5%E5%8F%8A%E9%9A%A8%E6%A9%9F%E6%A3%AE%E6%9E%97-random-forest-%E4%BB%8B%E7%B4%B9-7079b0ddfbda)
- 機器學習技法
> 1.[Decision Tree Hypothesis](https://www.youtube.com/watch?v=dAqPpAXnMJ4&index=34&list=PLXVfgk9fNX2IQOYPmqjqWsNUFl2kpk1U2)

> 2.[Decision Tree Algorithm](https://www.youtube.com/watch?v=s9Um2O7N7YM&index=35&list=PLXVfgk9fNX2IQOYPmqjqWsNUFl2kpk1U2)

> 3.[Decision Tree Heuristics in C&RT](https://www.youtube.com/watch?v=uvGC_Y0EYiA&list=PLXVfgk9fNX2IQOYPmqjqWsNUFl2kpk1U2&index=36)

> 4.[Decision Tree in Action ](https://www.youtube.com/watch?v=ryWTrPPbqcg&index=37&list=PLXVfgk9fNX2IQOYPmqjqWsNUFl2kpk1U2)

-[決策樹如何剪枝參考](https://blog.csdn.net/jerry81333/article/details/53182193)

- 投影片＆Ｃode
> 1. [Link to PPT](https://github.com/KPIxLILU/Machine-Learning-Workshop/blob/master/Week4.DecisionTree(CART).pdf)
> 2. [Link to code](https://github.com/erik1110/Machine-Learning/blob/master/Titantic-Decision%20Tree2.ipynb)
> 3. [Link to Demo Code_fran's review](https://github.com/sunchigg/JrML/blob/master/CART_DEMO_review_Titanic.ipynb)

### Week 5: Random Forest & Ensemble `fran&昱睿`(7/12)

lecture:https://www.youtube.com/watch?v=XsC9byQkUH8&feature=youtu.be
PDF:[pdf](http://speech.ee.ntu.edu.tw/~tlkagk/courses/ML_2016/Lecture/Ensemble%20(v6).pdf)

- Ensemble: Bagging and Boosting
- Two families of ensemble methods are usually distinguished:
> 1. In averaging methods, the driving principle is to build several estimators independently and then to average their predictions. On average, the combined estimator is usually better than any of the single base estimator because its variance is reduced.
> Examples: Bagging methods, Forests of randomized trees

> 2. By contrast, in boosting methods, base estimators are built sequentially and one tries to reduce the bias of the combined estimator. The motivation is to combine several weak models to produce a powerful ensemble.
> Examples: AdaBoost, Gradient Tree Boosting

### Week 6: Gradient Boosting Machine (GBM) & eXtreme Gradient Boosting (XGBoost) `璧羽&芳妤` (7/16)
lecture_GBDT https://www.youtube.com/watch?v=aX6ZiIWLjdk&index=42&list=PLXVfgk9fNX2IQOYPmqjqWsNUFl2kpk1U2
> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3885826/
前半段介紹ＧＢ
>https://blog.csdn.net/u011094454/article/details/78948989
先看完這三篇
>https://hk.saowen.com/a/e997166f37dc6022138607838ec7c83ba6f89b2d5d11fe248e0925968b410f33 
>https://hk.saowen.com/a/7214d5cc99d98d81736f766d77cd568dae07aadf85f027a1e5acdd57839e7f91
>http://www.52cs.org/?p=429
最後再看這篇
>https://medium.com/@cyeninesky3/xgboost-a-scalable-tree-boosting-system-%E8%AB%96%E6%96%87%E7%AD%86%E8%A8%98%E8%88%87%E5%AF%A6%E4%BD%9C-2b3291e0d1fe
>論文原文：   https://arxiv.org/pdf/1603.02754v1.pdf
>作者ＰＰＴ：  https://homes.cs.washington.edu/~tqchen/pdf/BoostedTree.pdf

### Week 7: Neural Networks `Jesse` (7/25)
