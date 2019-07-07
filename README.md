# Webcrawler

Approach to the solution:


Description:
 
The Web crawler is developed to fetch the links from a webpage, e.g. http://www.google.com. The web crawler is performing a ping test to check the validity of the website. If the response is 200 OK, that is the link is valid and hence it will be added to the queue of the valid links.

Prerequisites: 

Library installation –


•	Beautiful soup

•	Urllib3

•	Requests

•	Queue


Inputs by user: 

 
input_link = 'http://www.google.com/'

maxLinks = 10

Functions in the code: 

check_valid_link(): The code has a function check_valid_link()  to check if the link is valid or not.

getLinks(): Function to Queue all the valid links to a queue

callWebCrawler(): Web crawler starting point function







