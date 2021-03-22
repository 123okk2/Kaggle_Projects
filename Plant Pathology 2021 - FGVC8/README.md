# Plant Pathology 2021 - FGVC8

## Data From

https://www.kaggle.com/c/plant-pathology-2021-fgvc8

## Image
![plant](https://user-images.githubusercontent.com/51351974/111782827-d3b62d80-88fc-11eb-90e0-ebf2e2dfb8e3.JPG)


## 풀어법

ResNet-34을 호출하여 학습 진행.

검증은 여러 방면에서의 검증을 위해 Ten-Crop을 사용하여 열 개의 이미지로 나눈 후 출력값인 softmax를 조합하여 최종 출력 결정.