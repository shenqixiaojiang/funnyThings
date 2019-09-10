# funnyThings
## 1 图像风格化
[图像风格化介绍](https://www.jiqizhixin.com/articles/2018-05-15-5)

[Keras代码](https://github.com/keras-team/keras/blob/master/examples/neural_style_transfer.py)

## 2 文字风格化
[Keras 代码](https://github.com/yuweiming70/Style_Migration_For_Artistic_Font_With_CNN) 清华的学生做的，挺有意思。

## 3 物体检测
[Tensorflow demo](https://github.com/tensorflow/models/blob/master/research/object_detection/object_detection_tutorial.ipynb)

## 4 图片显著性区域检测
[基于传统算法的Saliency](https://github.com/yhenon/pyimgsaliency) <br>
[效果不错的FCN算法](https://github.com/NathanUA/BASNet)

## 5 图像超分辨率重建

#### [EDSR](https://github.com/thstkdgus35/EDSR-PyTorch)
下载好代码后，直接将待测试的数据放到test集合，然后使用下条命令即可。结果将保存到experiment/test/results-Demo/。
```
python main.py --data_test Demo --scale 4 --pre_train download --test_only --save_results
```

## 6 相似检索
[product quantization](http://vividfree.github.io/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0/2017/08/05/understanding-product-quantization)

## 7 自步学习
在[课程学习](https://blog.csdn.net/weixin_37805505/article/details/79144854)的基础上发展起来的。通过自步学习参数K控制从易到难的学习样本。<br>
* [基础知识](https://blog.csdn.net/Bear_Kai/article/details/77771127)
* [保证选择样本多样性](http://www.hanlongfei.com/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0/2017/07/28/spld/)

## 8 自学习
通过引入稀疏自编码器，学习到原始图像更充分的特征表达。
* [基础知识](https://blog.csdn.net/jiede1/article/details/76769248)

## 9 Multitask Learning
利用更多的任务信息增加特征的表达能力。
* [基础知识](https://mp.weixin.qq.com/s?__biz=MzIxNDgzNDg3NQ==&mid=2247483961&idx=1&sn=cf3fe6aafd40e87fac1c2689497fec96&chksm=97a0c9eda0d740fb5c673e010912582394597458b4d0f98c1832e5188bdedcce4abcdd20f19f&scene=21#wechat_redirect)

## 10 迁移学习
从源域到目标域的迁移。
* [基础知识](https://zhuanlan.zhihu.com/p/47991650)
* [解决多媒体不同模态之间共有特征和私有特征的问题](https://zhuanlan.zhihu.com/p/49479734)
