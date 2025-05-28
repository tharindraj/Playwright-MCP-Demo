# Instructions
- Run "Before Each Test case" section before running each test case.
- Run "After Each Test case" section after running each test case.

# Before Each Test case
- Navigate to https://www.advantageonlineshopping.com/#/

# Ater Each Test case
- Close the web browser.

# Test Cases
## TC 001 - Register as a user
### Priority : High
- Register as a new user. (Note : userame should be less than 15 characters)
- Update the Username and password in [User data](/TestData/UserData.md) file, so it can be used for future test cases.

## TC 002 - Verify Validation error messages
### Priority : Medium
- Navigate to "Create account" page.
- Enter a Username with more than 15 charters and focus out of the field.
- An inline error message should be shown saying "Use maximum 15 character"
- Enter a wrong email format and focus out of the field.
- An inline error message should be shown saying "Your email address isn't formatted correctly".
- Enter characters in Password field to violate following validations and check whether the validation error message is shown when you go focus out of the password field.
    - Use 4 character or Longer
    - Use maximum 12 characters
    - Including at least one lower letter
    - Including at least one upper letter
    - includign at least one number