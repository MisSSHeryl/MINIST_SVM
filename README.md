# MINIST_SVM

使用MINIST数据集train.csv 来进行训练，train.csv中80％的数据用于训练，20％的数据用于验证，使用test.csv进行测试。

SVM:首先使用线性核默认参数来训练MINIST数据集，得到准确率之后，又使用了高斯核默认参数进行训练，得到了准确率，然后对其和线性核

    一起做了比较，然后使用网格搜索来查找高斯核函数的最佳参数。然后对比其和线性核和高斯核默认参数的准确率。
    
    详情见代码MINIST_SVM(Linear and rbf).ipynb
    
    使用PCA优化进行特征降维，将特征值的维度降低，在准确率不降低的情况下，训练速度大幅下降
    
    详情见代码MINIST_PCA_SVM.ipynb
    
    


