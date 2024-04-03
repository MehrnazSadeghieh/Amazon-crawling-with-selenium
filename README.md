# Amazon Crawling with selenium
This project utilizes Selenium on Google Colab to crawl the Amazon website, extracting key features from each product. The extracted features include:

- Name of the product
- Price of the product
- Description
- Rating of the product
- Top 10 reviews
- URL of the product image
- Links to 2 unique similar items

## Process

1- Crawling:
- Using Selenium, the project navigates Amazon's website to extract the specified features from various products.

2- Data Conversion:
- The collected information for each product is compiled into a JSON file.

3- Elasticsearch Integration:
- The JSON file is indexed into Elasticsearch for efficient querying.

## Features

- Amazon Crawler: Utilizes Selenium for web scraping.
- Data Extraction: Extracts specific product features outlined above.
- JSON Conversion: Compiles extracted data into a JSON file.
- Elasticsearch Queries: Executes queries on the gathered information using Elasticsearch.

## Installation

In order to work with elasticsearch you have to run elastic search and use the API key and Cloud ID inorder to work with elasticsearch in colab.

## usage
in order to work with the `Elastic_Search`, first download the json file created in `Amazon_Crawling` and upload it into the `Elastic_Search`.

## Contact Us
We're excited to hear from you! If you have any questions, suggestions, or need assistance, don't hesitate to reach out.
Feel free to contact us via email at:
- neg.jaafari@gmail.com
- noorbakhsha1@gmail.com
- Mehrnaz271380@gmail.com

We're here to help and would love to hear about your experience using this project.

