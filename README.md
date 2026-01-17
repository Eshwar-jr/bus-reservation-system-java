Bus Reservation System (Java + JDBC)

A console-based Bus Reservation System developed using Java and MySQL to demonstrate JDBC connectivity and layered application design.



📌 Project Overview
This project allows users to view available buses and book tickets based on seat availability and travel date.  
It follows a clean separation of concerns using DAO and Service layers.



🚀 Features
- Display available buses
- Book tickets based on seat availability
- Date-based booking system
- DAO and Service layer architecture
- JDBC connectivity with MySQL
- Uses PreparedStatement to prevent SQL Injection
- Custom exception handling for business rules



🛠 Tech Stack
- Java
- JDBC
- MySQL
- Eclipse IDE


▶️ How to Run
1. Clone the repository
2. Import the project into Eclipse
3. Add MySQL Connector/J (8.x) to the build path
4. Create the required database and tables in MySQL
5. Update DB credentials in `DbConnection.java`
6. Run `BusDemo.java`



📘 What I Learned
- Java JDBC workflow and database connectivity
- Layered architecture (DAO & Service)
- Handling business logic separately from database logic
- Exception handling and validation
- Writing clean, maintainable Java code


🔮 Future Enhancements
- User login system
- GUI using JavaFX
- Web version using Spring Boot
- REST APIs for booking and bus management
