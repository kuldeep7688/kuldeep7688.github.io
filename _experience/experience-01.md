---
title: "Sr ML Engineer"
collection: experience
type: "GenAI Platform Team"
permalink: /experience/experience-01
venue: "Quantiphi (Client: AT&T)"
date1: 02 February 2025
date2: Present
excerpt: 'Replacing closed-source LLMs with fine-tuned open-source models in production (saving $800K/year), and building the RL post-training and evaluation infrastructure used by 10+ teams at AT&T.'
location: "Bedminster, NJ, USA"
---

## Overview
I work on AT&T's GenAI platform, where my focus is LLM post-training and evaluation: proving that smaller fine-tuned open-source models can beat frontier closed-source models on real business workflows, and building the shared infrastructure that lets other teams do the same.

## Replacing closed-source models with fine-tuned open-source models
- Fine-tuned open-source LLMs (4B to 12B parameters, Mistral and Gemma families) to replace GPT-4o and GPT-4.1 across 5 agentic workflows with 5 AT&T teams, covering customer support Q&A, call transcript diarization and customer journey summarization.
- The fine-tuned models outperformed the closed-source baselines by 5 to 10% on every use case's metrics, and also came out ahead when Subject Matter Experts reviewed outputs manually.
- Deployed models for 3 of these use cases are saving **$800K/year** in inference cost.
- Worked with each use case's Subject Matter Experts to define use-case-specific evaluation metrics, translating business requirements into measurable model-quality targets. Getting the metric right was as important as getting the model right.
- Used DSPy (GEPA) for prompt optimization alongside PEFT/LoRA fine-tuning and reinforcement learning.

## Reinforcement learning in the Finetuning-as-a-Service platform
- Owned the integration of GRPO, PPO and GSPO (Hugging Face TRL) into AT&T's Finetuning-as-a-Service platform end to end: framework selection, judge integration, platform integration and end-to-end testing.
- Wrote the design and presented it to AT&T stakeholders.
- The platform fine-tunes 1B to 30B parameter open-source models (Gemma, Llama, Mistral, Phi) for 10+ use case teams, and 3 of those teams now use the RL capability.

## Evaluation microservice
- Architected and co-built an evaluation microservice supporting custom LLM-as-a-judge and code-based judges.
- Used by 10+ teams across AT&T for evaluating fine-tuning runs, scoring rewards during RL training, and daily evaluations to track production quality.
- Presented the service to AT&T stakeholders.

## RAG evaluation and catching data drift
- Built RAG evaluation with Faithfulness, Relevancy and Context Sufficiency metrics for 2 production RAG applications.
- About two months after launch, our custom answer faithfulness metric caught a regression in a deployed fine-tuned model caused by a shift in the input data distribution. That signal drove the decision to re-fine-tune the model on fresh data using rejection sampling.

## Serving and load testing
- Benchmarked fine-tuned models' throughput and p95 latency with GuideLLM to size production serving, including load tests against peak traffic with a ~5 second p95 latency target. The results informed GPU allocation and autoscaling for deployment.

## Leadership
- Presented the RL integration, the evaluation microservice, and the fine-tuned models' quality and cost results to AT&T stakeholders.
- Mentored 1 intern.
