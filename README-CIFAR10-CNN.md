# DL-Projects
CIFAR 10

使用网络：
net.png

3 个卷积层  
1st in_ch=3  ou_ch=32 k_s=5*5,stride=1,padding=2,
2nd in_ch32, ou_ch=32,k_s=5*5,stride=1,padding=2, 
3rd in_ch32, ou_ch=64,k_s=5*5,stride=1,padding=2,

3 个最大池化层  kernel_size 2*2
2 个全连接层  1st 1024-->64  2nd 64-->10
1 个激活函数 - softmax

epochs = 150

可视化:
logs - 150 epochs
terminal - tensorboard --logdir=./logs

效果:
acc for training:  0.122-->0.697
acc for testing: 0.164-->0.696

数据集：
可自动下载

