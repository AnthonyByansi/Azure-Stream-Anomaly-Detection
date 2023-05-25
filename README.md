# Azure-Stream-Anomaly-Detection

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/travis/{username}/{repository}.svg)](https://travis-ci.org/{username}/{repository})
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/release/python-370/)

> Real-time Anomaly Detection: Build a system that monitors streaming data from various sources and uses Azure Stream Analytics to detect anomalies in real-time.

![Architecture Diagram](architectural_diagram.png)

## Overview

This project aims to build a real-time anomaly detection system that monitors streaming data from various sources (sensors, logs, IoT devices, etc.). The system utilizes Azure Stream Analytics to process the streaming data and applies machine learning algorithms to detect abnormal patterns or unexpected behavior. It triggers alerts or actions based on the detected anomalies.

### The main components of the project include:

- **Data Ingestion**: Set up data ingestion from various sources, such as Azure Event Hubs or IoT Hubs.
- **Preprocessing**: Prepare the streaming data by cleaning, transforming, and normalizing it for analysis.
- **Feature Engineering**: Extract relevant features from the data to aid in anomaly detection.
- **Model Selection and Training**: Choose and train a suitable machine learning algorithm to detect anomalies.
- **Azure Stream Analytics Integration**: Configure Azure Stream Analytics to process streaming data and apply the trained model in real-time.
- **Alerts and Actions**: Define criteria for triggering alerts or actions based on detected anomalies.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository:

   ```shell
   git clone 
