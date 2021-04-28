# 单词袋图片分类器

#### 介绍
使用Python中的视觉单词袋方法以及Lowe的SIFT和Libsvm实现基于内容的图像分类器。


源自：https://github.com/shackenberg/Minimal-Bag-of-Visual-Words-Image-Classifier github项目采用python2.x 本项目采用python3.x

#### 软件架构
软件架构说明


#### 安装教程

1.  xxxx
2.  xxxx
3.  xxxx

#### 使用说明

训练模型:
```
python learn.py -d path_to_folders_with_images
```
识别图片:
```
python classify.py -c path_to_folders_with_images/codebook.file -m path_to_folders_with_images/trainingdata.svm.model images_you_want_to_classify
```
训练素材格式:

.
|-- path_to_folders_with_images
|    |-- class1
|    |-- class2
|    |-- class3
...
|    └-- classN

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 码云特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5.  码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
