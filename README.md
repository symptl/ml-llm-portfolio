# ML & LLM Portfolio

A collection of machine learning and LLM projects completed during my Master of Information and Data Science (MIDS) program at UC Berkeley.

---

## Projects

### AI-Powered CBT Journal (Capstone)
A RAG-based journaling application that retrieves relevant Cognitive Behavioral Therapy context and generates personalized reflections using a locally hosted LLM. Features vLLM optimization with prefix caching, AWS SageMaker deployment, and a Bedrock knowledge base.

**Tech:** Python, LangChain, FastAPI, AWS (SageMaker, Bedrock, Elastic Beanstalk), vLLM, Quantization, KV Caching

[View Repository →](https://github.com/symptl/ai-powered-cbt-rag-journal)


### Yelp Two-Tower Recommender
A neural recommender system predicting user ratings using a two-tower architecture with pooled SBERT embeddings from review corpora. Designed for two-stage production deployment: dot product similarity enables fast vector search for candidate retrieval, followed by FFNN reranking for precision. Learnable entity embeddings address cold-start for new users/businesses. Achieves ~80% RMSE reduction vs. matrix factorization.

**Tech:** Python, PyTorch, Sentence Transformers (SBERT), Gensim (Word2Vec), Google Colab (T4/A100)

[View Repository →](https://github.com/symptl/yelp-two-tower-recommender)

---

### More to come, stay tuned!

---

## About Me

ML Engineer with 6 years of experience in biotech automation and a recent graduate from UC Berkeley MIDS (Master of Information and Data Science). Background in biomedical engineering (UNC, UCSD) with expertise in production ML systems, LLM deployment, and data infrastructure.

[LinkedIn](https://linkedin.com/in/shyam-patel-data)
