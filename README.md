# Healthcare_monitoring_by_Anirudra_Makur
📌 Overview
This project demonstrates an integrated healthcare monitoring solution using Microsoft Power Platform, SharePoint, Power BI, and AI (Google Colab). It enables predictive healthcare monitoring by collecting patient data, analyzing health metrics, and triggering alerts for critical conditions.
The solution includes:

1.PowerApps for patient data entry and mobile-friendly UI.

2.SharePoint as a secure backend for storing patient records.

3.Power Automate for automated email alerts.

4.Power BI dashboards for real-time analytics.

5.AI Model built in Google Colab for predictive analysis.

🛠 Features

Patient Data Entry via PowerApps.

SharePoint Lists for structured data storage.

Automated Alerts using Power Automate.

Predictive Analysis using Python (Random Forest Classifier).

Interactive Dashboards in Power BI hosted on SharePoint.

#🚀 Setup Instructions
1. Import PowerApps App

Go to Power Apps → Solutions → Import.
Upload AppPackage.zip.

2. Configure SharePoint

Create a SharePoint site.
Import SharePointSchema.xml or manually create the list with columns:

PatientName, PatientID, Gender, BloodPressure, SugarLevel, OxygenSaturation, PredictionResult, DoctorEmail.



3. Power Automate Flow

Create a flow with SharePoint trigger and Email action.
Configure to send alerts when new patient data is added.

