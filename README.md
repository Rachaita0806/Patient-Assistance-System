# 🏥 Patient Assistance System

A UiPath automation solution designed to assist with patient-related workflows through automated query handling, severity analysis, doctor approval, and email generation.

## 📌 Overview

The Patient Assistance System is a multi-component UiPath solution that automates different stages of a patient assistance workflow.

It includes specialized applications and automation agents for handling patient queries, analyzing severity, obtaining doctor approval, and generating emails.

## 🚀 Components

### 1. Doctor Approval App
Handles the doctor approval stage of the patient assistance workflow.

### 2. Query Assistance Agent
Assists with processing and responding to patient-related queries.

### 3. Severity Analysis Agent
Analyzes the severity of a patient's situation and helps determine the appropriate workflow.

### 4. Email Generation Agent
Generates email content based on the relevant patient workflow and information.

### 5. Send Email
Automates sending the generated email through the configured UiPath connection.

### 6. Flow
Coordinates the different components of the patient assistance process.

## 🔄 Workflow

```text
Patient Query
      ↓
Query Assistance
      ↓
Severity Analysis
      ↓
Doctor Approval
      ↓
Email Generation
      ↓
Send Email
```
🛠️ Technologies
* UiPath Studio Web
* UiPath Apps
* UiPath Automation
* UiPath Agents
* Workflow Automation
* Gmail integration

## 📂 Project Structure

```text
Patient-Assistance-System/
│
├── DoctorApprovalApp/
├── Email_Generation_Agent/
├── Query_Assistance_Agent/
├── Severity_Analysis_Agent/
├── Flow/
├── Send_Email/
├── resources/
├── SolutionStorage/
└── Patient Assistance System.uipx
```

## ⚙️ Setup

* Open the project in UiPath Studio Web.
* Configure the required UiPath connections.
* Make sure the required resources and integrations are available.
* Open and run the required workflow/application.

## 🔐 Security
No passwords, API keys, access tokens, or other authentication credentials are included in this repository.
Required connections and authentication should be configured securely through UiPath.

## 📄 Note
This repository contains the project files for the Patient Assistance System and is intended for demonstration and educational purposes.
