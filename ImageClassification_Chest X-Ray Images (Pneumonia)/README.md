# Chest X-Ray Images (Pneumonia)
## Framework
Pytorch

## Data From
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

## Image


## 풀이법
Pretrained EfficientNet-b7 사용

과적합을 방지하기 위해 train_acc가 98% 이상이거나 test_acc가 90% 이상이면 학습이 종료되도록 Early Stopping 설정