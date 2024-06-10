# web-scaping-challenge
This assidnment is didvied in 2 part.

# ================Part 1: Scrape Titles and Preview Text from Mars News=====================
In this part,we will do the following:
-First we'll create a Beautiful Soup object and use it to extract text elements from a website.
-Then we'll extract the titles and preview text of the news articles that we scraped. 
-After that we'll store the scraping results in Python data structures as follows:
  *Store each title-preview pair in a Python dictionary.
  *give each dictionary two keys: title and preview. 
  *store all the dictionaries in a Python list.
  *print the list in your notebook.

# ====================Part 2: Scrape and Analyze Mars Weather Data==========================
In this part,we will do the following:
-First we'll create a Beautiful Soup object and use it to scrape the data in the HTML table. 
-Then we'll assemble the scraped data into a Pandas DataFrame. 
-After that we'll examine the data types that are currently associated with each column and convert the data to the appropriate datetime, int, or float data types.
-Finally we'll analyze your dataset by using Pandas functions to answer the following questions:
  *How many months exist on Mars?
  *How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  *What are the coldest and the warmest months on Mars (at the location of Curiosity)?
 # ---------------------------- To answer this question:--------------------------
-We'll find the average minimum daily temperature for all of the months.
-Plot the results as a bar chart.
  *Which months have the lowest and the highest atmospheric pressure on Mars? 
# -----------------------------To answer this question:--------------------------
-We'll find the average daily atmospheric pressure of all the months.
-We'll plot the results as a bar chart.
  *How many terrestrial (Earth) days exist in a Martian year? 
# ----------------------------To answer this question:---------------------------
-We'll consider how many days elapse on Earth in the time that Mars circles the Sun once.
-Then we'll visually estimate the result by plotting the daily minimum temperature.
-Finally , we'll export the DataFrame to a CSV file.
