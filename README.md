# Neural_CF

본 레파지토리는 neural collaborative filtering 모델을 tensorflow 2.0 버전으로 구현한 코드를 이해하고, 학습하기 위해 리팩토링하였습니다.


### 파일 설명 

* data/EDA.ipynb : 데이터 EDA 
* Loader.py      : 데이터 로드 및 전처리 클래스 
* Metric.py      : top@K 메트릭 계산 클래스
* model/NeuMF.py : neural collaborative filtering 모델


### 데이터

* usersha1-artmbid-artname-plays.tsv : lastfm의 음악 스트리밍 데이터  
* 출처: http://ocelma.net/MusicRecommendationDataset/lastfm-360K.html


### 코드 실행 예시
```
python Run.py
```


### 출처
* https://github.com/LeeHyeJin91/Neural_CF


### update
* 작업중

