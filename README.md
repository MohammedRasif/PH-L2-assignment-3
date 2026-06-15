# Football Ticket Booking System Database

## Project Overview

This project contains the database design for a Football Ticket Booking System. The database manages users, football matches, and ticket bookings.

## Database Tables

### Users

Stores information about users of the system.

**Fields:**

* user_id
* full_name
* email
* role
* phone_number

### Matches

Stores information about football matches.

**Fields:**

* match_id
* fixture
* tournament_category
* base_ticket_price
* match_status

### Bookings

Stores ticket booking information.

**Fields:**

* booking_id
* user_id
* match_id
* seat_number
* payment_status
* total_cost

## Relationships

* One user can have multiple bookings.
* One match can have multiple bookings.
* Each booking belongs to one user.
* Each booking is associated with one match.

## Constraints Used

* Primary Key
* Foreign Key
* Unique Constraint
* Check Constraint

## Sample Data

The database includes sample records for:

* Users
* Matches
* Bookings

## Technologies

* PostgreSQL
* SQL (DDL & DML)

