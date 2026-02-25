Assignment 03: Library Management System with Collections & Exceptions
📌 Description
This project implements a robust Book Management System using the Java Collections Framework.
It emphasizes:
Dynamic data storage
User-defined exceptions
Strict data validation
Clean and reliable dataset management
The system prevents invalid data (such as negative book prices) at the object construction level, ensuring strong data integrity.
✨ Key Features
⚠️ Custom Exception Handling
Implements a user-defined exception: InvalidPriceException
Prevents creation of Book objects with negative pricing
Ensures financial data consistency
📚 Dynamic Data Storage
Uses ArrayList<Book>
Allows flexible and scalable inventory management
Supports dynamic addition and iteration of books
🏗️ Robust Constructor Validation
A parameterized Book constructor throws InvalidPriceException
Validation occurs during object creation
Invalid objects are never added to the collection
🔁 Functional Programming Elements
Uses forEach() with lambda expressions
Filters and displays books by genre (e.g., "Fiction")
Demonstrates modern Java iteration techniques
📊 Statistical Processing
Iterates through the collection
Calculates the average price of valid books
Demonstrates aggregation logic using collections
