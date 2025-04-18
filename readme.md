# 化妆品图片分类

# 使用方法
 
## 介绍
 
B站大佬：霹雳吧啦Wz视频：12.2 使用Pytorch搭建Swin-Transformer网络

讲解链接：https://www.bilibili.com/video/BV1yg411K7Yc?spm_id_from=333.999.0.0

引用：https://github.com/Ydjiao/deep-learning-for-image-processing/tree/master/pytorch_classification/swin_transformer

## 数据集介绍

数据集背景：
Paddle官方给的markup化妆品数据的基础上增加perfume(香水)一类数据集.

数据集内容：
包含blush、eyeshow、eyeshadow、foundation、lipstick、mascara、nail_polish、perfume共8类化妆品数据.

数据集来源：
Paddle官方给的markup化妆品数据的基础上增加perfume(香水)一类数据集,perfume(香水)类通过爬虫爬取百度图片香水类图片
https://aistudio.baidu.com/datasetdetail/39658

## 预训练模型
 
swin_tiny_patch4_window7_224.pth

https://huggingface.co/microsoft/swin-tiny-patch4-window7-224


## 教程

先下载以上数据，将模型和数据的路径在源码中改正后即可开始训练。

预测类似。
