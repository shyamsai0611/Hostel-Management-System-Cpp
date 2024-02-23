# Hostel Booking System

## Introduction
Welcome to the Hostel Booking System project! This C++ console application is designed to manage hostel room bookings, allowing users to book rooms and view details of existing bookings.

## Features
The application provides the following features:

- Book a room  
- Check how many beds are currently occupied
- Display details for rooms with 2 sharing students
- Display details for rooms with 3 sharing students
- Display details for rooms with 4 sharing students
- Exit the application

## How to Use
To use the application, run the executable and follow the on-screen prompts. A menu will provide you with options: 

```
********** WELCOME TO HOSTEL BOOKING **********

Press [1] to book a room.
Press [2] to know how many beds are occupied. 
Press [3] to display 2 sharing students details.
Press [4] to display 3 sharing students details.
Press [5] to display 4 sharing students details.
Press [6] to exit.

Enter your choice:
```

Choose the appropriate number for the action you want to perform and press enter.

## Design and Implementation
This project was designed and implemented using Object Oriented Programming (OOP) principles in C++. The key aspects are:

- Classes were defined for Room, Student, Booking etc. 
- Member functions were used to encapsulate behavior
- Constructor and destructor functions were used where needed
- Inheritance was used to define base and derived classes
- Polymorphism was implemented through virtual functions

This OOP approach made the code more modular, reusable and extensible.

## Installation
To install this application, you need to compile the source code using a C++ compiler such as g++. You can also use an IDE like Visual Studio or Code::Blocks that supports C++ projects.

### Compilation
If you are using g++, you can compile the project with the following command in the terminal:

```
g++ -o hostel_booking main.cpp
```

Replace `main.cpp` with the actual filename if it's different. 

### Execution
After compiling the code, you can run the application by executing the compiled binary:

On Windows:
```
hostel_booking.exe
``` 

On Linux or Mac:   
```
./hostel_booking
```

## Dependencies
Ensure you have a C++ compiler installed and properly set up on your system to build and run this application.

## Contribution
If you wish to contribute to this project, please feel free to fork the repository and submit a pull request with your enhancements.

## Contact
For any additional questions or feedback, please open an issue in the repository.
