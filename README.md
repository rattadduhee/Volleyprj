# Volleyprj

## ✍️ 요약

### 데이터 전처리 및 분석

- 팀명 통일(OK저축은행 → OK금융그룹) 및 팀 코드를 활용한 상대팀 컬럼 추가
- 홈/원정에 따른 경기 결과 분석
- 각 컬럼에 따른 직전 3경기, 5경기에 따른 승률 분석
- 홈/원정 경기장과 직전 3경기 결과에 따른 승률 분석
- 직전 3경기 결과에 따른 상대전적 분석

### EDA 결과

- 공격성공률, 승률에 영향을 미치는 제일 큰 요인은 R포지션을 담당하는 용병 선수의 기량에 따름

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/658e2403-bf77-4f64-8d62-5bc99c7959a1/Untitled.png)

- 공격종합 성공률이 승률에 가장 많은 영향을 미침
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/556d062c-a758-43ff-b982-7ab068c3c8e3/Untitled.png)
    
- 홈/원정 여부는 실제 승률에 영향을 줌

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/22dcff91-3d0c-432c-8f3f-f877f1a20a6f/Untitled.png)

### 모델 예측

![경기성공률.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c563d811-0846-4b7d-b810-7988fe44e649/%EA%B2%BD%EA%B8%B0%EC%84%B1%EA%B3%B5%EB%A5%A0.png)

## 🛠 사용 기술 및 라이브러리

- Python
- Logistic Regression, Decision Tree, Random Forest, XGB, LGBM
