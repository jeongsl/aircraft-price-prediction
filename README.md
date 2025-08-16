# aircraft-price-prediction
2020 DaJaVu 프로젝트 3조 : 다중회귀분석을 이용한 비행기 가격 예측

## 분석 목적
비행기 가격을 결정하는 데 영향을 끼치는 변수를 알아보기 위함


## 분석 데이터
[국토교통부 세계항공기 정보](https://www.data.go.kr/data/3048607/fileData.do)
* Y: 단가
* X: 제조사, 비행기 종류, 비행기 크기, 비행기 등급, 엔진 종류, 엔진 수, 생산 수량, 조종석 수, 승객수, 길이, 높이, 운송범위


## 분석 방법
* R-studio : 다중선형회귀분석
* $price = \beta_0 + \beta_1 제조사 + \beta_2 비행기 종류 + \beta_3 비행기 크기 + \beta_4 비행기 등급 + \beta_5 엔진 종류 + \beta_6 엔진 수 + \beta_7 생산 수량 + \beta_8 조종석 수 + \beta_9 승객수 + \beta_{10} 길이 + \beta_{11} 높이 + \beta_{12} 운송범위$


## 분석 결과
비행기 가격에는 승객 수, 운송 범위, 높이가 영향을 미침

![image](https://user-images.githubusercontent.com/128488488/235679980-d5f51244-ba14-42cf-980c-94bb89300c23.png)
![image](https://user-images.githubusercontent.com/128488488/235680150-fc8bf2de-1bc7-42ba-936e-d01bcd8dd8f9.png)

