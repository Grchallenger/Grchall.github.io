# 과제 : 아파트 경매 가격 예측

## 과제 목적

치솟아 가는 아파트 가격을 보며 사람들은 ‘내 집 마련의 꿈은 실현될 수 있을 것인가’ 라는 물음을 가지게 된다. 다수의 사람들이 집을 구매 하는 방법에 대해 단순히 부동산 중개업소를 통해 집을 구하거나 청약통장을 통해 아파트를 분양받는 일반적인 방법에 대해서만 알고 있으며, 부동산 경매를 통하는 방법에 대해 자세히 알지 못하는 것이 현실이다. 
특히, 경매에 대해 막연한 두려움을 가지기에 쉽게 포기해버린다. 하지만 경매를 잘 이용한다면, 시세보다 싼 가격에 좋은 매물을 얻을 수 있어, 내 집 마련에 더 쉽게 다가갈 수 있다. 
경매에 참여하는 일반인에게 가장 어려운 점은 정확한 경매가격 예상이다. 
이러한 이유로 일반인에게 경매 낙찰 예측가의 제공을 통해 보다 일반인이 경매에 쉽게 접근 할 수 있도록 하고자 한다. 또한, 아파트 경매 가격을 예측하고 실제 낙찰된 금액과 비교하여 차이를 확인하고자 한다. 추가로 가능한 금액 차이를 줄이고 보다 정확하게 예측하는 것을 목표로 한다. 

## 과제 결과물의 특징과 장점

데이콘의 데이터를 통해 아파트 경매에서 낙찰예상가를 가장 근접하게 예측할 수 있는 모델을 제작하였다. 이 데이터의 정확도가 하나의 장점이라고 할 수 있다. 
우선 제작한 모델을 가지고 데이콘의 학습모델을 제출하고 리더보드에서 순위를 확인 할 수 있었다.
 
![image](https://user-images.githubusercontent.com/101695209/170307790-8be938ce-5775-456f-b364-b26bccaf308d.png)
실제 제공된 데이터의 일부분을 보게 되면 위의 표와 같이 나타나게 되는데, 부산 동래구 낙민동 236번지의 주상복합을 하나의 예로 들고자 한다. 
데이콘에서 제공받은 Auction_master_train.csv 파일에서 해당 주소의 실제 낙찰가를 확인할 수 있는데, 135,330,000원(1억3천5백3십3만원)에 낙찰된 것을 확인할 수 있다. 
 
![image](https://user-images.githubusercontent.com/101695209/170307838-bdaf1ef2-cf87-46b8-891f-8198552a7936.png)
![image](https://user-images.githubusercontent.com/101695209/170307854-4d18f2a9-23c3-47c9-8879-5799d9681d14.png)

 
이번에는 상단에 위치한 표에서 7개 의 데이터를 가지고 예측모델을 통해 분석한 결과, 예측모델은 아래의 표와 같은 예측을 내놨다. 평균 낙찰 금액은 138,200,176원(1억3천8백2십만원)의 값을 예측하였다. 실제 낙찰가와 예측모델의 차이는  이므로 약 289만원 의 차이를 나타내었다. 

![image](https://user-images.githubusercontent.com/101695209/170307906-8198cf7b-ad7e-4a9d-9675-990d1a2f17a5.png)
 
오차율은 아래 와 같은 공식으로 구할 수 있는데, 약 2.12%의 오차율을 나타냈다. 이렇듯, 정확한 예측가격은 바탕으로 만든 데이터모델을 제공할 수 있다는 것이 과제의 가장 큰 장점이다.


![image](https://user-images.githubusercontent.com/101695209/170307925-79cbf14f-b2a5-4aa4-a6fe-974a7643f330.png)




![image](https://user-images.githubusercontent.com/101695209/170828385-7dd7fa81-c69c-46ae-b266-11f75aa64923.png)

## 스케줄표
![image](https://user-images.githubusercontent.com/101695209/170307465-82019cf3-a723-4c96-a299-8e319d839bf8.png)


## 팀 구성
|이름|학번|전공 |
|------|---|---|
|이건홍|20085344|빅데이터|
|손주현|20182337|빅데이터|
|김경하|20154309|화학과|

## 공지사항
### 1. 2022년 5월 27일 부로 git 파일 전면 삭제 후 재배치
### 2. 실행방법 안내
 1. projectfinal 폴더에 있는 파일을 전부 다운 받거나, Project_end.zip 파일을 다운받습니다.
 2.  파이참(파이썬 버전 3.9 혹은 3.10)을 사용하여 n_server 파일을 실행합니다.
 3.  http://127.0.0.1:5001/ 접속합니다.
