## Product Management System
A console-based Java application designed to manage product information efficiently using Object-Oriented Programming (OOP) principles. This project demonstrates core Java concepts such as classes, objects, collections, and service-based architecture.

### Project Overview
The Product Management System helps organizations manage and organize product-related data such as product name, category, storage location, and warranty year. The application provides simple yet effective search and retrieval functionality using Java collections.

### Objectives
- Store and manage product details in a structured manner
- Enable quick search and retrieval of product information
- Reduce manual errors using a centralized system
- Apply Java OOP concepts in a real-world use case

### Features
- Add multiple products
- View all products
- Search product by exact name
- Search products using partial keywords (case-insensitive)
- Modular and extensible code structure

### Technologies Used
- Java (Core Java)
- Object-Oriented Programming
- Java Collections (ArrayList)
- Console-based Application

### Class Description

### Product.java
Represents the product entity with attributes:
- Product Name
- Product Type
- Storage Location
- Warranty Year
  
Includes constructors, getters, setters, and toString() method.

### ProductService.java
Handles all business logic:
- Add product to the list
- Retrieve all products
- Find a product by name
- Search products using keywords
  
Uses ArrayList to store product objects.

### Main.java
- Acts as the entry point of the application
- Creates product objects
- Calls service methods
- Displays output on the console

### Sample Output
```shell
Products containing text: black

Product{name='Type C', type='Cable', place='Black Drawer', warranty=2024}
Product{name='Logitech Keyboard', type='Keyboard', place='Black Table', warranty=2024}
```
### Advantages
- Platform-independent (Java-based)
- Easy to understand and maintain
- Efficient product search functionality
- Scalable for future enhancements

### Limitations
- No graphical user interface (GUI)
- No database integration
- Suitable for small-scale use only

### Future Enhancements
- Integrate database using JDBC / MySQL
- Add GUI using JavaFX or Swing
- Implement user authentication
- Convert to REST API using Spring Boot
- Deploy as a web-based application

## References
- GeeksforGeeks
- Stack Overflow
- JavaTPoint
- W3Schools
- GitHub

## Conclusion
This project strengthened practical knowledge of Core Java and OOP concepts and serves as a strong foundational project for software development and data-related roles.
