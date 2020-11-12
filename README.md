
## Run the spider

    scrapy runspider flashbot.py


## For local testing

get the RSS page locally

   wget rss.jobsearch.monster.com/rssquery.ashx -O index.xml

Replace the value variable `start_urls` in the flashbot by the full path (obtained with `pwd`) if the index.xml file in your filestyme (starting with "file://")




