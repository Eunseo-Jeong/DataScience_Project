# DataScience_Project

<div>
        <b>Project name: Heart Disease Prediction (2020.03 ~ 2020.06)</b><br>
        <b>Explanation: 심장병 예측 프로그램 </b><br><br>
        <b> 데이터는 Kaggle에서 가져와 사용했습니다. </b><br>
</div><br>


## Screenshot
#### 1. Introduction
* 심장병을 사전에 예방하거나 미리 예측하기 위한 시스템입니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212279607-b166ed17-d1b2-481a-8ed4-f31e373ce803.png">

#### 2. Data Curation
* 데이터는 Kaggle에서 가져와 사용했습니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212279751-7e68b5c1-d3d2-4dd1-8f00-54eec186e606.png">

* 데이터 사이즈는 다음과 같습니다.<br>
<img width="500" hight="400" alt="스크린샷 2023-01-13 오후 6 04 17" src="https://user-images.githubusercontent.com/64178197/212280807-ecc8bd42-87aa-4570-a71a-88cb3ef5d2a1.png">

* Heatmap을 통해 데이터 간의 correlation을 파악해보았습니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212281105-54dcfb39-f138-4679-9ec7-0f5a95f510e6.png">

#### 3. Data Preprocessing
* 데이터 전처리는 다음 코드처럼 상관관계가 높은 것으로 채워, 결측치 값이 없도록 만들었습니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212281400-4bd168f8-f7c4-41d6-9051-cbfb923cc2e1.png">
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212281561-3840a1cf-7cbf-4d37-a913-aa7265f94da0.png">

#### 4. Data Analysis & Evaluation 
* KNN 모델을 통해 데이터를 분석합니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212282019-598554e4-980a-4e18-92f1-df714689da87.png">

* 이 부분은 가장 정확도가 높은 K값을 구하기 위한 for문 입니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212282081-2826efa4-3c20-43b3-830a-f4ca30f5bcf7.png">

* 각 K값에 대한 정확도를 plot으로 출력한 결과입니다. <br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212282820-2365db80-0caf-4aec-b757-b55cc6e69200.png">

* Logisitc Regression 모델을 통해 데이터를 분석합니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212284149-f5c04b2a-fd74-4b25-9058-501d7e6fba86.png">
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212284358-39fbf875-815b-4da5-9f5e-b503f8ccd022.png">

* Confusion Matrix를 통해 정확도를 측정합니다.<br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212284568-cf2af3b1-3470-4747-a85a-d42012945475.png">

* K-Fold 모델로, KNN 모델/Logisitic Regression 모델을 통해 분석한 결과를 검증합니다. <br>
<img width="500" hight="400" alt="image" src="https://user-images.githubusercontent.com/64178197/212285068-4eff32c5-eedd-45c4-829b-a3f63bbb06d9.png">


<br>
