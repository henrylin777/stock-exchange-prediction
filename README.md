# stock-exchange-prediction

JPX stock exchange price prediction via XGboost.

<br><br>

## Feature Engineering 

經過許多次的實驗，主要採用的 Feature 如下

* stock id
* Open, High, Low, Close
* Volume
* High - Low
* Open - Close
* Year, Month, Day
* MA5, MA10, MA15
* Bias5, Bias10, Bias15
* Bias_vol_5, Bias_vol_10, Bias_vol_15
* Bias_open_5, Bias_open_10, Bias_open_15 
* Bias_high_5, Bias_high_10, Bias_high_15

再加入一些零星的features，最後共有 27 個 features

<br><br>

