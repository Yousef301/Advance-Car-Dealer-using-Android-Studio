# Advance Car Dealer App
Project description: A car dealer has requested you to develop an Android application that enables users to conveniently view and reserve cars either online or through a local database. The application should be user-friendly and simple in design. The required functionalities include:

1- Introduction Layout
   This layout features a 'Connect' button designed to establish a connection to a server using REST to load all car types into an ArrayList.
    1.1 If the connection is successful, proceed to the login and registration section.
    1.2 If the connection is unsuccessful, display an error message and remain on the same layout

2- Login and Registration Layout
   This layout should include a "Login" button and a "Sign Up" button.
    
   2.1 In the main page (first page), the customer can enter their email and password, which are registered in the database so that if the email and password match the ones in the database the user can log into a special menu.
   This layout must have a checkbox labeled "Remember Me," which will save the email in shared preferences. This way, the next time users log in, they won't need to re-enter their email.

   2.2 The "Sign-Up" button for new users will redirect us to another layout where we will enter our email (must be an email) as a primary key, which contains the following:
   * First name (not less than 3 characters).
   * Last name (not less than 3 characters).
   * Gender (spinner).
   * Password (must not be less than 5 characters and must include at least 1 character, 1 number, and one special character).
   * Confirm password (the passwords should match each other and should be encrypted using a secure Hash Function).
   * Country (spinner with no less than 4 countries).
   * City (spinner with no less than 3 cities for each country).
   * One phone number (must have pre zip code (area code)). Eg. Palestine (00970), Jordan (00962), Syria (00963) …etc. *this must be changeable according to the country, NOT by the user.

   If all the previous conditions are entered correctly, then and only then we can register.
