# mask-tflite
一个用于检测是否戴口罩的分类器。
[English README](https://github.com/SingTown/mask-tflite/blob/main/README.md)


这个模型是使用edgeimpulse训练的，教程：
https://docs.edgeimpulse.com/docs/openmv-cam-h7-plus


## 注意:

1. 只有OpenMV4 H7 Plus能使用。
2. 我上传的样本只上传了单人的。如果你的测试画面有多人，准确度不可信。
3. 我没有使用背景分类，分类器只知道人脸是否戴了口罩。如果画面中没有人脸，准确度不可信。

## 使用:
1. 把 labels.txt 和 trained.tflite 拖到OpenMV4 H7 Plus中。
2. 使用OpenMV IDE运行 ei_image_classification.py。
3. 你可以在终端中看到结果.

## 结果
![test_face](https://github.com/SingTown/mask-tflite/blob/main/test/test_face.png)
![test_mask](https://github.com/SingTown/mask-tflite/blob/main/test/test_mask.png)
