# OpenMMLabCampHomework

这里是 OpenMMLab AI实战营 第二期 12班 同学 Jayce Ning 的作业仓库。

## 第一次作业

训练全流程代码见 ./homework1_RTMPose_ear_pose_estimate/main.ipynb

目标检测模型使用示例配置文件 rtmdet_tiny_ear.py 。训练 120 epoch 在测试集上得分为：

![](./homework1_RTMPose_ear_pose_estimate/img/detection_map.png)

关键点检测模型使用示例配置文件 rtmpose-s-ear.py 。 训练 300 epoch 在测试集上得分为：

![](./homework1_RTMPose_ear_pose_estimate/img/rtmpose_socre.png)

测试自己上传的耳朵图片，输出为：

![](./homework1_RTMPose_ear_pose_estimate/outputs/G2_RTMDet-RTMPose/myear.jpg)

## 第二次作业

训练全流程代码见 ./homework2_ResNet50_fruit_classification/main.ipynb

训练配置文件见 ./homework2_ResNet50_fruit_classification/projects/fruit/resnet50_finetune.py

在验证集上的准确率为：

![](./homework2_ResNet50_fruit_classification/img/test.png)