# javaProject
The provided Java code implements a simple Car Rental System. The system consists of three main classes: Car, Customer, and Rental. Additionally, there is a class named CarRentalSystem that serves as the main control center for managing cars, customers, and rental transactions

# Car Class
The Car class represents individual cars in the rental system. It has attributes such as carId, brand, model, basePricePerDay, and a boolean flag isAvailable to track the availability status. Methods include calculating the rental price, checking availability, and methods for renting and returning a car.

# Customer Class
The Customer class represents customers with attributes customerId and name. It is a simple class to store customer information.

# Rental Class
The Rental class encapsulates information about a rental transaction, including the rented Car, associated Customer, and the number of days for the rental.

# CarRentalSystem Class
The CarRentalSystem class manages the overall functionality of the car rental system. It maintains lists of cars, customers, and rental transactions. It provides methods for adding cars and customers, renting and returning cars, and a menu-driven interface for user interaction. The menu includes options to rent a car, return a car, and exit the system.

# CarRentManage Class (Main Class)
The CarRentManage class contains the main method, creating an instance of the CarRentalSystem and populating it with sample cars. It then invokes the menu method of the CarRentalSystem to allow users to interact with the car rental system through a console-based menu.

Overall, the code creates a basic framework for a car rental system, allowing users to rent and return cars with associated pricing information. Users can navigate through the system's functionalities using the provided menu.
