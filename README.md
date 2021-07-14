# Predicting-Loan-EMI

I have created a mortgage calculater in this project and have taken the help of online course from freecodecamp. This is not so fun but pretty useful.

# Project Objectives

Define a EMI function using python


Returning caluclated EMI based on user's preferred cost of home, downpayment, duration of loan and APR

# Functionality of the program

Take User's Input :

Duration of loan program,

Loan Amount,

Down Payment,

Interest Rate per year

Output:

Total Monthly EMI

# Interesting feature

No packages used. The complete calculation is as follows:

Loan Amount = Total Amount - Down Payment

EMI = Loan Amount**rate*((1+rate)**duration)/(((1+rate)**duration)-1)

Duration = Number of months*12

Down payment is set to 0 by default. User can change this by inputing their preferred amount for downpayment.

In case a user does not enter any amount, the program will consider it as 0.

# Instructions

You can take the code and play around with it by adding your own variables. However, it only makes sense to run it locally for testing purposes.


# Author & Acknowledgments
This code was created by Vaishali Gupta. Feel free to use it for your own project.








