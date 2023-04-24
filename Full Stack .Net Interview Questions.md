# Full Stack .Net Developer interview Questions and answers


1. What  is .NET?
.NET is a software framework developed by Microsoft that provides a programming model for building applications, and a runtime for executing those applications.
 are the different components of .NET?
Common Language Runtime (CLR), .NET Framework Class Library, ASP.NET, ADO.NET, Windows Forms, Windows Presentation Foundation (WPF), Windows Communication Foundation (WCF), and .NET Core.
 is C#?
C# is a modern, object-oriented programming language developed by Microsoft for building applications on the .NET Framework.

2. What  is ASP.NET?
ASP.NET is a web application framework developed by Microsoft for building dynamic web pages and web services.

3. What  is the difference between ASP.NET MVC and ASP.NET Web Forms?
ASP.NET Web Forms uses a page-based model, while ASP.NET MVC uses a controller-based model. ASP.NET MVC is better suited for complex web applications, while ASP.NET Web Forms is better suited for rapid development of simple web applications.

4. What  is the difference between .NET Core and .NET Framework?
.NET Core is a cross-platform, open-source version of .NET, while .NET Framework is a Windows-only version of .NET. .NET Core is designed to be modular and lightweight, while .NET Framework is more feature-rich and mature.

5. What  is a delegate in C#?
A delegate in C# is a type that represents a reference to a method. It can be used to pass methods as arguments to other methods, or to define callback methods.

6. What  is an interface in C#?
An interface in C# is a blueprint for a class that defines a set of methods and properties that the class must implement.

7. What  is a constructor in C#?
A constructor in C# is a method that is called when an object of a class is created. It is used to initialize the object's state.

8. What  is a static class in C#?
A static class in C# is a class that cannot be instantiated and contains only static members. It is used to group related methods and properties that do not require instance-level state.

9. What  is a sealed class in C#?
A sealed class in C# is a class that cannot be inherited from. It is used to prevent further derivation of a class.

10. What  is a nullable type in C#?
A nullable type in C# is a value type that can also be assigned a null value. It is denoted by appending a ? to the value type.

11. What  is garbage collection in .NET?
Garbage collection in .NET is a process by which the runtime automatically frees memory that is no longer in use by the application.

12. What  is the difference between Value Types and Reference Types in C#?
Value types in C# store their data in the stack, while reference types store their data in the heap. Value types include primitive types like int and bool, while reference types include objects and arrays.

13. What  is LINQ?
LINQ (Language-Integrated Query) is a set of language extensions in C# that provide a unified way to query data from different data sources, such as arrays, lists, and databases.

14. What  is Entity Framework?
Entity Framework is a data access technology in .NET that allows developers to work with databases using object-oriented programming concepts.

15. What  is the difference between ADO.NET and Entity Framework?
ADO.NET is a low-level data access technology in .NET that provides a set of classes for working with databases, while Entity Framework is a higher-level data access technology that provides an object-oriented abstraction over ADO.NET.

16. What  is a stored procedure? 
A stored procedure is a pre-compiled set of SQL statements that is stored in the database and can be executed repeatedly by calling the stored procedure instead of writing the same SQL statements multiple times.

17. What  is a stored procedure in SQL Server?
A stored procedure in SQL Server is a pre-compiled set of SQL statements that is stored in the database and can be executed repeatedly by calling the stored procedure instead of writing the same SQL statements multiple times.

18. What  is the difference between a stored procedure and a function in SQL Server?
A stored procedure in SQL Server does not return a value, while a function does. Functions can be used in SQL statements, while stored procedures cannot.

19. What  is the difference between an inner join and an outer join in SQL?
An inner join in SQL returns only the rows that have matching values in both tables being joined, while an outer join returns all the rows from one table and the matching rows from the other table being joined.

20. What  is the difference between a primary key and a unique key in SQL?
A primary key in SQL is a column or combination of columns that uniquely identifies each row in a table, while a unique key ensures that each value in a column or combination of columns is unique, but does not necessarily identify each row uniquely.

21. What  is the difference between a view and a table in SQL?
A view in SQL is a virtual table that is based on the result of a SELECT statement, while a table is a physical storage structure that holds data.

22. What  is the difference between a clustered index and a non-clustered index in SQL?
A clustered index in SQL physically reorders the data in a table based on the indexed column, while a non-clustered index creates a separate data structure that contains a copy of the indexed column and a reference to the original data.

23. What  is the difference between a synchronous and asynchronous method in .NET?
A synchronous method in .NET blocks the calling thread until the method completes, while an asynchronous method allows the calling thread to continue executing while the method executes in the background.

