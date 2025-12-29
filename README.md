# Nonparametric-Statistics-Project
통계청 마이크로데이터 5세 미만 영유아 출생-사망 연계자료(2018) 데이터를 활용해 출생아 사망에 영향을 미치는 생물학적/부모의 사회경제적 요인 분석을 진행했습니다.

## 프로젝트 소개
본 연구는 5세 미만 영유아 사망에 영향을 미치는 생물학적 요인(체중 등)과 부모의 사회경제적 요인(연령, 학력, 혼인 상태 등)을 분석한 프로젝트입니다. 
단순히 한 가지 원인이 아닌 복합적인 요인을 규명하고 CART 및 Spline 회귀모형을 통해 사망 고위험군을 조기에 선별할 수 있는 예측 모델을 구축하여 보건 정책적 시사점을 도출하고자 했습니다.

## 분석 프로세스

| 단계 (Phase) | 분석 방법 (Methodology) | 주요 내용 (Key Tasks) |
|-------------|-------------------------|-----------------------|
| 분포 비교 | KDE, Kruskal–Wallis Test | 생존·사망 그룹 간 체중 분포 시각화 및 임신 주기 중위수 차이 검정 |
| 유의성 검정 | Wilcoxon Ranksum Test, Permutation Test, Binomial Test | 출생아 생존 여부에 따른 체중 평균 및 중위수 차이 검정 |
| 연관성 분석 | Fisher’s Exact Test | 산모 연령, 부모 학력, 혼인 여부와 출생아 생존 여부 간 연관성 분석 |
| 예측 모델링 | Tree Model (CART), Logistic Spline | 체중, 산모 연령, 부모 직업 등을 활용한 생존 여부 예측 모델 개발 |


## 팀원

| Member |
|--------|
| <a href="https://github.com/iseonjae"><img src="https://avatars.githubusercontent.com/iseonjae" width="80px;" alt="iseonjae"/></a><br/>@iseonjae |
