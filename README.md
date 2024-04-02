# 20240403_Salary_Data

Link : https://dacon.io/competitions/official/236230

## Goals
* 개인 특성 데이터를 활용하여 개인 소득 수준을 예측하는 AI 모델 개발
* 수상권 노리기

## Dataset
개인의 소득 수준과 연관된 컬럼들 <br>
train.csv <br>
┣ ID : 학습 데이터 고유 ID <br>
┣ Age : 나이 <br>
┣ Gender : 성별 <br>
┣ Education_Status : 교육 수준 <br>
┣ Employment_Status : 고용 상태 <br>
┣ Working_Week (Yearly) : 연간 근무 기간(주단위) <br>
┣ Industry_Status : 산업군 <br>
┣ Occupation_Status : 직업군 <br>
┣ Race : 인종 <br>
┣ Hispanic_Origin : 히스패닉 출신지 <br>
┣ Martial_Status : 결혼 상태 <br>
┣ Household_Status : 가정 상태 <br>
┣ Household_summary : Household_Status 요약 버전 <br>
┣ Citizenship : 내국인 여부 <br>
┣ Birth_Country : 출생국 <br>
┣ Birth_Country (Father) : 출생국(부) <br>
┣ Birth_Country (Mother) : 출생국(모) <br>
┣ Tax_Status : 맞벌이 & 65세 이상 여부 <br>
┣ Gains : 재산 증가 <br>
┣ Losses : 재산 감소 <br>
┣ Dividends : 배당금 <br>
┣ Income_Status : 소득 수준(중간값 이상 여부) <br>
┗ Income : 1시간 단위 소득(TARGET) <br>
test.csv
<br>
sample_submission.csv

## 평가 방식
RMSE score

진행 기간
2024.03.27 ~ 2024.04.03

## 발표
XGBoost
