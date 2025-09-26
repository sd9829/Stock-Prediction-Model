# Stock-Prediction-Model 🚀

**Focus:** A lean version of a stock forecasting & trading simulation system using LSTM, GRU, Q-learning and Monte Carlo 
---

## Project Overview

This project delivers a minimal but representative pipeline for **stock price forecasting + trading simulation**, combining:

- **Recurrent deep learning models** (LSTM, GRU) to forecast next-step returns or price signals  
- **Reinforcement learning (Q-learning)** agent to convert signals into trading decisions  
- **Monte Carlo simulations & portfolio optimization** to stress-test strategies  

---

## Architecture & Modules

Here’s how the components tie together:

1. **Dataset / Preprocessing**  
   - Load historical price data, compute technical indicators, normalize.  
   - Optionally incorporate sentiment data (e.g. sentiment consensus features).

2. **Deep Learning Forecasting**  
   - **LSTM model** predicts next-period return or directional signal.  
   - **GRU model** performs similarly, offering alternative architecture.  

3. **Trading Agent (Q-learning)**  
   - Uses state features + forecasted signal to decide actions (buy / sell / hold).  
   - Trains via reward function (e.g. PnL, transaction costs).

4. **Simulations & Backtesting**  
   - Monte Carlo trajectories of price paths.  
   - Portfolio optimization across scenarios.  

---

## Results and Plots
1. LSTM forecasting
   <img width="1143" height="408" alt="image" src="https://github.com/user-attachments/assets/4b58b688-8425-4a54-9de3-9f14850c48eb" />

2. Bi-directional LSTM forecasting
<img width="1129" height="402" alt="image" src="https://github.com/user-attachments/assets/799075ce-0da6-4160-a0a7-bbb9a097953b" />

3. GRU Forecasting
<img width="1147" height="401" alt="image" src="https://github.com/user-attachments/assets/70adfef6-3e4f-4dbf-b233-73f17f6cac85" />

4. Bi-directional GRU Forecasting
<img width="1142" height="401" alt="image" src="https://github.com/user-attachments/assets/a7e51b10-87c4-48be-aa5a-22d5b3c2e221" />

5. Q-learning agent signals
<img width="1131" height="406" alt="image" src="https://github.com/user-attachments/assets/d072e3d4-bdbb-4c99-8bdc-f2521a135411" />

6. Monte carlo simulations
<img width="715" height="700" alt="image" src="https://github.com/user-attachments/assets/e4f90630-8928-4cda-bc46-e1ca539a7573" />


