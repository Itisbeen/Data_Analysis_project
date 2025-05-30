# 비트코인과 전통자산간의 동적 상관관계 분석

### 암호화폐 가격의 동적 상징성의 변화


서론 : 암호화폐과 전통 자산간의 상관관계는 없거나 미약한것으로 확인됨
2009년 암호화폐 발행 이후 2025년 현재까지 암호화폐의 가격은 우상향하였으며, 경제 시장에도 많은 영향을 끼치는 지표중 하나로써 이해된다.
16년이라는 기간동안 암호화폐에 대한 관심이 점진적으로 증가하였고, 특정 기간 속에서 위험자산으로써 외부 요인에 의해 쉽게 변동하는 모습을 보인 바
시계열 데이터인 가격 지표를 동적 기간에 따라 구분하고, 타 자산간의 상관관계를 분석하여 시간에 따른 비트코인의 역할 변화를 정량적으로 분석하기 위함이다.


연구 방법 : 
연구에 사용된 자산 가격 데이터의 경우, 지속적인 화폐 가치의 하락으로 우상향 하는 모습을 보이며 이것을 일종의 추세로 판단한다.
가격지표는 정상성(Stationarity) 를 띄지 않고 정규분포를 보장하지 않기에, pearson 상관계수를 사용함에 무리가 있다.
이에 가격 데이터를 로그 차분을 통해 수익률로 변환하여 추세를 제거하고, 정상성을 확보한 뒤 pearson 상관계수를 사용하여 전체 데이터에 대한 상관관계를 파악하고 시각화.

-----중간 보고까지의 내용-----

차후 연구 : 수익률 데이터를 기간에 따라 나눈 뒤, 타 자산간의 관계를 파악한다. 이를 시각화하고 정량적 분석 예정


Preferences
1. 이은주. "비트코인과 주요 자산 간 상관관계 분석: 금, 주식, 달러와의 비교." 국내석사학위논문 고려대학교 정책대학원, 2025. 서울
2. 2. Bitcoin: Medium of exchange or speculative assets?
