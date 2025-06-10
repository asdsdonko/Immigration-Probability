# Cultural Survival Through Immigration: A Probabilistic Analysis

*A CS 109 Challenge Project by Alice Dos Santos - June 2025*

## 🌍 Project Overview

This project explores how cultural knowledge survives (or dies) as it passes through generations of immigrant families, using my own family's Italian-Brazilian-American heritage as a case study. Through probabilistic modeling and information theory, I analyze the transmission patterns of cultural traditions across four generations.

## 🔬 Research Question

**How does cultural knowledge survive (or die) as it passes through generations of immigrant families, and what factors determine transmission success?**

## 📊 Methodology

### Family Background
- **0th Generation**: Great-grandparents from Veneto, Italy
- **1st Generation**: Grandmother raised in Brazil (Italian-Brazilian culture)  
- **2nd Generation**: Mother immigrated to United States
- **3rd Generation**: Me and my sister (Portuguese, English, some Veneto)

### Mathematical Framework

#### 1. Binomial Distribution Model
Each child represents an independent Bernoulli trial for tradition inheritance:
- **Success (X=1)**: Child inherits the tradition
- **Failure (X=0)**: Child does not inherit the tradition
- **Probability**: P_survive(g) based on generation g, decay rate λ, and initial strength S₀

#### 2. Statistical Analysis
- **Expected Value**: E[X] = average number of children inheriting tradition
- **Variance**: Var(X) = n·p·(1-p) quantifies transmission randomness
- **Joint Probabilities**: Likelihood of multiple traditions surviving simultaneously
- **Conditional Probabilities**: How traditions influence each other's survival

#### 3. Information Theory Extension
- **Entropy Calculation**: H(X) = -Σ p(x)log₂p(x)
- **Information Decay**: Measures cultural information loss over time
- **Vulnerability Assessment**: Identifies traditions most at risk

## 🔍 Key Findings

| Tradition Type | Decay Rate (λ) | Survival Pattern |
|----------------|----------------|------------------|
| Food Traditions | 0.2 | **Best survival** - Strong daily practice integration |
| Language (Veneto) | 0.3 | **Fastest decline** - Common in immigrant communities |
| Other Traditions | Varies | Sharp decline in multi-tradition preservation |

### Critical Insights
- Food traditions show highest cultural resilience
- Language faces rapid extinction without active preservation
- Joint tradition survival drops exponentially each generation
- Entropy analysis reveals information-rich preservation targets

## 🛠️ Technical Implementation

### Technologies Used
- Python for probabilistic modeling
- Statistical analysis libraries
- Information theory calculations
- Data visualization tools

### Key Components
1. **Interview Data Collection**: Multi-generational family interviews
2. **Parameter Estimation**: Tradition strength and decay rates
3. **Probabilistic Modeling**: Binomial distribution framework
4. **Entropy Analysis**: Information theory application
5. **Predictive Simulation**: Cultural loss forecasting

## 📈 Applications & Impact

### Direct Applications
1. **Endangered Language Preservation**
   - Quantify transmission rates
   - Predict extinction timelines
   - Guide intervention strategies

2. **Immigrant Assimilation Studies**
   - Compare decay rates across communities
   - Identify cultural preservation patterns
   - Inform integration policies

3. **Digital Cultural Archiving**
   - Prioritize high-risk traditions
   - AI-driven preservation systems
   - Predictive cultural loss modeling

### Broader Implications
- **Targeted Interventions**: Joint probability calculations enable focused preservation efforts
- **Cultural Information Value**: Entropy metrics identify most valuable traditions
- **Community Planning**: Data-driven cultural preservation strategies

