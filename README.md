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

3- Home Layout (Sign in as Normal Customer)
   This layout should be a Navigation Drawer Activity containing a summary of the car dealer's history on its main page.

   3.1 The navigation bar should include the following functionality:
   
   * Home: This section will display the history of the car dealer (main page).
   * Car Menu: This section will contain information about all the types of cars.
   * Your Reservations: This section will display all the cars the customer has reserved.
   * Your Favorites: This section will display all the cars marked as favorites by the customer.
   * Special Offers: This section will contain special offers made by the car dealer.
   * Profile: This section will allow the customer to change their password, name, and phone number.
   * Call Us or Find Us: This option will redirect the customer to call the car dealer or find their location on Google Maps.
   * Logout: This option will log the customer out of their profile and redirect them to the login page.

   Description of the above:

   3.2 Car Menu:
   This menu should include all car types, with each one defined by a name (factory name and type). When the customer clicks on a name, the details of the selected car should appear (implemented using fragments). Additionally, a filter to search
   for a specific type based on (Price), (Model), and (Name) should be implemented. It's worth noting that these features may be determined or changed later. Next to each type, there should be an "Add to Favorites" button, allowing customers to
   add the selected car to their favorites. Additionally, a "Reserve" button should be available, triggering a pop-up reserved menu with details of the car and a submit button to confirm the order.

   3.3 Your Reservations:
   This section will display all reserved cars, each with the date and time of the reservation.

   3.4 Your Favorites:
   This section will include all favorite cars added by the customer. It should also provide functionality for reserving, similar to the Car Menu.

   3.5 Special Offers:
   This section will showcase special offers made by the car dealer, with functionality for reserving and adding to favorites, similar to the Car Menu.

   3.6 Profile:
   In this layout, each customer can view personal information and change their first name, last name, password, and phone number, adhering to the conditions outlined in the sign-up page.

   3.7 Call Us or Find Us (5 points):
   This layout should feature three buttons:

   * The first button will initiate a call to the car dealer using the phone number "0599000000."
   * The second button will open Google Maps to help users locate the car dealer's store.
   * The third button will open Gmail with the recipient automatically set to "CarDealer@cars.com."

   3.8 Logout:
   This button will log the customer out of their profile and redirect them to the login page.

4- Home Layout (Sign in as Admin): 
   This layout should be a Navigation Drawer Activity, featuring the profile of the admin on its main page. The navigation bar should include the following functionality:
   
   * Delete Customers: Allows the Admin to delete any customer.
   * Add Admin: Enables the addition of a new admin to the car dealer. The parameters for adding a new admin should be the same as those in the sign-up page, and there must be a static admin.
   * View All Reserves: Provides the Admin with the ability to view all reserves, including the date, time, and the name of the customer for each order that is made.
   * Logout: This button will log the admin out of their profile and redirect them to the login page.

5- Advanced Features:
   
   * Advanced profile information: Adding a profile picture for the customer and allow the customer to change his profile picture.
   * Enhanced Filtering: Allow customers to filter cars based on additional criteria such as fuel type, transmission, or mileage.
   * User Reviews and Ratings: Implement a system for customers to leave reviews and ratings for cars, and display an average rating for each car.
   * Push Notifications: Implement push notifications to notify customers about special offers, promotions, or important updates.
