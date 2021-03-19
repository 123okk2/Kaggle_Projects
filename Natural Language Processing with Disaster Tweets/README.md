# Natural Language Processing with Disaster Tweets

## Data From
https://www.kaggle.com/c/nlp-getting-started

## Image
![nlp](https://user-images.githubusercontent.com/51351974/111782823-d2850080-88fc-11eb-9bbb-590c256b2328.JPG)


## 풀이법
sklearn의 로지스틱 회귀 사용.

각 데이터에 대한 결측치를 "None"으로 통일하고 TF-IDF 방식으로 벡터화하여 전처리.

이후 GridSearchCV로 최적의 파라미터 탐색 후 로지스틱 회귀에 적용.
