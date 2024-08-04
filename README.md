# Customer Sentiment Analysis with Google Cloud Platform

## Overview

This project demonstrates how to leverage Google Cloud Platform (GCP) services to automate sentiment analysis of customer reviews and generate actionable insights. The pipeline integrates data collection, sentiment analysis, insights generation, and visualization using BigQuery, Cloud Natural Language API, Vertex AI, Looker, and Gradio.

## Features

- **Data Collection:** Retrieves customer reviews from Google Places API and stores them in BigQuery.
- **Sentiment Analysis:** Analyzes review sentiment using Google Cloud Natural Language API.
- **Insights Generation:** Uses Vertex AI to generate actionable insights and summaries from sentiment data.
- **Visualization:** Creates interactive dashboards with Looker for visualizing sentiment trends and insights.
- **Interactive Interface:** Provides a Gradio interface for real-time sentiment analysis and insights.

## Architecture

1. **Data Collection & Storage:** 
   - Uses Python and APIs to collect and store customer reviews in BigQuery.

2. **Sentiment Analysis:**
   - Employs Google Cloud Natural Language API to analyze and categorize review sentiment.

3. **Generative Insights:**
   - Leverages Vertex AI to train models and generate insights from sentiment data.

4. **Visualization:**
   - Utilizes Looker to create dashboards for visualizing sentiment data.

5. **User Interaction Enhancement:**
   - Integrates Gradio to provide real-time interactive sentiment analysis.

## Prerequisites

- Python 3.x
- Google Cloud SDK
- Google Cloud account with BigQuery, Vertex AI, and Natural Language API enabled
- Gradio for interactive interfaces
- Required Python libraries

## Installation and Usage

For Installation and usage, follow my blog for all the step-by-step instructions to build this project: [Project Saadhna: Customer Sentiment Analysis for Retail](https://medium.com/@mihika.khemka/project-saadhna-customer-sentiment-analysis-for-retail-434ccf4e789c)

## License

This project is licensed under the APACHE 2.0 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Google Cloud Platform for providing robust tools for sentiment analysis and data visualization.
- Gradio for enabling interactive interfaces.
- Looker for powerful data visualization capabilities.

