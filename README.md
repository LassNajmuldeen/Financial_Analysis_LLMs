# Financial_Analysis_LLMs


# Overview
This project made for my SWE recidency at Headstarter uses LLMS to automate financial analysis. Built on Google Colab, it enables advanced capabilities such as analyzing financial datasets, generating reports, scraping websites, and extracting sentiment from news articles.

# Technologies and APIs
- Hugging Face Transformers: Used for sentiment analysis and event classification.
- LangChain: Managing embeddings and vector stores.
- OpenAI: LLM-powered natural language processing.
- Yahoo Finance API: For fetching financial news articles.
- BeautifulSoup: For web scraping.
  
# Core Features
- Research Automation: Search stocks on the NYSE using natural language queries or by metrics like Market Cap and Sector.
- Market Firehose: Process hundreds of articles per minute, extracting structured data (publisher, sentiment, related companies).
- Market Analysis: Analyze articles to classify event types, determine company sentiment, and provide actionable insights in near real-time.

# Getting Started
Run the project directly in Google Colab using the provided notebooks. Ensure all dependencies are installed and the API key is configured in a .env file.
