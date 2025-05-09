# Library Manager CLI

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![License](https://img.shields.io/badge/License-MIT-green)

A command-line application to manage your personal book library. This Python-based tool allows you to add, remove, search, and display books, as well as view statistics about your library. It also features file handling to automatically save and load your library data.

---

## Features

- **Add a Book**: Store book details such as title, author, publication year, genre, and read status.
- **Remove a Book**: Delete books by their title.
- **Search for a Book**: Search books by title or author.
- **Display All Books**: View all stored books in a formatted list.
- **Display Statistics**: Get insights into the total number of books and the percentage of books read.
- **Save and Load Library**: Automatically saves your library to `library.txt` when exiting and reloads it upon restart.

---

## Requirements

- Python 3.8 or higher
- No additional libraries or dependencies required

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Abdurrehman2003/library-manager-cli.git
   ```
2. Navigate to the project directory:
   ```bash
   cd library-manager-cli
   ```

---

## Usage

1. Run the program:
   ```bash
   python library_manager.py
   ```
2. Follow the on-screen menu to manage your library:
   ```
   Welcome to your Personal Library Manager!
   1. Add a book
   2. Remove a book
   3. Search for a book
   4. Display all books
   5. Display statistics
   6. Exit
   Enter your choice:
   ```
3. Choose an option to add, remove, search, or view books.
4. Your library data is automatically saved to `library.txt` upon exit.

---

## File Handling

The program automatically saves your library data to a file named `library.txt` in the same directory as the script.  

- **First Run**: If `library.txt` does not exist, the program starts with an empty library.  
- **Subsequent Runs**: The program loads data from `library.txt` if available.

---

## Example Workflow

### **Adding a Book**
```
Enter the book title: The Great Gatsby
Enter the author: F. Scott Fitzgerald
Enter the publication year: 1925
Enter the genre: Fiction
Have you read this book? (yes/no): yes
Book added successfully!
```

### **Displaying All Books**
```
Your Library:
1. The Great Gatsby by F. Scott Fitzgerald (1925) - Fiction - Read
2. 1984 by George Orwell (1949) - Dystopian - Unread
```

### **Displaying Statistics**
```
Total books: 2
Percentage read: 50.0%
```

### **Exiting**
```
Library saved to file. Goodbye!
```

---

## Contributing

Contributions are welcome! If you'd like to contribute, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch to your forked repository.
5. Submit a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Inspired by the need for a simple, command-line-based library management tool.
- Built with Python for ease of use and accessibility.

---

## Contact

For questions or feedback, reach out via:  
📧 Email: [abdulrehmanbinadeem@gmail.com](mailto:abdulrehmanbinadeem@gmail.com)  
🔗 LinkedIn: [Abdul Rehman](https://www.linkedin.com/in/abdulrehman-genai-engineer/)
<br> 
<br> 


## ⭐ If you like this project, please consider giving it a star! ⭐
