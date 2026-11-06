# 머신러닝 스터디

**IBAS 머신러닝 스터디 · 사이킷런으로 배우는 머신러닝**

스터디에서 다룬 개념과 실습을 7개 주제로 나누었습니다. 공개 목차에서 확인한 노트 45개를 수록했으며, 각 제목을 누르면 노션 원문이 열립니다.

[공부 기록 전체](README.md) · [노션 스터디 목차](https://deluxe-spatula-f98.notion.site/40a615b8106641d99c4bb64c0f53271e) · [딥러닝 스터디](deep-learning.md)

공동으로 정리한 스터디 자료입니다. 개인 프로젝트의 결과와 구분해 소개하며, 원문에 있는 작성자 표시와 참고자료는 그대로 유지합니다.

## 학습 흐름

데이터 준비와 검증 → 분류 지표 → 트리와 앙상블 → 회귀 → 차원 축소와 군집화 → 텍스트 분석

| 주제 | 노트 수 | 살펴볼 내용 |
|---|---:|---|
| 기초와 검증 | 5 | 학습 데이터를 어떻게 준비하고 성능을 평가할까? |
| 트리와 앙상블 | 10 | 트리 모형을 결합하고 설정을 조정하는 방법은 무엇일까? |
| 분류 응용 | 3 | 고객 만족도와 사기 거래를 어떻게 분류할까? |
| 회귀와 수요예측 | 7 | 수량과 가격을 예측하는 모형은 어떻게 비교할까? |
| 차원 축소 | 2 | 많은 변수를 어떻게 요약할까? |
| 군집화 | 6 | 정답 없이 비슷한 대상을 묶고 결과를 평가하려면? |
| 텍스트 분석 | 12 | 문자를 수치로 바꾸어 분류·유사도·가격 예측에 활용하려면? |

## 기초와 검증

| 원문 노트 | 내용 안내 |
|---|---|
| [사이킷런으로 시작하는 머신러닝(1)](https://deluxe-spatula-f98.notion.site/1-a2d688ccad834d5ebb6e208e79563a17) | 사이킷런으로 시작하는 모델 학습과 예측 |
| [교차 검증](https://deluxe-spatula-f98.notion.site/54865415dee643988918d2820f220f5a) | 학습 자료를 나누어 성능을 확인하는 방법 |
| [데이터 전처리](https://deluxe-spatula-f98.notion.site/a6b53c96316148c78bf442825f128689) | 모형에 입력하기 전 데이터 준비 |
| [분류, 오차행렬, 정밀도 재현율 트레이드오프](https://deluxe-spatula-f98.notion.site/94311ef148b549ea95437c5a2d12ec8c) | 분류 결과를 해석하는 지표와 기준 |
| [F1 Score, ROC-AUC, 당뇨병](https://deluxe-spatula-f98.notion.site/F1-Score-ROC-AUC-d63fd8868b9a44cc97c3364073f620d6) | 분류 평가 지표와 예제 |

## 트리와 앙상블

| 원문 노트 | 내용 안내 |
|---|---|
| [결정 트리의 이해](https://deluxe-spatula-f98.notion.site/77af3868eac4447c8e711bec318a9fab) | 결정 트리의 분할과 예측 구조 |
| [결정트리 과적합 이해 및 사용자 행동인식 데이터를 이용한 결정트리 실습](https://deluxe-spatula-f98.notion.site/ae4ae20282be49fa9119d72d5731db44) | 과적합과 행동인식 데이터 실습 |
| [앙상블 학습 - 보팅과 배깅](https://deluxe-spatula-f98.notion.site/fecb28e749c344248f0989661c5b19b8) | 보팅·배깅과 랜덤포레스트 실습 |
| [Boosting과 XGBoost](https://deluxe-spatula-f98.notion.site/Boosting-XGBoost-1596da19fe87448ab818726db8c8b02b) | 부스팅과 XGBoost |
| [XGBoost를 이용한 위스콘신 유방암 예측](https://deluxe-spatula-f98.notion.site/XGBoost-5bf15d54e85a418b918bbf23b19369de) | XGBoost 분류 실습 |
| [LightGBM 트리 분할 방식](https://deluxe-spatula-f98.notion.site/LightGBM-344492b840ec477c9756802b6a6e73f9) | LightGBM의 트리 구성 |
| [베이지안 최적화](https://deluxe-spatula-f98.notion.site/bb1da25f675f4cb48c7905885b381296) | 하이퍼파라미터 탐색 |
| [HyperOpt 기본실습 및 XGBoost 하이퍼 파라미터 튜닝](https://deluxe-spatula-f98.notion.site/HyperOpt-XGBoost-9aaf51060f9647b685a055dc695407d2) | HyperOpt를 이용한 모형 설정 탐색 |
| [스태킹, Classification Summary, Feature Selection](https://deluxe-spatula-f98.notion.site/Classification-Summary-Feature-Selection-835eacd41401432fb851205574e5a84f) | 스태킹과 분류 정리, 변수 선택 |
| [feature importance가 feature selection 기준이 될 수 없는이유](https://deluxe-spatula-f98.notion.site/feature-importance-feature-selection-bc80c5ead7d540b1a09041587accecd0) | 변수 중요도를 변수 선택에 활용할 때의 쟁점 |

## 분류 응용

| 원문 노트 | 내용 안내 |
|---|---|
| [은행 만족도, 신용 카드 실습](https://deluxe-spatula-f98.notion.site/af2f8b32543a481d9757824e40f07e53) | 고객 만족도와 신용카드 데이터 실습 |
| [분류실습 - 만족예측, 거래사기예측](https://deluxe-spatula-f98.notion.site/1c79183907d5480b97e953319a5592bc) | 만족도·사기 거래 분류 |
| [산탄데르 은행 고객 만족 예측, 신용카드 사기 예측 실습](https://deluxe-spatula-f98.notion.site/beaa163191074df68d4144f3c1aa0fcf) | 분류 문제의 적용 사례 |

## 회귀와 수요예측

| 원문 노트 | 내용 안내 |
|---|---|
| [회귀, RSS와 경사 하강법](https://deluxe-spatula-f98.notion.site/RSS-f3ac04522f554ef0865a10cd23d31037) | 회귀 오차와 모형 학습 |
| [다항회귀의 이해와 다항회귀를 이용한 보스턴 주택가격 예측, 다항회귀를 이용한 과소적합 및 과적합 이해](https://deluxe-spatula-f98.notion.site/ad4e98d2809e402ea59617f968eed96f) | 다항회귀의 복잡도와 과소·과적합 |
| [규제 선형 모델](https://deluxe-spatula-f98.notion.site/55a7a0c222e44da08aee028a0116844d) | 규제를 적용한 선형 모형 |
| [로지스틱 회귀, 회귀 트리](https://deluxe-spatula-f98.notion.site/c87e24be40af4d8ea2fc0ae900ff1020) | 로지스틱 회귀와 회귀 트리 비교 |
| [자전거 대여(공유) 수요 예측](https://deluxe-spatula-f98.notion.site/f381665782b348f5b57ef7b6ec357fd2) | 수요예측 회귀 실습 |
| [회귀 실습 : 주택 가격 예측 - 1](https://deluxe-spatula-f98.notion.site/1-4f8cc398f9fa44888303a7ec17cf0e0d) | 주택가격 예측 실습 |
| [주택가격예측 4, 5, 회귀 Summary](https://deluxe-spatula-f98.notion.site/4-5-Summary-6f53487e29e74f98a60d87b3a858720c) | 주택가격 예측과 회귀 정리 |

## 차원 축소

| 원문 노트 | 내용 안내 |
|---|---|
| [차원 축소 개요 및 PCA 실습(붓꽃 데이터)](https://deluxe-spatula-f98.notion.site/PCA-6061aae6d2804703b68dd2f9130158b0) | PCA의 개념과 붓꽃 데이터 실습 |
| [PCA(신용카드), LDA, SVD, NMF](https://deluxe-spatula-f98.notion.site/PCA-LDA-SVD-NMF-25b2c49862034fe5aeb94d3dca27b4dd) | 차원 축소 방법 비교 |

## 군집화

| 원문 노트 | 내용 안내 |
|---|---|
| [K-Means 군집화의 이해와 실습](https://deluxe-spatula-f98.notion.site/K-Means-3c08e210a1b4440bbf47084605c4fe8c) | K-Means의 구조와 실습 |
| [군집화 실습, 실루엣 분석](https://deluxe-spatula-f98.notion.site/215bffd49fdf46bb8299b8909b5ff0d7) | 군집 결과 평가 |
| [군집별 평균 실루엣 계수의 시각화를 통한 군집 개수 최적화 방법 ~ KDE의 이해와 사이킷런을 통한 MeanShift 군집화 실습](https://deluxe-spatula-f98.notion.site/KDE-MeanShift-0b6ea6ade9d54e2aa1abebe7120269ba) | 군집 수 검토와 MeanShift |
| [GMM 군집화의 이해와 실습](https://deluxe-spatula-f98.notion.site/GMM-51a072c4c251477a8358ea31a2b34df3) | 가우시안 혼합 모형 |
| [DBSCAN 군집화 이해 및 실습](https://deluxe-spatula-f98.notion.site/DBSCAN-8658a039a8324ae7a1758e4e311374e4) | 밀도에 기반한 군집화 |
| [군집화 실습 - 고객 세그먼테이션](https://deluxe-spatula-f98.notion.site/369f57642e7b47edad54ea88a6973145) | 고객 유형을 나누는 응용 |

## 텍스트 분석

| 원문 노트 | 내용 안내 |
|---|---|
| [사이킷런의 주요 피처 벡터화 클래스 소개, 희소행렬의 이해](https://deluxe-spatula-f98.notion.site/644081f32fb04b7c98021c2e830e6e11) | 텍스트 벡터화와 희소행렬 |
| [텍스트 분석의 개요, 실습](https://deluxe-spatula-f98.notion.site/3f938b3d5ac1400da2a37d6279a35875) | 텍스트 분석 입문 |
| [텍스트 분류 실습](https://deluxe-spatula-f98.notion.site/0a138246e737413183736dbc13a2a6d6) | 문서를 분류하는 실습 |
| [감성 분석의 이해와 지도학습기반의 IMDB 영화리뷰 감성분석 실습, 감성어휘 사전기반의 감성 분석 이해와 이를 이용한 IMDB 영화리뷰 감성분석 실습](https://deluxe-spatula-f98.notion.site/IMDB-IMDB-20068f6d333d41aeba7e637d7025de06) | 지도학습과 감성 사전을 활용한 영화리뷰 분석 |
| [토픽 모델링의 이해](https://deluxe-spatula-f98.notion.site/9f6b3f45dcbd4d67a37feab3aff2407b) | 문서의 주제 탐색 |
| [문서 군집화 이해와 실습](https://deluxe-spatula-f98.notion.site/78133fb9f4294a6095258d590f206fde) | 유사한 문서끼리 묶는 방법 |
| [문서 유사도](https://deluxe-spatula-f98.notion.site/f4bf1b88ae8a40d9b952e28c853b5e77) | 문서 간 유사성 비교 |
| [한글 NLP개요, KoNLPy소개](https://deluxe-spatula-f98.notion.site/NLP-KoNLPy-b2c64bf6bc8b48ebb467f5796b02f9a6) | 한국어 자연어 처리 입문 |
| [한글 텍스트 처리 실습](https://deluxe-spatula-f98.notion.site/36b1c829a26d4e4fb5e124b3cd87d256) | 한국어 문서 처리 |
| [텍스트분석 실습 1,2 (1)](https://deluxe-spatula-f98.notion.site/1-2-1-1f16334f175d46e5a4ef2c692f6f1fc3) | 텍스트 분석 응용 실습 |
| [Mercari Price Suggestion - 3, 4](https://deluxe-spatula-f98.notion.site/Mercari-Price-Suggestion-3-4-787b2cea5bb34409818f8834aa5cdd52) | 상품 텍스트와 가격 예측 |
| [Mercari - 5, Summary](https://deluxe-spatula-f98.notion.site/Mercari-5-Summary-e8441a03b71b4169a85a41501ab11ec3) | Mercari 실습 정리 |

## 프로젝트와 함께 보기

- **수요예측**: [유통데이터 프로젝트](https://github.com/zzongzzz47/retail-demand-forecasting)와 함께 회귀, 교차 검증, 자전거 수요예측 노트를 읽을 수 있습니다.
- **트리 앙상블**: [컨테이너 이동 위치 추천](https://github.com/zzongzzz47/yardwise)과 [창고 출고 지연예측](https://github.com/zzongzzz47/amr-delay-prediction)의 모형을 이해할 때 관련 개념을 참고할 수 있습니다.
- **군집화**: [대전 수거함 입지 분석](https://github.com/zzongzzz47/daejeon-medicine-access)과 함께 군집화와 실루엣 분석을 살펴볼 수 있습니다.

학습 노트에 있는 모든 방법을 위 프로젝트에 적용했다는 의미는 아닙니다. 프로젝트별 구현과 결과는 각 저장소의 코드와 보고서를 기준으로 확인합니다.

정리 기준: 2026-11-06. 공개 목차에서 제목을 확인한 45개 노트를 주제별로 연결했습니다. ‘사용 권한 없음’으로 표시된 항목은 목록에서 제외했습니다.
