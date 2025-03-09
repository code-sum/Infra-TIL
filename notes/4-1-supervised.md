### Supervised Learning 과 Unsupervised Learning 의 차이



1. Supervised Learning (지도학습)
   - 특징: **정답(레이블) 있음**. 훈련 데이터에 각 입력에 대한 정답(출력)이 주어짐. 모델은 입력과 출력 간의 관계를 학습.
   - 목표: 주어진 입력에 대해 예측하거나 분류하는 모델을 만드는 것.
   - 예시:
     - 분류(Classification): 이메일이 스팸인지 아닌지를 예측하는 문제.
     - 회귀(Regression): 집의 가격을 예측하는 문제.

2. Unsupervised Learning (비지도학습)
   - 특징: **정답(레이블) 없음**. 모델은 데이터의 패턴이나 구조를 스스로 탐색.
   - 목표: 데이터의 숨겨진 구조나 분포를 이해하거나 그룹화하는 것.
   - 예시: 
     - 군집화(Clustering): 고객을 비슷한 행동을 하는 그룹으로 묶는 문제.
     - 차원 축소(Dimensionality Reduction): 데이터를 더 작은 차원으로 축소하여 중요한 특징을 추출하는 문제.
     - 이상 탐지: 정상적인 패턴에서 벗어난 이상치를 찾는 데 사용. 예를 들어, 신용카드 사기 탐지나 제조업에서 기계의 고장을 예측하는 데 사용될 수 있음.
     - 추천 시스템: 사용자들의 선호도를 군집화하여 비슷한 성향을 가진 사용자에게 맞춤형 제품을 추천하는 데 활용.
   - 알고리즘 예시: K-means Clustering(K-평균 군집화), Hierarchical Clustering(계층적 군집화), PCA(주성분 분석), t-SNE
3. 차이점
   - Supervised Learning 은 입력과 출력이 모두 주어지고, Unsupervised Learning 은 출력(정답)이 주어지지 않음.
   - Supervised Learning 은 예측, 분류 문제를 해결하는 데 주로 사용되며, Unsupervised Learning 은 데이터의 구조를 분석하거나 패턴을 찾는 데 사용.
   - **Unsupervised Learning 이 다룰 수 있는 문제의 범위가 더 넓고, 더 다양한 방식으로 데이터를 분석. 데이터의 구조나 패턴을 스스로 학습할 수 있기 때문에, 라벨이 없는 데이터나 새로운 정보가 계속 들어오는 상황에서 유용함.**