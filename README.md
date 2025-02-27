# Builders-Bootcamp-HW3-
Build an Automation with an LLM: 
# Description: BGP LLM based Anomaly Detection Pipeline¶
# Powered by Scikit-Learn and LLaMA2 via Ollama

This software provides an automated pipeline for BGP anomaly detection, integrating:

    Scikit-learn for data preprocessing
    Ollama-hosted LLaMA2 for AI-powered classification
    Pandas & NumPy for dataset handling

It loads BGP data from RIS (Routing Information Service), preprocesses it using a Scikit-learn pipeline, and classifies entries as "normal" or "abnormal" using an AI-driven anomaly detection approach.
Features

    Preprocesses BGP data (missing values, scaling, encoding)
    Uses LLaMA2 AI Model for anomaly detection via Ollama
    Fully automated pipeline using Scikit-learn
    Locally hosted, no external dependencies

# Usage

To run this notebook, install dependencies:

    * pip install scikit-learn pandas requests jupyter
    * Start the Ollama server: (Download the server and model from : https://ollama.com/)
     ollama serve
