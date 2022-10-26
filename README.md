HTTP request and reponse
- request
    - method type: eg. GET, POST, etc.
    - url parameters: eg. /me?my-name=Kuno&my-surname=Kitsing.
    - headers
    - body of the request
- response
    - response code
    - headers
    - cookies
    - body of the response


Project plan
Topic: Find My Meal
Technologies:
- Java 17
- SpringBoot 2.7.x
- Bootstrap
- Bootstrap Material 
- Thymeleaf
- H2 db for development purposes, mySQL for production

Business requirements
1. Gathering requirements
- calculate
- show time
- categories
- meals
- restaurants
- Feedback
- Restaurant rating
- Meal rating
- prices
- client information
- log in
- reservation
- statistics & graphs
- categories
----------------------------


2. Clarifications of requirements
   - OK -MEALS
     - category of meals
     - category of price
     - availability
     - category of drinks
     - other services
     
       - RESTAURANTS
     - name of restaurant
     - restaurant address (city, country)
     - opening hours (availability)
     
       - RESERVATION
     - client
     - restaurant 
     - date and time
     - number of customers

        -CLIENT
     - client name
     - client surname
     - e-mail
     - phone number
     - country

- OK - LOG IN
    - username
    - password
    - type of the account
    - registration of new user
    - captcha
    - remember me functionality
    - forgot password
    - 
- NC - CALCULATE
    - bill
    - taxes
    - date and time