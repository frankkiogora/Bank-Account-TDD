
Assignment: Bank Account TDD
Now that we have studied the basics of TDD, let's apply that directly to our Bank Account class we created from the OOP chapter in Ruby.

/bankaccount/bankaccount_spec.rb
require_relative 'bankaccount'
RSpec.describe BankAccount do
end
Let's start testing our BankAccount class. Create the following tests:

To do
- Has a getter method for retrieving the checking account balance

- Has a getter method that retrieves the total account balance

- Has a function that allows the user to withdraw cash

- Raises an error if a user tries to withdraw more money than they have in the account

- Raises an error when the user attempts to retrieve the total number of bank accounts

- Raises an error when the user attempts to set the interest rate
