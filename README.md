# Scraping-Data
In this article, we will scrap data from Zillow.com using the Python programing language. There are several libraries that can help us to do this but today we will start with request and Beautiful Soup.

Basically, the whole web scraping process is to send an HTTP request to the URL of the webpage that we want to get the data from, then the HTML content of the webpage will be returned. After creating a nested/tree structure of the HTML by a parser, we can start to navigate and search for the patterns that we are looking for.

 you can find the code in Zillow files:
 - Zillow-manyCities.ipynb: for many cities at the same time - due to the changing from Zillow, this file does not work anymore, however, I still keep this one in case they switch it back.  
 - OneCity-Redding.ipynb: for one city, Redding, only, this one work for Zillow web's 2022 structures. 
