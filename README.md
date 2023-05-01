Download Link: https://assignmentchef.com/product/solved-car-shoppers-inc
<br>
In an effort to boost sales, Car Shoppers Inc. is offering buyers a choice of either a large cash rebate or an extremely low financing rate, much lower than the rate most buyers would pay by financing the car through their local bank. Jake Miller, the manager of Car Shoppers Inc., wants you to create an application that helps buyers decide whether to take the lower financing rate from his dealership, or take the rebate and then finance the car through their local bank. Be sure to use one or more independent Sub procedure in the application.

Some things to include:

In MainForm_Load,load two list boxes with rates from 2-15%. Load the Terms list box with 2-5years. Automatically select an entry from the list box.

Create a private function as the construct to calculate payment:

¤Pass it three parameters: rate, term, price

¤Be sure to convert rate to a decimal if it is selected as a percent.

Use the Financial.Pmtmethod to calculate the payment, like:   Payment = -Financial.Pmt(rate/ 12, term * 12, price, 0, DueDate.BegOfPeriod)  (Note the negative sign in the calculation which converts the result to a positive number.)

•Create an independent subprocedureto clear the labels on the form when the user keys new information.

•Use all of the good design and programming features learned to date.