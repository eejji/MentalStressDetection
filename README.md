# MentalStressDetection
WESAD 데이터 세트를 사용하여 정신적 스트레스 분류 

- 대학교 프로젝트 수업의 자유주제로 ECG신호와, 스펙토그램을 이용한 합성곱신경망 기반 정신적 스트레스 분류 비교를 진행하였습니다.
이 링크에 좋은 연구를 하신 분이 계셔서 소개 합니다.
#### https://github.com/Edouard99/Stress_Detection_ECG


## 데이터 구축
- 데이터는 버터워스필터를 적용한 후 윈도우 100, 200, 300, 400의 구간에 따라 더 성능이 높은 구간을 찾은 뒤 그 구간의 필터링된 신호와 스펙토그램으로 추출 하였습니다.


### 3초 동안 기록된 ECG 정상 신호
![image](https://github.com/eejji/MentalStressDetection/assets/124345335/9f312fc2-a9f6-4d79-83ed-e32d3c584feb)
