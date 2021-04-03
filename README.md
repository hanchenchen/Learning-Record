# Learning-Record

#### Plan && Tracking

| Date | Priority |        Task        |                 Milestone                  | Start Time | Duration | End Time | Result |
| :--: | :------: | :----------------: | :----------------------------------------: | :--------: | :------: | :------: | :----: |
| 4.3  |    01    |    Train VFNet     |           Submit the new result            |    4.1     |  2 days  |   4.3    |        |
| 4.4  |    02    | Read paper *VFNet* | Find some trick that can be added to VFNet |   16:15    | 45 mins  |  17:00   |        |
| 4.3  |    03    |  Automatic tuning  |                Can I use it                |   17:05    | 25 mins  |  17:30   |        |
| 4.3  |    04    |      DanceNet      |         Understand the main ideas          |   18:00    | 45 mins  |  18:45   |        |
|      |          |                    |                                            |            |          |          |        |
|      |          |                    |                                            |            |          |          |        |
|      |          |                    |                                            |            |          |          |        |
|      |          |                    |                                            |            |          |          |        |
|      |          |                    |                                            |            |          |          |        |
|      |          |                    |                                            |            |          |          |        |
|      |          |                    |                                            |            |          |          |        |
|      |          |                    |                                            |            |          |          |        |

后续计划：

- [ ]  [贝叶斯优化(Bayesian Optimization)深入理解 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/53826787)
- [ ] ACTION-Net https://mp.weixin.qq.com/s/L2_lkhKbVhW8fjAaDdsyWQ
- [ ] *
   - [ ] 在线难例挖掘（OHEM online hard example mining）
   - [ ] 骨干网络蒸馏
   - [ ] 裁剪图片多线程
   - [ ] TTA, Test time augment
- [ ] 将全部数据用于训练
- [ ] 模型瘦身



#### 4-2

今日计划：

- [ ] 01 - Train VFNet
- [ ] 02 - Read paper *VFNet*
- [ ] 03 - Automatic tuning
- [ ] 04 - DanceNet https://mp.weixin.qq.com/s/MOksw35ddu8QRtZoOzMl0A

# 

#### 3-30

今日计划：

- [x]  使用pandas进行EDA，查看size of bboxs 的分布特点
- [ ]  ResNet不同深度的结构的区别 ？
- [ ]  Adjust the setting of anchors to diffrent categories. [mmdetection 代码库中的 anchor 设置原则][https://blog.csdn.net/yangyehuisw/article/details/105373508]
- [ ]  比较04和05结果
- [x]  阅读star_paper
- [ ]  记录训练结果

明日计划：

- [ ] NMS -> Soft-NMS [mmdetection 模型训练技巧_Guo_Python的博客-CSDN博客](https://blog.csdn.net/Guo_Python/article/details/108148385)
- [ ] Focal loss [目标检测系列三：奇技淫巧 - 超杰 (spytensor.com)](http://spytensor.com/index.php/archives/53/?telchm=x4e3v1)
- [ ] Adjust the hyper parameters 自动调参？ [贝叶斯优化(Bayesian Optimization)深入理解 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/53826787)
- [ ] Train until the eval loss doesn't change
- [ ] do lr x10 until the loss no longer converge.
- [ ] *
   - [ ] 在线难例挖掘（OHEM online hard example mining）
   - [ ] 骨干网络蒸馏
   - [ ] 裁剪图片多线程
   - [ ] TTA, Test time augment
- [ ] https://zhuanlan.zhihu.com/p/345657476
- [ ] 将全部数据用于训练
- [ ] 模型瘦身
- [ ] 肌电手势识别算法应用方案V0.2
- [ ] Surface-Electromyography-Based Gesture Recognition by Multi-view Deep Learning
- [ ] sEMG-Based Gesture Recognition With Embedded Virtual Hand Poses and Adversarial Learning
- [ ] star_paper

# 

#### 3-29

今日计划：

- [ ] **解决150服务器SSH断联问题**
   - [ ] 修改201.150服务器ssh配置文件
- [x] Faster rcnn https://zhuanlan.zhihu.com/p/31426458
- [x] 在Task1_test中使用不同的滑动窗口大小/对图像采用不同的尺寸进行切割，overlap = 0.2 。



#### 3-28

今日计划：

- [x] Make a plan for learning GRE
- [ ] **解决150服务器SSH断联问题**
  - [ ] 修改201.150服务器ssh配置文件
- [x] 在PANDA数据集上对coco预训练的Cascade RCNN进行微调
  - [x] 使用screen或nohup运行程序
- [x] 整理TOP2的Blogs中可能有用的tricks
- [ ] Faster rcnn https://zhuanlan.zhihu.com/p/31426458
- [ ] 在Task1_test中使用不同的滑动窗口大小/对图像采用不同的尺寸进行切割，overlap = 0.2 。
- [x] GLOU loss
- [x] Save files of models to OneDrive. Name: 01_cascade_rcnn_r101_fpn_1x_coco_lr_0.02_batch_8

# 

#### 3-27

今日计划：

- [x] 再次连接，连接关闭后，进程会莫名其妙停掉，没有报错。 --screen
- [ ] Make a plan for learning GRE —— 0%

# 

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



