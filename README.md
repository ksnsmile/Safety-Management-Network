# Safety-Management-Network
## 안전관리망을 개발하는 프로젝트(이 과정들을 국문과 영문으로 나누어서 진행 )

### 주 개발 내용

1. 사고 사례 데이터를 수집

2. 사고 사례 데이터에서 인과 관계 키워드 추출

3. 인과 관계 키워드을 통해 인과 관계 분류
   - 원인 결과 관계에 있는지 판단

4. 인과 관계 키워드 별 관계도 저장
   - 얼마나 키워드 별 관계가 있는지 가중치 계산

5. 대표 키워드 지정하여 키워드 통합

6. 키워드를 이용하여 인과관계 네트워크 시각화

# 국문 개발 핵심

- 키워드를 따로 추출하여 정제하여 키워드 추출

1. SRoBERTa 모델을 통해 벡터화 하였다

2. 명사화한 것과 명사화 하지 않은 것의 차이로 명사화한 것이 네트워크의 복잡성을 줄였다는 것을 보여줌

3. KoELECTRA를 이용하여 인과관계 도출 함
