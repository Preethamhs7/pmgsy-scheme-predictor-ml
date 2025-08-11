PMGSY Scheme Classifier

Automatically classify rural infrastructure projects into the correct Pradhan Mantri Gram Sadak Yojana (PMGSY) scheme using IBM Watsonx.ai AutoAI. This project leverages real-world data from AI Kosh and deploys a machine learning model on IBM Cloud for real-time scheme prediction.

 *** Project Overview

This project addresses the challenge of manually classifying road and bridge construction projects under various PMGSY schemes (e.g., PMGSY-I, PMGSY-II, RCPLWEA). By using machine learning, we automate this process based on key attributes like project length, cost, construction year, and location.

*** Tech Stack

IBM Watsonx.ai Studio (AutoAI)

IBM Cloud Object Storage

IBM Watson Deployment (Lite Plan)

CSV dataset from AI Kosh

*** Dataset

Source: AI Kosh – https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html

Format: CSV

Input Features: Length, Cost, Year, State, District, etc.

Target Variable: PMGSY_SCHEME

*** Workflow

1 - Dataset uploaded to IBM Watsonx.ai project

2 - AutoAI experiment run with PMGSY_SCHEME as the target column

3 - Multiple ML pipelines trained and evaluated

4 - Best model selected and saved

5 - Model deployed as an online REST API

6 - Tested with project data for predictions


*** How to Use


Log in to IBM Cloud

1 - Upload dataset as a data asset

2 - Launch AutoAI and select PMGSY_SCHEME as target

3 - Let AutoAI run and rank pipelines

4 - Save, promote, and deploy the best model



*** Future Improvements

Add more features (e.g., terrain, contractor info)

Build a simple web UI for non-technical users

Expand to other rural infrastructure schemes

Enable feedback-based retraining for continuous improvement


*** Author

Preetham H S

Dayananda Sagar University

Department of Computer Science and Engineering

 ***References

AI Kosh PMGSY Dataset 

IBM Watsonx.ai Documentation

Government of India PMGSY Portal
