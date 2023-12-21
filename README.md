# customer_banking
This project had us create a customer banking system that allows the user to track their interest earned on based on inputs from the user for savings and CD acounts. 
We were provided a starter file with 4 .py files inside.
### Account
This first file was provided completed. It created the Account Class with the methods blance and interest. This file will be used to import into the savings_account and cd_account files.
### Savings Account
The first file we had to work on had us create a savings account using the create_savings account function. We created an instance called 'savings' and have it set to pass in the interest, and balance values. Using the calculation in the hints provided for in the Challenge Instructions and following the psuedo code written out the rest of this was pretty intuitive. After calculating interest we created new variables to set the savings and interest earned and returned those values.
### CD Account
This was a copy and paste job from the savings_account file, just had to edit the names to fit the cd names.
### Customer Banking
This is our main function. We imported the create_savings_account and create_cd_account functions from their respective files.
We promted the user with three printed question to set the balance, interest and maturity of the account. 
Unpacking the part to pass the variables provided by the user. One variable was created initially, until later it was noticed we needed another to store the interested value in. ChatGPT was referenced to figure this part out. 
The same steps above were repeated for the cd account and then we just called the main function, printing the results when we do so.