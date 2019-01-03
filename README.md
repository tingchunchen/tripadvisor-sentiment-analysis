tripadvisor-sentiment-analysis
This project can help you scrape hotel information from Tripadvisor. I divide the process into three steps as following:

Step1
Extract hotel names and urls from hotel.csv file.

Step2
In scrape.py, scrape comments and replies based on information from step1.

Step3
Conduct sentiment analysis.

Preparation
Use Chromedriver or PhantomJS
Set your file path
set your main url
To Do List
Scrape the whole comments by clicking 'More' button shown in review
Scrape comments of all the languages


<terminal>
git clone https://github.com/tingchunchen/tripadvisor-sentiment-analysis.git
pip install selenium
cd tripadvisor-sentiment-analysis
python scrape.py
