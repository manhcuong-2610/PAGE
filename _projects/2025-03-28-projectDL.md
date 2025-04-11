---
title: "Stock market prediction"
date: 2025-03-28
collection: projects
permalink: /projects/2025-03-28-projectDL/
excerpt: "Deep Learning project"
notebook_url: "/PAGE/files/LSTM.html"
---
## Overview

This project focused on creating a predictive model for next-day stock market returns using historical daily percentage movements from 442 companies between April 2010 and March 2022. Conducted as part of a Kaggle competition, participants were initially ranked based on 50% of results in the public leaderboard, with final results released on a private leaderboard. Key tasks included thorough data preprocessing, constructing sequence-based data loaders for time-series forecasting, and building a Recurrent Neural Network (RNN) structure. I chose a Long Short-Term Memory (LSTM) model, refined through extensive hyperparameter tuning via Optuna (e.g., cross-validation on hidden layers, neuron counts, learning rates and other metrics related to regularization). The model was trained and evaluated using Mean Squared Error (MSE) as the main metric to measure its predictive accuracy.

**My Kaggle notebook:** [Click here to view the notebook]({{ page.notebook_url }})
