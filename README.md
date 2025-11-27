# 👋 Collin Lee’s Portfolio

I build high-impact data solutions across computer vision, time-series forecasting, NLP, and more. Below are a few highlights:

<p align="center">
  <img
    src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYnBlZ3diMTU3ZG42YXJ2NjduMDU3c3RqM3R4MDlzNWhnNTg0YnFqNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/i45P7BemKpvpu/giphy.gif"
    alt="Pokemon"
    width="200"
  &nbsp;&nbsp;
    src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMXU2b3VhaHN2eW81Z2J4cnNtZng4NHhqcHRnY3VrY3VvMmFpcmw0byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/139eZBmH1HTyRa/giphy.gif"
    alt="Pikachu dancing"
    width="200"
  />
</p>

---

- **Image Classification Project**
- [Image Classification Project](https://github.com/LinLee10/Image_Classification_project)
  Transfer-learned MobileNetV2 in Colab to classify ten custom image categories—reaching **91%** validation accuracy in under 20 epochs, with real-time training visualization and experiment tracking via Weights & Biases.

- **Time-Series Forecasting**
- [Time Series Analysis & Forecasting](https://github.com/LinLee10/Time-Series_Forecasting-Rain)
  Engineered windowed LSTM models to predict next-day rainfall across multiple stations—achieving a **0.48″ RMSE** and **R² = 0.86** on held-out data, outperforming persistence baselines by over 20%.

- **SQL Interpolation & Outlier Detection**
- [Interpolation_Outlier_Detector_SQL](https://github.com/LinLee10/Interpolation_Outlier_detector_SQL)
  Designed a three-stage PostgreSQL pipeline using advanced window functions and CTEs to auto-fill 100% of sub-hour gaps and flag critical ±3σ anomalies, streamlining data integrity workflows for real-time sensor networks.

- **Stock News Sentiment Analysis**
- [Stock news Sentiment Analysis](https://github.com/LinLee10/Stock_news)
  Built an end-to-end FinBERT pipeline that scrapes financial headlines, quantifies sentiment, and backtests trading signals—generating **12.5% annualized returns** vs. **6.3%** buy-and-hold, with automated report generation. STILL IN PROGRESS

- **Regression Exploration**
- [Regression Exploration](https://github.com/LinLee10/Regression_Exploration/tree/main)
  Conducted a full EDA and regression study using Linear, Ridge, and Lasso models on real-world data—engineering polynomial features to hit **R² = 0.78** and **RMSE = 2.4**, complete with interactive visualizations.


- **Community Air Sampler Data & 6PPD-Q Dashboard**
- [**Community Air Sampler Data & 6PPD-Q Dashboard**](#) ELT lands field forms, GPS traces, and lab CSVs into a validated warehouse with geospatial and weather joins. Hotspot models and an auto refreshed public dashboard deliver school level exposure summaries, with QC logs linking each barcoded filter to time and place.     https://drive.google.com/drive/folders/1OaJtdjYCFR23Ns3QCkTPv-6Q46DLShaC?usp=sharing

* Agent security vulnerability evaluation

* [AgentVulnBench][agentvuln] AI agent security benchmark that evaluates GPT 4 class models on fixing Python code vulnerabilities from the CyberNative dataset, with a green agent that scores similarity, vulnerability removal, static analysis, execution, and cost.

* CSR greenwashing detection

* [Greenwashing in Corporate Sustainability Statements][csrgreen] UC Berkeley NLP research project that classifies corporate sustainability statements as Genuine, Mixed, or Greenwashing using TFIDF and a fine tuned BERT model, reaching test accuracy 0.99 versus 0.52 for the majority baseline.

[agentvuln]: https://github.com/LinLee10/AgentVuln&#45;Bench
[csrgreen]: https://github.com/LinLee10/CSR&#45;Greenwashing&#45;Detection

* MedHive 510k Knowledge Graph QA
* [MedHive FDA 510k Medical Device Knowledge Graph QA](https://github.com/LinLee10/MedHive510k_KnowledgeGraph_QA) Built a Python and Neo4j pipeline that turns FDA 510k device PDFs into a structured knowledge graph with subject predicate object triples, Cypher question answering over devices, indications and manufacturers, and knowledge graph embeddings that propose SAMEAS links across submissions to improve coverage and consistency.
