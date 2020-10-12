# mask-tflite
A classification of whether or not to wear a mask.
This model I trained with edgeimpulse, tutorial:
https://docs.edgeimpulse.com/docs/openmv-cam-h7-plus

## Note:

1. only OpenMV 4 Plus can be used.
2. my sample only uploaded a single person picture. If there are more than one person in the test screen, the accuracy is not credible.
3. I don't have a background, I can only tell if I'm wearing a mask and I'm not wearing a mask. If the test screen has no face, the accuracy is not credible.

## To use:
1. drag labels.txt and trained.tflite to OpenMV Plus.
2. run ei_image_classification.py with OpenMV IDE.
3. you can see result in terminal.
