---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
Accomplished Machine Learning Engineer with over 5 years of industry experience, expertly developing and deploying scalable ML models and GenAI solutions, driving innovation and efficiency across diverse industries.

Education
======
* M.S. in Data Science, Michigan State University, East Lansing, MI — GPA: 4.00/4.00 (08/2022 – 04/2024)
* B.Tech in Civil Engineering, Indian Institute of Technology Roorkee — GPA: 3.26/4.00 (07/2013 – 05/2017)

Work experience
======
* 02/2025 – Present: Sr ML Engineer, Quantiphi (Client: AT&T) — Bedminster, NJ
  * Optimized Agentic AI workflows using DSPy (GEPA), PEFT, and RL, saving $800K/year
  * Benchmarked fine-tuned models' inference performance using GuideLLM to measure throughput (RPS) and p95 latency, informing GPU scaling and deployment strategy for production load
  * Designed an Evaluation Microservice supporting custom LLM-as-a-judge and code-based judges
  * Integrated GRPO, PPO, and GSPO reinforcement learning algorithms into the FTaaS (Finetuning-as-a-Service) platform using Hugging Face TRL
  * Engineered robust RAG evaluation with metrics like Faithfulness, Relevancy, and Context Sufficiency

* 08/2024 – 02/2025: AI Engineer, BYO — New York, NY
  * Implemented Continual Instruction Tuning methods based on SFT and PEFT techniques using DeepSpeed
  * Built RAG Agents using LangChain and Ollama with word and topic guardrails, achieving a 15% improvement in response accuracy through tunable contextual grounding and relevance scoring
  * Developed LLM instruction-tuning pipelines with Dagster, AWS S3, SQS, DynamoDB and Torchserve

* 04/2024 – 08/2024: AI Consultant, Department of Family Medicine, MSU — East Lansing, MI
  * Improved document retrieval recall score by 22% in RAG Agents using AWS Bedrock, OpenSearch, Titan Embeddings, and Claude Sonnet, enhancing search quality and consistency
  * Deployed a scalable ML backend, reducing API response times by 40% using FastAPI, AWS ECR and ECS
  * Built LLM workflows using LangGraph for information extraction
  * Designed information extraction methods using the OpenAI API, function calling and Pydantic data models

* 06/2023 – 08/2023: AI Research Associate Intern, JP Morgan & Chase — New York City, NY
  * Built a financial QA system using LLMs, improving end-to-end accuracy by 7% via hybrid embedding methods and advanced negative sampling
  * Improved the retrieval model's R@3 metric by 2.4% on the test set, leading to SOTA results on the FinQA dataset
  * Implemented Chain of Thought, self-consistency and self-prompting with GPT-4, Llama2 and PaLM
  * Experimented with LangChain, LlamaIndex and ChromaDB for deploying a RAG pipeline

* 01/2021 – 07/2022: NLP Engineer, ConcertAI Pvt. Ltd. — Bengaluru, India
  * Developed information extraction models using SpaCy and Hugging Face for Electronic Health Records
  * Enhanced a site-of-mets extraction model using weak supervision (Snorkel, Skweak), boosting F1-score by 7.5% and increasing training data volume by 3x
  * Streamlined annotation tasks using active learning with SpaCy, resulting in a 30% decrease in manual effort
  * Optimized a sentiment analysis pipeline with AWS Comprehend, Lambda, S3 and AWS Textract, reducing processing time by 80%

* 08/2017 – 01/2021: Data Scientist, Innoplexus Consulting Services Pvt. Ltd — Pune, India
  * Developed an extractive Question Answering pipeline using SPECTER and FAISS, served via FastAPI in Python
  * Boosted the NER model by 5% F1 per entity and the Relation Classification model by 4.2% Micro F1
  * Developed BERT and LSTM models for NER, Sentiment Analysis and Topic Extraction using PyTorch
  * Developed an LSTM Coreference Resolution model and a BERTopic-based Topic Extraction model using PyTorch
  * Built NLP training and inference pipelines using AWS Step Functions, EventBridge, S3, Batch and SNS
  * Optimized NLP training and inference pipelines, reducing costs by 45% with AWS SageMaker
  * Automated webpage classification for 500K+ documents weekly, reducing classification time by 90% with PySpark, AWS EMR, S3, EventBridge, Lambda

Skills
======
* **Languages & ML Frameworks**: Python, PyTorch, TensorFlow, Scikit-learn, Hugging Face Transformers & TRL, Pandas, NumPy, XGBoost
* **LLM / GenAI**: DSPy (GEPA), PEFT, LoRA, GRPO, PPO, GSPO, RAG, Agentic AI, LangChain, LlamaIndex, ChromaDB, LiteLLM, Arize, RAGAS, TruLens, DeepEval, Prompt Engineering, GPT-4, GPT-OSS, Llama2, PaLM, Claude, Gemma3, Gemma4, Ministral
* **Deployment & MLOps**: vLLM, Ollama, TorchServe, DeepSpeed, GuideLLM, Quantization (GGUF, AWQ, ONNX, TensorRT), Docker, Kubernetes, MLflow, FastAPI, PySpark, AWS (SageMaker, Bedrock, ECS, ECR, S3, SQS, DynamoDB, EMR, Lambda, Comprehend, Textract, EventBridge)
* **NLP & Data**: SpaCy, Snorkel, Skweak, Weak Supervision, FAISS, SPECTER, OpenSearch, Titan Embeddings, BERT, NER, Active Learning

Certifications
======
* [AWS AI Practitioner](https://www.credly.com/badges/d774de4e-2d65-4dec-93c2-8ff68f160017/linked_in_profile)
* [AWS Cloud Technical Essentials](https://www.coursera.org/account/accomplishments/certificate/KJ6JH37Q582R)
* [Machine Learning Engineering for Production](https://coursera.org/share/9caf9f3b1897a954cb3fa27d27eaf388)
* [Claude Certified Developer - Foundations](https://www.credly.com/badges/de146cba-4777-4b4f-9ad3-fa887e25dab7)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
