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
The Product Management System using Java demonstrates an effective implementation of core Java and Object-Oriented Programming concepts to manage product data in a structured and efficient manner. The application enables operations such as adding, retrieving, and searching products using a simple service-based approach, which improves code organization and usability. By utilizing Java collections and modular design, the system ensures faster data handling and reduces the chances of manual errors.

Although the current version is console-based, it provides a strong foundation for building more advanced systems. The project can be further enhanced by integrating a database, adding a graphical user interface, or converting it into a web-based application. Overall, this project reflects practical understanding of software development principles and serves as a solid step toward developing scalable and real-world applications.
