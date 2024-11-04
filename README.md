# Movie Ticket Booking System 🎬

A simple and efficient movie ticket booking system developed in C++ using MySQL for seat reservations. This project leverages Object-Oriented Programming (OOP) principles to ensure a structured and modular design. Users can view seat availability and book tickets, with real-time updates to the database for seamless functionality.

## Features ✨
- **Seat Reservation System**: Users can view available seats, book them, and get real-time updates on seat status.
- **OOP-based Modular Design**: The project follows OOP principles, making it easy to maintain, extend, and modify.
- **Real-Time Updates**: SQL queries manage seat availability, ensuring the database stays updated in real time.
- **Encapsulation & Abstraction**: The `Seats` class manages seat availability, hiding internal data representation and exposing only necessary functionalities to the user.
- **Cross-platform Sleep Functionality**: Windows API used for adding delays to simulate real-time system interactions.

## Technologies Used 💻
- **C++**: Core language for developing the booking system.
- **MySQL**: Database for managing seat reservations.
- **SQL**: To execute queries for real-time updates on seat availability.
- **OOP Concepts**: Encapsulation, abstraction, and modularity for a clean and structured codebase.
- **Windows API**: Used for implementing sleep functionality to simulate time delays.

## Installation and Setup 🚀

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/movie_ticket_booking.git
    ```

2. **Install MySQL**: Ensure you have MySQL installed on your system. You can download it from [here](https://dev.mysql.com/downloads/installer/).

3. **Set up the MySQL database**:
    - Open the MySQL console.
    - Create a database for the project:
      ```sql
      CREATE DATABASE movie_booking;
      USE movie_booking;
      ```
    - Import the database schema (if provided in the repository) using the following command:
      ```bash
      mysql -u your_username -p movie_booking < schema.sql
      ```

4. **Compile the C++ code**: Use your favorite C++ compiler (e.g., `g++` or `Visual Studio`) to compile the project files.
    ```bash
    g++ main.cpp -o movie_booking_system
    ```

5. **Run the program**:
    ```bash
    ./movie_booking_system
    ```

## Usage 📝

Once the system is running, you will be presented with the following options:
- View available seats.
- Book tickets.
- Real-time seat status updates are reflected as soon as a seat is booked.

## Code Structure 🏗️

The project is structured around OOP principles:
- **`Seats` class**: Manages seat availability, booking, and status updates. Encapsulation is applied to hide internal data structures.
- **Database interaction**: SQL queries are used to fetch and update seat data in the MySQL database.

## Future Improvements 🌟
- Implement a user authentication system to allow multiple users to log in and book tickets.
- Add support for viewing different shows and times.
- Enhance the UI for better user experience.
- Expand the system to support multiple theaters and screens.

## Contributing 🤝

Contributions are welcome! Please follow these steps to contribute:
1. Fork the project.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
