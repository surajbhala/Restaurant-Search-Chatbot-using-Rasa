# Restaurant-Search-Chatbot-using-Rasa

This is a restaurant search chatbot built using RASA and python .
The chatbot searches top 5-10(descending order with respect to the ratings) restaurants for a given cuisine(6 cuisines) and city , the cities under consideration are Tier 1 and Tier 2 cities of India : http://en.wikipedia.org/wiki/Classification_of_Indian_cities, but can be exapanded to have all the cities in the Zomato Database.
Zomato API has been used to perform the restaurant search , details about which can be found on : https://developers.zomato.com/api#headline1
Further the chatbot can also be used to send emails with the top 10restaurants to the given email id.
Integration with Slack was also done and the chatbot can be deployed as an autonomous slackbot which will reply to the user queries
The chatbot was trained to identify different types of searches and respond accordingly , further it can identify if the email id is incorrect by the email id format .
Also the chatbot was designed so as to identify alternative names of the cities used and it could map it to the exact city and accordingly search for the restaurants.



Steps to use it :
1) First create a virtual env 
2) Download all dependencies for Rasa using the following commands
2.a) pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
2.b) Install spacy : $ pip install rasa[spacy]
$ python -m spacy download en_core_web_md
$ python -m spacy link en_core_web_md en

Libraries and there versions used can be found in the Libraries.txt file
