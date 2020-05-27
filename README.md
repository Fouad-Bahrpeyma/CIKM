# CIKM
Data for CIKM:
The Data including the series as well as their characteristics can be accessed via the following link:
https://drive.google.com/drive/folders/12DfKOkdePtltCN5761BKX6oYRwGc83GM?usp=sharing

The data, in current form, do not any preprocessing, cleaning or aggregation.
<br/>
The time series are provided in json files where the data and information stored in an XML format. The data can be loaded using a json reader software or C/python/java/... library.
Each entry in the json files contain the following information:

<br/>
*ID* indicates the id of a specific time series.
<br/>
*modelType* shows the way through which the time series components are combined with the same order as shown in the paper.
<br/>
*noiseType* shows the type of the model, 0:fGn, 1:fBm, and 2:mBm.
<br/>
*nSamples* indicates the number of samples in the time series.
<br/>
*_scaleCoeff* indicates the scale of the time series.
<br/>
*_signal1* contains the final time series, *_signalT* contains the trend, *_signalS* contains the seasonal component and *_signalI* contains the irregular component.
<br/>
Also *trendConf* and *_seasonalConf* provide details about the configuration of the trend and seasonal component, respectively.
<br/>
