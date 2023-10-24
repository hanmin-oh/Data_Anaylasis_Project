# 데이터 분석 프로젝트
## 기획단계 
- 2022년 서울의 아파트 실거래가를 분석하여 집값을 예측하고자 하였다..
- 하지만 서울의 기본적으로 지역에 따른 집값의 차이가 크고 같은 지역 내에서도 고급 아파트의 실거래가의 차이도 크기 때문에 일률적으로 적용해서 집값을 예측하는 것은 정확도가 많이 낮다고 생각하였다. 
- 그래서 동북부의 강북구, 도봉구, 노원구를 묶어서 비교하려고 하였다. 한강과 떨어져 있고 중심 업무지구(강남, 광화문, 여의도) 등과 떨어져 있기 때문에 적당하다고 생각하였다. 
- 1차는 기본적으로 면적(㎢)당 학원 수, 고등학교의 수, 지하철 역의 개수 등을 피쳐로 삼아 집값(면적(㎡)당 가격)을 타겟으로 기본적인 지도학습을 수행할 예정이다.

### 1) 전처리 작업

