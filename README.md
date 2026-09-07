<div align="center">

# 🧠 AI / ML ROADMAP

### From Python → Machine Learning → Deep Learning → Generative AI → LLMs → RAG → Agentic AI → MLOps

<p>
  <strong>A structured, dependency-first roadmap for learning and building modern AI systems.</strong>
</p>

<br>

![AI](https://img.shields.io/badge/AI-Machine%20Learning-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-Fundamentals-yellow?style=for-the-badge\&logo=python\&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep-Learning-red?style=for-the-badge)
![GenAI](https://img.shields.io/badge/Generative-AI-purple?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLMs-Transformers-orange?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Retrieval-green?style=for-the-badge)
![Agents](https://img.shields.io/badge/Agentic-AI-black?style=for-the-badge)

</div>

---

## 📌 About This Roadmap

This repository contains a **complete, structured roadmap for Artificial Intelligence and Machine Learning**, progressing from programming fundamentals to production-grade AI systems.

The roadmap is organized according to **conceptual dependencies**, rather than simply listing popular technologies.

```text
                         ARTIFICIAL INTELLIGENCE
                                  │
             ┌────────────────────┴────────────────────┐
             │                                         │
       Machine Learning                         Other AI Methods
             │
      ┌──────┼───────┐
      │      │       │
 Supervised Unsupervised Reinforcement
      │      │       │
      └──────┼───────┘
             │
       Deep Learning
             │
    ┌────────┼─────────┐
    │        │         │
   CNN      RNN       NLP
    │        │         │
    └────────┼─────────┘
             │
        Transformers
             │
       Generative AI
             │
            LLMs
       ┌─────┴─────┐
       │           │
 Fine-Tuning      RAG
       │           │
       └─────┬─────┘
             │
       Multimodal AI
             │
        Agentic AI
             │
     AI Application Layer
             │
      Cloud / Deployment
             │
           MLOps
             │
          LLMOps
```

---

# 🗺️ Complete Roadmap

> **Legend:**
> 🟢 Foundation
> 🔵 Core
> 🟣 Advanced
> 🟠 Production

---

<details open>
<summary><h2>🟢 01 — Programming Foundation</h2></summary>

### Python

* Syntax
* Variables & Data Types
* Operators
* Input / Output
* Conditional Statements
* Loops
* Functions
* Recursion
* Lists
* Tuples
* Sets
* Dictionaries
* Strings
* List / Dictionary / Set Comprehensions
* Iterators
* Generators
* Lambda Functions
* Decorators
* Object-Oriented Programming

  * Classes
  * Objects
  * Inheritance
  * Polymorphism
  * Encapsulation
  * Abstraction
* Modules & Packages
* Exception Handling
* File Handling
* Virtual Environments
* `pip`
* Type Hints
* Testing
* Debugging

### Development Tools

* Git
* GitHub
* Branching
* Merging
* Pull Requests
* Version Control
* Basic Linux / Terminal

</details>

---

<details>
<summary><h2>🟢 02 — Mathematics & Statistics</h2></summary>

### Linear Algebra

* Scalars
* Vectors
* Matrices
* Matrix Operations
* Dot Product
* Norms
* Linear Transformations
* Eigenvalues
* Eigenvectors
* Matrix Decomposition
* Singular Value Decomposition — SVD

### Calculus

* Functions
* Limits
* Derivatives
* Partial Derivatives
* Gradients
* Chain Rule
* Integrals
* Optimization

### Probability

* Random Variables
* Conditional Probability
* Bayes' Theorem
* Expectation
* Variance
* Covariance
* Probability Distributions

### Statistics

* Mean
* Median
* Mode
* Variance
* Standard Deviation
* Sampling
* Confidence Intervals
* Hypothesis Testing
* Correlation

### Optimization

* Objective Functions
* Loss Functions
* Gradient Descent
* Learning Rate
* Convexity Basics

### Information Theory

* Entropy
* Cross-Entropy
* KL Divergence

</details>

---

<details>
<summary><h2>🔵 03 — Python Data & ML Ecosystem</h2></summary>

### Core Libraries

| Library      | Purpose                     |
| ------------ | --------------------------- |
| NumPy        | Numerical computing         |
| Pandas       | Data manipulation           |
| Matplotlib   | Visualization               |
| Seaborn      | Statistical visualization   |
| SciPy        | Scientific computing        |
| Scikit-learn | Classical machine learning  |
| Jupyter      | Interactive experimentation |

### Learn

* Arrays
* DataFrames
* Series
* Data manipulation
* Visualization
* Statistical analysis
* Scientific computing
* ML pipelines

</details>

---

<details>
<summary><h2>🔵 04 — Data Analysis & Preprocessing</h2></summary>

Before training a model, learn how to work with data.

### Data Preparation

* Data Collection
* Data Cleaning
* Exploratory Data Analysis — EDA
* Missing Values
* Duplicate Data
* Outlier Detection
* Categorical Variables
* Encoding
* Feature Scaling
* Normalization
* Standardization

### Feature Engineering

* Feature Creation
* Feature Transformation
* Feature Selection
* Dimensionality Reduction

### Dataset Management

* Training Set
* Validation Set
* Test Set
* Cross-Validation
* Data Leakage
* Class Imbalance
* Data Augmentation
* Reproducibility

</details>

---

<details>
<summary><h2>🔵 05 — Machine Learning</h2></summary>

## Supervised Learning

Learning from labeled data.

### Regression

* Linear Regression
* Polynomial Regression
* Regularization

### Classification

* Logistic Regression
* K-Nearest Neighbors — KNN
* Naive Bayes
* Decision Trees
* Random Forest
* Support Vector Machines — SVM
* Gradient Boosting
* XGBoost
* LightGBM
* CatBoost

---

## Unsupervised Learning

Learning patterns from unlabeled data.

### Clustering

* K-Means
* Hierarchical Clustering
* DBSCAN
* Gaussian Mixture Models

### Dimensionality Reduction

* PCA
* Other Dimensionality Reduction Methods

### Other

* Anomaly Detection

---

## Reinforcement Learning

Learning through interaction with an environment.

```text
              ┌─────────────┐
              │    Agent    │
              └──────┬──────┘
                     │ Action
                     ▼
              ┌─────────────┐
              │ Environment │
              └──────┬──────┘
                     │
              State + Reward
                     │
                     ▼
                  Agent
```

### Concepts

* Agent
* Environment
* State
* Action
* Reward
* Policy
* Value Function
* Q-Function
* Markov Decision Process
* Exploration vs Exploitation

### Algorithms

* Q-Learning
* SARSA
* DQN
* Policy Gradient
* Actor-Critic
* PPO

</details>

---

<details>
<summary><h2>🔵 06 — ML Engineering</h2></summary>

### Model Evaluation

#### Classification

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* PR-AUC
* Confusion Matrix

#### Regression

* MAE
* MSE
* RMSE
* R²

### Model Optimization

* Cross-Validation
* Hyperparameter Tuning
* Grid Search
* Random Search
* Bayesian Optimization

### Engineering

* Scikit-learn Pipelines
* Model Serialization
* Experiment Tracking
* Reproducibility
* Model Comparison

</details>

---

<details>
<summary><h2>🔵 07 — Deep Learning</h2></summary>

### Neural Networks

* Artificial Neurons
* Perceptron
* MLP
* Layers
* Weights
* Bias
* Parameters

### Training

* Forward Propagation
* Backpropagation
* Computational Graphs
* Loss Functions
* Activation Functions

### Activation Functions

* ReLU
* Sigmoid
* Tanh
* Softmax

### Optimizers

* SGD
* Momentum
* Adam
* AdamW

### Regularization

* Dropout
* Batch Normalization
* Layer Normalization
* Weight Initialization
* Learning Rate Scheduling

### Common Problems

* Overfitting
* Underfitting
* Vanishing Gradients
* Exploding Gradients

### Frameworks

* PyTorch
* TensorFlow
* Keras

</details>

---

<details>
<summary><h2>🔵 08 — Computer Vision</h2></summary>

### Foundations

* Images as Tensors
* Image Representation
* Image Preprocessing
* Image Augmentation
* OpenCV

### CNN

* Convolution
* Kernels
* Filters
* Feature Maps
* Pooling
* Stride
* Padding

### Tasks

* Image Classification
* Transfer Learning
* Object Detection
* Image Segmentation
* Semantic Segmentation
* Instance Segmentation
* OCR

### Modern Vision

* YOLO
* Vision Transformers
* Image Embeddings
* Vision-Language Models

</details>

---

<details>
<summary><h2>🔵 09 — Sequence Modeling</h2></summary>

Neural architectures designed for sequential data.

* Sequential Data
* RNN
* LSTM
* GRU
* Bidirectional RNN
* Seq2Seq
* Encoder-Decoder
* Attention
* Teacher Forcing
* Sequence Generation

> RNNs/LSTMs are important historically and conceptually, while Transformers dominate many modern NLP and multimodal applications.

</details>

---

<details>
<summary><h2>🔵 10 — Natural Language Processing</h2></summary>

### Text Processing

* Text Cleaning
* Tokenization
* Stop Words
* Stemming
* Lemmatization
* N-Grams

### Classical NLP

* Bag of Words
* TF-IDF

### Word Representations

* Word2Vec
* GloVe
* FastText
* Word Embeddings

### NLP Tasks

* Text Classification
* Sentiment Analysis
* Named Entity Recognition — NER
* POS Tagging
* Language Modeling
* Text Generation

</details>

---

<details>
<summary><h2>🟣 11 — Transformers</h2></summary>

Transformers are the foundation of most modern LLM systems.

### Attention

* Query
* Key
* Value
* Scaled Dot-Product Attention
* Self-Attention
* Multi-Head Attention

### Architecture

* Positional Encoding
* Positional Embeddings
* Feed-Forward Networks
* Residual Connections
* Layer Normalization
* Encoder
* Decoder
* Encoder-Decoder Architecture
* Masked Attention
* Causal Attention

### Important Architectures

* BERT
* GPT
* T5

</details>

---

<details>
<summary><h2>🟣 12 — Generative AI</h2></summary>

AI systems capable of generating new content.

### Generative Models

* Autoencoders
* Variational Autoencoders — VAE
* GANs
* Diffusion Models
* Foundation Models

### Modalities

* Text Generation
* Image Generation
* Audio Generation
* Video Generation
* Multimodal Generation

</details>

---

<details>
<summary><h2>🟣 13 — Large Language Models</h2></summary>

### LLM Fundamentals

* LLM Architecture
* Transformer Architecture
* Foundation Models
* Pretraining
* Self-Supervised Learning
* Next-Token Prediction

### Data

* Dataset Preparation
* Data Filtering
* Data Quality
* Tokenization
* Vocabulary
* Tokens

### Model Internals

* Embeddings
* Parameters
* Weights
* Logits
* Softmax
* Attention
* Context Window

### Scaling

* Model Size
* Scaling Laws
* Compute
* Training Data

### Inference

* Prompt → Tokens
* Tokens → Logits
* Logits → Probabilities
* Probability → Next Token
* Repeated Generation → Output

</details>

---

<details>
<summary><h2>🟣 14 — LLM Inference & Decoding</h2></summary>

Understanding how an LLM generates output.

### Decoding

* Greedy Decoding
* Sampling
* Temperature
* Top-K
* Top-P / Nucleus Sampling
* Beam Search
* Repetition Penalty
* Stop Tokens

### Inference Engineering

* Context Management
* KV Cache
* Batching
* Streaming
* Quantization
* Inference Optimization
* Latency
* Throughput

</details>

---

<details>
<summary><h2>🟣 15 — LLM Adaptation & Fine-Tuning</h2></summary>

### Prompt Engineering

* Zero-Shot Prompting
* Few-Shot Prompting
* System Prompts
* Structured Outputs
* Prompt Templates

### Fine-Tuning

* Fine-Tuning
* Instruction Tuning
* Supervised Fine-Tuning — SFT
* Preference Optimization
* RLHF
* DPO

### Parameter-Efficient Fine-Tuning

* PEFT
* LoRA
* QLoRA

### Model Optimization

* Quantization
* Distillation

### Key Decision

```text
Need new / private / changing knowledge?
                │
                ▼
               RAG
                │
                └───────────────┐
                                │
Need different model behavior? │
                                ▼
                          Fine-Tuning
```

### RAG vs Fine-Tuning

| Requirement                    | Better Approach   |
| ------------------------------ | ----------------- |
| Frequently changing knowledge  | RAG               |
| Private documents              | RAG               |
| External knowledge             | RAG               |
| Consistent output format       | Fine-Tuning       |
| Specific behavior/style        | Fine-Tuning       |
| Task adaptation                | Fine-Tuning       |
| Need both knowledge + behavior | RAG + Fine-Tuning |

</details>

---

<details>
<summary><h2>🟣 16 — Embeddings & Vector Databases</h2></summary>

### Embeddings

* Text Embeddings
* Image Embeddings
* Multimodal Embeddings
* Vector Representations
* Semantic Similarity
* Cosine Similarity

### Vector Search

* Vector Indexing
* Similarity Search
* Approximate Nearest Neighbor Search
* Metadata Filtering

### Vector Databases / Systems

* FAISS
* Chroma
* Pinecone
* Weaviate
* Milvus

</details>

---

<details>
<summary><h2>🟣 17 — Retrieval-Augmented Generation — RAG</h2></summary>

### Basic RAG Pipeline

```text
Documents
    │
    ▼
Document Loading
    │
    ▼
Parsing / Cleaning
    │
    ▼
Chunking
    │
    ▼
Embeddings
    │
    ▼
Vector Database
    │
    ▼
Retriever
    │
    ▼
Relevant Context
    │
    ▼
LLM
    │
    ▼
Answer
```

### Core Components

* Document Loading
* Document Parsing
* Chunking
* Chunk Size
* Chunk Overlap
* Embedding
* Indexing
* Retrieval
* Context Construction
* Generation
* Reranking

### Advanced Retrieval

* Hybrid Search
* Keyword Search + Vector Search
* Metadata Filtering
* Query Expansion
* Query Rewriting
* Multi-Query Retrieval
* Parent-Child Retrieval
* Corrective RAG
* Agentic RAG
* Graph RAG

### Evaluation

* Retrieval Evaluation
* Generation Evaluation
* Context Relevance
* Answer Relevance
* Faithfulness
* Hallucination Analysis

</details>

---

<details>
<summary><h2>🟣 18 — Multimodal AI</h2></summary>

AI systems working across multiple modalities.

### Modalities

* Text
* Images
* Audio
* Video

### Technologies

* Vision-Language Models
* Image Understanding
* Speech-to-Text
* Text-to-Speech
* Audio Understanding
* Multimodal Embeddings
* Multimodal LLMs

```text
              Multimodal AI
             /      |       \
          Text    Vision    Audio
             \      |       /
              Multimodal LLM
                    │
                  Video
```

</details>

---

<details>
<summary><h2>🟣 19 — Agentic AI</h2></summary>

An AI agent combines models with reasoning, tools, state, memory, and actions to accomplish tasks.

### Agent Loop

```text
          ┌───────────────┐
          │   Perception  │
          └───────┬───────┘
                  ▼
          ┌───────────────┐
          │   Reasoning   │
          └───────┬───────┘
                  ▼
          ┌───────────────┐
          │    Planning   │
          └───────┬───────┘
                  ▼
          ┌───────────────┐
          │  Tool / Action│
          └───────┬───────┘
                  ▼
             Observation
                  │
                  └──────────► Repeat
```

### Core Concepts

* Agent
* Agent Loop
* Perception
* Reasoning
* Planning
* Action
* Tool Calling
* Function Calling
* Tool Selection
* Memory
* Short-Term Memory
* Long-Term Memory
* Reflection
* Replanning
* ReAct

### Agent Types

* Workflow Agents
* Planning Agents
* Autonomous Agents
* Multi-Agent Systems

### Production Concepts

* Agent Orchestration
* Human-in-the-Loop
* Agent Evaluation
* Agent Safety
* State Management
* Tool Permissions

</details>

---

<details>
<summary><h2>🟣 20 — Agent Frameworks</h2></summary>

### Frameworks

* LangChain
* LangGraph
* LlamaIndex
* AutoGen
* CrewAI
* Hugging Face Agents

### Important Concepts

* Tool Abstractions
* Provider Abstractions
* Agent State
* Graph-Based Workflows
* Execution Graphs
* Memory
* Tool Registry
* Agent Orchestration

</details>

---

<details>
<summary><h2>🟠 21 — AI Application Engineering</h2></summary>

Once models and agents are understood, learn how to build actual applications around them.

### Backend

* APIs
* REST
* HTTP
* JSON
* FastAPI
* Authentication
* Authorization

### Databases

* PostgreSQL
* Redis
* SQL
* Caching

### Application Architecture

* Async Programming
* WebSockets
* Background Jobs
* Queues
* Frontend Integration
* Error Handling
* Rate Limiting
* Secrets Management

### Typical AI Application

```text
Frontend
    │
    ▼
API / Backend
    │
    ├────────► LLM
    │
    ├────────► RAG
    │
    ├────────► Tools
    │
    ├────────► Database
    │
    └────────► Agent
```

</details>

---

<details>
<summary><h2>🟠 22 — Deployment & Cloud</h2></summary>

### Linux

* Shell
* Processes
* Environment Variables
* Permissions
* Networking Basics

### Docker

* Containers
* Dockerfiles
* Images
* Volumes
* Networks
* Docker Compose
* Container Registries

### Kubernetes

* Pods
* Deployments
* Services
* ConfigMaps
* Secrets
* Scaling

### Cloud

Learn at least one major cloud platform deeply.

* AWS
* Azure
* Google Cloud

### Cloud Fundamentals

* Compute
* Storage
* Networking
* IAM
* Load Balancing
* Autoscaling
* Monitoring

### AI Deployment

* GPU Deployment
* Model Serving
* Inference Servers
* Serverless
* Batch Inference
* Real-Time Inference

</details>

---

<details>
<summary><h2>🟠 23 — MLOps</h2></summary>

MLOps focuses on operating machine-learning systems reliably in production.

### ML Lifecycle

```text
Data
 ↓
Training
 ↓
Evaluation
 ↓
Experiment Tracking
 ↓
Model Registry
 ↓
Deployment
 ↓
Monitoring
 ↓
Retraining
```

### Core Topics

* ML Lifecycle
* Dataset Management
* Data Versioning
* Model Versioning
* Experiment Tracking
* Model Registry
* Training Pipelines
* Feature Stores
* Reproducibility

### Tools

* MLflow
* DVC

### CI/CD

* Automated Testing
* Build Pipelines
* Deployment Pipelines
* Continuous Integration
* Continuous Delivery

### Monitoring

* Logging
* Metrics
* Data Drift
* Concept Drift
* Model Performance
* Latency
* Throughput
* Resource Usage
* Observability

</details>

---

<details>
<summary><h2>🟠 24 — LLMOps</h2></summary>

LLMOps extends production engineering concepts to LLM-based applications.

### Evaluation

* LLM Evaluation
* RAG Evaluation
* Agent Evaluation
* Prompt Evaluation
* Human Evaluation
* Automated Evaluation

### Observability

* Tracing
* Token Monitoring
* Cost Monitoring
* Latency Monitoring
* Throughput
* Error Monitoring

### Production

* Prompt Versioning
* Model Versioning
* Model Routing
* Fallback Models
* Caching
* Guardrails
* Safety
* Hallucination Detection
* Feedback Loops
* Continuous Evaluation
* Production Monitoring

</details>

---

# 🧩 The Complete Dependency Map

```text
┌───────────────────────────────┐
│      PROGRAMMING              │
│ Python + Git + Linux Basics   │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│   MATHEMATICS & STATISTICS    │
│ Linear Algebra + Probability  │
│ Calculus + Statistics         │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│       DATA & PYTHON           │
│ NumPy + Pandas + Visualization│
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│    DATA PREPROCESSING         │
│ EDA + Features + Cleaning     │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│      MACHINE LEARNING         │
│ Supervised + Unsupervised    │
│ Reinforcement Learning        │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│       ML ENGINEERING          │
│ Evaluation + Tuning + MLOps   │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│       DEEP LEARNING           │
│ Neural Networks + PyTorch     │
└───────┬─────────┬─────────────┘
        │         │
        ▼         ▼
      CNN       RNN/LSTM
        │         │
        └────┬────┘
             ▼
            NLP
             │
             ▼
       TRANSFORMERS
             │
             ▼
       GENERATIVE AI
             │
             ▼
            LLMs
        ┌────┴────┐
        │         │
        ▼         ▼
 Fine-Tuning     RAG
        │         │
        └────┬────┘
             ▼
      MULTIMODAL AI
             │
             ▼
       AGENTIC AI
             │
             ▼
    APPLICATION ENGINEERING
             │
             ▼
       CLOUD / DEPLOYMENT
             │
             ▼
           MLOps
             │
             ▼
          LLMOps
```

---

# 🧠 Mental Model

| Layer               | Question It Answers                                   |
| ------------------- | ----------------------------------------------------- |
| 🐍 Python           | How do I program?                                     |
| 📐 Mathematics      | Why do ML algorithms work?                            |
| 📊 Data             | How do I prepare useful data?                         |
| 🤖 ML               | How can machines learn patterns?                      |
| 🧠 Deep Learning    | How can neural networks learn representations?        |
| 👁️ Computer Vision | How can machines understand images/video?             |
| 📝 NLP              | How can machines process language?                    |
| ⚡ Transformers      | How do modern foundation models process sequences?    |
| ✨ Generative AI     | How can models generate new content?                  |
| 🧠 LLMs             | How do language foundation models work?               |
| 🔧 Fine-Tuning      | How can I adapt model behavior?                       |
| 🔎 RAG              | How can I give models external knowledge?             |
| 🌐 Multimodal AI    | How can models work across modalities?                |
| 🤖 Agents           | How can models reason, use tools, and complete tasks? |
| 🏗️ AI Engineering  | How do I turn models into applications?               |
| ☁️ Cloud            | Where does my application run?                        |
| ⚙️ MLOps            | How do I operate ML systems reliably?                 |
| 🚀 LLMOps           | How do I operate LLM applications in production?      |

---

# ⚖️ Important Conceptual Distinctions

### Machine Learning vs Deep Learning

**Machine Learning**

Traditional algorithms learn patterns from engineered or structured features.

**Deep Learning**

Neural networks learn increasingly useful representations directly from data.

---

### Supervised vs Unsupervised vs Reinforcement Learning

| Type          | Data / Signal        | Example            |
| ------------- | -------------------- | ------------------ |
| Supervised    | Labeled examples     | Classification     |
| Unsupervised  | Unlabeled data       | Clustering         |
| Reinforcement | Experience + rewards | Game-playing agent |

> Reinforcement Learning does **not** mean "no data". The agent generates and learns from experience.

---

### CNN vs RNN vs Transformer

| Architecture | Main Strength                     |
| ------------ | --------------------------------- |
| CNN          | Spatial patterns                  |
| RNN          | Sequential dependencies           |
| LSTM / GRU   | Longer sequence dependencies      |
| Transformer  | Attention-based sequence modeling |

---

### RAG vs Fine-Tuning

```text
             Need to improve AI system?
                       │
             ┌─────────┴─────────┐
             │                   │
      Need knowledge?      Need behavior?
             │                   │
             ▼                   ▼
            RAG             Fine-Tuning
             │                   │
       External data       Model parameters
       at inference        are adapted
```

---

### RAG vs Agents

**RAG** is primarily a retrieval architecture.

**Agents** are systems that can decide what actions/tools to use.

An agent can use RAG as one of its tools.

---

### Model vs AI Application

```text
Model
  │
  ├── LLM
  ├── Vision Model
  └── Embedding Model

Application
  │
  ├── Model
  ├── Database
  ├── RAG
  ├── Tools
  ├── Agent
  ├── API
  ├── Authentication
  ├── UI
  ├── Monitoring
  └── Deployment
```

A model is only one component of a production AI system.

---

# 🛠️ Suggested Technology Stack

| Area                | Technologies                     |
| ------------------- | -------------------------------- |
| Programming         | Python                           |
| Numerical Computing | NumPy                            |
| Data                | Pandas                           |
| Visualization       | Matplotlib, Seaborn              |
| Classical ML        | Scikit-learn                     |
| Deep Learning       | PyTorch                          |
| Computer Vision     | OpenCV, YOLO                     |
| NLP                 | Transformers                     |
| LLMs                | Hugging Face                     |
| LLM Applications    | LangChain, LangGraph, LlamaIndex |
| RAG                 | FAISS, Chroma, Vector DBs        |
| Backend             | FastAPI                          |
| Database            | PostgreSQL, Redis                |
| Containers          | Docker                           |
| Cloud               | AWS / Azure / GCP                |
| MLOps               | MLflow, DVC                      |
| Version Control     | Git + GitHub                     |

> The goal is **not** to learn every tool listed here. Learn the underlying concepts first, then select tools according to the project.

---

# 🎯 Recommended Learning Strategy

Do not attempt to master the entire roadmap sequentially before building anything.

Use this cycle:

```text
LEARN
  ↓
UNDERSTAND
  ↓
IMPLEMENT
  ↓
BUILD PROJECT
  ↓
EVALUATE
  ↓
DEPLOY
  ↓
IMPROVE
```

### Phase 1

```text
Python
   ↓
NumPy / Pandas
   ↓
Matplotlib / Seaborn
   ↓
Mathematics & Statistics
```

### Phase 2

```text
Data Preprocessing
   ↓
Supervised ML
   ↓
Unsupervised ML
   ↓
Model Evaluation
```

### Phase 3

```text
Neural Networks
   ↓
Backpropagation
   ↓
PyTorch
   ↓
CNN
   ↓
RNN / LSTM
```

### Phase 4

```text
NLP
   ↓
Attention
   ↓
Transformers
   ↓
BERT / GPT Concepts
```

### Phase 5

```text
Generative AI
   ↓
LLMs
   ↓
Inference
   ↓
Prompt Engineering
   ↓
Fine-Tuning
```

### Phase 6

```text
Embeddings
   ↓
Vector Search
   ↓
RAG
   ↓
Advanced RAG
   ↓
RAG Evaluation
```

### Phase 7

```text
Tool Calling
   ↓
Agent Loops
   ↓
Memory
   ↓
Planning
   ↓
LangGraph / Agent Frameworks
   ↓
Multi-Agent Systems
```

### Phase 8

```text
FastAPI
   ↓
Databases
   ↓
Docker
   ↓
Cloud
   ↓
CI/CD
   ↓
MLOps
   ↓
LLMOps
```

---

# 📚 What "Good Enough" Looks Like

You do **not** need to know every topic at the same depth.

### Foundation

You should be able to explain and implement the fundamentals.

### Core

You should understand the mathematics, architecture, assumptions, strengths, and limitations.

### Advanced

You should be able to read papers, implement techniques, compare approaches, and build projects.

### Production

You should be able to deploy, monitor, debug, evaluate, and maintain systems.

---

# 🚀 Project Progression

A strong learning roadmap should eventually turn into projects.

```text
Python Project
      ↓
Data Analysis Project
      ↓
Classical ML Project
      ↓
Deep Learning Project
      ↓
Computer Vision / NLP Project
      ↓
Transformer Project
      ↓
LLM Application
      ↓
RAG Application
      ↓
Agentic AI Application
      ↓
Production AI System
      ↓
MLOps / LLMOps
```

---

# 📈 Final Roadmap

```text
                    AI
                     │
                     ▼
                  Python
                     │
                     ▼
          Mathematics & Statistics
                     │
                     ▼
              Data Analysis
                     │
                     ▼
            Machine Learning
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
     Supervised  Unsupervised   RL
          │          │          │
          └──────────┼──────────┘
                     ▼
               Deep Learning
                     │
          ┌──────────┼───────────┐
          ▼          ▼           ▼
         CNN       RNN/LSTM      NLP
          │          │           │
          └──────────┼───────────┘
                     ▼
                Attention
                     │
                     ▼
                Transformers
                     │
                     ▼
               Generative AI
                     │
                     ▼
                    LLMs
             ┌───────┴───────┐
             ▼               ▼
        Fine-Tuning          RAG
             │               │
             └───────┬───────┘
                     ▼
              Multimodal AI
                     │
                     ▼
                Agentic AI
                     │
                     ▼
            AI Engineering
                     │
                     ▼
             Cloud / DevOps
                     │
                     ▼
                  MLOps
                     │
                     ▼
                  LLMOps
```

---

# ⭐ Core Principle

> **Do not learn AI as a collection of libraries. Learn it as a hierarchy of concepts.**

```text
Concept
   ↓
Mathematics
   ↓
Algorithm
   ↓
Implementation
   ↓
Framework
   ↓
Application
   ↓
Deployment
   ↓
Monitoring
```

Understanding this hierarchy makes it much easier to move between frameworks, models, and technologies.

---

# 📌 Roadmap Checklist

* [ ] Python
* [ ] Mathematics & Statistics
* [ ] NumPy / Pandas
* [ ] Data Analysis
* [ ] Machine Learning
* [ ] ML Engineering
* [ ] Deep Learning
* [ ] Computer Vision
* [ ] Sequence Models
* [ ] NLP
* [ ] Transformers
* [ ] Generative AI
* [ ] LLMs
* [ ] LLM Inference
* [ ] Prompt Engineering
* [ ] Fine-Tuning
* [ ] PEFT / LoRA / QLoRA
* [ ] Embeddings
* [ ] Vector Databases
* [ ] RAG
* [ ] Advanced RAG
* [ ] RAG Evaluation
* [ ] Multimodal AI
* [ ] Agentic AI
* [ ] Agent Frameworks
* [ ] AI Application Engineering
* [ ] APIs / FastAPI
* [ ] Databases
* [ ] Docker
* [ ] Cloud
* [ ] CI/CD
* [ ] MLOps
* [ ] LLMOps

---

# 📄 License

This project is licensed under the **MIT License**.

```text
MIT License

Copyright (c) 2026 Dinesh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<div align="center">

### 🧠 Learn → Build → Deploy → Evaluate → Improve

**AI / ML Roadmap**

</div>
