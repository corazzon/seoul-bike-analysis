# 서울특별시 공공자전거 따릉이 대여이력 분석
* [miningful/seoulbike: 따릉이 따세권EDA](https://github.com/miningful/seoulbike)에서 흥미를 얻어 분석을 시작하게 됨

## 데이터 출처 :
* 서울특별시 공공자전거 대여이력 정보
http://data.seoul.go.kr/dataList/datasetView.do?infId=OA-15182&srvType=F&serviceKind=1&currentPageNo=1

* `(이달의주요공개정보)_서울_공공자전거(따릉이)_이용현황 자료(161021).xlsx (1.24MB)`
https://opengov.seoul.go.kr/anspruch/10045476


## PyCon KR 2019 Tutorial

* google colaboratory 를 통해 실습합니다. 실습을 위해 google drive 로그인을 위한 gmail 계정이 필요하며, 개인노트북을 지참해 주셔야 합니다.


### [서울시 자전거 따릉이 데이터로 파이썬 기초부터 크롤링까지 :: 파이콘 한국 2019](https://www.pycon.kr/program/tutorial-detail?id=154)
> 파이썬을 처음 배우는 분들을 위한 튜토리얼 입니다. 
> 서울시 자전거 따릉이 대여소 위치를 크롤링해서 분석해 봅니다.
* 8월 15일 (목) 10:00~8월 15일 (목) 13:00
* 티켓구매 : https://www.pycon.kr/program/tutorial-detail?id=154

#### 실습 내용
* 따릉이 데이터 분석과 수집을 위한 파이썬 기초 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/seoul-bike-analysis/blob/master/python-for-seoul-bike.ipynb)
* Pandas cheat sheet 로 데이터 분석 기초 스킬 익히기
  * [Pandas_Cheat_Sheet.pdf 파일 보기](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
* 파이썬으로 자전거 대여소 목록 수집하기
  * requests와 beautifulsoup 을 활용해서 대여소 목록을 수집합니다. 
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/seoul-bike-analysis/blob/master/bike_station_scrape.ipynb)
  * 크롤링 한 결과에 대해 Pandas로 전처리를 하고 시각화 해봅니다. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/seoul-bike-analysis/blob/master/seoul-bike-station-location.ipynb)

### [서울시 자전거 따릉이 데이터로 파이썬 시계열 분석부터 기계학습까지 :: 파이콘 한국 2019](https://www.pycon.kr/program/tutorial-detail?id=155)

> 파이썬과 판다스의 기본적인 사용법을 알고 있는 분들을 위한 튜토리얼 입니다.
> 파이썬이 처음이신 분들은 오전에 진행되는 기초 튜토리얼을 함께 신청해 주세요.

* 8월 15일 (목) 14:00~8월 15일 (목) 17:00
* 티켓구매 : https://www.pycon.kr/program/tutorial-detail?id=155

#### 실습 내용
* Pandas 로 여러 데이터 파일 합치고 나누기
* 파이썬 데이터 전처리와 분석 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/seoul-bike-analysis/blob/master/seoul-bike-eda.ipynb) 
* 시계열 분석 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/seoul-bike-analysis/blob/master/time-series-forecast.ipynb)
* 기계학습으로 특정 대여소의 자전거 이용거리 예측하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/seoul-bike-analysis/blob/master/ml-regression.ipynb)

### 오전, 오후 실습 내용 일부 미리보기

> 아래 이미지는 실습 예시로, 실제 진행되는 튜토리얼의 내용과는 차이가 있을 수도 있습니다.

<img src="https://i.imgur.com/7pUjfdt.png">

<img src="https://i.imgur.com/MxdXVBe.png">

<img src="https://i.imgur.com/YQQL90w.png">

<img src="https://i.imgur.com/B75XRCH.png">

<img src="https://i.imgur.com/EE2nG1Q.png">

<img src="https://i.imgur.com/IMLx9G5.png">

<img src="https://i.imgur.com/NbMiiqq.png">

<img src="https://i.imgur.com/TpiqlaV.png">

## 관련자료 
* [(석간) 서울시 따릉이 회원 62만 돌파 출 퇴근시간 38% 집중](http://spp.seoul.go.kr/main/news/news_report.jsp#view/253821)
* [공공자전거 따릉이 인기 따라 '따세권' 형성…소외지역도 :: 공감언론 뉴시스통신사 ::](http://www.newsis.com/view/?id=NISX20180706_0000356247&cID=10201&pID=10200)
* [서울특별시 빅데이터 캠퍼스 > 분석결과/사례공유 > 서울시 분석사례 > 서울시 자전거 이동경로 분석](https://bigdata.seoul.go.kr/noti/selectNoti.do?r_id=P430&bbs_seq=229&sch_type=&sch_text=&currentPage=1)
* [따릉이 편리하게 이용하기 위한 14가지 | 서울시 정보소통광장(정보공개)](https://opengov.seoul.go.kr/mediahub/15085803)
