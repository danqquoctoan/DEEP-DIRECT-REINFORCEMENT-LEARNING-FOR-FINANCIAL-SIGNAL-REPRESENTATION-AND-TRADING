# Deep Direct Reinforcement Learning for Financial Signal Representation and Trading

[![Project Status](https://img.shields.io/badge/Status-Thesis%20Project-blue.svg)](https://github.com/your-github-username/your-repo-name)  <!-- Replace with your repo link -->
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) <!-- Optional: Add your license file and link, if applicable -->

## Overview

This project explores the application of **Deep Direct Reinforcement Learning (DRL)** for automated financial signal representation and trading. It is a research project conducted at the **Faculty of Information Technology, Industrial University of Ho Chi Minh City**.

The core objective is to develop a computational agent capable of **outperforming experienced human traders** in financial markets.  This is achieved by training a system that can:

* **Represent complex financial signals effectively.**
* **Make real-time trading decisions autonomously.**

The project introduces a novel architecture based on a **Recurrent Deep Neural Network (RDNN)** combined with **Fuzzy Logic** to address the challenges of financial trading, such as noisy data, market volatility, and the need for robust decision-making under uncertainty.

## Methodology

This project leverages a combination of advanced techniques:

* **Deep Direct Reinforcement Learning (DRL):**  A reinforcement learning approach where the agent directly learns a policy (trading actions) from raw financial data, without relying on traditional value function approximation methods for complex, continuous action spaces.
* **Recurrent Deep Neural Network (RDNN):**  A deep neural network architecture with recurrent connections. The RDNN is used to:
    * **Capture temporal dependencies** in financial time series data.
    * **Represent market conditions** by learning powerful feature representations directly from the data.
    * **Incorporate memory** of past trading actions and market states to make informed decisions.
* **Fuzzy Logic:** Integrated to address the inherent **uncertainty and noise** in financial markets. Fuzzy logic is used in the input representation layer to:
    * **Reduce data uncertainty** by mapping raw numerical data to fuzzy sets (representing concepts like "increase," "decrease," "no trend").
    * **Improve robustness** and stability of the trading agent by handling imprecise and ambiguous financial signals.
* **Task-Aware Backpropagation Through Time (Task-Aware BPTT):** A modified BPTT algorithm tailored for the RDNN architecture to address the vanishing gradient problem and improve training efficiency in deep and recurrent networks. This method propagates gradients directly from the task objective (profit maximization) to deeper layers, enhancing learning in complex sequential decision-making tasks.

## Key Features & Findings

* **Novel RDNN-Fuzzy Architecture:**  Introduces a unique deep learning architecture combining RDNNs and Fuzzy Logic for financial trading.
* **Robust Feature Learning:** The RDNN component enables automatic and effective feature extraction from complex financial time series, surpassing traditional handcrafted technical indicators.
* **Enhanced Decision Making:**  The DRL framework allows the agent to learn optimal trading policies directly from market interactions, adapting to dynamic market conditions.
* **Uncertainty Handling:** Fuzzy logic integration improves the system's ability to handle noisy financial data and make more stable and reliable trading decisions.
* **Empirical Validation:** The system was tested on real-world financial market data for futures contracts, demonstrating its potential to generate consistent profits across various market conditions and outperform other trading strategies.

## Installation 
* Required Libraries (Example - adjust based on your actual project):

Python (>= 3.7 recommended)

TensorFlow/Keras (or PyTorch for Deep Learning)

NumPy

Pandas

... (Add other libraries like scikit-fuzzy if used for Fuzzy Logic, etc.)

## Results
* The thesis provides detailed experimental results and performance evaluations. Key findings are visualized and summarized within the thesis document, demonstrating the effectiveness of the proposed DRNN-Fuzzy architecture.

* Refer to the figures within the thesis document (like "Cumumlative profit through time step" and "Avg300 training steps") for visual representations of the results.

**Authors**
* Đặng Quốc Toàn - 20051051

* Nguyễn Trường Chinh - 20045391

* Đỗ Thu Đông - 20043131

* Faculty of Information Technology, Industrial University of Ho Chi Minh City
* Year: 2024
