# Solar-flare-class-prediction
Solar flares represent a powerful and dynamic form of solar activity, serving as a critical indicator of space weather disturbances. In the realm of space weather forecasting, accurately predicting flare classes is essential. This project introduces a more detailed division of the forecasts of different flare classes prediction model utilizing the Random Forest algorithm. The model leverages 24-hour time series data of magnetic field variations within solar active regions to construct predictive samples. By applying Principal Component Analysis (PCA), we assess the temporal evolution of magnetic field characteristics to forecast specific flare subclasses(≥B class, ≥M class, and ≥C class, ≥X class). Each data sample comprises 25 features, including magnetic parameters derived from the Space-weather HMI Active Region Patches (SHARP) and related datasets, along with 8 flare history parameters. The study examines flare events occurring between May 2010 and May 2018, utilizing GOES X-ray flare catalogues from the National Centres for Environmental Information (NCEI). During the model development, ten key feature parameters were identified as inputs through K-Means clustering, based on their significance, gain rate, and coverage. Comparative testing demonstrates that our model out performs traditional machine learning models, achieving an accuracy rate of 0.9091 and a macro-average precision of 0.87. These results highlight the model’s effectiveness in providing more detailed and accurate forecasts across different flare classes.
