### 뉴욕시 택시 수요 예측  
- 뉴욕시 택시 데이터는 GCP bigquery에서 SQL언어를 이용해 데이터 추출 후 파이썬에서 사용
- 지역 단위 : 뉴욕시에 존재하는 5개 자치구 ( 브르클린, 맨해튼, 퀸즈, 브록스, 스탠튼 섬 )에서 많은 택시가 위치할 것으로 생각되는 맨해튼의 우편번호 기준으로 프로젝트 진행
- 수요 예측 단위 : 수요 예측 단위는 실제 데이터 분포 확인 후 결정 -> 이번 분석에서는 60분을 기준으로 수요 예측 수행


#### 분석 방향
- 데이터 EDA ( 시간 관점 )
- 데이터 EDA ( 지역 관점 )
- 베이스라인 형성 ( 반복 실험을 위한 Sacred 형성 )
