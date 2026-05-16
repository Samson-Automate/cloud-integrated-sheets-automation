# Cloud-Integrated Financial Market Tracker & Google Sheets Dashboard

A production-ready Python automation tool engineered to sync dynamic asset price data directly into cloud-based Google Sheets dashboards. The system runs completely in the background, calculates 24-hour performance trends, applies localized accounting formats, and updates the remote sheet cells using Google Cloud API frameworks.

## Key Features

* Autonomous Cloud Sync: Integrates seamlessly with the Google Sheets API for fast cell writing streams.
* Smart Data Formatting: Automatically applies uniform tabular layouts, localized currency formatting, and positive/negative mathematical trend indicators.
* Fault-Tolerant Engine: Features built-in logic to execute stable database simulation loops without hitches.
* Lightweight Footprint: Operates entirely inside background daemon workers without requiring heavy, resource-intensive browser processes.
* Clean Environment Decoupling: Zero hardcoded project settings. Runtime configurations are managed via an external metadata architecture.

## Tech Stack

* Core Language: Python 3.8+
* API & Integration Ecosystem: gspread API Engine, Requests HTTP Client
* External Cloud Infrastructure: Google Cloud Platform (Sheets & Drive API Integrations)
* Orchestration Worker: Python-Schedule Loop Scheduler

## System Architecture Workflow

Below is the conceptual architecture showing how the automated pipeline schedules tasks, processes market data, and triggers updates:

<img width="1264" height="842" alt="image_5c250b9a" src="https://github.com/user-attachments/assets/635a7d08-6c36-4ebf-899a-422cebf44238" />

## Repository File Structure

```text
├── config.json          # Application configuration settings
├── requirements.txt     # Environment package dependency checklist
└── sheets_automation.py # Main core script engine controller
```

## Quick Start Configuration Guide

To deploy and execute this tracking system, you must link the application script cleanly to your private Google Cloud platform by generating a secure verification credential file.

### 1. Project Files Deployment
Clone or download the complete suite of repository files directly to your machine workspace directory folder.

### 2. Standard Environment Configuration
Open your host machine terminal command screen inside the root directory and install all required framework packages:
```bash
pip install -r requirements.txt
```

### 3. Generate Your Google Cloud API Key (credentials.json)
* Access the Google Cloud Platform Console console (://google.com) and set up a new project space named `Sheets-Automation`.
* Use the top search index bar to locate the **Google Sheets API** and select **Enable**.
* Repeat the exact step for the **Google Drive API** to grant complete remote sheet matrix operational authorization access.
* Navigate to **APIs & Services > Credentials**, click **+ Create Credentials**, and provision a new **Service Account**. Label it `sheets-bot`.
* Click on the newly registered Service Account email string identity link from the list, click the top **Keys** tab framework option, select **Add Key > Create new key**, tick the **JSON** formatting box layout, and save the generation action block.
* Move the newly downloaded file directly into your Python root code installation directory and change its filename to exactly: `credentials.json`

### 4. Create and Share Your Google Spreadsheet Workspace
* Open your browser sheet utility framework workspace and construct a new sheet titled exactly: `Live Market Tracker`
* Keep the first worksheet tab name on the standard system default label format (`Sheet1`).
* Open your local `credentials.json` data block inside any plain notepad editor, locate the entry row line string parameter key named `"client_email"`, and duplicate the exact unique address string.
* Click the blue **Share** options button on your open Google Sheet canvas window dashboard, insert the copied client email identity string, designate the access verification authority authorization tier role to **Editor**, and save the permissions block.

### 5. Review Metadata Settings (config.json)
Ensure your target sheet naming rules align properly inside the configuration metadata blueprint profile file before triggering runtime execution paths:
```json
{
    "google_sheet_name": "Live Market Tracker",
    "check_interval_seconds": 10,
    "target_cryptos": ["bitcoin", "ethereum", "solana", "cardano", "ripple"],
    "vs_currency": "usd"
}
```

### 6. Execute Application Monitor
Launch the loop framework operation sequence via your terminal prompt:
```bash
python sheets_automation.py
```

## System Operational Previews

### 1. Remote Cloud Dashboard Interface
Below is the live operational layout capture showcasing the automated tracking data grid seamlessly organized into production clean columns inside the active remote cloud dashboard workspace:

<img width="1366" height="610" alt="dashboard_preview jpg" src="https://github.com/user-attachments/assets/dae9a67b-6e7c-4bdd-a53d-a55bbbe24aad" />

### 2. Live Automation Server Control Logs
Below is the live background worker execution loop showcasing flawless sub-second data pooling transactions and rapid cloud matrix data-stream write synchronizations:

<img width="980" height="511" alt="terminal_logs jpg" src="https://github.com/user-attachments/assets/fb089d78-f5aa-4925-aae1-ac3ce22d377c" />

## Commercial & Enterprise Business Value

* Operational Overhead Mitigation: Transforms slow and tedious manual data logging routines into rapid, sub-second autonomous pipelines.
* Universal Data Distribution: Maps local execution code paths to accessible cloud environments, enabling cross-team performance audits without installation bottlenecks.
* Production Reliability: Implements robust error protection models to secure continuous performance runs without data loss or memory leaks.

## Contact & Professional Collaboration

If you require custom software engineering solutions, data pipelines, web scrapers, or direct cloud synchronization systems configured precisely for your corporate workflow frameworks, reach out anytime:

* Email: samson.automates@gmail.com
* X (Twitter): [Twitter/X Profile](https://x.com/Samson_Automate/)
* Discord: `samson005473`

Need help deploying this script or want a custom automation solution built for your specific business requirements? Let's connect and discuss your project.

Thanks and Best Regards,
Samson
