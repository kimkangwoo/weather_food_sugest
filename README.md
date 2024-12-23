# 날씨 기반 음식 추천(weather_food_sugest)

| 이름   | 역할       |
|--------|------------|
| 김강우 | 팀 리더     |
| 손준호 | 개발자     |
| 김동영 | 디자이너   |
| 조해수 | 마케터     |


**프로젝트 가설 설정**
본 프로젝트는 날씨와 음식 간의 상관관계를 탐구하기 위해 시작되었습니다. 우리는 날씨가 음식 선택에 미치는 영향을 가정하고, 이를 검증하기 위한 데이터를 수집하기로 하였습니다.

**데이터 수집**
서울시의 특정 구 6곳에서 NAVER map을 활용하여 크롤링한 결과, 총 100만 여개의 음식점 리뷰와 기상청의 일일 기상 데이터를 확보하였습니다. 추가적으로, 빅데이터 플랫폼에서 크롤링한 댓글 데이터를 통해 더 많은 정보를 얻었습니다.

**데이터 분석**
수집한 데이터를 분석한 결과, 비 오는 날에는 국수 관련 음식점의 방문 수가 증가하는 경향이 있었습니다. 또한, 서울의 300여 개 음식점을 기반으로 한 분석에서, 양식 음식점의 방문 수가 가장 높게 나타났습니다. 계절별로는 봄에 음식점 방문 수가 가장 많았으며, 가을에는 가장 적은 수치를 기록했습니다.

**머신러닝 모델 학습**
PYCARET을 사용하여 수집한 데이터를 학습한 결과, 특정한 패턴을 발견하기에는 한계가 있었습니다. 최고 정확도는 34.5%로 나타났으며, 이는 날씨와 음식 간의 연관성이 매우 낮음을 시사합니다.

**결론**
결론적으로, 날씨와 음식 간의 직접적인 연관성은 미미하나, 이 데이터를 효과적으로 활용한다면 사용자에게 가벼운 음식 추천 서비스를 제공하고, 배달 서비스의 품질을 향상시킬 수 있을 것으로 기대됩니다. 앞으로의 연구에서는 추가적인 변수나 다른 접근 방식을 통해 보다 높은 정확도를 목표로 해야 할 것입니다.


### [날씨 기반 음식 추천 PDF](./김치찌개/오늘%20뭐%20먹지.pdf)