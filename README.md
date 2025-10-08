# Intelligent Recruitment Automation Workflow

**Tech Stack:** n8n, OpenAI API, Google Sheets, Gmail API, Web Forms, JSON, HTTP Requests

## Overview
This project is an **AI-powered recruitment automation workflow** designed to streamline candidate evaluation and shortlisting. It collects candidate data via web forms, categorizes profiles by role (e.g., AI Developer, Frontend Developer, Backend Developer), and performs AI-based analysis to generate actionable insights.

## Features
- **Automated Data Collection:** Gathers candidate details through web forms and stores them in Google Sheets.
- **Role-Based Categorization:** Classifies candidates into specific job roles for targeted evaluation.
- **AI-Powered Resume Analysis:** Evaluates resumes to highlight strengths, weaknesses, and performance insights.
- **Integrated Scoring & Recommendations:** Provides a scoring system and AI-generated recommendations to simplify shortlisting.
- **Seamless Communication:** Sends notifications and updates to candidates via Gmail API.

## Workflow Architecture
1. **Form Submission → Google Sheets:** Candidate data is automatically captured.
2. **Data Processing → n8n & AI:** Profiles are analyzed using OpenAI API and scored based on predefined criteria.
3. **Shortlisting & Notifications → Gmail API:** Top candidates are flagged, and emails are sent automatically.

## Purpose
This workflow reduces manual effort in recruitment, ensures objective candidate evaluation, and accelerates the hiring process through intelligent automation.

## Getting Started
To use this workflow:
1. Clone the repository.
2. Set up n8n on your machine or server.
3. Configure API keys for OpenAI, Gmail, and Google Sheets.
4. Import the workflow `.json` file into n8n.
5. Customize forms, scoring criteria, and email templates as needed.
