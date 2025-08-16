# Steel-Industry-Energy-Consumption-Prediction
End-to-end ML pipeline to predict steel industry energy consumption. Ingests plant telemetry, imputes missing values, caps outliers, encodes categoricals and engineers lag/rolling features. Selects features via mutual information and RFE, preprocesses data, benchmarks models incl. XGBoost, tunes with CV, reports RMSE/MAE/R² and saves artifacts.
