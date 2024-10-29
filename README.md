# Web Scraper Script that pulls detailed links from cybersecurity articles online

# Selenium based script that can be used to stay on top of current news and important cybersec events

The purpose of this project is to create an automated script that will  run weekly to keep me updated on cybersecurity news. It will pull Article links from popular cybersecurity and adjacent websites, and send them to a specified email. 

* Use Selenium and BeautifulSoup4 to pull data from the web in a neat format
* Task Scheduler (Windows) used to create a new task that runs weekly which will execute the script automatically
* SMTP used to send the data to specified email 