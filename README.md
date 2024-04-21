# FireSoft-Limited_Airport-Flight-Management-System

# Airline Flight Management System

This is a simple command-line program written in C++ that allows users to manage flight schedules, book flights, cancel flights, and search for available flights.

## Prerequisites

To compile and run this program, you need to have the following installed on your system:

- C++ compiler (e.g., g++)
- Make utility

## Compilation

1. Open a terminal and navigate to the project directory.
2. Run the following command to compile the program:

"make"
This will create an executable file named `airline_flight_management`.

## Running the Program

After compiling the program, you can run it using the following command:

"./airline_flight_management"
This will start the Airline Flight Management System, and you will see a menu with the following options:

1. Schedule New Flight
2. Show Flight Schedule
3. Book Flight
4. Cancel Flight
5. Search Flights
6. Exit

## Using the Program

1. **Schedule New Flight**: Select this option to add a new flight to the schedule. You will be prompted to enter the origin, destination, departure time, arrival time, number of available seats, and ticket price.

2. **Show Flight Schedule**: Select this option to display all the scheduled flights with their details, including flight ID, origin, destination, departure time, arrival time, available seats, and ticket price.

3. **Book Flight**: Select this option to book a flight. You will be prompted to enter the flight ID of the flight you want to book. If the flight is available and has seats, the booking will be successful.

4. **Cancel Flight**: Select this option to cancel a scheduled flight. You will be prompted to enter the flight ID of the flight you want to cancel.

5. **Search Flights**: Select this option to search for available flights between a specific origin and destination. You will be prompted to enter the origin and destination locations.

6. **Exit**: Select this option to exit the program.

## Running Tests

The project includes a test suite written using the Catch2 unit testing framework. To run the tests, compile the program and then run the `catch2_tests` executable:

"./catch2_tests"
This will run all the test cases and display the results in the terminal.

## Notes

- The program uses a vector to store the flight information. All data is stored in memory and will be lost when the program exits.
- Flight IDs are generated randomly using alphanumeric characters.
- Input validation is minimal in this implementation, so please ensure that you enter valid data when prompted.

