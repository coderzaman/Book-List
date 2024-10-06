### Book-List

**Project Description**:
The **Book-List** project is a simple web application where users can add books to their personal list by entering the book's title, author's name, and ISBN. The application also allows users to delete books from the list. All books are stored using `localStorage`, ensuring that the list persists even after the page is refreshed.

Key Features:
- Add books to the list by providing:
  - **Book Title**
  - **Author Name**
  - **ISBN**
- Prevents adding duplicate books with the same ISBN.
- Delete books from the list.
- Validates input fields to ensure all fields are filled before adding a book.
- Stores the book list in `localStorage` so that the data is retained across browser sessions.

**Technologies Used**:
- **HTML**: For the basic structure of the application.
- **CSS**: For minimal styling (optional).
- **JavaScript**: For form validation, list management, and interaction with `localStorage`.

**Usage**:
1. Clone or download the repository.
2. Open `index.html` in your browser.
3. Input the book title, author's name, and ISBN.
4. Click "Add Book" to add the book to your list.
5. You can delete a book by clicking the "Delete" button next to it.
6. If you try to add a book with an ISBN that already exists, a message will notify you that the book is already in the list.

**Form Validation**:
- All fields (Book Title, Author Name, and ISBN) are required.
- If any field is not filled, an error message will be shown prompting the user to fill it out.
- Duplicate ISBNs are not allowed.

**Installation**:
- No special setup required. Clone the repo and open `index.html` in your browser.

```bash
git clone https://github.com/coderzaman/book-list.git
```

**How It Works**:
- When a user submits the form, JavaScript validates the input fields.
- If all fields are valid and the ISBN is unique, the book is added to the list and saved in `localStorage`.
- The list of books is displayed on the page, and each book has a "Delete" button to remove it from the list and `localStorage`.

**Example**:
Add a book with:
- Title: _The Great Gatsby_
- Author: _F. Scott Fitzgerald_
- ISBN: _9780743273565_

If successful, the book will be added to the list. If the ISBN is already present, an error message will appear.

**Future Enhancements**:
- Improve user interface with better styling.
- Add search functionality to filter books in the list.
- Implement editing functionality for books.

---

Feel free to contribute to this project or suggest improvements!
