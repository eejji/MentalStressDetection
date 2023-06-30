# MentalStressDetection
WESAD 데이터 세트를 사용하여 정신적 스트레스 분류 

- 대학교 프로젝트 수업의 자유주제로 ECG신호와, 스펙토그램을 이용한 합성곱신경망 기반 정신적 스트레스 분류 비교를 진행하였습니다.
이 링크에 좋은 연구를 하신 분이 계셔서 소개 합니다.
#### https://github.com/Edouard99/Stress_Detection_ECG


## 데이터 구축
- 데이터는 버터워스필터를 적용한 후 윈도우 100, 200, 300, 400의 구간에 따라 더 성능이 높은 구간을 찾은 뒤 그 구간의 필터링된 신호와 스펙토그램으로 추출 하였습니다.


### 3초 동안 기록된 ECG 정상 신호
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/9f312fc2-a9f6-4d79-83ed-e32d3c584feb)

### 원래의 신호와 필터링 된 신호
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/895b57f2-d248-4181-bf41-700e22f2818c)

### R-peak 지점 기준 100개, 200개, 300개, 400개 샘플까지 나눈 이미지의 검증정확도
- 테스트 이미지의 정확도로 비교못한 부분에서 아쉬운 점이 있음.
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/648cb065-30ac-4ee1-9353-eb098dd47f3b)


### 필터링 된 신호와 변환된 스펙토그램 
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/9eff52ab-6789-4af9-b845-4661cf4fc440)

### 신호 분류 과정 
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/b0fc14b0-1916-4742-9644-83ba89cf2ac1)


## 모델링

###  CNN 구조 
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/781b1988-40fe-4e0e-8d8b-bbdfa55d9ecd)


## 실험 결과 
### 모델 검증 정확도 비교 
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/1cdc0a23-e7fa-4a35-9e58-dff5c7e6606a)

### 필터링 신호의 이미지 혼동행렬 
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/1474f031-7f2f-4be9-bb23-ff5a01e20396)

### 스펙토그램 이미지 혼동행렬
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/99eedb99-41aa-4bbc-8d75-0e69ac323ec3)


