Project objective:
To evaluate whether environmental radioactivity exhibits predictable temporal structure and to identify the most reliable statistical model for short-term forecasting.
[unnamed-chunk-21-1.pdf](https://github.com/user-attachments/files/24671149/unnamed-chunk-21-1.pdf)

Key steps and methodology:
	•	Aggregated raw measurements into monthly average activity values
	•	Conducted exploratory analysis using STL decomposition
	•	Performed stationarity testing (ADF & KPSS)
	•	Interpreted ACF and PACF to understand temporal dependence and seasonality
	•	Built and evaluated multiple forecasting models:
	•	SARIMA
	•	ETS (Exponential Smoothing)
	•	TBATS
	•	Used a proper time-based train–test split (2011–2019 train, 2020 test)
	•	Compared models using RMSE, MAE, MASE, and Theil’s U
[unnamed-chunk-27-1.pdf](https://github.com/user-attachments/files/24671165/unnamed-chunk-27-1.pdf)

Key findings:
	•	The Czech Republic dataset showed strong and stable annual seasonality
	•	SARIMA(3,0,0)(1,0,1)[12] achieved the best out-of-sample performance
	•	SARIMA consistently outperformed ETS and TBATS on the test set
	•	Forecasts remained stable and realistic, preserving known seasonal behavior
[unnamed-chunk-24-1.pdf](https://github.com/user-attachments/files/24671167/unnamed-chunk-24-1.pdf)

Outcome:
The project demonstrates that classical statistical time series models, when applied rigorously, can produce reliable forecasts for environmental monitoring data and serve as strong baselines for anomaly detection and policy support.

This work strengthened my understanding of:
	•	time-series diagnostics
	•	model selection beyond in-sample fit
	•	proper forecast evaluation using unseen data
  
[unnamed-chunk-32-1.pdf](https://github.com/user-attachments/files/24671168/unnamed-chunk-32-1.pdf)

Happy to discuss the approach, results, or possible extensions (external regressors, ML models, dashboards).
