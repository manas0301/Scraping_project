# Scraping_project
Web scraping is the process of extracting and 
parsing data from websites in an automated fashion using a 
computer program. It’s a useful technique for creating datasets for research and learning. 


This project uses Python progarmming language, Pandas library, Requests library and Beautiful Soup 4 for scraping https://github.com/topics for list of topics and for each
topic getting the top 30 repositoriies and storing the repository name, username and URL in a CSV file.
Here are the steps that are involved in this:

    Scraped--> https://github.com/topics
    Get a list of topics. For each topic,  get topic title, topic page URL and topic description
    For each topic, get the top 30 repositories in the topic from the topic page
    For each repository, grab the repo name, username, stars and repo URL
    For each topic create a CSV file.
