# 文件夹的数字代表对应任务
2号任务中的五个文件分别代表对应改动与优化
  1是直接把1号任务的模型照搬过来      
  1.1将tanh函数改为了relu      
  1.2添加了L2正则化      
  1.3将三层网络砍为双层     
  1.4就是综合了各种优化手段的目前最好结果


3号任务所有网络都表现的很不错

4号任务除了VIT，和预训练的resnet18，其它都只有56%左右正确率

VIT表现出不错的潜力，但受限于个人电脑外加时间，只能训练200轮看效果。
