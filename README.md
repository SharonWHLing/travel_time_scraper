# travel_time_scraper

Demo Python 3.7.4 script to scrape travel times using Google Distance Matrix API. Built in Jupyter Notebooks. 

This is a script that I'm using for an academic project. 

Beta/personal use so expect some bugs.

Code relies on Google Distance Matrix API for results.

REQUIRES: .csv file with columns [FULL ADDRESS], [long], and [lat] for multiple starting locations. Destination is the same one location. 

Currently set up to pull driving travel times for every 1/2 hour from 6am-9am and 3pm-6pm (peak hours), and write the results to a .csv file.

Returns both "best guess" and "pessimistic" travel time estimates from Google Distance Matrix API.

