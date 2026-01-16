Project objective:
To evaluate whether environmental radioactivity exhibits predictable temporal structure and to identify the most reliable statistical model for short-term forecasting.

<img width="623" height="430" alt="Screenshot 2026-01-16 at 11 38 00 AM" src="https://github.com/user-attachments/assets/322c29c0-2349-4d5f-b60d-1347012f85c1" />


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

<img width="624" height="429" alt="Screenshot 2026-01-16 at 11 38 16 AM" src="https://github.com/user-attachments/assets/5aa83517-e3ba-4738-8616-267ee5d752cd" />

Key findings:
	•	The Czech Republic dataset showed strong and stable annual seasonality
	•	SARIMA(3,0,0)(1,0,1)[12] achieved the best out-of-sample performance
	•	SARIMA consistently outperformed ETS and TBATS on the test set
	•	Forecasts remained stable and realistic, preserving known seasonal behavior
	
<img width="807" height="487" alt="Screenshot 2026-01-16 at 11 42 13 AM" src="https://github.com/user-attachments/assets/62125032-e578-4d91-b9db-e87ee374d803" />


Outcome:
The project demonstrates that classical statistical time series models, when applied rigorously, can produce reliable forecasts for environmental monitoring data and serve as strong baselines for anomaly detection and policy support.

<img width="788" height="471" alt="Screenshot 2026-01-16 at 11 42 01 AM" src="https://github.com/user-attachments/assets/807d7b6f-e9ca-4783-a5c5-ce4bac84ff25" />


This work strengthened my understanding of:
	•	time-series diagnostics
	•	model selection beyond in-sample fit
	•	proper forecast evaluation using unseen data
	
  <img width="606" height="427" alt="Screenshot 2026-01-16 at 11 38 28 AM" src="https://github.com/user-attachments/assets/a93b50be-74e4-4a41-a106-9b4cd80cfe3f" />



Happy to discuss the approach, results, or possible extensions (external regressors, ML models, dashboards).

<img width="620" height="429" alt="Screenshot 2026-01-16 at 11 38 47 AM" src="https://github.com/user-attachments/assets/5dcc770f-2053-40fc-ad15-a40932bbde2c" />

