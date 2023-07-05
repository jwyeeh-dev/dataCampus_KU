# 7월 5일 NLP 강의 필기

## 인공지능 적용 분야
- 최근 인공지능이 들어가지 않는 분야가 없다.

- 일종의 '인프라'로써 평가하는 사람들도 있다.

- AlphaGo : Reinforcement Learning + Supervised Learnings

- 의료계는 AI에 대한 신뢰도가 떨어짐. 오류가 있을 수 밖에 없기 떄문이다. 이상한 말을 생성하거나 정밀도 측면에서 문제가 있음.

- 인식 오류가 많다. 인공지능은 데이터 싸움이라고 볼 수 있는데, 라벨링의 문제 혹은 데이터의 부족으로 인하여 발생할 수 있는 오류이다. 

## 머신러닝/딥러닝 기술 향상

- 빅데이터 : 금융,마케팅 데이터, IoT 데이터, 모바일 데이터, ...
- 하드웨어의 발전 : 
- 알고리즘 고도화 : 

- 3가지 기본적인 구조
    1. DNN (-> CNN, LSTM)
    2. CNN
    3. RNN 

- Seq, Transformer ... : 추가적인 

- GPU 장비가 필요함. -> 연산 속도가 매우 빠름. 

- ChatGPT 도움을 받으시기도 함. 
- 일반적인 질문에 대해서도 대답을 잘한다는 것을 확인할 수 있다. 

- 물류 : 자동화 로봇 -> Amazon 

- 뇌를 수학적으로 모방한 Perceptron -> 여러가지 변수를 하나의 출력으로 제공하는

<img width="700" alt="스크린샷 2023-07-05 오전 10 51 18" src="https://github.com/jwyeeh-dev/dataCampus_KU/assets/99489807/16b4569c-06c2-4f3c-8510-598987de06df">


- 이러한 뉴런이 여러개가 한번에.

- input / hidden / output

- ANN은 히든레이어가 1개. DNN은 히든레이어가 많음(최소 26개~34개).

<br>

[tensorflow playground](http://playground.tensorflow.org/)

<img width="700" alt="스크린샷 2023-07-05 오전 10 52 57" src="https://github.com/jwyeeh-dev/dataCampus_KU/assets/99489807/8ec1f7e7-b3b7-4b7b-84b0-edff820adce7">

</br>

- 인공지능은 구분하는 능력이 존재한다. 
- Classification : 구분하기.
- Regression : 값 맞추기

### 성능 높이는 방법.
1. 뉴런 늘리기.
2. 히든레이어 늘리기.
    - 고차원의 문제를 세밀하게. -> weight * param metrix

### 어떻게 Weight와 Cost를 비교할 수 있을까?

Difference가 가장 minimize된다면 -> 가장 베스트인.

- layer가 늘어나면 chain dif 진행. -> back-propagation (w를 조금씩 바꾼다.)
- Attention 


### 머신러닝의 개념
- 기계가 스스로 데이터 패턴을 찾고 학습하며 모델을 최적화하는 기술
    1. Traditional Programming
    

    2. Machine Learning 

        어떤 데이터가 될 확률을 의미하는 형태가 된다. -> ML

- DL 트렌드 : [PaperWithCode](https://paperswithcode.com/)

- 현재 파이토치 우세. 

- 딥러닝 공부 : [Edwith](https://edwith.org)

