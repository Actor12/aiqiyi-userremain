#2021爱奇艺用户存留预测

竞赛网址：  
官方：http://challenge.ai.iqiyi.com/detail?raceId=61600f6cef1b65639cd5eaa6  
datafountain: https://www.datafountain.cn/competitions/551  
博客比赛总结：https://blog.csdn.net/weixin_45526335/article/details/122732559#comments_21278048

最终成绩：A榜11/991  B榜19/991

本次比赛主要采用了lightGBM和自建的gru两种模型训练，结果做投票融合；

提分点：特征衍生、nullimportance特征筛选法、调整网络参数和结构、finetuning、交叉验证、伪标签、vote融合。

