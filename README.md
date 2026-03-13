# AI News Agent (n8n Workflow)

An automated AI-powered news assistant built using n8n.
The workflow generates personalized news queries using an LLM, retrieves relevant articles from Google News RSS feeds, and sends a curated morning news briefing via email.

## Features

* AI generates news search queries dynamically
* Supports multiple domains such as AI, sports, and regional news
* Fetches real-time articles from Google News RSS
* Sends automated daily news emails
* Optional chat interface for selecting user preferences
* Fully automated using scheduled triggers

## Workflow Overview

User preference → LLM generates queries → RSS news fetch → format news → email delivery

## Technologies Used

* n8n workflow automation
* Groq LLM API
* Google News RSS feeds
* Node.js environment

## Example Use Case

The workflow can run daily at 8 AM to deliver personalized news summaries based on user interests such as:

* AI and technology
* Sports updates
* Regional news
* Global events

## Importing the Workflow

1. Open n8n
2. Click **Import Workflow**
3. Upload the `workflow.json` file
4. Add your API credentials

## Disclaimer

This project is for educational and demonstration purposes.
News content is sourced from publicly available RSS feeds.

