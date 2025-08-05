# Intelligent Portfolio Optimizer  
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://modernportfolio.streamlit.app/)

An interactive Streamlit app for **modern portfolio optimization** using historical data and Markowitz theory to construct an efficient investment portfolio tailored to your return requirements and risk appetite.

🔗 **Try it live:** [modernportfolio.streamlit.app](https://modernportfolio.streamlit.app/)

---

## 📈 What This App Does

This app helps users **build an optimal investment portfolio** based on:

- **Minimum desired return**
- **Selected list of mutual funds or ETFs**
- **Historical risk-return characteristics (since 2023)**

Using the **Markowitz Mean-Variance Optimization framework**, the app computes the optimal asset allocation that minimizes portfolio risk for a user-defined return target.

---

## 🚀 Key Features

- 🎯 **Target Return Selection**: Customize your minimum required return and let the optimizer do the rest.
- 🧺 **Fund Selection**: Choose from a curated list of funds to include in the portfolio.
- 📊 **Risk-Return Visualization**: Compare selected funds and the optimized portfolio in a clear scatter plot.
- 📉 **Historical Performance Analysis**: Understand how your portfolio would have performed in the past.
- 🔮 **Projection & Risk Insights**: See projected returns and probabilities of loss across various investment horizons.
- 🧮 **Customizable Assumptions**: Modify expected returns, volatilities, and correlations in the **Data** tab to stress-test or personalize the model.

---

## 🛠️ How It Works

1. **User Inputs**: Choose your target return and select funds.
2. **Data Processing**: The app calculates historical returns, volatilities, and correlations using post-2023 data.
3. **Optimization**: It applies the Markowitz efficient frontier methodology to find the lowest-risk portfolio for the chosen return.
4. **Visualization**: You’ll see intuitive charts showing:
   - Risk-return profiles
   - Optimal asset weights
   - Portfolio vs individual fund performance
   - Probabilities of negative returns across time

---

## 🌐 Try It Now

📍 **Live App**:  
👉 [https://modernportfolio.streamlit.app/](https://modernportfolio.streamlit.app/)

---

## 📎 Tech Stack

- **Python**
- **Streamlit**
- **Pandas / NumPy / SciPy**
- **Matplotlib / Plotly**
- **CVXPY or SciPy Optimize (for quadratic programming)**

---

## 💡 Future Improvements

- Add support for live data via APIs (e.g., Yahoo Finance)
- Include Sharpe Ratio filtering and constraints (e.g., max weight per asset)
- Allow users to upload their own fund return data
- Add Monte Carlo simulation for return projections