24. What  is a task in .NET?
A task in .NET is an object that represents an asynchronous operation. It can be used to manage and monitor the progress of the operation, and to retrieve the result when it completes.

25. What  is the difference between a thread and a task in .NET?
A thread in .NET is a unit of execution that runs in the operating system, while a task in .NET is an abstraction over a thread that provides a higher-level programming model for managing asynchronous operations.

26. What  is the difference between a static and an instance method in C#?
A static method in C# is a method that can be called without creating an instance of the class, while an instance method is a method that is called on an instance of the class.

27. What  is the difference between a public and a private method in C#?
A public method in C# can be called from any code that has access to the class, while a private method can only be called from within the class itself.

28. What  is the difference between an abstract class and an interface in C#?
An abstract class in C# can have method implementations and state, while an interface can only have method signatures. A class can inherit from only one abstract class, but can implement multiple interfaces.
29. What  is the difference between a thread-safe and non-thread-safe code in .NET?
Thread-safe code in .NET is code that can be safely called from multiple threads without causing conflicts or errors, while non-thread-safe code can cause race conditions and other concurrency issues. Thread-safety can be achieved through various mechanisms, such as locking, atomic operations, and synchronization.

30. What  is the purpose of the using statement in C#?
The using statement in C# is used to declare and initialize disposable objects and ensure that they are properly disposed of when they are no longer needed.

31. What  is LINQ in .NET?
LINQ (Language-Integrated Query) is a set of language extensions to C# and VB.NET that allow developers to query data from various data sources, such as databases, XML documents, and objects, using a unified syntax.

32. What  is Entity Framework in .NET?
Entity Framework is an object-relational mapping (ORM) framework in .NET that enables developers to work with relational data using domain-specific objects and methods instead of writing SQL code.

33. What  is ASP.NET in .NET?
ASP.NET is a web application framework in .NET that allows developers to create dynamic web applications using a variety of programming languages, such as C# and VB.NET.

34. What  is MVC in ASP.NET?
MVC (Model-View-Controller) is a design pattern in ASP.NET that separates the application into three components: the model (data), the view (user interface), and the controller (logic).

35. What  is the difference between an abstract class and a sealed class in C#?
An abstract class in C# cannot be instantiated and is meant to be subclassed, while a sealed class cannot be subclassed. An abstract class can have abstract and non-abstract members, while a sealed class can only have non-virtual, non-abstract members.

36. What  is the difference between a struct and a class in C#?
A struct in C# is a value type that is stored on the stack, while a class is a reference type that is stored on the heap. Structs are typically used for small, simple types, while classes are used for larger, more complex types.

37. What  is the difference between a delegate and an event in C#?
A delegate in C# is a type that represents a method signature and can be used to pass methods as parameters to other methods or to store methods in variables. An event in C# is a way for objects to signal that something has happened and for other objects to respond to that signal by executing a method.

38. What  is the difference between the .NET Framework and .NET Core?
The .NET Framework is a Windows-only framework for building desktop and web applications using the .NET platform. .NET Core is a cross-platform framework for building applications using the .NET platform that can run on Windows, Linux, and macOS.

39. What  is a nuget package in .NET?
A nuget package in .NET is a collection of files, such as DLLs, that can be easily installed and managed in a project using the NuGet package manager. NuGet packages can be used to add functionality, such as libraries and tools, to a .NET project.

40. What  is an interface in C#?
An interface in C# is a type that defines a set of method signatures that a class or struct must implement. It provides a way to enforce a contract between two parts of a codebase, ensuring that they can communicate with each other.

41. What  is dependency injection in .NET?
Dependency injection is a technique in .NET where the dependencies of a class or method are passed in as arguments or are retrieved from a container, rather than being instantiated directly by the class or method. This makes it easier to write and maintain code that is loosely coupled and highly testable.

42. What  is a unit test in .NET?
A unit test in .NET is a type of automated test that verifies the behavior of a small, isolated piece of code, such as a single method or class. It helps to ensure that code is correct, reliable, and maintainable.

43. What  is a mock object in .NET?
A mock object in .NET is a type of object that is used in unit testing to simulate the behavior of a real object. It can be used to test the interactions between objects or to simulate the behavior of external dependencies.

44. What  is a repository pattern in .NET?
The repository pattern in .NET is a way of separating the data access logic of an application from the business logic. It provides a way to abstract away the details of data storage and retrieval and allows for more flexibility in how data is managed.

