# PerformanceTest

Develop a working JMeter script simulating a full user journey to be as follows: <br>
1- Navigate to http://automationpractice.com/ landing Page. <br>
2- Click on “Sign In” button displayed on the upper right corner on the landing page. <br>
3- Type in the following credentials in both “Email address” and “Password” fields and then hit “Sign In”. <br>
Email: ITI41@gmail.com<br>
PW: ITI41<br>
You can use these working credentials or you can manually register as many as you like.<br>
4- Now you should be on the “My Account” page, From the upper navigation bar click on “T-SHIRTS”.<br>
5- Hover your mouse on “Faded Short Sleeve T-Shirts” after that you will be able to add it to your cart.<br>
6- A popup box will be displayed confirming your item, use it to “Proceed to checkout”.<br>
7- On the “SHOPPING-CART SUMMARY” page click on “Proceed to checkout”.<br>
8- On the “ADDRESSES” page click on “Proceed to checkout”.<br>
9- On the “SHIPPING” page click on “Proceed to checkout”. (Make sure to check terms and conditions 
checkbox first).<br>
10- On the “Payment Method” page click on “Pay by bank wire”.<br>
11- On the “Order Summary” page click on “I confirm my Order”. <br>
12- Validate that the order has been dispatched by asserting on “Your order will be sent as soon as we receive <br>
payment.” On the “ORDER CONFIRMATION” Page. <br>

Script quality will be judged as follows: <br>
1- The correct use of parameterization, try as much as you can to make your script fully independent on <br>
test data. By replacing hardcoded values on each request by a user defined variable. <br>
2- Adding assertion for each response to validate the correct user navigation through the different pages. <br>
Make it a text response assertion not a response code. <br>
3- Make you script independent on the running environment by using HTTP Request Defaults. <br>
4- All the multivalued test data (Like No. of Passengers, Departing From, Service Class, Flights,…etc.) <br>
should be placed in an external sheet and then read through the use of " CSV Data Set Config”. <br>
5- Use Constant Timers with reasonable delays therefore, we can have a more realistic script. <br>
6- User Cache manager as force it to clear cache for each iteration.<br>
7- Feel free to use Cookie manager when needed.<br>
