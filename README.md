PMGSY Scheme Classifier

Automatically classify rural infrastructure projects into the correct Pradhan Mantri Gram Sadak Yojana (PMGSY) scheme using IBM Watsonx.ai AutoAI. This project leverages real-world data from AI Kosh and deploys a machine learning model on IBM Cloud for real-time scheme prediction.

 Project Overview

This project addresses the challenge of manually classifying road and bridge construction projects under various PMGSY schemes (e.g., PMGSY-I, PMGSY-II, RCPLWEA). By using machine learning, we automate this process based on key attributes like project length, cost, construction year, and location.

 Tech Stack

IBM Watsonx.ai Studio (AutoAI)
IBM Cloud Object Storage
IBM Watson Deployment (Lite Plan)
CSV dataset from AI Kosh

 Dataset

Source: AI Kosh – https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html
Format: CSV
Input Features: Length, Cost, Year, State, District, etc.
Target Variable: PMGSY_SCHEME

 Workflow

Dataset uploaded to IBM Watsonx.ai project

AutoAI experiment run with PMGSY_SCHEME as the target column

Multiple ML pipelines trained and evaluated

Best model selected and saved

Model deployed as an online REST API

Tested with project data for predictions


 How to Use

Option 1: IBM Watsonx.ai GUI

Log in to IBM Cloud

Upload dataset as a data asset

Launch AutoAI and select PMGSY_SCHEME as target

Let AutoAI run and rank pipelines

Save, promote, and deploy the best model



 Future Improvements

Add more features (e.g., terrain, contractor info)

Build a simple web UI for non-technical users

Expand to other rural infrastructure schemes

Enable feedback-based retraining for continuous improvement


 Author

Preetham H S-
Dayananda Sagar University-
Department of Computer Science and Engineering

 References

AI Kosh PMGSY Dataset-
IBM Watsonx.ai Documentation-
Government of India PMGSY Portal