45. What  is the difference between a private and a protected member in C#?
A private member in C# can only be accessed from within the class that defines it, while a protected member can be accessed from within the class that defines it or any subclass of that class.

46. What  is the difference between a synchronous and an asynchronous method in C#?
A synchronous method in C# blocks the calling thread until the method completes, while an asynchronous method returns immediately and allows the calling thread to continue executing while the method completes in the background.

47. What  is a lambda expression in C#?
A lambda expression in C# is a shorthand way of writing an anonymous method that can be used to define delegates, events, and LINQ queries. It allows for concise and expressive code that is easier to read and write.

48. What  is the difference between a reference type and a value type in C#?
A reference type in C# is a type that is stored on the heap and passed by reference, while a value type is stored on the stack and passed by value. Reference types include classes, interfaces, arrays, and delegates, while value types include structs, enums, and primitive types.

49. What  is the purpose of the static keyword in C#?
The static keyword in C# is used to declare a class, method, property, or field as belonging to the type itself, rather than to any instance of the type. Static members can be accessed without creating an instance of the class, making them useful for utility methods and constants.

50. What  is the difference between an abstract class and an interface in C#?
An abstract class can provide implementation details and define fields and constructors, while an interface cannot. A class can implement multiple interfaces, but can only inherit from a single abstract class. Abstract classes are designed to be extended, while interfaces are designed to be implemented.

51. What  is the purpose of the using statement in C#?
The using statement in C# is used to ensure that a resource, such as a file or database connection, is properly disposed of when it is no longer needed. It is a shorthand way of calling the Dispose method on an object that implements the IDisposable interface.

52. What  is LINQ in .NET?
LINQ (Language-Integrated Query) is a set of extensions to the .NET Framework that allow for querying data from various sources using a common syntax. It provides a way to write expressive and concise queries that can be used with in-memory collections, databases, and other data sources.

53. What  is the difference between a primary key and a foreign key in a database?
A primary key is a column or combination of columns that uniquely identifies each row in a table, while a foreign key is a column or combination of columns that refers to a primary key in another table. Foreign keys are used to enforce referential integrity and establish relationships between tables.

54. What  is an HTTP cookie?
An HTTP cookie is a small piece of data that is sent from a website to a user's web browser and stored on the user's device. It is typically used to store user preferences and session data, and can be used to track user behavior across multiple sessions.

55. What  is CORS in web development?
CORS (Cross-Origin Resource Sharing) is a mechanism in web development that allows a web page to make requests to a different domain than the one that served the original page. It is used to enable secure communication between different domains and prevent cross-site scripting attacks.

56. What  is ASP.NET MVC?
ASP.NET MVC (Model-View-Controller) is a framework for building web applications in .NET that separates the application into three components: the model (data and business logic), the view (UI), and the controller (handles user input and manages communication between the model and the view).

57. What  is Entity Framework in .NET?
Entity Framework is an object-relational mapping (ORM) framework in .NET that provides a way to map a database schema to a set of objects in code. It allows developers to work with data in an object-oriented way and abstract away the details of database access.

58. What  is ASP.NET Web API?
ASP.NET Web API is a framework for building HTTP services that can be consumed by a variety of clients, including web applications, mobile apps, and desktop applications. It provides a way to build RESTful APIs in .NET that can be consumed by any client that supports HTTP.

59. What  is the difference between a string and a StringBuilder in C#?
A string in C# is an immutable object that cannot be modified once it is created, while a StringBuilder is a mutable object that allows for efficient manipulation of character strings. StringBuilder is typically used when building or modifying long strings, as it can be more efficient than repeatedly creating new string objects.

60. What  is the difference between an asynchronous method and a synchronous method in C#?
A synchronous method blocks the execution of the current thread until it completes, while an asynchronous method allows the current thread to continue executing while the method is running in the background. Asynchronous methods can be more efficient for operations that involve waiting for I/O or other operations that don't require the CPU to be active.

61. What  is the purpose of the lock statement in C#?
The lock statement in C# is used to synchronize access to a shared resource in a multithreaded environment. It ensures that only one thread can access the shared resource at a time, preventing race conditions and other synchronization issues.

62. What  is the difference between a struct and a class in C#?
A struct is a value type that is typically used for small, lightweight objects that are frequently created and destroyed, while a class is a reference type that is typically used for larger, more complex objects that have a longer lifespan. Structs are typically stored on the stack, while classes are stored on the heap.

