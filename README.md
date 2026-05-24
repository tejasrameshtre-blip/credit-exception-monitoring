# Credit Exception Monitoring System

An automated data pipeline built in **n8n** that monitors credit risk datasets, filters for exceptions, logs them to Google Sheets, and sends a daily summary report via Gmail.

## 🚀 What this does
- **Automatic Scheduling**: Runs daily to stay updated.
- **Data Filtering**: Identifies credit exceptions automatically.
- **Centralized Logging**: Appends all exceptions to a Google Sheet "Master CRRT" audit trail.
- **Automated Reporting**: Sends a summary email with risk metrics to the relevant stakeholders.

## 🛠 Tech Stack
- **n8n**: Workflow automation platform.
- **Google Sheets API**: Data storage and audit trail.
- **Gmail API**: Automated reporting.

## 📝 Setup Instructions
1. Import the `workflow_name.json` file into your n8n instance.
2. Configure your Google Sheets and Gmail credentials in the respective nodes.
3. Update the filter criteria in the "Filter" node to match your specific risk thresholds.
4. Toggle "Publish" to activate the automated schedule.

---
*Built as a production-grade automated credit risk monitoring tool.*
