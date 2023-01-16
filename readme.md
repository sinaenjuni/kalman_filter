## 1. 평균 필터
- 장점: 
    - 데이터의 개수만으로 쉽게 계산이 가능
    - 평균에 의한 잡음 제거 효과가 있음
    - 실시간 처리에 용이
- 단점: 
    - 

## 2. 이동 평균 필터
- 장점: 
    - 데이터 잡음 제거에 유용
- 단점:
    - 적절한 이동 평균 데이터의 개수 선정 필요
    - 너무크면 노이즈에는 강하지만, 시간 지연에 문제가 있음
    - 모든 데이터에 

## 3. 저주파 통과 필터
- 장점: 
    - 수식이 간단하고 구현하기 쉬움
    - 최근 값의 영향은 크게, 오래된 값의 영향을 지수적()으로 줄임
    - 이동 평균 필터보다 측정 신호의 변화 추이를 더 잘 감지
- 단점:
    - 
    - 