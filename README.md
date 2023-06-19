# data-collection-challenge
Module 11

Welcome to my Module 11 Data Collection Challenge! 

In Part 1, I scraped titles and preview text from Mars news articles on the Mars news site. I used automated browsing to visit the Mars news site and inspected the page to identify which elements to scrape. I then created a Beautiful soup object and used it to extract text elements from the site. I extracted the titles and preview text and stored the results in Python data structures. 

In Part 2, I used automated browsing to visit the Mars Temp Data Site and inspected the page to identify which elements to scrape. I created a Beautiful Soup object to scrape the data in the HTML table. Next, I made a pandas data frame to include the scraped data. I then examined the data types currently associated with each column and converted them to the appropriate data types. I analyzed the data using pandas functions to answer several questions.
    1. How many months exist on Mars?
    2. How many Martian days worth of data exist in the scraped dataset?
    3. What are the coldest and warmest months on Mars?
    4. Which months have the lowest and highest atmospheric pressure on Mars?
    5. About how many terrestrial days exist in a Martian year?

Finally, I exported the DataFrame to a CSV file (see mars.csv)