63. What  is the difference between an instance method and a static method in C#?
An instance method operates on an instance of a class and can access instance-level data and methods, while a static method is associated with the class itself and can only access static data and methods. Static methods are typically used for utility functions that don't require access to instance data.

64. What  is the purpose of the IDisposable interface in C#?
The IDisposable interface in C# is used to indicate that an object has unmanaged resources that need to be cleaned up when the object is no longer needed. It provides a way for objects to release resources such as file handles or database connections, even if an exception is thrown or the object is not explicitly disposed.

65. What  is the difference between a delegate and an event in C#?
A delegate is a type that represents a method signature and can be used to encapsulate a method call, while an event is a way to notify other objects when a particular action occurs. Events are typically implemented using delegates, and allow objects to subscribe to and unsubscribe from the event.

66. What  is the difference between a sealed class and a static class in C#?
A sealed class cannot be inherited, while a static class cannot be instantiated. Sealed classes are typically used to prevent inheritance and ensure that a class cannot be extended or modified, while static classes are used for utility functions that don't require instance-level data.

67. What  is the difference between a shallow copy and a deep copy in C#?
A shallow copy creates a new object that references the same data as the original object, while a deep copy creates a new object with new data that is a complete duplicate of the original object. Shallow copying is typically faster and more efficient, but can lead to issues if the original object is modified. Deep copying is slower but provides a completely independent copy of the original object.

68. What  is the difference between an implicit conversion and an explicit conversion in C#?
An implicit conversion is a conversion that occurs automatically, without the need for a cast or conversion operator, while an explicit conversion requires an explicit cast or conversion operator. Implicit conversions are typically used for conversions that are considered safe and reliable, while explicit conversions are used for conversions that may result in data loss or other issues.

69. What  is the difference between a nullable type and a non-nullable type in C#?
A nullable type can have a value or a null value, while a non-nullable type must have a value. Nullable types are typically used for scenarios where a value may not be present, such as optional parameters or database fields.

70. What  is the difference between LINQ and SQL in C#?
LINQ is a language-integrated query syntax that allows developers to query data from any data source using a consistent syntax, while SQL is a language used specifically for querying data from relational databases. LINQ is more flexible than SQL and can be used to query data from a variety of sources, including in-memory collections, XML documents, and web services.
71. What  is a lambda expression in C#?
A lambda expression is an anonymous function that can be used to create delegates or expression trees in C#. It provides a concise syntax for defining a function inline, without the need for a separate method or delegate declaration.

72. What  is an extension method in C#?
An extension method is a static method that can be called on an instance of a class as if it were an instance method. It allows developers to add functionality to existing types without modifying the original type or creating a new derived type.

73. What  is the difference between a StringBuilder and a string in C#?
A StringBuilder is a mutable string that can be modified without creating a new instance, while a string is immutable and cannot be modified. StringBuilder is typically used for scenarios where a string needs to be modified frequently, such as when building a long string from smaller parts.

74. What  is the difference between an abstract class and an interface in C#?
An abstract class can contain implementation code and can have fields and methods with access modifiers, while an interface only contains method and property signatures and cannot contain implementation code or access modifiers. An abstract class can be used as a base class for other classes, while an interface is used to define a contract that a class must implement.

75. What  is the difference between a try-catch block and a try-finally block in C#?
A try-catch block is used to catch and handle exceptions that may be thrown during the execution of a block of code, while a try-finally block is used to ensure that a block of code is executed regardless of whether an exception is thrown. The finally block is always executed, even if an exception is thrown and not caught.

76. What  is a unit test in C#?
A unit test is a type of automated test that is used to verify the correctness of a single unit of code, such as a method or class. It is typically written by the developer and is used to ensure that changes to the code do not introduce new bugs or regressions.

77. What  is a mock object in C#?
A mock object is a test double that is used in unit testing to simulate the behavior of a real object. It allows developers to isolate the code being tested and control the behavior of dependencies that may be difficult or expensive to create in a test environment.

78. What  is the difference between an integration test and a unit test in C#?
An integration test is a type of automated test that is used to verify the correct interaction between multiple units of code, while a unit test is used to verify the correctness of a single unit of code. Integration tests are typically more complex and may require the use of test data or external dependencies.

79. What  is a deployment package in C#?
A deployment package is a collection of files and other resources that are used to deploy a software application. It typically includes executable files, configuration files, and other resources that are required for the application to run in a production environment.

80. What  is the difference between a value type and a reference type in C#?
A value type contains the actual value of a variable, while a reference type contains a reference to the location in memory where the value is stored. Value types are typically smaller in size and are passed by value, while reference types are larger in size and are passed by reference.

