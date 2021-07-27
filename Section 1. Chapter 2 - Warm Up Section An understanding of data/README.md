# Understanding of data
### 모델을 학습할 때 영향을 주는 것들
> - y = ax + b
>	> - y: 종속 변수 / x: 독립변수
>	> - a, b: 알고리즘을 통해 최적값 도출   

> - Feature
>	> - 머신러닝에서 **데이터의 특징을 나타내는 변수**
>	> - 테이블의 Column 의미
>	> - 하나의 data instance(실제 데이터) → feature vector로 표현   

> - y = ω1X1 + ω2X2 + ω3X3 + ... ω0X0 = ∑ωιXι = w(T)X   

### 차원의 저주(Curse of dimensionality)
> - 데이터의 차원이 증가할 수록(feature가 증가할 수록) **데이터를 표현하는 공간이 증가**
>	> - 희박한 벡터가 증가(값이 없는 feature가 늘어남)
>	> - 샘플데이터가 급속도로 늘어남
> - **데이터 분포나 모델 추정의 어려움 발생**

### Data types
####연속형 값 vs 이산형 값
> - **continuous**(연속형): 연속적인 값, 일반적으로 실수 값
> - **discrete**(이산형): 비연속적 값, Label로 구분 되는 값   

#### Numeric Types
> - 정량적으로 측정 가능한 data type
> - 일반적으로 정수 혹은 실수 형태
> - Interval-scaled type(단위가 있는)
> - Ratio-scaled type(비율이 있는)   

#### Nominal Types
> - 범주로 측정 가능한 data type
