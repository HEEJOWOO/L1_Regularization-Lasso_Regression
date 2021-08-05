# L1_Regularization-Lasso_Regression

L1 Regularization
------------------
  * L1 Regularization은 성능은 유지하며 모델의 coefficients(계수)를 최대한 sparse(희소)하게 만듦
  * sparse model은 실제 이용하는 파라미터의 수가 줄어들어 모델의 압추에도 유용
  * L1 Regularization을 이용하는 Softmax Regression을 Lasso Regression이라고 함
  * Logistic Regression에서 Penalty를 L1으로 설정하면 아래의 cost function을 최소화 하는 solution을 계산
  * cost는 model이 얼마나 분류를 잘하느냐의 Loss와 모델의 L1 norm으로 정의되는 Regularization을 더한 형태로 정의
  * 아래의 식은 분류를 잘하면서도 theta는 sparse하게 학습하라는 것

![image](https://user-images.githubusercontent.com/61686244/128285067-60e6aba8-2fd5-462d-ad9f-60f8666320ab.png)
