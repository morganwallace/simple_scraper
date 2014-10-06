simple_scraper
==============

Easy to use website scraper using lxml and xpath


Use this to build larger scripts that scrape from websites.
You can also import it like so:

	from scraper import scrape

	scrape(url="http://www.nytimes.com/",xpath='//*[@class="story-heading"]/a/text()')
