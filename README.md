# A-Comparison-of-Economic-Trends-in-Korea-and-the-United-States

### Summary
현재 우리나라의 경제는 COVID-19 바이러스로 인해 민간 소비와 수출이 큰 폭으로 위축되며 0.2% 성장한 후,
2021년 양호한 회복세를 나타낼 전망이다. 경기 위축과 유가 하락 등이 겹치면서 물가 상승률 또한 낮게
유지 될 것으로 전망된다.

한국의 대미 수출 상품 구조가 저가의 공산품에서 자동차, IT제품 등 고가의 내구제 중심으로
변화됨에 따라 한국의 대미 수출 증가율이 이전에 비해 미국경기와 더욱 밀접한 관계를 맺게 되었다.
또한 2000년 이후 한국 금융시작의 대외 개방이 가속화됨에 따라 국내 자본 시작의 외국인 투자
비중과 영향력 역시 증가되는 추세이다.

따라서 한국증시(Kospi), 미국증시(DJI), 원달러 환율을 통해 한국과 미국의 경제 동향에 대한 비교 및 LSTM을 통해 간단한 예측을 실습한다.


### Implementation
*Requirements*
- python3
- tensorflow
- numpy
- seaborn
- matplotlib
- pandas

### REFERENCE
"Data"
- Kospi : https://www.kaggle.com/gomjellie/kospi-price-data
- DJI : https://stooq.com/q/d/?s=%5Edji&c=0&d1=20140101&d2=20170707
- Won/Dollar exchange rate : https://www.kaggle.com/biokpc/us-korean-exchange-rate/data

"Documents"
- 서지용(2008), 한국 주식 수익률과 글로벌 영향요인과의 관계변화에 관한 연구, 산업경제연구 제21권 제5호
- 티스토리, 블로그, https://aidalab.tistory.com/m/41
- 권상기 외 1명(2020), 토닥토닥 파이썬 - 머신러닝,https://wikidocs.net/book/2383
- 권상기 외 1명(2020), 토닥토닥 파이썬 - 시계열 회귀를 위한 딥 러닝 (텐서플로우 v1), https://wikidocs.net/book/2920
- Hvass-Labs, TensorFlow-Tutorials, 23_Time-Series Prediction, https://github.com/Hvass-Labs/TensorFlow-Tutorials/blob/master/23_Time-Series-Prediction.ipynb
- bKDI 한국개발 연구원 경제전망, 2020 상반기, http://www.kdi.re.kr/forecast/forecasts_outlook.jsp
- 대외경제정책연구원, 미국의 경기변화가 한국 경기에 미치는 영향, http://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE06744420
