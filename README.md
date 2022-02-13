# Burgerzilla Hamburger Ordering System Project for Yemeksepeti
## Overview
---
Taking orders from hamburger restaurants, with the order, which can view the status of the order Transactions under the authority of the relevant customer/restaurant A REST-API microservice that enables.

### Most Common Python and Flask Libraries
```
Flask-SQLAlchemy
Flask-Migrate
flask-restx
Werkzeug
psycopg2-binary
flask-marshmallow
```
Before we begin, kindly install following on your system:-

-   [python3.x](http://www.python.org)
-   [Virtualenv](https://virtualenv.pypa.io/en/stable/)
How to Run the App?
-------------------

-   Git clone <https://github.com/Yemeksepeti-Python-Bootcamp/BurgerZilla_onurakyol.git>
-   Open the terminal and run,
```
docker build -t burgerzilla-main:latest .
```
-   After that run this code,
```
docker compose up --build web
```
-   You can reach all API documentation from Postman Collection

Everything should be ready. In your browser open
<http://127.0.0.1:5000/>

Customer Endpoints
-------------------

|Method|Endpoint|Description|      
|----|-----|-------|      
|GET|127.0.0.1:5000/client/Restaurants|Get all restaurants| 
|GET|127.0.0.1:5000/client/Menu/menuId|Get menu with menuId|
|POST|127.0.0.1:5000/client/createOrder|Create an hamburger order|
|POST|127.0.0.1:5000/client/watchOrders|Watch the order|
|GET|127.0.0.1:5000/client/getAllOrder/userid|Shows order with <userid>|
|GET|127.0.0.1:5000/client/cancelOrder/orderid|Cancel your order with <orderid>|