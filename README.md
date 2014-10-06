simple_scraper
==============

Easy to use website scraper using lxml and xpath


Use this to build larger scripts that scrape from websites.
You can also import it like so:
``from scraper import scrape

scrape(url="http://berkeley-crossfit.com/2013/12/03/wod-12-03-2013/",xpath='//*[@class="entry-content"]/p/text()')
``
