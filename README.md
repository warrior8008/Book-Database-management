# Library Management System

A simple C program to manage books in a library using a menu-driven interface. The program allows users to add, display, search, update, delete, and store book records. It also supports file handling for saving and loading records.

## Features
- Add a new book record
- Display all book records
- Search a book by ISBN, author, or title
- Update a book record
- Delete a book record
- Save book records to a file
- Load book records from a file
- Exit the system

## Getting Started

### Prerequisites
To run this program, you need:
- A C compiler (like `gcc`)

### Running the Program

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/library-management-system.git
    ```

2. Navigate to the project directory:
    ```bash
    cd library-management-system
    ```

3. Compile the program:
    ```bash
    gcc library_management_system.c -o library_management_system
    ```

4. Run the program:
    ```bash
    ./library_management_system
    ```

## Program Features

### Menu Options
When the program runs, the following menu options will be displayed:

1.Add a new book record
2.Display all book records
3.Search a book by ISBN
4.Search a book by Author
5.Search a book by Title
6.Update a book record
7.Delete a book record
8.Save book records to a file
9.Load book records from a file
10.Exit


Users can select the desired option by entering the corresponding number.

### Adding a Book
To add a book, the program will prompt for:
- ISBN
- Title
- Author
- Year of publication

### Searching for a Book
You can search for a book by:
- ISBN
- Author name
- Title

### Updating a Book
To update a book, enter the ISBN of the book you want to update, then modify the title, author, or year of publication.

### Deleting a Book
To delete a book, enter the ISBN of the book to be removed.

### Saving and Loading Records
- **Saving:** The program saves the book records to a file (`library_records.dat`) for future use.
- **Loading:** When the program starts, it can load existing book records from the file.

## Example Output

1. **Adding a Book:**
    ```
    Enter ISBN: 123456
    Enter Title: The C Programming Language
    Enter Author: Brian Kernighan, Dennis Ritchie
    Enter Year: 1988
    ```

2. **Displaying Books:**
    ```
    Book 1:
    ISBN: 123456
    Title: The C Programming Language
    Author: Brian Kernighan, Dennis Ritchie
    Year: 1988
    ```

3. **Search by ISBN:**
    ```
    Enter ISBN: 123456
    ISBN: 123456, Title: The C Programming Language, Author: Brian Kernighan, Dennis Ritchie, Year: 1988
    ```

## File Handling
The program uses file handling to persist data. All book records are stored in a file (`library_records.dat`). When the program starts, it loads any previously saved book records from this file.

## Authors
- [Your Name](https://github.com/yourusername)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
