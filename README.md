# LinkedIn_Followers_Tracker
This python script uses Beautiful Soup for web scraping, 
Selenium module for browser automation(FireFox specifially),
and openpyxl for Working with MS excel sheet
to scrape your followers' names from your LinkedIn profile
and adds it to an excel sheet on your desktop by either creating a new one(if not already present) or by modifying an existing one. 
The date is added to the top of each column. 
Followers in the previous column (if present) are matched with the current ones to see which ones have you lost or gained.
The lost ones are marked in red font in the previous column and the new followers are marked green in the new column.
