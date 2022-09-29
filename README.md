# QUOTES

## Spiders

Generate a spider: `scrapy genspider <spider-name> <domain>`

List spiders: `scrapy list`

### Scrapy shell

Enter the shell: `scrapy shell`

Fetch to domain: `fetch("<domain>")`

Execute our crawler quotes inside `spiders`: `scrapy crawl quotes`

### Export to csv

`scrapy crawl quotes -o items.csv` It generates a .csv file with the output
`scrapy crawl quotes -o items.json` It generates a .json file with the output
`scrapy crawl quotes -o items.xml` It generates a .xml file with the output
