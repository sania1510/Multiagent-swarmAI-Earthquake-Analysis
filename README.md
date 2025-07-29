# **Multi-Agent Swarm Intelligence for Earthquake Analysis & Seismic Risk Zone Prediction**
Research Project | Seismic AI | Swarm Optimization | Anomaly Detection | Risk Mapping
## **Project Overview**

This research project applies Swarm Intelligence algorithms (PSO + ACO) and machine learning to analyze seismic activity, predict earthquake magnitudes and classify seismic risk zones. It combines real-time and historical data from trusted sources like JMA and Kyoshin Network enhancing earthquake risk modeling with intelligent signal denoising, anomaly detection and feature optimization.

## **Key Highlights**

  Hybrid Swarm Intelligence Pipeline: 
    Developed a multi-agent system combining Particle Swarm Optimization (PSO) and Ant Colony Optimization (ACO) to reduce feature space by 47% while preserving critical seismic dependencies.

  Accurate Magnitude Prediction: 
    Trained a PSO-tuned XGBoost model achieving a Mean Absolute Error of 0.0002 and residuals within ±0.1 on magnitude forecasts.

  Seismic Risk Zoning: 
    Built a Random Forest classifier with 100% precision, recall, and F1-score to classify regions into Low / Medium / High risk zones.

   Rare Event Detection: 
    Applied Kalman Filters, Isolation Forest and DBSCAN to denoise signals and identify 705+ rare seismic anomalies.

  Geospatial Risk Mapping: 
    Implemented 10×10 km² grid-based binning to visualize seismic risk zones and improve early warning mechanisms.

 ## **Tech Stack**

    ML Models: XGBoost, Random Forest

    Swarm Intelligence: PSO (feature selection), ACO (path modeling)

    Anomaly Detection: Isolation Forest, DBSCAN

    Signal Processing: Kalman Filter

    Languages & Tools: Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Geopandas

## **Data Sources**

    Japan Meteorological Agency (JMA) – Seismic event data

    Kyoshin Network – Ground motion waveforms (real-time + historical)
