# NLP_covid19_civil_complaint
### 코로나 19 이후의 서울 민원 텍스트 변화
+ 데이터 : 서울시 다산콜센터 접수 민원
+ 기간 : 2019.01.01 ~ 2020.12.31
+ 건수 : 약 450만

## 1. 코드 설명
### 1) dasan.ipynb
- 데이터 셋 확인
### 2) dasan_new.ipynb
+ 전처리 관련 코드
+ 불용어 제거
+ 기초통계량 확인
- ![톹계량 ](https://user-images.githubusercontent.com/60343930/110743674-c43f4080-827b-11eb-92a0-f40b08ae9085.png)
### 3) word2vec.ipynb
+ 코로나 19 관련 민원 추출
+ word2vec과 pca를 활용한 시각화
### 4) bert_naver_movie.ipynb
+ bert로 네이버 영화 리뷰 데이터 학습
+ 학습된 모델 저장
### 5) 민원텍스트_감정분석.ipynb
+ 학습된 모델을 사용하여 민원텍스트 감정분석
+ 각 민원텍스트에 해당하는 감정(부정:0, 긍정:1) 태깅
### 6) dasan_covid_STM.Rmd
+ 구조적 토픽 모델(Structural topic model)
+ 민원 텍스트와 메타정보(시간, 일일 확진자수 등)의 관계를 활용한 토픽모델링

## 2. 참여자
#### 1. 과제 책임자
- 김병준(성균관대 인터랙션사이언스학과 박사과정)
- 김도연
- 김주영
- 박다원

#### 2. 참여 연구진
- 박건철(서울디지털재단 데이터혁신팀장)

## 3. 보도자료
- [서울특별시-김학준] https://www.seoul.go.kr/news/news_report.do#view/333709
- [뉴스로-김미소] https://han.gl/C1cep
