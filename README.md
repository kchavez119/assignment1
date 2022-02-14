# Assignment1
### Homework 1 for big data
This code was used for a project that I had in Web Analytics. This specific portion of the code was used to gather review data for about 80 different credit cards.
The website the data was being scraped from was Credit Karma. Another team memeber had already saved the URLs for each credit card. So in this code I open up that
file and create a for-loop so that we are able to go through each link. We chose 5 pages of reviews to scrape for each card and decieded to gather the review,author,date,review
title, and review text. After the data was gathered I ran a line a code to drop any duplicate reviews in case any were gathered and reset the index and then saved the data frame
to a CSV.
