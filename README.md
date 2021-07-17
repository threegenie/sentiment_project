# 📝 Sentiment Project
### 1. 네이버 쇼핑 리뷰 데이터를 통해 감성 분석하기
#### 사용한 데이터
- 네이버 쇼핑 제품별 후기 20만 건 (2020.06~2020.07) FROM https://github.com/bab2min/corpus/tree/master/sentiment

#### 사용한 패키지
- 전처리, 시각화 : Pandas, Numpy, Matplotlib, Seaborn, Counter, Mecab, Sklearn, Keras(Tokenizer), Wordcloud
- 모델링 : Keras - GRU, LSTM

#### 코드
- Mecab을 사용하여 전처리한 분석 내용 : [Mecab 분석 코드 링크](https://github.com/threegenie/sentiment_project/blob/main/sentiment_project_using_mecab.ipynb)
- Okt를 사용하여 전처리한 분석 내용 : [Okt 분석 코드 링크](https://github.com/threegenie/sentiment_project/blob/main/sentiment_project_using_okt.ipynb)
- Okt를 사용하여 전처리하고 머신러닝 모델을 사용한 분석 내용 : [머신러닝 코드 링크](https://github.com/threegenie/sentiment_project/blob/main/sentiment_project_using_okt_and_machine_learning.ipynb)

#### 프로젝트 정리
- [프로젝트 PPT 링크](https://github.com/threegenie/sentiment_project/blob/main/Project%20PPT.md)

***

### 2. 긍정 리뷰와 부정 리뷰의 분포가 잘 드러나 있는 어플리케이션 리뷰 분석

카카오페이지 플레이스토어 리뷰 데이터 분석

#### 사용한 데이터 
- 직접 크롤링한 데이터(2021.06.08, https://drive.google.com/file/d/1JBZmRP-Dcc69sQFgPqELTVUYrYCRIBRN/view?usp=sharing)

#### 코드 
- [카카오페이지 리뷰 데이터 분석 코드 링크](https://github.com/threegenie/sentiment_project/blob/main/kakaopage_playstore_review_analysis.ipynb)
- [플레이스토어 리뷰 데이터 크롤링을 위한 코드 레포](https://github.com/threegenie/appstore_review_crawling)
