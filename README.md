# Learning-Record

#### Plan && Tracking

|    Date    | Priority |                             Task                             |     Milestone      | Start Time | Duration | End Time | Result |
| :--------: | :------: | :----------------------------------------------------------: | :----------------: | :--------: | :------: | :------: | :----: |
| 2021-03-25 |    00    | 服务器105，在PANDA数据集上对coco预训练的Cascade RCNN进行微调 |  完成CATE_1的训练  |   19:06    |    3h    |  21:06   |        |
| 2021-03-26 |    01    |                          添加Tricks                          |                    |            |          |          |        |
| 2021-03-26 |    02    |                在服务器49上运行dist_train.py                 | 完成四个类别的训练 |            |          |          |        |



#### 3-25

今日计划：

- [ ] **解决SSH断联问题**
- [x] 关闭SSH后让进程继续运行
- [ ] 再次连接，连接关闭后，进程会莫名其妙停掉，没有报错。
- [x] 阅读关于模型训练的调参技巧
- [x] 图片增广
- [ ] 在PANDA数据集上对coco预训练的Cascade RCNN进行微调 ——25%
- [ ] Make a plan for learning GRE —— 0%
- [x] Some concepts
  - [x] Up sampleing
  - [x] FPN
  - [x] mAP, [详解object detection中的mAP - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/56961620)

明日计划：

- [ ] 在Task1_test中使用不同的滑动窗口大小。
- [ ] [贝叶斯优化(Bayesian Optimization)深入理解 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/53826787)
- [ ] Train until the loss doesn't change
- [ ] [mmdetection 模型训练技巧_Guo_Python的博客-CSDN博客](https://blog.csdn.net/Guo_Python/article/details/108148385)
  - [ ] NMS -> Soft-NMS
  - [ ] 用GIoULoss代替L1Loss
  - [ ] 模型瘦身
  - [ ] 在线难例挖掘（OHEM online hard example mining）
- [ ] [目标检测系列三：奇技淫巧 - 超杰 (spytensor.com)](http://spytensor.com/index.php/archives/53/?telchm=x4e3v1)
  - [ ] GLOU loss
  - [ ] Focal loss
  - [ ] TTA, Test time augment
- [ ] 整理TOP2的Blogs中可能有用的tricks
  - [ ] 将全部数据用于训练
  - [ ] 骨干网络蒸馏
  - [ ] 裁剪图片多线程
  - [ ] 对图像采用不同的尺寸进行切割，overlap = 0.2 。 

# 

#### 3-24

今日计划：

- [ ] ~~完成 Faster RCNN阅读笔记~~
- [x] 在Tianchi官网中进行结果提交
- [ ] Make a plan for learning GRE —— 0%
- [x] Read 2 blogs about Tianchi competition and object detection
- [ ] 在PANDA数据集上对coco预训练的Cascade RCNN进行微调 ——25%

明日计划：

1. 划分训练集和测试集：5：1。
   对图像采用不同的尺寸进行切割，overlap = 0.2 。
2. 阅读关于模型训练的调参技巧
3. 整理TOP2的Blogs中可能有用的tricks
4. 图片增广


