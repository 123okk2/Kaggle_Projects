# Fingers
## Framework
Pytorch

## Data From
https://www.kaggle.com/koryakinp/fingers

## Image
![fingers](https://user-images.githubusercontent.com/51351974/111782837-d57ff100-88fc-11eb-8d99-4c15249305fc.JPG)


## 풀이법
직접 모델을 만드는 것보다, 기존의 모델을 빌려와 학습하는 것이 더 뛰어난 성능을 보일 것이라 판단.

DenseNet을 사용하려 했으나 메모리로 인해 어쩔 수 없이 ResNet-34를 가져왔고,

출력층만 변경하여 사용.
