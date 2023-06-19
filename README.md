# RealTime-Streaming-Data-Pipeline-with-Kafka-and-GCP



## Introduction
The purpose of this project is to develop a real-time streaming data pipeline that generates stock values, ingests them into Apache Kafka, processes the data using a consumer, triggers a Cloud Function to stream the data into BigQuery, and performs analysis on the data by plotting graphs. The pipeline leverages the capabilities of Apache Kafka, Google Cloud Platform (GCP), and various services provided by GCP.

## Pipeline Overview
The pipeline consists of the following steps:

## Stock Value Generation: Python code acts as a producer, generating real-time stock values.
## Kafka Broker Setup: A Kafka broker is set up on a GCP virtual machine to handle data ingestion.
## Data Ingestion: The producer sends the stock values to the Kafka broker for data ingestion.
## Consumer: A consumer application subscribes to the Kafka topic, retrieves the stock values, and processes them.
## Cloud Function: When data is loaded at the consumer, a Cloud Function is triggered to stream the data into BigQuery.
## Data Analysis: The streamed data is stored in BigQuery, allowing for further analysis.
## Graph Plotting: Analysis is performed on the data by plotting graphs to gain insights and visualize the stock trends.

## Pipeline Steps

 Stock Value Generation:

 Implement a Python code that generates random stock values using appropriate libraries (e.g., Pandas, NumPy).
Set up a producer that publishes the generated stock values to the Kafka topic.

 Kafka Broker Setup:

Create a GCP virtual machine instance.
Install and configure Apache Kafka on the virtual machine to act as a broker.
Ensure the Kafka broker is accessible to the consumer and the Cloud Function.
Data Ingestion:

Set up the necessary Kafka topic and partitions for data ingestion.
Ensure the producer is configured to send the generated stock values to the Kafka broker.
Consumer:

Develop a consumer application that subscribes to the Kafka topic and retrieves the stock values.
Implement any necessary data processing or transformations required before streaming to BigQuery.
Cloud Function:

Create a Cloud Function that is triggered when data is loaded at the consumer.
Configure the Cloud Function to stream the data into BigQuery using the BigQuery API or relevant client libraries.
Data Analysis:

Set up a BigQuery table to store the streamed stock values.
Perform analysis on the data stored in BigQuery using SQL queries or data processing libraries available in GCP.
Graph Plotting:

Utilize data analysis libraries such as Matplotlib or Plotly to plot graphs and visualize the stock trends.
Generate meaningful visualizations to gain insights and monitor the performance of the stocks over time.
Conclusion

This project demonstrates the development of a real-time streaming data pipeline using Apache Kafka and Google Cloud Platform (GCP). By generating stock values, ingesting them into Kafka, streaming to BigQuery, and performing analysis with graph plotting, the pipeline enables real-time monitoring and analysis of stock trends. The comprehensive report provides step-by-step instructions for setting up and executing the pipeline. Feel free to customize and enhance the report based on your project's specific details and requirements.


![image](https://github.com/jashshah-dev/RealTime-Streaming-Data-Pipeline-with-Kafka-and-GCP/assets/132673402/2d870876-ab43-40f0-b1e8-1708a1fda45e)
![image](https://github.com/jashshah-dev/RealTime-Streaming-Data-Pipeline-with-Kafka-and-GCP/assets/132673402/95e7a2b8-95c3-4187-b3bf-41caa66435ac)


