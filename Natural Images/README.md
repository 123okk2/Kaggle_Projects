# Natural Images

## Framework
Pytorch

## Data From
https://www.kaggle.com/prasunroy/natural-images/code

## Image
![natureal image](https://user-images.githubusercontent.com/51351974/112018865-4714a500-8b72-11eb-96d2-57979934d9f7.JPG)


## 풀이법
각 이미지의 사이즈가 전부 다르기에 224, 224로 Reshape하여 사이즈 통일 후 학습.

크게 복잡한 데이터가 아니기에 ImageFolder와 DataLoader로 이미지를 불러온 후

5쌍의 Conv-MaxPool, 평균풀링으로 faltten 후 3개의 Linear 레이어를 사용해 분류
