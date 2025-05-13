# Bus Booking System (MySQL Database Project)

## Description

The **Bus Booking System** is a relational database project designed to simulate the core backend functionality of an online bus reservation platform. It manages buses, routes, schedules, drivers, passengers, bookings, and payments using well-structured SQL tables and constraints. This project demonstrates the use of **primary keys**, **foreign keys**, **1-to-1**, **1-to-many**, and **many-to-many** relationships.

## Features

- Admin management (credentials for system access)
- Driver and bus assignment (1-to-1)
- Route and schedule planning (1-to-many)
- Passenger registration
- Booking system with seat number validation
- Payment tracking for each booking

## How to Set Up and Run the Project

### Prerequisites

- MySQL Server (v5.7 or higher recommended)
- MySQL Workbench or any SQL client

### Steps to Run

1. Clone or download this repository.
2. Open **MySQL Workbench** (or your preferred SQL editor).
3. Create a new schema (database) named `bus_booking`:
   ```sql
   CREATE DATABASE bus_booking;
   USE bus_booking;
   
