# ML & LLM Portfolio

A collection of machine learning and LLM projects completed during my Master of Information and Data Science (MIDS) program at UC Berkeley.

---

## Projects

### AI-Powered CBT Journal (Capstone)
A RAG-based journaling application that retrieves relevant Cognitive Behavioral Therapy context and generates fast and personalized reflections using a locally hosted LLM. Features vLLM optimization with prefix caching, AWS SageMaker deployment, and a Bedrock knowledge base.

**Tech:** Python, LangChain, FastAPI, AWS (SageMaker, Bedrock, Elastic Beanstalk), vLLM, Quantization, KV Caching

[View Repository →](https://github.com/symptl/ai-powered-cbt-rag-journal)


### Yelp Two-Tower Recommender
A neural recommender system predicting user ratings using a two-tower architecture with pooled SBERT embeddings from review corpora as a content-based filtering approach. Designed for two-stage production deployment: dot product similarity enables fast vector search for candidate retrieval, followed by FFNN reranking for precision. Learnable entity embeddings address cold-start for new users/businesses (when collaborative filtering can fail). Achieves ~80% RMSE reduction vs. matrix factorization.

**Tech:** Python, Tensorflow, Keras, Sentence Transformers (SBERT), Embeddings

[View Repository →](https://github.com/symptl/yelp-two-tower-recommender)


### Flight Delay Prediction at Scale
A PySpark ML pipeline in Databricks predicting flight delays across 30M DOT/NOAA records (2015-2019). Engineered novel features including preceding flight delays (via tail number tracking) and airport graph centrality metrics, which emerged as top predictors across all models. Time-series cross-validation with 2019 holdout preserves temporal ordering. Classification (whether a delay is > 15 minutes) achieves AUC 0.82 / F1 0.76; regression RMSE 43.81 minutes.

**Tech:** PySpark, Databricks, Spark ML, XGBoost, TensorFlow/Keras, NetworkX

[View Repository →](https://github.com/symptl/flight-delay-prediction-big-data)

---

### More to come, stay tuned!

---

## About Me

ML Engineer with 6 years of experience in biotech automation and a recent graduate from UC Berkeley MIDS (Master of Information and Data Science). Background in biomedical engineering (UNC, UCSD) with expertise in production ML systems, LLM deployment, and data infrastructure.

[LinkedIn](https://linkedin.com/in/shyam-patel-data)
