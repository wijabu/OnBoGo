# BOGO Sales Alerts
Scrapes weekly ads for sales and sends user notifications.

##### Disclaimer

> This project is a work in progress. Version 1.0 is a POC for the Python program functionality, but future versions will see this project transform from a simple Python script into a Flask Application.

## DEPENDENCIES:

Beautiful Soup (https://pypi.org/project/beautifulsoup4/) for html parsing
smtplib to send email
ssl to send SMS messages

## FUTURE PLANS: 
1. allow user to define preferred alert method (email, sms, push notifications)
2. automate script to run weekly on schedule
3. integrate into web application to allow user to log in and save / modify keywords in database