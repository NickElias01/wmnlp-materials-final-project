# wmnlp-materials-final-project
Week 7 Custom Web Scraping project


This project aims to leverage the Amazon API to gather and analyze user reviews for a specific coffee machine model. By scraping data such as review ratings, customer feedback, and product details, the project will provide insights into customer satisfaction, common issues, and overall product performance. The goal is to create a comprehensive dataset that can be used for further analysis, such as sentiment analysis or trend identification, to help consumers make informed decisions based on peer experiences.

Dependencies needed for this project:
- Boto3: Amazon's official SDK for Python to interact with AWS services and access the Amazon API.
- Requests: For making HTTP requests to access web pages or APIs.
- BeautifulSoup (optional): If you plan to scrape data from Amazon's web pages directly (in addition to the API).
- Pandas: For managing and analyzing the collected data.
- Amazon Product Advertising API: You'll need to set up and configure access to Amazon’s API to retrieve reviews and product information. Make sure to generate an API key via the Amazon Developer Portal.
- JSON: Useful for working with the response data from the API.
