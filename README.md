# USA–Iran–India Geopolitical Forecasting System

## Multi-Agent Strategic Simulation and Market Impact Analysis

---

## Project Overview

This project is a geopolitical forecasting and market impact simulation system that models strategic interactions between:

* United States
* Iran
* India

The system combines:

* Historical geopolitical events
* Real financial market data
* Markov chain forecasting
* Monte Carlo simulation
* Bayesian updating
* Reinforcement learning agents
* NLP-based sentiment analysis
* Interactive Streamlit dashboard

The goal of the project is to simulate geopolitical evolution, estimate strategic actions of major actors, and forecast market impacts under different escalation scenarios.

---

# Key Features

## Historical Geopolitical Event Modeling

The project includes a manually curated geopolitical dataset covering major Iran-related geopolitical events from 1979 to 2025.

Examples include:

* Iranian Revolution
* Iran-Iraq War
* JCPOA Nuclear Deal
* Soleimani Assassination
* Iran-Israel escalation events

Each event includes:

* USA action
* Iran action
* India response
* Event category
* Escalation severity

---

## Real Financial Market Data

Historical market data is downloaded using Yahoo Finance.

Markets included:

* Brent Crude Oil
* S&P 500
* NIFTY 50
* Gold
* VIX

The system analyzes:

* Oil shocks
* Volatility spikes
* Equity market reactions
* Safe haven behavior

---

## Markov Chain Geopolitical Forecasting

The system models geopolitical states using a Markov transition framework.

States:

| State | Meaning          |
| ----- | ---------------- |
| 0     | Stable           |
| 1     | Moderate Tension |
| 2     | High Tension     |
| 3     | Crisis           |

The transition matrix estimates:

P(next_state | current_state)

This allows probabilistic forecasting of geopolitical evolution.

---

## Strategic Action Prediction

The project predicts likely strategic actions of:

* USA
* Iran
* India

based on:

* current geopolitical state
* historical escalation patterns
* strategic incentives

Example actions:

### USA

* Economic Sanctions
* Military Pressure
* Naval Deployment
* Cyber Operations

### Iran

* Proxy Escalation
* Missile Demonstration
* Oil Route Threat
* Nuclear Expansion

### India

* Oil Diversification
* Strategic Mediation
* Neutral Diplomacy
* Energy Security Measures

---

## Monte Carlo Simulation

The project simulates hundreds of possible geopolitical futures.

Outputs include:

* Crisis probability
* Oil impact distributions
* Market risk ranges
* Strategic action frequencies
* State probability distributions

---

## Bayesian Updating

The system dynamically updates geopolitical probabilities using new evidence.

Examples:

* Missile strike
* Diplomatic agreement
* Sanctions announcement
* Naval deployment

This allows evidence-driven geopolitical forecasting.

---

## Reinforcement Learning Agents

The project includes simplified reinforcement learning agents where:

* USA learns strategic preferences
* Iran adapts responses
* India optimizes energy and diplomatic strategy

Q-learning is used to reinforce strategies that produce favorable outcomes.

---

## NLP Sentiment Analysis

The system uses VADER sentiment analysis to analyze geopolitical headlines.

Headlines influence:

* geopolitical state probabilities
* escalation forecasts
* market expectations

Examples:

* aggressive rhetoric increases crisis probability
* diplomatic headlines increase stability probability

---

## Unified Forecasting Engine

The final forecasting engine combines:

* Markov chains
* Bayesian updates
* Reinforcement learning
* NLP sentiment analysis
* Market impact simulation

The engine forecasts:

* geopolitical evolution
* strategic actions
* market reactions
* crisis probabilities

---

# Technologies Used

| Technology      | Purpose                   |
| --------------- | ------------------------- |
| Python          | Core programming language |
| Pandas          | Data analysis             |
| NumPy           | Numerical computation     |
| Matplotlib      | Visualization             |
| yFinance        | Historical market data    |
| Streamlit       | Interactive dashboard     |
| VADER Sentiment | NLP sentiment analysis    |
| Google Colab    | Development environment   |

---

# Project Structure

```text
geopolitical-risk-forecasting-system/
│
├── app.py
├── requirements.txt
├── README.md
├── notebooks/
├── data/
└── models/
```

---

# How to Run the Project

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/geopolitical-risk-forecasting-system.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Streamlit Dashboard

```bash
streamlit run app.py
```

---

# Future Improvements

Potential future upgrades:

* Real-time news ingestion
* GDELT integration
* Reuters RSS integration
* Transformer-based NLP
* Advanced reinforcement learning
* Real-time dashboards
* Live market feeds

---

# Important Disclaimer

This project is a probabilistic geopolitical simulation system.

It does NOT provide:

* guaranteed predictions
* investment advice
* real-world policy recommendations

The system is designed for:

* educational purposes
* research-style experimentation
* geopolitical risk analysis
* simulation and forecasting studies

---

# Author

Samarth Vatsal

Second-Year AIML Student
RNS Institute of Technology

---

# License

This project is intended for educational and research purposes.
