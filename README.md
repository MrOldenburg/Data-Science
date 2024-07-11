# Data-Science
This is my first data scraping project I've created for myself to learn.  

My First Website Scraped

Toscrape-Books-Example.ipynb is python code that scrapes all 50 pages of the website for book title, price and star ratings.  It then writes those values in individual cells in excel neatly.  The code works flawlessly however, stripping the excess characters for the star ratings proved challenging.  

Problems I ran into:
A coma in a book title tells excel to write in the next cell. <br />-Fixed by substituting the character in the title from "," into " -"<br />
		-This causes another problem that may come up, if a title uses a coma for a number such as "10,000 leagues" it will rewrite it as "10-000 leagues".<br />
-When I grabed the star rating it brought with it the rating and the entire tag which was very long and horribly formated. <br />
		-No already documented fixes seemed to work for me so I had to find a way to take it apart like a puzzle.  I'm sure there is a much more efficent way to do this, but hey this is my first data scrape, I call it a win.


