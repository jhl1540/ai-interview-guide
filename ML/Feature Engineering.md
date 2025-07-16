# Feature Engineering
> 작성자: [최고운](github.com/id)   
> 키워드: 

https://wikidocs.net/148349#google_vignette
https://velog.io/@jjb6904/PP-feature-engineering
https://dodonam.tistory.com/387
https://wikidocs.net/185336

## Feature Engineering 이란?
    - 0000
    - 필요성: 0000


## Feature Extraction
### Simple Statistical Derived Feature (기초 통계 기반 파생 변수)
    - 평균(Mean), 합계(Sum), 최댓값(Max), 최솟값(Min) 등 기초 통계량을 계산해 새로운 변수 생성
    - (예) 최근3개월평균구매금액

### Feature Crossing (특성 교차)
    - 둘 이상의 변수 조합으로 새로운 범주형 변수 생성
    - (예) 요일+시간대 결합해 이용건수_주말_오전

### Ratios and Proportions (비율 및 비중 피처)
    - 두 변수 간의 비율이나 구성비 계산
    - (예) 총 이용금액 중 쇼핑 업종 비중, 수익/비용 등

### Trend 변수 파생
    - 0000

### Auto-encoder, PCA 등 이용해 특성 생성
    - 0000

### Embedding vector 추가
    - 0000

### Domain Knowledge 기반 피처 추가
    - 업무 지식 또는 전문가 직관을 활용해 만든 파생 변수

## Feature Selection
### **Filter Method**
    - 
    - 

### **Wrapper Method**
    - Forward Selection
    - Backward Elimination
    - Exhaustive Feature Selection
    - Genetic Algorithm

### **Embedded Method**
    - Regularization with Lasso : 정규화로 중요하지 않은 변수 제거
    - Random Forest Importance, Gradient Boosted Trees Importance : 트리 모델에서 자동 계산된 피처 중요도
    - Information Value : 타겟과의 분포 차이 기반
    
### **Hybrid Method**
    - Recursive Feature Elimination
    - Recursive Feature Addition