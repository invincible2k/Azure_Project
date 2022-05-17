# Azure_Project

A web application service where the user can enter the url of any product page from Amazon's website and the application will output the analysis of the customer reviews of that product. This will save the user's time as he will not have to read each and every review. He can simply use this web application and in the click of a button he will get complete insights of the product.

This project uses sentiment analysis to find the user sentiments on a particular Amazon product via text analytics service of Azure. 

There are two code files: 1) login.html (for the user interface)
                          2) web_scraping.py - python backend using Flask framework

Web scraping.py scrapes customer reviews data from Amazon's website (url entered by user) and performs sentiment analysis on it to give an idea about positive/ negative reviews. 

Public website url (https://saamira.azurewebsites.net)
