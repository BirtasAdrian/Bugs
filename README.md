# Bugs 

Below are some Bug samples that I wrote from my experience. 

-----------------

## Low visibility buttons on the Tesla website

**Priority & Severity**

P4 – Low

**Description**

The buttons at the bottom of the home page have low visibility.

**Steps to reproduce**
1.  Go to https://www.tesla.com/ro_ro?redirect=no
2.  Go to the bottom of the page
3. Look at the buttons

**Expected result**

The buttons should be perfectly visible.

**Actual result** 

The buttons are not perfectly visible.
### Bug Images
<img src="Bug Images/Tesla Bug image 1.png " witdh="400" height="500" >  
<img src="Bug Images/Tesla Bug image 2.jpg" witdh="400" height="447" >

-----------------


## Product store doesn’t have a quantity field for products

**Priority & Severity**

P3 – Normal

**Description**

When we add more products from the same product to the cart there is no quantity field for them. This generates a long list of products.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html  
2. Sing up to the site
3. Log in to the site
4. Add the same product several times
5. Press the ,,Cart” button
6. Look at the product

**Expected result**

The product should have a quantity field with a unit of measure.

**Actual result**

The product doesn’t have a quantity field.
### Bug Images

<img src="Bug Images/Product store bug .png" witdh="400" height="405" >  

-----------------

## No currency symbol for products

**Priority & Severity**

P3 – Low

**Description**

Products don’t have a currency symbol in the price area on the website.

**Steps to reproduce**

1. Go to https://juice-shop.herokuapp.com/#/
2. Look in the price area for products

**Expected result**

There should be a currency symbol in the price area.

**Actual result**

There is no currency symbol in the price area.

### Bug Images

<img src="Bug Images/Juice Shop bug.png" witdh="400" height="405" >  

-----------------

## Values of the keys “base” and “main” are not translated into Romanian

**Priority & Severity**

P5 – Low

**Description**

When we access the API with the parameter ,,lang”  and the value ,,ro”, the values of the keys ,,base” and ,,main”  are not translated into Romanian.

**Steps to reproduce**

1. Go to api.openweathermap.org/data/2.5/weather?q=London&appid=0cd1604bc507bb598a3f12fa26d68fa0&units=metric&lang=ro in Postman
2. Look at the ,,base” and ,,main” keys

**Expected result**

The values of the keys should be translated.

**Actual result**

The values are not translated.

### Bug Images

<img src="Bug Images/API bug.jpg" witdh="400" height="405" >  

-----------------
## Wrong message displayed for the value of the key ,,id''

**Priority & Severity**

P5 – Low

**Description**

When we access the API with the ,,id” parameter and a value that is not in the table, we receive a positive message.

**Steps to reproduce**
1. Go to: http://qachallenge.ro/api/test_api.php?action=fetch_all in Postman 
2. Send the endpoint
3. Add an id that is not in the response for the endpoint of the next step
4. Go to http://qachallenge.ro/api/test_api.php?action=delete&id=  in Postman 
5. Send the endpoint
6. Look at the message

**Expected result**

The message should be negative.

**Actual result**

The message is positive.

### Bug Images

<img src="Bug Images/API bug 2.jpg" >  

-----------------

## On the order form important fields are missing

**Priority & Severity**

P1 – Normal

**Description**

On the order form we can’t find in the credit card area the fields ,,Full name”, ,,Card number”, ,,CVC or CVS”, ,,Expiration data”. The ,,Street & number” field are also missing.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html  
2. Sing up to the site
3. Log in to the site
4. Add a product to the cart
5. Press the ,,Cart” button
6. Press the ,,Place order” button
7. Look at the form

**Expected result**

The fields will be there.

**Actual result**
The fields are not there.

### Bug Images

<img src="Bug Images/Product store bug 2.png" witdh="400" height="405" >  

-----------------

## Order only with the name and number of the card
**Priority & Severity**

P1 – High

**Description**

You can place an order without going through all the necessary information. In order form you can complete just the name and number of the card and to press  „Order” button.

**Steps to reproduce**
1. Go to https://www.demoblaze.com/index.html  
2. Sing up to the site
3. Log in to the site
4. Add a product to the cart
5. Press the ,,Cart” button
6. Press the ,,Place order” button
7. Fill in ,,Name” and ,,Credit card”  fields
8. Press ,,Order” button

**Expected result**

You will not be able to order.

**Actual result**

The order is placed.

-----------------

## Wrong video in ,,About Us" section on demoblaze.com store 

**Priority & Severity**

P4 – low

**Description**

In „About Us” section is a video that doesn’t describe the store. A course in it is described in the video. 

**Steps to reproduce**
1. Go to http://www.demoblaze.com/index.html 
2. Click on the section ,,About Us”
3. Click on the video

**Expected result**

The video should describe the store.

**Actual result**

The video describe a course in it. 

