# Data Science Portfolio
(Last update : 2020.05.29)

This repository contains my mentionable progress in Data Science. The purpose of this work is to organize my knowledge of the field and to self-motivate through the to-do list.
<br><br>


## 0. Table of Contents
#### 1. [Work Experience](#work_experience)
- Job Description
- Projects
#### 2. [Job-related Experiences](#job_related)
#### 3. [Major Projects](#major_projects)
- Projects
- Application
#### 4. [Study](#study)
- Ongoing Study/To-do List
- Toy Projects (Kaggle)
- Data Structure/Algorithm
- Mathematics
- Sources
#### 5. [Contact](#contact)
<br><br>


## 1. Work Experience <a name="work_experience"></a>
- ### Job Description
  - Field: 반도체/디스플레이 등 제조업 스마트팩토리
  - Job Title: AI 연구원
  - Work Period: 2019.08 - 2019.12
  - Work History: L기업, H기업 스마트팩토리 프로젝트 진행
  
- ### Projects

|Title|Data Type|Descrription|Preprocessing|Model|Stack|Duration|
|:---:|:-------:|:----------:|:-----------:|:---:|:---:|:------:|
|이미지 양불 판정|Image|반도체/디스플레이 이미지 양불 판정|Object Detection using OpenCV|CNN|`Python`, `Keras`, `OpenCV`|2019.11 - 2019.12|
|가상계측 모델|Time series, <br> structured data|공정 데이터를 활용해 계측값을 예측하는 가상계측 모델을 만들어 계측공정 생략|Anomaly detection, resampling 등|DNN + CNN + biLSTM + Self-Attention|`Python`, `Keras`, `msSQL`|2019.10 - 2019.11|
|R2R(Run-to-Run) 솔루션 연구|Time series|가상계측모델(VM) 구축. <br>이전 공정변수로부터 피드백을 받아 다음 변수 조절. <br>--> 계측값의 분산 최소화 및 불량률 감소 기대.|가상데이터를 생성, 노이즈 추가|Linear Regression|`Python`, `Statsmodel`|2019.10 - 2019.10|
|이미지 분석 솔루션 개발|Image|이미지 분류 모델을 커스터마이징 할 수 있도록 자체 솔루션 베타버전 개발|내부 알고리즘(이미지 전처리, 모델 아키텍쳐, 하이퍼파라미터 튜닝 등) 구현|CNN|`Python`, `Keras`, `C#`|2019.08 - 2019.10|

*보안상의 이유로 구체적인 데이터와 성능은 공개하지 않겠습니다.
<br><br><br>


## 2. Job-related Experiences <a name="job_related"></a>
<img width="750" alt="Timeline" src="https://user-images.githubusercontent.com/45453533/83252418-2562bf80-a1e6-11ea-8398-19602ec7f75c.png">
<br><br>


## 3. Major Projects <a name="major_projects"></a>
- ### Projects

|Problem|Descrription|Dataset|Model|Stack|Last Update|
|:-----:|:----------:|:-----:|:---:|:---:|:---------:|
|웹앱 개발|코로나아웃::공적마스크 재고 알리미 <br>https://coronaout.kr|마스크재고API, <br>판매처 영업시간 및 전화번호 크롤링|-|`Python`, `HTML`, `CSS`, `JavaScript`, `KakaoMap API`|2020.04|
|감성분석|[식당 리뷰에서 <br>가성비/웨이팅/서비스에 대한 감성 분석](https://github.com/dataminegames/MangoPlate_NLP)|망고플레이트 <br>식당 리뷰 크롤링|biLSTM + self-Attention, Boosting(LightGBM)|`Python`, `PyTorch`, `Sklearn`, `Flask`, `HTML`, `CSS`, `jQuery`|2019.06|

- ### Application

<img width="282" alt="코로나아웃" src="https://user-images.githubusercontent.com/45453533/82897996-7dee4e80-9f93-11ea-8d16-0f54e8d80fce.png"> &emsp;&emsp; ![망고플레이트](https://user-images.githubusercontent.com/45453533/82911319-b3e8fe00-9fa6-11ea-88ec-fe958819df21.gif)
<br><br><br>


## 4. Study <a name="study"></a>
- ### Ongoing Study/To-do List
  - [x] `수학` ~~선형대수 강의 : 주재걸 교수님 (Edwith)~~
  - [x] `수학` 선형대수 강의 : 이상화 교수님 (KOCW)
  - [ ] `수학` 선형대수 강의 : 이옥연 교수님 (OCW)
  - [x] `프로젝트` Segmentation : baseline --> 성능 올리기 (Kaggle)
  - [x] `프로젝트` DCGAN : baseline --> 성능 올리기 (Kaggle)
  - [x] `코딩` 자료구조 : 매주 level3 이상 2문제 풀기 (프로그래머스 등)
  - [ ] `코딩` 프레임워크 환승 : Keras --> PyTorch or Tensorflow2.0 (프레임워크 환승)


- ### Toy Projects (Kaggle)
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
<br>


- ### Mathematics
  - 개념 정리 (예정)
<br><br><br>


## 5. Contact <a name="contact"></a>
- E-mail: dataminegame@gmail.com
