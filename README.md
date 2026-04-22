<<<<<<< HEAD
# MovieTicketBookingApplication

##  Desktop Application (JavaFX) for booking movies tickets with SQLlite Database


## Features
- Movie selection
- User login and account creation
- Payment flow
- Order confirmation
- SQLite database integration

## Tech Stack
- Java
- JavaFX
- SQLite
- JDBC
- IntelliJ IDEA

## How to Run
1. Open the project in IntelliJ IDEA
2. Make sure JavaFX and SQLite JDBC are configured
3. Run Main.java

## General Information
We built an application in JavaFX where the user can book movie tickets


## Specifications
The project includes the following files:

1. Main-Class

2. Customer class: to save and handle all customer-related data

3. Datasource class: two SQLlite database to save account information (name, emails, etc.) and booking details (Booking-ID, name of selected movie, total price, etc.)

4. SelectMovie class (Stage 1): where the user chooses the movie they would like to watch, the date and number of tickets

 ![alt text](https://github.com/JannisMueller/MovieTicketBookingApplication/blob/master/Stage%201.png)

5. LogInPage class (Stage 2): where the user is asked to sign in to continue the check out

![alt text](https://github.com/JannisMueller/MovieTicketBookingApplication/blob/master/Stage%202.png)

6. CreateAccount class (Stage 3): if the user is not a customer yet, they needs to create an account 

![alt text](https://github.com/JannisMueller/MovieTicketBookingApplication/blob/master/Stage%203.png)

7. Payment class (Stage 4): after sign in, the user is ask to fill in their payment information (only credit card payment) and finalize the payment

![alt text](https://github.com/JannisMueller/MovieTicketBookingApplication/blob/master/Stage%204.png)

8. OrderConfirmation class (Stage 5): after the payment, the customer gets an overview over their order

![alt text](https://github.com/JannisMueller/MovieTicketBookingApplication/blob/master/Stage%205.png)



# Installation
Clone the repository and open the files in an IDE of your choice.  

$ git clone https://github.com/JannisMueller/MovieTicketBookingApplication.git

# License 

[MIT License](https://opensource.org/licenses/MIT)

=======
# movie-ticket-booking-app
JavaFX Based Movie Ticket Booking Desktop application with SQLite Integration
>>>>>>> b882239691b66c84f10d66a7f90d83cf669971ed