81. What  is the difference between an event and a delegate in C#?
An event is a type of delegate that is used to notify subscribers when a specific action occurs, while a delegate is a type that represents a method signature and can be used to reference a method or a group of methods that share the same signature.

82. What  is the difference between a static method and an instance method in C#?
A static method belongs to a class and can be called without creating an instance of the class, while an instance method is called on an instance of a class. Static methods are typically used for utility methods or methods that do not require access to instance-level data.

83. What  is the difference between synchronous and asynchronous programming in C#?
Synchronous programming is a type of programming where the program waits for an operation to complete before moving on to the next operation, while asynchronous programming is a type of programming where the program can continue to execute while an operation is in progress. Asynchronous programming is typically used for operations that may take a long time to complete, such as network operations or disk I/O.

84. What  is a task in C#?
A task is an object that represents a single unit of work that can be executed asynchronously. It can be used to perform long-running operations without blocking the main thread of the application, and can be monitored and cancelled if necessary.

85. What  is the difference between a thread and a task in C#?
A thread is an execution path that can run concurrently with other threads, while a task is a higher-level abstraction that can represent a single unit of work that may be executed on one or more threads. Tasks can be managed by the Task Parallel Library and can be more efficient than manually managing threads.

86. What  is the difference between an inner join and an outer join in SQL?
An inner join returns only the rows that have matching values in both tables, while an outer join returns all the rows from one table and the matching rows from the other table, with NULL values in the columns where there is no match.

87. What  is normalization in SQL?
Normalization is a process of organizing data in a relational database to reduce data redundancy and improve data integrity. It involves breaking down a database into smaller, more manageable tables and defining relationships between them.

88. What  is a stored procedure in SQL?
A stored procedure is a precompiled set of SQL statements that can be stored in a database and executed as a single unit. It can be used to improve performance by reducing network traffic and improving security by limiting access to the underlying data.

89. What  is a trigger in SQL?
A trigger is a special type of stored procedure that is automatically executed in response to certain database events, such as an insert, update, or delete operation on a table. It can be used to enforce business rules, validate data, or perform other operations based on changes to the database.

90. What  is an index in SQL?
An index is a database structure that improves the speed of data retrieval operations by creating a copy of a portion of a table's data in a separate data structure. It can be used to speed up searches, sorts, and joins on the indexed columns.

91. What  is a deadlock in SQL?
A deadlock occurs when two or more transactions are waiting for each other to release resources that they need to complete their operations. This can result in a situation where neither transaction can proceed, and the database is effectively stuck.

92. What  is a view in SQL?
A view is a virtual table that is based on the result of a select statement. It can be used to simplify complex queries, provide a layer of abstraction over the underlying data, or restrict access to sensitive data by showing only a subset of the available columns.

93. What  is a cursor in SQL?
A cursor is a database object that is used to retrieve and manipulate data row-by-row. It can be used to perform complex processing on large datasets, but should be used with caution as it can have a negative impact on performance.

94. What  is a transaction in SQL?
A transaction is a sequence of one or more database operations that are executed as a single unit of work. Transactions can be used to ensure data consistency and integrity, and can be rolled back if an error occurs or if the transaction is cancelled.

95. What  is LINQ in C#?
LINQ (Language-Integrated Query) is a set of features in C# that provides a consistent way to query different types of data sources, including databases, collections, and XML documents. It allows developers to write SQL-like queries in C# code, making it easier to work with data.

96. What  is Entity Framework in C#?
Entity Framework is an object-relational mapping (ORM) framework for .NET that allows developers to work with relational databases using object-oriented code. It provides a set of tools for generating database schemas from code, querying data using LINQ, and performing CRUD (Create, Read, Update, Delete) operations.

97. What  is dependency injection in C#?
Dependency injection is a design pattern that allows objects to be constructed and wired together in a way that decouples them from their dependencies. It involves passing dependencies into a class through its constructor or properties, rather than having the class create or look up its own dependencies.

98. What  is the difference between a stack and a queue in C#?
A stack is a collection of items that supports last-in, first-out (LIFO) access, meaning that the last item added to the stack is the first item that is removed. A queue is a collection of items that supports first-in, first-out (FIFO) access, meaning that the first item added to the queue is the first item that is removed.

99. What  is garbage collection in C#?
Garbage collection is a feature of the .NET runtime that automatically manages memory by reclaiming unused memory objects. It works by periodically identifying and deleting memory objects that are no longer being used by the application, freeing up memory for other objects to use.
