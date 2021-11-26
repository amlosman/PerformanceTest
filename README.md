# PerformanceTest

Develop a working JMeter script simulating a full user journey to be as follows: 
1- Navigate to http://automationpractice.com/ landing Page. 
2- Click on “Sign In” button displayed on the upper right corner on the landing page. 
3- Type in the following credentials in both “Email address” and “Password” fields and then hit “Sign In”. 
Email: ITI41@gmail.com
PW: ITI41
You can use these working credentials or you can manually register as many as you like.
4- Now you should be on the “My Account” page, From the upper navigation bar click on “T-SHIRTS”.
5- Hover your mouse on “Faded Short Sleeve T-Shirts” after that you will be able to add it to your cart.
6- A popup box will be displayed confirming your item, use it to “Proceed to checkout”.
7- On the “SHOPPING-CART SUMMARY” page click on “Proceed to checkout”.
8- On the “ADDRESSES” page click on “Proceed to checkout”.
9- On the “SHIPPING” page click on “Proceed to checkout”. (Make sure to check terms and conditions 
checkbox first).
10- On the “Payment Method” page click on “Pay by bank wire”.
11- On the “Order Summary” page click on “I confirm my Order”.
12- Validate that the order has been dispatched by asserting on “Your order will be sent as soon as we receive
payment.” On the “ORDER CONFIRMATION” Page.

Script quality will be judged as follows: 
1- The correct use of parameterization, try as much as you can to make your script fully independent on 
test data. By replacing hardcoded values on each request by a user defined variable. 
2- Adding assertion for each response to validate the correct user navigation through the different pages. 
Make it a text response assertion not a response code. 
3- Make you script independent on the running environment by using HTTP Request Defaults. 
4- All the multivalued test data (Like No. of Passengers, Departing From, Service Class, Flights,…etc.) 
should be placed in an external sheet and then read through the use of " CSV Data Set Config”. 
5- Use Constant Timers with reasonable delays therefore, we can have a more realistic script. 
6- User Cache manager as force it to clear cache for each iteration.
7- Feel free to use Cookie manager when needed.
