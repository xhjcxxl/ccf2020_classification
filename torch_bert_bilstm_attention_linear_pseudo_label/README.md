# 说明

这个代码是完全重写了dataset，参照着其他代码自己来实现的，很清楚里面的每一个步骤，使得对dataset.dataloader更加深刻

另外，这个代码里面添加了shuffle，所以训练起来更好，更加稳定，之前的代码没有加打乱，训练起来效果非常不好

结构 bert+BiLSTM+attention+两个线性层

使用之前训练出来的伪标签进行进一步训练

