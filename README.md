The stock market plays a pivotal role in the global economy, with its inherent volatility and sensitivity to economic, political, and psychological factors making stock price forecasting highly challenging. Accurate predictions are especially vital for high-impact companies such as FAANG (Meta, Apple, Amazon, Netflix, and Google), which influence major indices and reflect broader market sentiment.

This study investigates the use of advanced deep learning techniques to forecast stock prices of FAANG companies using historical time-series data. Two architectures are developed and compared: a Long Short-Term Memory (LSTM) network and a Transformer-based model.

Both models are trained on normalized closing prices with extensive data preprocessing, statistical transformations, and feature engineering to enhance learning performance. Evaluation is performed using RMSE and residual analysis, providing insights into each model’s predictive accuracy and bias. The Transformer model outperforms LSTM in capturing complex patterns, particularly in volatile stocks like NFLX and AMZN.

To enhance trading performance and realism, this study integrates algorithmic trading via an agentic AI reinforcement learning framework. The Deep Q-Network (DQN)-based trading agent leverages a reward function blending profit, Sharpe ratio, and holding incentives, and observes technical indicators like RSI, volatility, and volume.

Trained with a decaying learning rate and extended exploration, the agent outperforms a traditional buy-and-hold strategy, achieving higher returns and more stable portfolio growth. The findings highlight the effectiveness of combining deep learning with adaptive agentic systems in navigating dynamic financial markets, while also exposing the limitations of static strategies in volatile environments.



