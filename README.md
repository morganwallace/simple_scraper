simple_scraper
==============

Easy to use website scraper using lxml and xpath


Use this to build larger scripts that scrape from websites.
You can also import it like so:

	from scraper import scrape
	
	#Get today's New York Times headlines
	scrape(url="http://www.nytimes.com/",xpath='//*[@class="story-heading"]/a/text()')
