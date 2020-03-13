# Scrapy Projects

For parsing data on your local machine create new virtual environment and execute this command:

`pip install -r requirements.txt`

Site #1<br />
https://www.worldometers.info/<br />

1. set next data in scrapy.cfg:<br />
`[settings]`<br />
`default = worldometers.settings`<br />
`[deploy]`<br />
`#url = http://localhost:6800/`<br />
`project = worldometers`<br />

2. for parsing results in terminal execute this commands:<br /> 
`scrapy crawl countries`

3. for saving data in next formats: .xml, .csv or .json, execute this commands:<br />
`scrapy crawl countries -o filename.xml`<br />
`scrapy crawl countries -o filename.csv`<br />
`scrapy crawl countries -o filename.json`<br />

Site #2 <br />
https://imdb.com <br />

1. set next data in scrapy.cfg:
`[settings]`<br />
`default = imdb.settings`<br />
`[deploy]`<br />
`#url = http://localhost:6800/`<br />
`project = imdb`<br />

2. for parsing results in terminal execute this commands:<br /> 
`scrapy crawl best_movies`

3. for saving data in next formats: .xml, .csv or .json, execute this commands:<br />
`scrapy crawl best_movies -o filename.xml`<br />
`scrapy crawl best_movies -o filename.csv`<br />
`scrapy crawl best_movies -o filename.json`<br />