# Real-Time Cryptocurrency Price Forecasting System

## Authors
- Yi-Chun Huang

## Introduction
This repository contains the environment and documentation for a real-time cryptocurrency price forecasting system. The system is designed to efficiently ingest and process high-velocity data from the CoinCap API, apply an ARIMA model for forecasting, store the results in a MySQL database, and visualize the data using Grafana. 

### Additional Keywords
Data Engineering, Real-time Data Processing, Cryptocurrency Price Forecasting, Apache NiFi, Python, ARIMA Model, MySQL, Grafana, CoinCap API

## Background
Cryptocurrency price forecasting has become increasingly important in the financial world. Various methods have been used to predict cryptocurrency prices, including traditional statistical models and complex machine learning algorithms. One widely applied method is the ARIMA model, known for its effectiveness in time series forecasting.

## Datasets and Characteristics
The data used for this project is sourced from the CoinCap API, a reliable resource for real-time cryptocurrency data. The data is characterized by its high volume, frequent updates, authenticity, diversity, and real-time nature.

## Design Approach
The system is designed as a data processing pipeline with several stages:
1. **Ingestion:** Data is ingested in real-time from the CoinCap API using Apache NiFi.
2. **Transformation:** Data is cleaned and prepared for analysis, including data consistency and error handling.
3. **Analysis:** An ARIMA model implemented in Python is used for forecasting.
4. **Storage:** The raw and forecasted data is stored in a MySQL database.
5. **Visualization:** Grafana is used to create interactive dashboards for visualizing the data and predictions.

![Pipeline Design](images/pipeline.jpeg)

## Implementation
The implementation stack includes Apache NiFi, Python, MySQL, and Grafana, all integrated within Docker containers. Apache NiFi handles data ingestion and transformation, Python implements the ARIMA model, MySQL stores the data, and Grafana provides data visualization.

## Evaluation
The system has been found to efficiently handle real-time data ingestion, transformation, and storage. The ARIMA model performs well, and Grafana provides valuable data visualization capabilities.

## Concluding Remarks
This project demonstrates the power of a well-designed data engineering pipeline for real-time data processing. While the system is effective, there is room for improvement, such as integrating offline optimization and experimenting with different forecasting models.

## References

<a id="1">[1]</a> Brett Scott, John Loonam, and Vikas Kumar. Exploring the rise of blockchain technology: Towards distributed collaborative organizations. Strategic Change, 26(5):423–428, 2017.

<a id="2">[2]</a> Shakir Khan and Hela Alghulaiakh. ARIMA model for accurate time series stocks forecasting. International Journal of Advanced Computer Science and Applications, 11(7), 2020.

<a id="3">[3]</a> Ahmed M Khedr, Ifra Arif, Magdi El-Bannany, Saadat M Alhashmi, and Meenu Sreedharan. Cryptocurrency price prediction using traditional statistical and machine-learning techniques: A survey. Intelligent Systems in Accounting, Finance and Management, 28(1):3–34, 2021.

<a id="4">[4]</a> M Poongodi, V Vijayakumar, and Naveen Chilamkurti. Bitcoin price prediction using ARIMA model. International Journal of Internet Technology and Secured Transactions, 10(4):396–406, 2020.

<a id="5">[5]</a> K Dhinakaran, J Divya, C Indhumathi, R Asha, et al. Cryptocurrency exchange rate prediction using ARIMA model on real time data. In 2022 International Conference on Electronics and Renewable Systems (ICEARS), pages 914–917. IEEE, 2022.

<a id="6">[6]</a> Shubhankar Mohapatra, Nauman Ahmed, and Paulo Alencar. KryptoOracle: a real-time cryptocurrency price prediction platform using twitter sentiments. In 2019 IEEE international conference on big data (Big Data), pages 5544–5551. IEEE, 2019.

<a id="7">[7]</a> Jiwon Bang and Mi-Jung Choi. Design and implementation of storage system for real-time blockchain network monitoring system. In 2019 20th Asia-Pacific Network Operations and Management Symposium (APNOMS), pages 1–4. IEEE, 2019.
