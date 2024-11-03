# Rent Or Buy Property Console-Line Application
This repository showcases a beginner C# console applications for renting or buying a property.

## Context
The Rent or Buy Property is a C# command-line application that aims to assist family members determine if the amount of money they are paying is sufficient to purchase a house.

## Table of Contents
- [Rent or Buy Property](#rent-or-buy-property-console-line-application)
- [Context](#context)
- [Table of Contents](#table-of-contents)

## Overview
Rent or Buy Property Application 

You requested assistance in using an application to help a family member determine if the amount of money they are paying is sufficient to purchase a house. The family member will use the application to input their gross monthly income (before deductions), estimated monthly tax deducted, and estimated monthly expenditures in various categories. Then they can choose between renting accommodation or buying a property. If they choose to rent, they can input the monthly rental amount. If they choose to buy a property, they must enter the purchase price, total deposit, interest rate, and number of months to repay. The Application will calculate the monthly home 
loan repayment for buying a property and alert the user if the repayment amount is more than a third of their gross monthly income, indicating that approval of the home loan is unlikely. The Application will also calculate the available monthly money after all specified deductions.
- The coding standards should be internationally acceptable, and the code should include comprehensive 
comments explaining variable names, methods, and the logic of programming code.  
- Submit source code and a readme file with instructions for compiling and running the software:

### Demonstrating functionality

Prompt user for gross monthly income:
<br> <img src="assets/images/RoB1.png" alt="Rent or Buy Property image 1">

Prompt user for estimated monthly tax deduction:
<br> <img src="assets/images/RoB2.png" alt="Rent or Buy Property image 2">

Prompt user for estimated monthly living expenses:
<br> a.
<br> <img src="assets/images/RoB3a.png" alt="Rent or Buy Property image 3a">

<br> b.
<br> <img src="assets/images/RoB3b.png" alt="Rent or Buy Property image 3b">

Prompt user to choose between renting or buying:
<br> <img src="assets/images/RoB4.png" alt="Rent or Buy Property image 4">

Prompt user for monthly rental amount (if renting):
<br> <img src="assets/images/RoB5.png" alt="Rent or Buy Property image 5">

Prompt user for purchase price (if buying):
<br> <img src="assets/images/RoB6.png" alt="Rent or Buy Property image 6">

Prompt user for total deposit amount (if buying):
<br> <img src="assets/images/RoB7.png" alt="Rent or Buy Property image 7">

Prompt user for interest rate (if buying): 
<br> <img src="assets/images/RoB8.png" alt="Rent or Buy Property image 8">

Prompt user for number of months for repayment (if buying):
<br> <img src="assets/images/RoB9.png" alt="Rent or Buy Property image 9">

Calculate available monthly funds (if renting):
<br> <img src="assets/images/RoB10.png" alt="Rent or Buy Property image 10">

Calculate monthly home loan repayment amount (if buying):
<br> <img src="assets/images/RoB11.png" alt="Rent or Buy Property image 11">

Display alert if home loan repayment > 1/3 of income:
<br> <img src="assets/images/RoB12.png" alt="Rent or Buy Property image 12">

Calculate available monthly funds (if buying):
<br> <img src="assets/images/RoB13.png" alt="Rent or Buy Property image 13">


#### Handle invalid input: 
If the user does not enter any value, they will be prompted again to enter their name and if they enter their name with a small letter, it would be capitalized automatically:
<br> <img src="assets/images/RoB14.png" alt="Rent or Buy Property image 14">

For ALL input, if the user enters a negative number or some text, the user will be prompted again until they enter valid input:
<br> <img src="assets/images/RoB15.png" alt="Rent or Buy Property image 15">

When prompted for Renting or Buying, if the user enters a number that is not either 1 or 2, or a negative number, or some text, they will be prompted again until they enter valid input:
<br> <img src="assets/images/RoB16.png" alt="Rent or Buy Property image 16">

Again, if the user enters a negative number or some text, they will be prompted again until they enter valid input:
<br> <img src="assets/images/RoB17.png" alt="Rent or Buy Property image 17">