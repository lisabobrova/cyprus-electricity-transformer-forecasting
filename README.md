# Transformer-Based Forecasting of Cyprus Day-Ahead Electricity Prices

This repository contains work completed during my Summer Research Internship at the PHAETHON Centre of Excellence.

The project investigates the use of transformer-based deep learning models to analyse and forecast sharp price movements and Day-Ahead electricity prices in the Cyprus electricity market.

## Project Overview

The project focused on predicting the timing of significant price movements in the Cyprus Day-Ahead electricity market and using these predictions to support electricity-price forecasting.

The work progressed from controlled experiments on synthetic time series to applications using real electricity-market data.

## Methodology

Transformer-based models were used for both classification and forecasting tasks.

For the sharp-movement classification task, market forecast variables were used to predict the probability of a significant price movement during each market interval.

These predicted probabilities were subsequently used to identify meaningful regions within the forecast day. Separate transformer-based forecasting models were then applied to the resulting price segments.
