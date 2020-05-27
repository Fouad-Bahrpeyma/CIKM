# CIKM
Data for CIKM:
The Data including the series as well as their characteristics can be accessed via the following link:
https://drive.google.com/drive/folders/12DfKOkdePtltCN5761BKX6oYRwGc83GM?usp=sharing

We do not need any preprocessing, cleaning or aggregation. I explained it clearly in the thesis and I can a brief explanation is properly provided in the paper. However, as I explained before, we have an original signal which needs to be stationarized first. So we needed to detrend and deseasonalize it. So, for each time series, the dataset has the original time series, trend and seasonality and also detrended and deseasonalized stationary signal. Thus, the dataset contains all the required components for each series. And, this is the strength of our synthetic data.
<br/>
The series are provided in json files where the data and information stored in an XML format. The data can be loaded using a json reader software or C/python/java/... library.
Each entry in the json files contain the following information:
<br/>
<em> _signal1 <\em> contains the final time series.
<em> _signalT <\em> contains the trend, <em> _signalT <\em> contains the trend, <em> _signalS <\em> contains the seasonal component and <em> _signalI <\em> contains the irregular component.
