# Public Procurement AI Monitoring System

![Project Logo](insert_logo_url_here)

## Table of Contents

- [About the Project](#about-the-project)
- [Files Included](#files-included)
- [Screenshots](#screenshots)
- [How It Works](#how-it-works)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About the Project

The **Public Procurement AI Monitoring System** is an innovative solution aimed at revolutionizing the monitoring of public procurement, supply chain management, and asset acquisition processes. By leveraging AI technology, this system verifies and assesses submitted proposals, tenders, and bids before the sealed physical tender dossier opening meetings, providing valuable insights to procurement departments. This project aims to streamline and enhance the procurement process for both suppliers and procurement authorities.

## Files Included

- `bid_2.txt`: Sample bid file for testing.
- `bid_scoring2.h5`: Pre-trained AI model for bid scoring.
- `3,457 mohtaseb.ipynb`: Jupyter Notebook containing code for the AI system.

## Screenshots

![Screenshot 1](insert_screenshot_url_here)
![Screenshot 2](insert_screenshot_url_here)

## How It Works

Our system operates as follows:

1. **Submission Verification**: Suppliers submit sealed physical dossiers and electronic copies to an independent repository system managed by an AI interface.

2. **AI Analysis**: The AI system reviews and analyzes the submitted offers, comparing them to predefined keywords and historical procurement data.

3. **Report Generation**: Reports are generated for each keyword, detailing how the submitted dossier corresponds to those keywords. A separate numerical report compares the costs submitted by each supplier.

4. **Cost Comparison**: The system uses statistical and graph-making modules to rank cost items from highest to lowest.

5. **Recommendation**: The AI system combines keyword analysis and cost comparison to recommend the selected winner of the tender. However, the contracting & procurement committee can override the AI's recommendation with a justification.

6. **Feedback**: Non-successful bidders receive electronic notifications and can voice grievances within one week. The AI system redacts confidential data from committee reports if a bidder contests the decision.

## Features

- Automated keyword analysis of bid submissions.
- Comparative cost analysis for

