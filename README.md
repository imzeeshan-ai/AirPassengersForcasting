# AirPassengersForcasting


# <font color = black|red|yellow>**********Time Series Analysis**********</font>

Time series analysis is a statistical technique that deals with time series data, or trend analysis.  Time series data means that data is in a series of  particular time periods or intervals.  The data is considered in three types:

### <b>Time series data:</b>  
A set of observations on the values that a variable takes at different times.

### <b>Cross-sectional data:</b>
Data of one or more variables, collected at the same point in time.

### <b>Pooled data:</b> 
A combination of time series data and cross-sectional data.
<br>

## <font color = darkyellow><b>Terms and concepts:</b></font>
### <b>Dependence:</b> 
Dependence refers to the association of two observations with the same variable, at prior time points.

### <b>Stationarity:</b> 
Shows the mean value of the series that remains constant over a time period; if past effects accumulate and the values increase toward infinity, then stationarity is not met.

### <b>Differencing:</b> 
Used to make the series stationary, to De-trend, and to control the auto-correlations; however, some time series analyses do not require differencing and over-differenced series can produce inaccurate estimates.

### <b>Specification:</b> 
May involve the testing of the linear or non-linear relationships of dependent variables by using models such as ARIMA, ARCH, GARCH, VAR, Co-integration, etc.


## <font color = darkyellow><b>TimeExponential smoothingreenime series analysis:</b></font>
        
This method predicts the one next period value based on the past and current value.  It involves averaging of data such that the nonsystematic components of each individual case or observation cancel out each other.  The exponential smoothing method is used to predict the short term predication.  Alpha, Gamma, Phi, and Delta are the parameters that estimate the effect of the time series data.  Alpha is used when seasonality is not present in data.  Gamma is used when a series has a trend in data.  Delta is used when seasonality cycles are present in data.  A model is applied according to the pattern of the data.  Curve fitting in time series analysis: Curve fitting regression is used when data is in a non-linear relationship. The following equation shows the non-linear behavior:
Dependent variable, where case is the sequential case number.
Curve fitting can be performed by selecting “regression” from the analysis menu and then selecting “curve estimation” from the regression option. Then select “wanted curve linear,” “power,” “quadratic,” “cubic,” “inverse,” “logistic,” “exponential,” or “other.”<br>

### <b>ARIMA:</b><br>
ARIMA stands for autoregressive integrated moving average.  This method is also known as the Box-Jenkins method.
Identification of ARIMA parameters: 
    
### <b>Autoregressive component:</b>
AR stands for autoregressive.  Autoregressive paratmeter is denoted by p.  When p =0, it means that there is no auto-correlation in the series.  When p=1, it means that the series auto-correlation is till one lag.<br>

### <b>Integrated:</b> 
In ARIMA time series analysis, integrated is denoted by d.  Integration is the inverse of differencing.  When d=0, it means the series is stationary and we do not need to take the difference of it.  When d=1, it means that the series is not stationary and to make it stationary, we need to take the first difference.  When d=2, it means that the series has been differenced twice.  Usually, more than two time difference is not reliable.<br>

### <b>Moving average component:</b> 
MA stands for moving the average, which is denoted by q.  In ARIMA, moving average q=1 means that it is an error term and there is auto-correlation with one lag.
In order to test whether or not the series and their error term is auto correlated, we usually use W-D test, ACF, and PACF.<br>
### <b>Decomposition:</b> 
Refers to separating a time series into trend, seasonal effects, and remaining variabilityAssumptions:<br>

### <b>Stationarity:</b> 
The first assumption is that the series are stationary.  Essentially, this means that the series are normally distributed and the mean and variance are constant over a long time period.<br>
### <b>Uncorrelated random error:</b> 
We assume that the error term is randomly distributed and the mean and variance are constant over a time period.  The Durbin-Watson test is the standard test for correlated errors.
