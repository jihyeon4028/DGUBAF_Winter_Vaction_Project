# DGUBAF_Winter_Vaction_Project
 동국대학교 비어플 겨울방학 프로젝트 이상거래탐지 3조

## 📌 Data
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## 📌 전체 실행 프로세스
#### 1. LightGBM 설치
#### 2. 라이브러리 불러오기   
#### 3. 데이터 불러오기
#### 4. 탐색적 자료분석 (EDA)
  - 불균형한 데이터
  - 이상치 및 결측치 확인

#### 5. 데이터 전처리 
  - 중복 데이터 제거
  - SMOTETomek Sampling
  - Scaling
  - 이상치 제거
  - 다중공선성 제거
  - 모델 별 변수 선택

#### 6. 모델링
  - 모델 비교
    - Random Forest
    - CatBoost
    - XGBoost
    - LGBM
  - LGBM의 F1-score가 가장 높은 성능

<br>

## 📌 Structure
```python
훠궈  
├── README.md
├── [비어플3조] 이상거래.pdf
├── data  
│    └───creditcard.csv
│          
└── code
     ├───이상거래탐지_EDA.ipynb
     └───이상거래탐지_preprocessing_LGBM.ipynb
    
```
<br>


## 📌 Contributors
<table>
  <tr>
    <td align="center"><b>최솔</b></sub></td>
    <td align="center"><b>박지현</b></sub></td>
    <td align="center"><b>변지형</b></sub></td>
    <td align="center"><b>신수빈</b></sub></td>
</table>
