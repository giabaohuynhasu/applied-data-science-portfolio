# applied-data-science-portfolio
Applied Data Science, Econometrics &amp; Machine Learning Portfolio (Empirical datasets &amp; research framework credited to WorldQuant University)


---

## 📊 Applied Data Science & Econometric Modeling Systems

An end-to-end collection of eight quantitative data science, econometric forecasting, and machine learning systems built on real-world empirical datasets across Latin America, East Africa, South Asia, Central Europe, and North America ([`applied-data-science-portfolio/`](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio)):

| System Module | Empirical Dataset & Domain | Econometric & ML Architecture |
| :--- | :--- | :--- |
| **[01 · Mexican Real Estate Valuation](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/01-mexico-real-estate-analytics)** | `21,000+` residential property listings across Mexican states & Distrito Federal | Multi-source tabular normalization, geospatial Mapbox visualization, regional price-per-$\text{m}^2$ distributions, Pearson correlation analysis |
| **[02 · Buenos Aires Hedonic Pricing Pipeline](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/02-buenos-aires-hedonic-housing-pipeline)** | Urban apartment listings across Capital Federal (`Properati` dataset) | Interdecile outlier trimming, spatial coordinate surface modeling, `OneHotEncoder` neighborhood fixed effects, $L_2$-penalized `Ridge` regression |
| **[03 · Nairobi PM2.5 Air Quality Forecasting](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/03-nairobi-pm25-air-quality-forecasting)** | High-frequency IoT particulate telemetry (`SensorAfrica` Nairobi sensor network) | MongoDB document ingestion, `Africa/Nairobi` timezone localization, 1-hour mean resampling, ACF/PACF diagnostics, $\text{ARMA}(2, 1)$ forecasting |
| **[04 · Nepal Seismic Structural Damage Modeling](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/04-nepal-seismic-structural-damage-modeling)** | Post-2015 Gorkha Earthquake engineering survey across Kavrepalanchok & Gorkha | Multi-table SQLite relational joins, `LogisticRegression` odds ratios, `DecisionTreeClassifier` depth tuning, Gini importance, cross-district transferability |
| **[05 · Corporate Bankruptcy Imbalanced Ensembles](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/05-corporate-bankruptcy-imbalanced-ensemble)** | `64` accounting & liquidity ratios of Polish firms (`<5%` insolvency rate) | Compressed JSON ingestion, `RandomOverSampler` / `RandomUnderSampler`, `RandomForest` & `GradientBoosting` ensembles, Precision-Recall threshold optimization |
| **[06 · U.S. Household Wealth Segmentation](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/06-household-wealth-unsupervised-clustering)** | U.S. Federal Reserve Survey of Consumer Finances (`SCF`) balance-sheet microdata | Credit-constrained household profiling, `StandardScaler` + `KMeans` segmentation, Silhouette diagnostics, `PCA` 2D latent factor extraction, interactive `Dash` app |
| **[07 · Automated NoSQL A/B Experimentation Engine](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/07-ab-experimentation-etl-conversion-engine)** | Digital applicant funnel telemetry & randomized treatment logs | Custom `MongoRepository` ETL pipeline (`extract`, `transform`, `load`), statistical power analysis (`GofChisquarePower`), contingency table Pearson $\chi^2$ testing |
| **[08 · Equity Volatility GARCH(1,1) Microservice](https://github.com/giabaohuynhasu/research-landing/tree/main/applied-data-science-portfolio/08-financial-volatility-garch-microservice)** | Indian equity market daily OHLCV histories (`AMBUJACEM.BSE`, `SUZLON.BSE`) | Test-driven `AlphaVantageAPI` & `SQLRepository` layer, `arch` $\text{GARCH}(1, 1)$ conditional variance estimation, 500-step walk-forward validation, `FastAPI` `/fit` & `/predict` service |

> **Data & Research Attribution:** Empirical datasets, domain problem formulations, and foundational research infrastructure are credited to **[WorldQuant University](https://www.wqu.edu/)** (*Applied Data Science Lab*).
