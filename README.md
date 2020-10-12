# mask-tflite
A classification of whether or not to wear a mask.
[中文README](https://github.com/SingTown/mask-tflite/blob/main/README_CN.md)


This model I trained with edgeimpulse, tutorial:
https://docs.edgeimpulse.com/docs/openmv-cam-h7-plus


## Note:

1. only OpenMV 4 Plus can be used.
2. my sample only uploaded a single person picture. If there are more than one person in the test screen, the accuracy is not credible.
3. I don't have a background, the classifier only knows whether the face is wearing a mask. If the test screen has no face, the accuracy is not credible.

## To use:
1. drag labels.txt and trained.tflite to OpenMV Plus.
2. run ei_image_classification.py with OpenMV IDE.
3. you can see result in terminal.

## result
![test_face](https://github.com/SingTown/mask-tflite/blob/main/test/test_face.png)
![test_mask](https://github.com/SingTown/mask-tflite/blob/main/test/test_mask.png)
