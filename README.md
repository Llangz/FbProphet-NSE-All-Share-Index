# FbProphet-NSE-All-Share-Index
Tried out the Facebook Open source time series predictor, Prophet, to forecast Nairobi All Share Index
The main challenge I faced was with the Prophet validator (from fbprophet.plot import plot_cross_validation_metric/
fig = plot_cross_validation_metric(df_cv, metric='mape')), got a TypeError (TypeError: cannot astype a timedelta from [timedelta64[ns]] to [int32]),)
