# HTML-Challenge
 
# Project Description

The tasks for this project include:
- Deliverable 1: Scrape titles and preview text from Mars new articles
- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table

# Questions for Analysis
Both deliverables are given a Starter Code that is opened using Jupyter Notebook.
 
Deliverable 1: Scrape Titles and Preview Text from Mars News
1. Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to extract text elements from the website.

3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures.
    - Store each title-and-preview pair in a Python dictionary and, give   each dictionary two keys: title and preview.
    - Store all the dictionaries in a Python list.
    - Print the list in your notebook.

Deliverable 2: Scrape and Analyze Mars Weather Data
1. Use automated browsing to visit the Mars Temperature Data Site. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.

4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

5. Analyze your dataset by using Pandas functions to answer a set of questions shown in the Jupyter Notebook.

6. Export the DataFrame to a CSV file.

# Files
1. part_1_mars_news jupyter source file
2. part_2_mars_weather jupyter source file
3. mars_weather csv file
