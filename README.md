# Web_Scraping_On_Github_Topics
 
Web Scraping on github topics page

What is Web Scraping in short terms? Web scraping is the automated process of extracting information from websites. It involves fetching the data displayed on a website and converting it into a structured format (e.g.,a CSV, spreadsheet, database, or JSON) for further analysis or use.

Introduction to GitHub GitHub https://github.com/ is a platform for developers and teams to host, manage, and collaborate on projects using Git, a version control system. It provides tools to work on code collaboratively, track changes, and integrate seamlessly with other development workflows.

Problem Statement We are going to use the topics page i.e https://github.com/topics, and from that page we are going find the list of topics for each repository and download it.

Tools used in this project requests : a Python library is used for making HTTP requests to a specified URL. HTTP request returns a response object with all the response data.

Beautiful Soup : a Python library used for web scraping purposes to extract data from HTML and XML documents. It provides tools for navigating, searching, and modifying the parse tree of these documents in a simple and readable way.

Pandas : is widely used in web scraping workflows to structure, clean, and analyze the data extracted from websites. After using tools like Beautiful Soup, or requests to scrape data, Pandas helps process the data into meaningful formats like tables or spreadsheets.

Steps that will be followed -

We're going to scrape https://github.com/topics

We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description

For each topic, we'll get the top 25 repositories in the topic from the topic page

For each repository, we'll grab the repo name, username, stars and repo URL

For each topic we'll crete a CSV file in the following format.

Scrape the list of topics from GitHub use requests to download the page use BeautifulSoup to parse and extract information convert it into a panda data frame
