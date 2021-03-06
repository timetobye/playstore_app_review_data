Google play app review data EDA
===========
![alt text](https://img.shields.io/badge/Python-3.7-red.svg)
![alt text](https://img.shields.io/badge/App_Review-EDA-blue.svg)


## Table of contents
- Purpose
- EDA result Example
- App review list

## :star: Purpose
구글 플레이에 있는 앱의 리뷰를 스크래핑 한 [페이지](https://github.com/timetobye/google_playstore_review_scraping)에서 나온 데이터 셋을 가지고 분석을 해보는 것이 목적 입니다.
각 기업 별로 앱의 별점 변화, 리뷰 코멘트 등을 살펴 보고 결과를 정리합니다. 별점이 높은 앱부터 낮은 앱까지 모두 해볼 생각입니다. 너무 많은 수고를 들이지는 않을거고
앱의 전반적인 흐름을 파악하고 나중에 앱을 만들 때 공부하기 위한 자료롤 활용 할 계획입니다.

캐글의 좋은 데이터 셋을 가지고 하는 것도 중요하지만 스스로 자료를 구해서 분석해보는 것도 좋은 것 같습니다. ~~자료의 양이 적은게 흠이지만..-0-~~ 

## EDA result Example
Jupyter Notebook으로 EDA를 진행하였고 아래는 EDA를 통해서 확인 할 수 있는 항목 예시 입니다. 

- 요일

![alt text](sample_image/daily.png)

- 요일 별 별점 비율 분포

![alt text](sample_image/heatmap_daily_rating.png)

- 리뷰 작성 횟수 비율 분포

![alt text](sample_image/ratio_of_comment_counting.png)

- 별점 별 비율

![alt text](sample_image/app_rating.png)

- 답변 비율

![alt text](sample_image/answer_ratio.png)

- 일간 별점 변화

![alt text](sample_image/daily_rating_graph.png)

- 월간 별점 변화

![alt text](sample_image/monthly_daily_rating.png)

- 리뷰에 대한 답변 소요 시간 및 누적 그래프

![alt text](sample_image/answer_1.png)

- 단어 빈도 수

![alt text](sample_image/word_frequency.png)


## App Review List

### Done
- [Coupang](https://nbviewer.jupyter.org/github/timetobye/playstore_app_review_data/blob/master/EDA_result/coupang_20191229/%5Bcoupang%5Dgoogle_play_store_review_EDA.ipynb)
- [Azar](https://nbviewer.jupyter.org/github/timetobye/playstore_app_review_data/blob/master/EDA_result/Azar_20191229/%5BAzar%5Dgoogle_play_store_review_EDA_20191229.ipynb)
- [Socar]()
- [tada]()
- hakuna
- banksalad
- coupang
- myrealtrip
- ohhouse(오늘의집)
- yanolja
- yogiyo

### TODO
- 배달의 민족
