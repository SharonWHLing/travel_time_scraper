# travel_time_scraper

Demo Python 3.7.4 script to scrape travel times using Google Distance Matrix API. Built in Jupyter Notebooks. 

This is a demo project. Beta/personal use so expect some bugs.

----------------------------------------------------------------

REQUIRES: .csv file with columns [FULL ADDRESS], [long], and [lat] for multiple starting locations. Destination is the same one location. 

RESULTS: Populates a copy of the .csv file with travel times based on certain input parameters (see below). 

----------------------------------------------------------------

NOTES: Currently pulls driving travel times for departure times of every 1/2 hour from 6am-9am and 3pm-6pm (peak hours).

Returns both "best guess" and "pessimistic" travel time estimates from Google Distance Matrix API.

