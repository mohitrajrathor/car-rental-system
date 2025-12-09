# Car Rental System

## Overview

The **Car Rental System** is a console-based Java application that simulates a simple car rental service. It allows customers to rent vehicles for a specified number of days and provides functionality to manage cars, customers, and rental transactions.

## Features

* Add and manage cars in the rental system
* Register customers and associate them with rentals
* Calculate rental cost based on the number of days
* Rent available cars and update their availability status
* Process car returns and restore availability
* Display clear information about rentals and pricing

## Project Structure

* **Car**
  Represents a car with attributes such as `carId`, `brand`, `model`, and `basePricePerDay`. Includes methods to manage rental availability.

* **Customer**
  Represents a customer with fields like `customerId` and `name`.

* **Rental**
  Represents a rental transaction, linking a `Car` and `Customer` for a defined rental duration.

* **CarRentalSystem**
  Core class that manages the lists of cars, customers, and rentals. Provides methods to add cars, rent them out, and process returns.

* **Main**
  Entry point of the application. Initializes the system, loads sample data, and launches the interactive console menu.

## How to Run the Project

### Prerequisites

* Java Development Kit (JDK) installed
* Basic familiarity with running Java programs

### Steps

1. Clone or download the project.
2. Open it in your preferred IDE (IntelliJ, Eclipse, VS Code, etc.).
3. Run the `Main` class.
4. Follow on-screen console prompts to rent or return cars.

### Menu Options

* **Rent a Car** – Enter your name, choose a car, and specify rental days
* **Return a Car** – Return a rented vehicle using its car ID
* **Exit** – Close the application

## Example Usage

```
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 
```

**Renting a car example:**

```
=== Rent a Car ===
Enter your name: John Doe

Available Cars:
C001 - Toyota - Camry
C002 - Honda - City

Enter the car ID you want to rent: C001
Enter the number of days for rental: 5

=== Rental Information ===
Customer ID: CUS1
Customer Name: John Doe
Car: Toyota Camry
Rental Days: 5
Total Price: $300.00

Confirm rental (y/n): y
Car rented successfully.
```

## Future Improvements

* Add a graphical user interface (GUI)
* Integrate a database to store car and customer records
* Implement additional features such as:

  * Discount options
  * Insurance add-ons
  * Expanded car categories

## Technologies Used

* **Java** – Core programming language
* **JDK** – For compiling and running the program
