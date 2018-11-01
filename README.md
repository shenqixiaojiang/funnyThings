# funnyThings
## 1 图像风格化
[图像风格化介绍](https://www.jiqizhixin.com/articles/2018-05-15-5)

[Keras代码](https://github.com/keras-team/keras/blob/master/examples/neural_style_transfer.py)

## 2 文字风格化
[Keras 代码](https://github.com/yuweiming70/Style_Migration_For_Artistic_Font_With_CNN) 清华的学生做的，挺有意思。

## 3 物体检测
[Tensorflow demo](https://github.com/tensorflow/models/blob/master/research/object_detection/object_detection_tutorial.ipynb)

## 4 图片显著性区域检测
[基于传统算法的Saliency](https://github.com/yhenon/pyimgsaliency)

## 5 图像超分辨率重建

#### [EDSR](https://github.com/thstkdgus35/EDSR-PyTorch)
下载好代码后，直接将待测试的数据放到test集合，然后使用下条命令即可。结果将保存到experiment/test/results-Demo/。
```
python main.py --data_test Demo --scale 4 --pre_train download --test_only --save_results
```
