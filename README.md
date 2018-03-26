# RA-CNN-PyTorch
PyTorch version for Recurrent Attention-CNN

## Platform:
python2.7

pyTorch - 0.3.1.post2


## Notes
Codes are finishing, please wait.


## Step 1: Init VGG net and APN net
1) Init VGG net
Using ImageNet-pretrained VGG119 for initialization.

2) Init APN net
Train APN net through finding the maximal value in feature map(conv5_4), and model it to a regression problem.

The hyper-parameters are:
```
self.LR_BASE = 0.0001*0.001
self.LR_STEP = [1000, 1500]  # LR_STEP * batch
self.LR_GAMMA = 0.1
self.TRAIN_BATCH_SIZE = 64
```
