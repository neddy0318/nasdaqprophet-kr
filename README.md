use this package for predicting nasdaq stock for upcoming 1 year. 

You can see a graph of a specific company's stock data for the past 5 years and one year of future data,
another graph and some metrics for measuring the predictability of the tool (Prophet) in the package,
and also anticipated profit based on the amount of dollors you'd like to invest if you follow the steps below.
(Plz note that the information on anticipated profit will be provided only in Korean).

1. install :

pip install nasdaqprophet

3. import the function

from nasdaqprophet.nasdaqprophet_kr import showmetheprophet

3. use the function :
plz write the name of the company in nasdaq list and the amount of the money(dollors) you'd like to invest
here's an example:

showmetheprophet('TYO', 100)




본 패키지를 사용해 추후 1년 동안의 나스닥 주가를 예측해보세요!

다음의 스텝을 따르면 지난 5년 동안의 주가 데이터 및 추후 1년 동안의 예측 데이터 그래프,
그리고 본 패키지에서 사용한 툴(prophet)의 예측력 테스트 지표들 및 그래프,
입력한 투자금액에 따른 예측 수익률 등을 확인할 수 있습니다.

1. 설치 :

pip install nasdaqprophet

2. 함수 import :

from nasdaqprophet.nasdaqprophet_kr import showmetheprophet

3. 함수 사용 : 나스닥에 기재된 회사명 및 투자 금액(달러) 입력
예시:

showmetheprophet('TYO', 100)

