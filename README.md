# OpinatorScraper
Scrapes reviews from ecommerce websites.

The project uses Scrapy to scrape data from ecommerce websites.
## Functioning of the project

* DriverPHP.php executes the ScrapyDriver_AmazonSpider.py, giving ProductID of the product as command line
  argument.
* DriverPHP.php will decide which "Spider" to call based on the url and the
  corresponding "ScrapyDriver" file would be executed.
* ScrapyDriver_AmazonSpider.py executes the "Spider" through command line.

### Scrapy version: 0.24.0
