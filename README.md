# scrapy-mongodb

This is a scrapy web scraper that scrapes to a mongoDB database. 
It is based on this tutorial (https://www.mongodb.com/basics/how-to-use-mongodb-to-store-scraped-data)

However, some changes have been made. Since the special characters required for a mongodb password don't work in the git terminal, I've inserted the mongodb connect URI as plaintext in pipelines.py. Add your mongoDB connect URI (and login/password if needed) in the place of the one here, and exclude it from the parameters of the final scrapy call in your git terminal.
