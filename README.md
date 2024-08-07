# 💪 LGAimers - 해커톤
> LG에서 제공한 실제 B2B 고객 데이터를 활용하여 영업 전환 성공 여부를 예측하는 모델 개발

</br>
</br>

## I. 프로젝트 정보 
1. 제작기간
> 2024.02 ~ 2024.02 (25일)

</br>

2. 참가 목적
> 학부 수업을 수강하면서 교수님께서는 "실무데이터는 이렇게 꺠끗하지 않을 것이다. largeP smallN 구조의 데이터를 어떻게 해석하고 인사이트를 도출할 것인지에 대해 항상 고민해야한다." 라고 항상 말씀하셨다. 따라서, 현업으로 가기 전에 나의 분석 역량을 평가하고 더 성장하기 위해 참가했다.

</br>

3. 결과 및 느낀점
> 해당 모델은 마케팅 및 영업 팀이 한정된 자원을 보다 효율적으로 배분하고 매출 상승에 기여할 수 있도록 설계되었다. 우리팀은 결국 Public Score 0.7012를 달성하여, 800여 팀 중에서 134등을 차지하는 성과를 이루어냈다. 이 경험은 데이터 분석 및 모델링에 대한 실질적인 경험을 제공했을 뿐만 아니라, 실제 비즈니스 문제를 해결하는 데 있어 데이터 전처리의 중요성을 깊이 이해할 수 있는 계기가 되었다. 


</br>
</br>

## II. 데이터 분석

1. 데이터 설명
   > 학습데이터: 60000개
   > 제출데이터(평가): 6000개
   > 데이터는 B2B 고객 정보로 구성되어 있으며, 다양한 변수들을 포함하고 있다. 예를 들어, 고객 국가, 비즈니스 유닛, 고객 타입, 제품 카테고리, 응답 시간, 요청 내용 등이 있다.

2. 데이터 전처리
   > 고객 국가 변수의 경우, 번지/도시/국가의 형태로 되어있거나 해석하기 어려운 형태로 존재한다. 따라서, 오른쪽 끝에 있는 값만 가져와서 국가로 새롭게 매핑을 했다. 



2. 모델 설계


