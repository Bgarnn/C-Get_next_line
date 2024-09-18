** LineReader - Read a Line from a File Descriptor

Welcome to LineReader, a project designed to efficiently read a line from a file descriptor. This implementation provides a versatile solution for handling line-by-line reading from various sources, making it an essential tool for file processing in C programs.

** Project Overview **

- What does LineReader do?
    - LineReader is a function that reads a line from a file descriptor. It uses dynamic reading to allocate memory only as needed for each line, optimizing both efficiency and memory usage. This is particularly useful for processing large datasets by reading and managing files line by line.

- Key Features
    - Dynamic Memory Allocation: LineReader dynamically allocates memory for each line it reads, ensuring efficient resource usage.
    - Compatibility: The implementation works seamlessly with a variety of file descriptors, making it versatile for different input sources.
    - Error Handling: Robust error handling is integrated to provide informative messages in case of unexpected scenarios or file-related issues.

** How to Compile LineReader **

To compile LineReader, follow these straightforward steps:

  - Clone the Repository:
      - `git clone git@github.com:Bgarnn/C-LineReader.git`
      - `cd C-LineReader
  - Compile the Function:
      - `gcc line_reader.c line_reader_utils.c `
      - `./a.out`