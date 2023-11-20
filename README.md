Get_next_line - Read a Line from a File Descriptor

Welcome to Get_next_line, a project designed to read a line from a file descriptor. This implementation offers a versatile and efficient solution for reading lines from various sources, making it an invaluable tool for file processing within C programs.

** Project Overview **

- What does Get_next_line do?
    - Get_next_line is a function that reads a line from a file descriptor. It allows for dynamic reading, ensuring that only the necessary amount of memory is allocated for each line, providing an efficient and memory-conscious solution. This project is particularly useful when dealing with large datasets, as it streamlines the process of reading and processing files line by line.

- Key Features
    - Dynamic Memory Allocation: Get_next_line dynamically allocates memory for each line it reads, ensuring optimal resource usage.
    - Compatibility: The implementation is designed to work seamlessly with a variety of file descriptors, making it versatile for different input sources.
    - Error Handling: Robust error handling is integrated to provide informative messages in case of unexpected scenarios or file-related issues.

** How to Compile Get_next_line **

To compile the Get_next_line function, follow these straightforward steps:

  - Clone the Repository:
      - git clone git@github.com:Bgarnn/01-Get_next_line.git
      - cd 01-Get_next_line
  - Compile the Function:
      - make: This will generate static library containing the Get_next_line function.
  - Clean the Build:
      - make clean: This removes the object files, leaving only the compiled library.
