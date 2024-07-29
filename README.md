# RentalFlix ERD
## Overview
### Design an Entity-Relationship Diagram (ERD) for a movie rental service, capturing the key entities and relationships required to manage the service efficiently.

> **Explanation:**  
> Movie - MovieFormat:</br>
> One-to-Many: One movie can have multiple formats.</br>
Movie.MovieID → MovieFormat.MovieID.
>
> Customer - Rental:</br>
> One-to-Many: One customer can have multiple rentals.</br>
Customer.CustomerID → Rental.CustomerID.
>
> MovieFormat - Rental:</br>
> Many-to-One: Many rentals can be associated with one movie format.</br>
Rental.FormatID → MovieFormat.FormatID.
>
> Movie - Reservation:</br>
> One-to-Many: One movie can have multiple reservations.</br>
Movie.MovieID → Reservation.MovieID.
>
> Customer - Reservation:</br>
> One-to-Many: One customer can have multiple reservations.</br>
Customer.CustomerID → Reservation.CustomerID. 

## ERD

![ERD](images/rental-flix-erd.PNG)