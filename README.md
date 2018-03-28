# RA-CNN-PyTorch
PyTorch version for Recurrent Attention-CNN

## Platform:
python2.7

pyTorch - 0.3.1.post2


## Notes
Codes are finishing, please wait.


## Step 1: Init VGG net and APN net
1) **Init VGG net**

Using ImageNet-pretrained VGG119 for initialization.

2) **Init APN net**

Train APN net through finding the maximal value in feature map(conv5_4), and model it to a regression problem with MSEloss.


## Step 2: Train VGG with CrossEntropy Loss

## Step 3: Train APN with Rank Loss

## Step 4: Iterative training
