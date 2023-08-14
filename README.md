# Url-Shortener-Golang
This go project is build to show how a url-shortener works and what all is involved in making it. 
Used GoLang, Redis for this project. 

API : 
localhost:3000/api/v1 (Post request)
#### Sample input : {
   ####  "url":"your_url",
  #### "short":"abc",
#### "expiry": 48
#### }

In sample input, short and expiry are not mandatory. Short is the custom short url that you want. 

Sample Output: 


### This URL shortener has a limit per ip address set to 10 successful requests per 30 minutes. 
