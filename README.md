# Data Science Portfolio
> (Last update : 2020.11.26)

This repository contains my mentionable progress in Data Science. The purpose of this work is to organize my knowledge of the field and to self-motivate through the to-do list.
<br><br>


## 0. Table of Contents
#### 1. [Work Experience](#work_experience)
- Job Description
- Projects
#### 2. [Awards](#awards)
#### 3. [Job-related Education](#job_related)
#### 4. [Major Projects](#major_projects)
- Projects
- Application
#### 5. [Study](#study)
- Ongoing Study/To-do List
- Toy Projects (Kaggle)
- Data Structure/Algorithm
#### 6. [Contact](#contact)
<br><br>


## 1. Work Experience <a name="work_experience"></a>
- ### Job Description
  - Job Title: AI 연구원
  - Work Period: 2019.08 - 2019.12
  - Field: 반도체/디스플레이 등 제조업 스마트팩토리
  - Tasks: L기업, H기업 스마트팩토리 프로젝트 진행
  
- ### Projects

|Title|Data Type|Descrription|Preprocessing|Model|Stack|Duration|
|:---:|:-------:|:----------:|:-----------:|:---:|:---:|:------:|
|이미지 양불 판정|Image|반도체/디스플레이 이미지 양불 판정|Object Detection using OpenCV|CNN|`Python`, `Keras`, `OpenCV`|2019.11 - 2019.12|
|가상계측 모델|Time series, <br> structured data|공정 데이터를 활용해 계측값을 예측하는 가상계측 모델을 만들어 계측공정 생략|Anomaly detection, resampling 등|DNN + CNN + biLSTM + Self-Attention|`Python`, `Keras`, `msSQL`|2019.10 - 2019.11|
|R2R(Run-to-Run) 솔루션 연구|Time series|가상계측모델(VM) 구축. <br>이전 공정변수로부터 피드백을 받아 다음 변수 조절. <br>--> 계측값의 분산 최소화 및 불량률 감소 기대.|가상데이터를 생성, 노이즈 추가|Linear Regression|`Python`, `Statsmodel`|2019.10 - 2019.10|
|이미지 분석 솔루션 개발|Image|이미지 분류 모델을 커스터마이징 할 수 있도록 자체 솔루션 베타버전 개발|내부 알고리즘(이미지 전처리, 모델 아키텍쳐, 하이퍼파라미터 튜닝 등) 구현|CNN|`Python`, `Keras`, `C#`|2019.08 - 2019.10|

*보안상의 이유로 구체적인 데이터와 성능은 공개하지 않겠습니다.
<br><br><br>


## 2. Awards <a name="awards"></a>
|Name|Organizer|Problem|Prize|Article|Date|
|:--:|:-------:|:-----:|:---:|:-----:|:--:|
|2020 빅데이터</br>활용 경진대회|더존비즈온,</br>한국정보화진흥원|`주제 1`:</br>대한민국 중소중견기업의 매출 예측</br>(중소중견기업 10개 분기 데이터를 활용해 다음 분기 매출 예측)</br></br>`주제 2`:</br>대한민국 유통 활성화를 위한 적요 표준화</br>(중소중견기업 산업별 회계장부 적요 텍스트 데이터 비지도 분류)|대상|[링크](https://www.mk.co.kr/news/business/view/2020/11/1131764/)|2020.11.03|
|빅데이터</br>소셜마케팅|한국경제신문|지체장애인 서울시 저상버스 이용 증진</br>(데이터 시각화 및 텍스트 분석을 통한 인사이트 기반 마케팅 제안)|장려상|[링크](https://www.hankyung.com/news/article/2017021626771)|2017.02.11|

</br></br>

## 3. Job-related Education <a name="job_related"></a>
<img width="750" alt="Timeline" src="https://user-images.githubusercontent.com/45453533/83252418-2562bf80-a1e6-11ea-8398-19602ec7f75c.png">
<br><br>


## 4. Major Projects <a name="major_projects"></a>
- ### Projects

|Problem|Description|Dataset|Model|Stack|Last Update|
|:-----:|:----------:|:-----:|:---:|:---:|:---------:|
|웹앱 개발|코로나아웃::공적마스크 재고 알리미 <br>https://coronaout.kr|마스크재고API, <br>판매처 영업시간 및 전화번호 크롤링|-|`Python`, `HTML`, `CSS`, `JavaScript`, `KakaoMap API`|2020.04|
|감성분석|[식당 리뷰에서 <br>가성비/웨이팅/서비스에 대한 감성 분석](https://github.com/dataminegames/MangoPlate_NLP)|망고플레이트 <br>식당 리뷰 크롤링|biLSTM + self-Attention, Boosting(LightGBM)|`Python`, `PyTorch`, `Sklearn`, `Flask`, `HTML`, `CSS`, `jQuery`|2019.06|

- ### Application

<img width="282" alt="코로나아웃" src="https://user-images.githubusercontent.com/45453533/82897996-7dee4e80-9f93-11ea-8d16-0f54e8d80fce.png"> &emsp;&emsp; ![망고플레이트](https://user-images.githubusercontent.com/45453533/82911319-b3e8fe00-9fa6-11ea-88ec-fe958819df21.gif)
<br><br><br>


## 5. Study <a name="study"></a>
- ### Toy Projects (Kaggle)

> - Recommandation System

|Algorithm|Dataset|
|:-------:|:---:|
|Content Based Filtering|tmdb-movie-metadata|
|Colaborative Filtering|movielens-100k-dataset|

> - DL
	
|Algorithm|Data Type|Title|Ranking|
|:-------:|:-------:|:---:|:-----:|
|LSTM|Sound|TensorFlow Speech Recognition Challenge|-|
|DCGAN|Image|Simpsons Faces|-|
|Segmentation|Image|TGS Salt Identification Challenge|2,056 / 3,229 <br>(상위 %0.637%)|
|CNN|Image|Dogs vs. Cats Redux: Kernels Edition|28 / 1,314 <br>(상위 %0.021%)|
|LSTM|Text, <br>structrued data|Mercari Price Suggestion Challenge|47 / 2,382 <br>(상위 0.02%)|
|LSTM|Text|Sentiment Analysis on Movie Reviews|22 / 861 <br>(상위 0.026%)|
|LSTM|Text|Toxic Comment Classification Challenge|1,451 / 4,550 <br>(상위 0.319%)|

> - ML
	
|Problem|Algorithm|Title|Ranking|
|:-----:|:-------:|:---:|:-----:|
|Regression||Mercedes-Benz Greener Manufacturing|11 / 3,831 <br>(상위 0.003%)|
|Classification||San Francisco Crime Classification|61 / 2,332 <br>(상위 0.026%)|
|Regression||Housing Prices Competition for Kaggle Learn Users|298 / 33,855 <br>(상위 0.009%)|
|Regression||Walmart Recruiting - Store Sales Forecasting|11 / 690 <br>(상위 %0.16%)|
|Classification||Otto Group Product Classification Challenge|560 / 3,511 <br>(상위 0.159%)|
|Classification||Medical Appointment Noshows|-|
|Regression||Bike Sharing Demand|7 / 3,251 <br>(상위 0.002%)|



- ### Data Structure/Algorithm
  - 알고리즘 사이트(프로그래머스 등) [문제 풀이](https://github.com/dataminegames/Algorithm_study/tree/master/Programmers)



## 6. Contact <a name="contact"></a>
- E-mail: dataminegame@gmail.com
