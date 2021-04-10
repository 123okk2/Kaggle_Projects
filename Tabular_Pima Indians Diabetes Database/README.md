# Pima Indians Diabetes Database
## Framework
Pytorch

## Data From
https://www.kaggle.com/uciml/pima-indians-diabetes-database

## Image


## 풀이법
간단하게 나이, 피부두께만 범주형 데이터로 변환 후 예측 수행

OUTPUT을 포함해 3개의 층으로 이루어진 DNN으로 구성

ReLU를 사용했을 때 정확도가 60%대에서 멈춰 LeakyReLU 사용