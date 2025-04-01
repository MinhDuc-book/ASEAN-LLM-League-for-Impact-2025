# ASEAN LLM League for Impact 2025 - Fine-tuning AI Journey

## Introduction
In the **ASEAN LLM League for Impact 2025** competition, I had the opportunity to participate in a challenge focused on fine-tuning large models to optimize performance. This repository summarizes my journey, experiments, and key achievements in AI fine-tuning. 

## Abstract
Organizer: AI Singapore

Co-organizer: Amazon Web Services

Participant: Students studying at universities in ASEAN (Vietnam, Malaysia, Indonesia, Philipines, Thailand)

Mission: Develop or fine tune a large language model (LLM) with Amazon Sagemaker Jumpstart, that can outperform a reference LLM model and other competing models in a quiz-based evaluation
Tool:
  - Generate data: PartyRock
  - Model : Meta LLaMA 3.2 3B Instruct

## Process Overview
**Data Preparation:**  
  - Use PartyRock to compile a dataset in quiz-style prompts, ensure diversity and relevance to Generative AI, Agent AI, Prompt Engineering, Foundation Model
  - Remove duplicate questions and check the relevance, accurracy of responses
  
**Model Fine-tuning:**  
  Applied techniques:
  - Key steps included: 
    - Data preprocessing (used PartyRock to generate dataset) 
    - Fine-tuned, trained model
    - Evaluated and compared results

**Performance Evaluation:**  
  Measure accuracy, F1 score and response time, compared to the original and reference models to determine improvement

## Key Challenge Faced:
- Insufficent labeled data for fine-tuning
- Do not have so much knowledge about AI, LLM or relevances
- Overfitting during initial training stages

## Solutions
- Used **PartyRock** to enrich data
- Leverage **SageMaker** for efficient computation
- Fine-tuning serveral hyperparameters to mitigate overfitting

## Achievements
**Improved Model Performance:**  
  - Increased accuracy by **59%** compared to the baseline model

## Detail About Best Submit Model:
- 
  
**Technical Contributions:**  
  - Successfully apply LoRA technique and optimize dataset, improve model inference ability
  
**Competition Ranking:**  
  - Achieved **Top 20** of ASEAN and **Top 2** of Vietnam in competition

## Key Learnings
**Optimization of Training Pipeline:**  
  - Fine-tuning hyperparameters and optimizing the training pipeline greatly enhanced model efficiency
  - Testing multiples strategies to find the best solution.
  
**Practical Experience:**  
  - Participating in the competition provided valuable insights into the challenges and solutions when working with large-scale AI models
  - Learn to build future-ready Generative AI applications

