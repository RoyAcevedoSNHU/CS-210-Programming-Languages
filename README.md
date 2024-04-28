# CS-210-Programming-Languages

# Summarize the project and what problem it was solving.
This project defines a class ItemTracker that tracks the frequency of items read from a file. It has methods to load input from a file, save the frequency data to a file, get the frequency of a specific item, and print the frequency of all items and an item histogram.

The problem it solves is to read a list of items from a file, track the frequency of each item, and provide functionality to query and visualize the frequency data. The main function creates an ItemTracker instance, loads the input file, and then provides a menu-driven interface to interact with the ItemTracker object, allowing the user to query and visualize the item frequency data.

# What did you do particularly well?
I did several things well in the program including modular design, file handling, map usage, and menu-driven interface. 
I structured my code into a class ItemTracker, which encapsulates the functionality related to tracking item frequencies. This makes the code organized and easier to maintain. My program effectively reads input from a file and saves frequency data to a file using ifstream and ofstream classes. This demonstrates a good understanding of file handling in C++.
I used the std::map container to efficiently store item frequencies. This is a suitable choice as it allows quick retrieval and update of frequency counts. My use of a do-while loop and a switch statement to create a menu-driven interface is a good approach for user interaction. It provides a clear and structured way for users to interact with your program.

# Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
I could improve my code in several areas, such as memory management, error handling, input validation, and efficient file operations, to make it more effective, safe, and maintainable. 
To guarantee that the user submits accurate data, include input validation. For instance, I could make sure the user selects a legitimate option from the menu or verify that the file exists before trying to load it. When reading from or writing to files, look for and address possible issues to improve error handling. Before reading from an input file, for instance, make sure it was properly opened. You should also handle any exceptions that may arise while working with files.
 I could consider using smart pointers (e.g., std::unique_ptr, std::shared_ptr) to manage memory more safely and efficiently, especially if my program needs to allocate memory dynamically. When reading or writing large files, I could consider using buffered I/O (std::ifstream and std::ofstream are already buffered) to improve performance.

 # Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
Understanding how to correctly open, read from, and write to files was it bit challenging, to overcome this I referred to C++ documentation and tutorials that explain file handling concepts in detail. I had difficulties using the std::map container to store and manage item frequencies, I overcame this by reading up on how std::map works and practicing with simple examples.
I had trouble creating a menu-driven interface using a do-while loop and a switch statement, I overcame this by breaking down the implementation into smaller, manageable steps and testing each step individually to ensure it works as expected. Implementing robust error handling and input validation was a bit challenging, especially when dealing with file operations and user input. I overcame this by identifying potential error scenarios and then implementing error-checking code to handle these scenarios gracefully.

# What skills from this project will be particularly transferable to other projects or coursework?
The following project-related abilities are very transferable to other projects or coursework: file handling, data structures, object-oriented programming (OOP), and user interaction. My program's usage of classes and objects shows a basic grasp of object-oriented programming (OOP) ideas, which are broadly applicable across a wide range of programming languages and paradigms. Any project involving reading from or writing to files, such as data processing, logging, or configuration management, benefits greatly from my program's file-handling features.
The ability to work with data structures is demonstrated by the usage of the std::map container to store item frequencies, which is necessary for many programming jobs.
The ability to create user-friendly interfaces, which is essential in many software programs to deliver a seamless user experience, is demonstrated by the implementation of a menu-driven interface.

# How did you make this program maintainable, readable, and adaptable?
I made several design decisions that helped my program be more readable, maintainable, and flexible. These decisions include modular design, descriptive naming, comments, and consistent formatting. By encapsulating the functionality related to item tracking within the ItemTracker class, I've created a modular and reusable component. This makes it easier to maintain and modify the code in the future. I've used descriptive names for classes, functions, and variables (e.g., ItemTracker, loadInputFile, saveFrequencyData), which makes the code easier to understand and maintain.
I've included comments throughout the code to explain the purpose of each function and key sections of the code. This helps other developers (and your future self) understand the code's logic and intent. My code follows a consistent formatting style, which enhances readability. Consistency in formatting makes it easier to understand the code's structure and flow.
