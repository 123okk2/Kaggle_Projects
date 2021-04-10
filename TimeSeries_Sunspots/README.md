# Sunspots

## Framework
Keras

## Data From
https://www.kaggle.com/robervalt/sunspots

## Image
![Sunspots](https://user-images.githubusercontent.com/51351974/111782831-d44ec400-88fc-11eb-8a27-07cf17b6b1de.JPG)


## 풀이법
그래프 상으로 평균과 분산이 일정한 정상 시계열 데이터라는 판단 하에 별 다른 전처리는 하지 않음.

윈도우 사이즈를 30개로 설정하여, 30일간의 측정치를 토대로 다음 날의 예상 측정치를 추정.

두 개의 Bidirectional LSTM으로 구성했고, 두 개의 완전연결층으로 구성.
