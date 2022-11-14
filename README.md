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

## 🖥 담당한 기능

- 홈/원정에 따른 경기 결과 분석
- 각 컬럼에 따른 직전 3경기, 5경기에 따른 승률 분석
- 예측 모델 선정 및 모델 정확도 확인

## 💡 성장한 부분

- BeautifulSoup과 Selenium을 활용한 **데이터 크롤링** 능력 향상
- 경기 결과 예측 성공률을 높이기 위한 새로운 **컬럼 생성**(직전 3경기, 5경기 결과 평균 등)을 통해 다양한 인사이트 도출 능력 향상
- 데이터 EDA를 통한 **유의미한 feature** 선정을 통해 **모델 정확도 개선**
- 다양한 모델(Decision Tree, Random Forest 등)을 확인하여 가장 **정확도가 높은 모델을 선정**하며 모델 선정 인사이트 향상

## 🎈 향후 개선사항

- 모델 선정에 있어 정확도가 가장 높은 모델 하나를 선정하는 것이 아니라 **각 팀 별 정확도가 가장 높은 모델을 선정**하여 적용하여 구현

     👉🏻 각 팀 별 알맞는 모델 선정을 통해 전체 예측 성공률을 높힐 수 있음
