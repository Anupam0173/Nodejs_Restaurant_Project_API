# Nodejs_Restaurant_Project_API

# -------Restaurant API----------

http://127.0.0.1:3003/restaurant---------------list all restaurants    (get)

http://127.0.0.1:3003/restaurant------------>Register new restaurants   (post) 
{
    "name":"Taj",
    "address":"145 road, near by abc garden, mumbai",
    "opening_hours":"from 9am to 7pm"
}


http://127.0.0.1:3003/restaurant/6130b4d36b79d7900906b962 ---->List all the products of a restaurant  (get)


http://127.0.0.1:3003/restaurant/6130b4d36b79d7900906b962  -------------->Change a restaurant's data   (patch)
{
    "name":"fajmahal",
    "address":"145 road, near by abc garden, mumbai",
    "opening_hours":"from 9am to 7pm"
}


http://127.0.0.1:3003/product/6130b5e46b79d7900906b96d           ---------------------->Change a restaurant product   (patch)
{
    "name": "Gulab jamun",
  "price": 100,
  "category":"spice"
}


# ------------product related API------------

http://127.0.0.1:3003/product---------------->Create a restaurant product   (post)
Data will be passed as a form-data
{
	product_image:select the file
    "name": "Berger",
  "price": 100,
  "category":"spice"
}


http://127.0.0.1:3003/product/delete/6130b4d36b79d7900906b962/6130e85b78cdb5bc13f9c5b1  ------->Delete a product from a restaurant


http://127.0.0.1:3003/product/6130b5e46b79d7900906b96d------------->for accessing the buffer image.  (get)

# this project contains all api and validations
