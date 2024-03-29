# 딥러닝을 이용한 비트코인 가격예측

- 사용한 데이터 : 비트코인 가격데이터 
- 목적 : 비트코인의 향후의 가격을 예측하여 투자를 더 용이하게 만듦.

- 비트코인 가격데이터를 사용한 이유 : 주식가격에 영향을 주는 요소보다 비트코인 가격에 영향을 주는 요소들이 더 적고 수치화 시켜 딥러닝에
  학습시키기에 더 용이할 것이라 판단함. 추가적으로 주식보다 심리적인 요인이 더 크게 작용할 것이라 생각함.
    
- 이전 머신러닝때와 다르게 딥러닝을 이용하여 진행하였고 더 높은 성능이기에 이전보다 오를지 내릴지가 아닌 가격 자체를 예측하는 모델을 진행해 보았음.
- 기존의 데이터를 이용하여 심리적인 정도를 확인할 수 있는 지표들을 추가하여 학습시켜 주었음.

- 결과 : 진행결과 예측가격과 데이터의 실제가격이 거의 동일한 수준임과 더불어 지표들을 추가함으로써 손실률또한 줄어듦을 확인할 수 있었음.
하지만 이는 잘못된 진행이었는데 미래의 가격의 정보가 이미 데이터에 들어있었고 이를 학습한 것이기 때문에 거의 동일한 예측을 한 것이기 때문임.
 이를 해결하기 위해서는 예측하고자 하는 시점의 가격이 아닌 데이터들을 생성하여 학습시켜야 할 것으로 보임.
