# bikes-prediction
numpy,python,BP推导

使用numpy建立一个包含一层隐藏层的前馈神经网络，对共享单车的使用量进行预测
主要体现了神经网络的向前传播和反向传播的过程，梯度下降的具体实现
了解神经网络的内部实现有利于发现和解决构建神经网络过程中出现的问题，如梯度消失是指训练到某一个时刻时权重改变值接近0，训练速度十分缓慢，需要注意使用多层的sigmoid激活函数，会使前面的层误差项越来越小，导致训练困难。
