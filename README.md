# 👋 Collin Lee’s Portfolio

I build high impact data solutions across agent evaluation, NLP, and data engineering. Here are a few highlights from research, security, and pipelines.

<p align="center">
  <img
    src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYnBlZ3diMTU3ZG42YXJ2NjduMDU3c3RqM3R4MDlzNWhnNTg0YnFqNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/i45P7BemKpvpu/giphy.gif"
    alt="Pokemon"
    width="200"
  />
  <img
    src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMXU2b3VhaHN2eW81Z2J4cnNtZng4NHhqcHRnY3VrY3VvMmFpcmw0byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/139eZBmH1HTyRa/giphy.gif"
    alt="Pikachu dancing"
    width="200"
  />
</p>

***

## Agentic security and evaluation

* **Code vulnerability and security agent**  
  [AgentVulnBench][agentvuln] security evaluation framework that loads vulnerable and fixed Python functions from the CyberNative dataset and tests GPT, Claude, and Gemini agents on repairing real code vulnerabilities. Combines LLM judging, Bandit based static analysis, and sandboxed execution checks into one metrics pipeline that scores whether each proposed fix compiles, reduces issues, and stays close to a reference patch. Ships a FastAPI web dashboard and an AgentBeats style green agent so users can run experiments from a browser or command line and see live progress, metrics, and side by side code comparisons.  
  Stack: Python, OpenAI, Anthropic, Gemini, Bandit, FastAPI.

* **OSWorld v2 agent benchmark research**  
  Contribute tasks and evaluation code to OSWorld v2, a next generation benchmark suite for real world LLM computer use agents with BAIR Lab. Design long horizon desktop workflows with full task configuration, VM checks, and automatic scoring so agents are evaluated on realistic sequences rather than single clicks, and study robustness and exploit resistant task structures for stable evaluation.

***

## Research grade NLP and knowledge graphs

* **MedHive 510k knowledge graph QA**  
  [MedHive FDA 510k Medical Device Knowledge Graph QA](https://github.com/LinLee10/MedHive510k_KnowledgeGraph_QA) Python and Neo4j pipeline that turns FDA 510k device PDFs into a structured knowledge graph with subject predicate object triples aligned to a custom device ontology. Supports Cypher question answering over devices, indications, and manufacturers, with embeddings that propose SAMEAS links across submissions to improve coverage and consistency.

* **CSR greenwashing detection**  
  [Greenwashing in Corporate Sustainability Statements][csrgreen] UC Berkeley NLP research project that classifies corporate sustainability statements as Genuine, Mixed, or Greenwashing using TF IDF Logistic Regression, Ordinal Regression, and BERT fine tuning. Improves accuracy from a 0.52 baseline to 0.99 with confidence interval evaluation, confusion matrix diagnostics, and feature importance views for interpretability.

* **Financial news sentiment analyzer**  
  [Stock news Sentiment Analysis](https://github.com/LinLee10/Stock_news) transformer based pipeline that classifies Bloomberg style financial news into positive, neutral, or negative sentiment per ticker. Fine tunes DistilBERT on labeled financial text with careful train dev test splits, benchmarks against bag of words baselines, and produces reusable sentiment by ticker time series for event study style analyses of earnings and regulatory news.

***

## Data engineering and analytics pipelines

* **NYC taxi analytics warehouse on Google Cloud**  
  NYC taxi analytics project that builds a BigQuery warehouse with bronze, silver, and gold tables scheduled in Dataform. Produces daily trip facts, zone flows, vendor metrics, and data quality snapshots using schema contracts and assertion suites for nulls, allowed values, time gaps, and row deltas, while benchmarking partition and clustering choices to control cost and runtime.

* **Community air sampler data and 6PPD Q dashboard**  
  [Community Air Sampler Data and 6PPD Q Dashboard](https://drive.google.com/drive/folders/1OaJtdjYCFR23Ns3QCkTPv&#45;6Q46DLShaC?usp=sharing) ELT that lands field forms, GPS traces, hourly sensors, and lab CSVs into a validated warehouse with geospatial and weather joins. Hotspot models and an auto refreshed public dashboard deliver school level exposure summaries, with quality control logs linking each barcoded filter to time and place for cohort comparisons.

* **SQL interpolation and outlier detection**  
  [Interpolation Outlier Detector SQL](https://github.com/LinLee10/Interpolation_Outlier_detector_SQL) three stage PostgreSQL pipeline that uses window functions and CTEs to fill all sub hour gaps and flag critical three sigma anomalies in sensor streams. Supports real time integrity checks so downstream analytics work with complete and trustworthy time series.

***

## Core modeling and ML experiments

* **Time series rainfall forecasting with LSTM**  
  [Time Series Analysis and Forecasting](https://github.com/LinLee10/Time&#45;Series_Forecasting&#45;Rain) sequence modeling project that trains an LSTM on sliding windows of multi station rainfall data to predict short horizon rainfall. Tunes sequence length, hidden size, and training schedule, then benchmarks against a persistence baseline and inspects residuals across storm patterns to understand where the model breaks.

* **Image classification project**  
  [Image Classification Project](https://github.com/LinLee10/Image_Classification_project) transfer learned MobileNetV2 in Colab to classify ten custom image categories, reaching 91 percent validation accuracy in under twenty epochs with training visualizations and experiment tracking through Weights and Biases.

* **Regression exploration**  
  [Regression Exploration](https://github.com/LinLee10/Regression_Exploration/tree/main) end to end EDA and regression study using Linear, Ridge, and Lasso models on a real world dataset. Engineers polynomial features to reach R squared of 0.78 and RMSE of 2.4, with interactive visualizations and clear documentation of model behavior.

[agentvuln]: https://github.com/LinLee10/AgentVulnBench  
[csrgreen]: https://github.com/LinLee10/CSR&#45;Greenwashing&#45;Detection
