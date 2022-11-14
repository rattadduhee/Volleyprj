# 배구 경기 결과 예측 프로젝트
머신러닝을 활용한 배구 경기 결과 예측 프로젝트

## ✍️ 요약

### 데이터 전처리 및 분석

- 팀명 통일(OK저축은행 → OK금융그룹) 및 팀 코드를 활용한 상대팀 컬럼 추가
- 홈/원정에 따른 경기 결과 분석
- 각 컬럼에 따른 직전 3경기, 5경기에 따른 승률 분석
- 홈/원정 경기장과 직전 3경기 결과에 따른 승률 분석
- 직전 3경기 결과에 따른 상대전적 분석

### EDA 결과

- 공격성공률, 승률에 영향을 미치는 제일 큰 요인은 R포지션을 담당하는 용병 선수의 기량에 따름

![1](https://user-images.githubusercontent.com/34684492/200192139-539f3c1e-7c06-4b98-89af-e6ec0874d305.JPG)


- 공격종합 성공률이 승률에 가장 많은 영향을 미침
    
![2](https://user-images.githubusercontent.com/34684492/200192144-2cb52ced-3874-4eb3-a3e1-6b0065487fb2.JPG)
  
  
- 홈/원정 여부는 실제 승률에 영향을 줌

![3](https://user-images.githubusercontent.com/34684492/200192155-a61d7b87-b07f-4414-a216-6747f04aa579.JPG)


### 모델 예측

![경기성공률](https://user-images.githubusercontent.com/34684492/200192162-8dadc9e4-6a1d-42e9-a8fe-e66b7e91bcba.png)


## 🛠 사용 기술 및 라이브러리

- Python
- Logistic Regression, Decision Tree, Random Forest, XGB, LGBM
