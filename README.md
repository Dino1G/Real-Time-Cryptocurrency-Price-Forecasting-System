# Real-Time Cryptocurrency Price Forecasting System

## Introduction

This repository contains the design and implementation of a real-time data processing pipeline for cryptocurrency price forecasting. The system, built using Docker, NiFi, Python, MySQL, and Grafana, efficiently ingests and transforms high-velocity data from the CoinCap API. A Python-implemented ARIMA model is used for the forecasting task. The results, stored in a MySQL database, are visualized using Grafana, demonstrating the effectiveness of a well-structured data processing pipeline in extracting valuable insights from real-time data.

## Key Features

- Data Engineering
- Real-time Data Processing
- Cryptocurrency Price Forecasting
- Apache NiFi
- Python
- ARIMA Model
- MySQL
- Grafana
- CoinCap API

## ACM Reference

Yi-Chun Huang. 2023. Real-Time Cryptocurrency Price Forecasting System: Design and Implementation of a Data Engineering Pipeline. 1, 1 (May 2023), 7 pages. [DOI](https://doi.org/10.1145/nnnnnnn.nnnnnnn)

## Background

The field of cryptocurrency price forecasting has been an active area of research and development, spurred by the dramatic rise of digital currencies over the past decade. Various approaches have been employed to tackle this problem, ranging from traditional statistical to complex machine learning algorithms.

## Datasets and Characteristics

The data for this project is sourced from the CoinCap API, which provides real-time data on countless cryptocurrencies. The data is characterized by its volume, authenticity, diversity, and real-time nature, making it ideal for predicting cryptocurrency prices.

## Design Approach

The data pipeline consists of several interrelated stages:
1. Ingestion
2. Transformation
3. Analysis
4. Storage
5. Visualization

Each stage is designed for efficiency and reliability.

## Implementation

The implementation stack includes:
- Apache NiFi
- Python
- MySQL
- Grafana

These technologies are integrated in a Docker environment to create a seamless data processing pipeline.

## Evaluation

The system performed effectively in handling real-time data streams and predicting cryptocurrency prices. Observations were made regarding the performance of each component of the pipeline.

## Concluding Remarks

The project highlighted the importance of a well-designed data engineering pipeline in handling real-time data effectively. It also emphasized the need for ongoing monitoring and optimization.
