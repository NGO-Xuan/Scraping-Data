
# Scraping-Data
>  In this article, we will scrap data from Zillow.com using the Python programing language. There are several libraries that can help us to do this but today we will start with request and Beautiful Soup.Basically, the whole web scraping process is to send an HTTP request to the URL of the webpage that we want to get the data from, then the HTML content of the webpage will be returned. After creating a nested/tree structure of the HTML by a parser, we can start to navigate and search for the patterns that we are looking for.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!----------------->


## General Information
- The scope of this project is  to scrap data from Zillow.com: 
    1. Address 
    2. Link
    3. Price
    4. Detail
    5. Posted time
- Gather all information and create a data frame

## Technologies Used
- pip install requests
- pip install bs4
- pip install random


## Usage
 you can find the code in Zillow files:
 - Zillow-manyCities.ipynb: for many cities at the same time - due to the changing from Zillow, this file does not work anymore, however, I still keep this one in case they switch it back.  
 - OneCity-Redding.ipynb: for one city, Redding, only, this one work for Zillow web's 2022 structures. 
 
## Project Status
Project is:  _completed_ 

## Room for Improvement
- How stop being blocked from Zillow
## Contact
Created by <datasciencelife2021@gmail.com> - feel free to contact me!


