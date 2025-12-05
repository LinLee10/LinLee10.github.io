# Collin Lee’s Portfolio I build high impact data solutions across agent evaluation, NLP, and data engineering. Here are selected research experiences and projects. <p align="center"> <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYnBlZ3diMTU3ZG42YXJ2NjduMDU3c3RqM3R4MDlzNWhnNTg0YnFqNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/i45P7BemKpvpu/giphy.gif" alt="Pokemon" width="300" /> <img </p> ***


## Research experience

* **OSWorld v2 agent benchmark research**  
  * Researcher on OSWorld v2, a next generation benchmark suite for real world LLM computer use agents with BAIR. Design long horizon desktop workflows with full task configuration, VM checks, and automatic scoring so agents are evaluated on realistic sequences rather than single clicks, and study evaluation stability and exploit resistant task structures.

* **MedHive 510k knowledge graph QA**  
  * [MedHive FDA 510k Medical Device Knowledge Graph QA](https://github.com/LinLee10/MedHive510k_KnowledgeGraph_QA) Python and Neo4j pipeline that turns FDA 510k device PDFs into a structured knowledge graph with subject predicate object triples aligned to a custom device ontology, enabling Cypher question answering over devices, indications, and manufacturers plus embeddings that propose SAMEAS links across submissions.

Links: [MedHive poster](https://docs.google.com/presentation/d/1dnmPos8YzpEr1x9waxknjIxrBJ_SUchz/edit?usp=sharing&ouid=104640654789902592392&rtpof=true&sd=true)

* **Financial news sentiment analyzer**  
  * [Stock news Sentiment Analysis](https://github.com/LinLee10/Stock_news) transformer based pipeline that classifies Bloomberg style financial news into positive, neutral, or negative sentiment per ticker. Fine tunes DistilBERT on labeled financial text, benchmarks against bag of words baselines, and produces finance specific sentiment time series that support event study style analyses of earnings and policy news.

* **CSR greenwashing detection**  
  * [Greenwashing in Corporate Sustainability Statements][csrgreen] UC Berkeley NLP research project that classifies corporate sustainability statements as Genuine, Mixed, or Greenwashing, implementing TF IDF Logistic Regression, Ordinal Regression, and BERT fine tuning. Improves accuracy from a majority baseline to 0.99 on held out data, with confusion matrix analysis and feature importance views for interpretability.

* **Fung Fellowship, EarthTeam**  
  * Worked with EarthTeam and high school interns to analyze environmental questions near schools, translating messy community datasets into clear, community facing insights and recommendations.
  * Built a lightweight, reproducible workflow for cleaning, joining, and analyzing multi source environmental data in Python and SQL.
  * Mentored student analysts through scoping, debugging, and interpretation, improving team consistency and confidence in results.
  * Communicated findings in concise writeups and presentations for non technical audiences.

Links: [Slides](https://drive.google.com/drive/folders/1OaJtdjYCFR23Ns3QCkTPv-6Q46DLShaC?usp=sharing)

***

## Projects

* **Agent security vulnerability evaluation**  
  * [AgentVulnBench][agentvuln] AI agent security benchmark that loads vulnerable and fixed Python functions from the CyberNative dataset and evaluates GPT 4 class models on repairing real code vulnerabilities. Combines an LLM judge, Bandit based static analysis, and sandboxed execution checks into one metrics pipeline that scores similarity, vulnerability removal, execution, and cost, with a FastAPI web dashboard and a green scoring agent for live experiments.

* **NYC taxi analytics pipeline on Google Cloud**  
  * [Nyc taxi analytics pipeline on Google Cloud](https://github.com/LinLee10/Nyc_Taxi_Data_Bigquery_Pipeline) NYC taxi analytics project that builds a BigQuery warehouse with bronze, silver, and gold tables scheduled in Dataform. Produces daily trip facts, zone flows, vendor metrics, and data quality snapshots using schema contracts and assertions for nulls, allowed values, time gaps, and row deltas so downstream analytics work with clean and reliable data.

* **Community air sampler data and 6PPD Q dashboard**  
  * [Community Air Sampler Data and 6PPD&#45;Q Dashboard](https://drive.google.com/drive/folders/1OaJtdjYCFR23Ns3QCkTPv&#45;6Q46DLShaC?usp=sharing) ELT that lands field forms, GPS traces, lab CSVs, and weather data into a validated warehouse with geospatial joins. Hotspot models and an auto refreshed public dashboard deliver school level exposure summaries, with QC logs linking each barcoded filter to time and place.

* **SQL interpolation and outlier detection**  
  * [Interpolation Outlier Detector SQL](https://github.com/LinLee10/Interpolation_Outlier_detector_SQL) three stage PostgreSQL pipeline that uses window functions and CTEs to fill all sub hour gaps and flag three sigma anomalies in sensor data streams, supporting automated integrity checks for real time monitoring systems.

* **Time series rainfall forecasting with LSTM**  
  * [Time Series Analysis and Forecasting](https://github.com/LinLee10/Time-Series_Forecasting-Rain) sequence modeling project that trains an LSTM on sliding windows of multi station rainfall data to predict next day rainfall. Achieves RMSE around 0.48 inches and R squared of 0.86 on held out data, outperforming a persistence baseline and inspecting residuals across different storm patterns.

* **Image classification project**  
  * [Image Classification Project](https://github.com/LinLee10/Image_Classification_project) transfer learned MobileNetV2 in Colab to classify ten custom image categories, reaching 91 percent validation accuracy in under twenty epochs with real time training visualization and experiment tracking through Weights and Biases.

* **Regression exploration**  
  * [Regression Exploration](https://github.com/LinLee10/Regression_Exploration/tree/main) EDA and regression study using Linear, Ridge, and Lasso models on a real world dataset. Engineers polynomial features to reach R squared of 0.78 and RMSE of 2.4, with clear comparisons of bias variance tradeoffs and interactive visualizations.
