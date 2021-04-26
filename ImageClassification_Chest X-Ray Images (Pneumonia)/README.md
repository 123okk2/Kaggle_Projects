# Chest X-Ray Images (Pneumonia)
## Framework
Pytorch

## Data From
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

## Image
![chest](https://user-images.githubusercontent.com/51351974/116092163-889fef00-a6e0-11eb-9294-550966f550b9.JPG)

## 풀이법
Pretrained EfficientNet-b7 사용

과적합을 방지하기 위해 train_acc가 98% 이상이거나 test_acc가 90% 이상이면 학습이 종료되도록 Early Stopping 설정
