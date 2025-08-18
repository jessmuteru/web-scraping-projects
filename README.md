# Web scraping project using Jupyter and PythonAnywhere
Web scraping is an essential part for data mining. This repository contains two web scraping projects designed for data mining, enabling the collection of structured data from sources not readily available in pre-cleaned formats like CSV. The projects focus on extracting data from a clothing website and news articles related to AI, data science, data analytics, and data jobs using the NewsAPI. These datasets are valuable for market research, trend analysis, and staying informed on industry developments.

## projects Overview
1. **Clothing website data scraping**
This project scrapes product data from a clothing website, capturing details such as product names, prices, categories, and other relevant attributes.

**Use case**
- Market Research: Analyze price points across different outfit types (e.g., shirts, pants, dresses) to understand pricing strategies.
- Competitor Analysis: Compare prices with other clothing retailers to calculate market averages and identify competitive positioning.
- Benchmarking: Provide insights for retailers, analysts, or consumers to assess value propositions and trends in the fashion industry.

**Data extracted**
- Brand
- Product name
- Price
- Image url
- product url


2. **News API data scraping**
- This project fetches news articles related to artificial intelligence, data science, data analytics, and data jobs using the NewsAPI, saving them to a CSV and emailing the results weekly.

**Use case**
- Trend Monitoring: Keeps users informed about the latest developments in AI, data science, analytics, and related job markets.
- Research and Analysis: Provides a dataset for analyzing trends, innovations, or job market shifts in the data and AI fields.
- Industry Updates: Useful for professionals, researchers, or enthusiasts to stay updated without manual news aggregation.

### Tools Used
1. Jupyter Notebook: Used for prototyping, testing, and debugging scripts interactively before deployment.
2. PythonAnywhere: A cloud platform for hosting and scheduling Python scripts. Used to run the NewsAPI script daily and send weekly emails.
3. Grok: AI assistant (by xAI) used for generating, debugging, and optimizing the NewsAPI script, including fixing errors like NoneType.
4. ChatGPT: Provided initial script ideas and implementation guidance for both projects.
5. Python Libraries:
-requests: For making HTTP requests to NewsAPI or website scraping.
-pandas: For structuring and saving data to CSV.
-smtplib, email.mime: For sending emails with CSV attachments.
-BeautifulSoup.
-NewsAPI: External API for fetching news articles .