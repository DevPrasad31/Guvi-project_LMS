# 🧠 Java IO-Based Project with Basic UI & File Storage

This project demonstrates a complete Java application built using *JDK, **Java IO, **DAO pattern, and a **console-based user interface*. It follows a structured approach for file-based data persistence and CRUD operations.

---

## ✅ Project Setup Steps

### 1. Creating the New Project with JDK & IDE Setup
- Install JDK (version 8 or above).
- Set up your project in an IDE like IntelliJ IDEA or Eclipse.
- Configure the build path and create the main class files.

---

### 2. Define the Project Structure

A modular folder structure is followed:

project-root/ │ ├── model/             # Java classes representing entities ├── dao/               # DAO classes for CRUD logic ├── io/                # File handling logic ├── ui/                # Console UI logic ├── main/              # Entry point └── data/              # Text/CSV files used for storage

---

### 3. Design the Database Schema (File-based)

Instead of a traditional RDBMS, we use files to store structured data. Example schema:

Account.txt

AccountNumber | HolderName | Balance | AccountType | IsActive

Each entry is stored as a line in a .txt file.

---

### 4. Create Files for CRUD Operations

- File creation: At application start, check and create necessary files.
- File structure follows one-record-per-line logic.
- Fields are separated by delimiters like | or ,.

---

### 5. Implement IO Connectivity using java.io Package

- Use BufferedReader, BufferedWriter, FileReader, FileWriter, etc.
- Read and write records line by line.
- Implement methods for:
  - Storing new data
  - Reading existing data
  - Updating a line
  - Deleting a record (by rewriting file)

---

### 6. Create Model and DAO Classes

- *Model Classes* represent real-world entities (Account, User, etc.)
- *DAO (Data Access Object)* Classes handle:
  - create()
  - read()
  - update()
  - delete()

Follows SRP (Single Responsibility Principle) for separation of logic.

---

## 🎨 UI Layer (Console-Based)

### 7. Aesthetics and Visual Appeal

- Text-based menus with clear prompts.
- Print success/failure messages using standard output.
- Separator lines and formatted outputs for readability.

### 8. Component Placement & Alignment

- Menu-driven structure for user interaction.
- Clear input prompts followed by logic execution.
- Proper spacing and indentation for ease of use.

### 9. Responsiveness and Accessibility

- Prompt for re-entry on wrong input.
- Case-insensitive inputs.
- Input validation for numbers, strings, etc.
- Error messages are descriptive and helpful.

---

## 🔧 Tools & Technologies

- *Java SE* (JDK 8+)
- *Java IO Package*
- *Console UI*
- *Text File Storage*

---

## 🛠 Future Enhancements

- Add GUI with *JavaFX* or *Swing*
- Use *JDBC + MySQL* for real database integration
- Implement authentication and role-based access
- Export reports to PDF or CSV

---

## 📌 Author

*Dev Prasad*

---

## 📄 License

This project is released under the [MIT License](LICENSE).

> Feel free to clone, fork, or enhance this project. Happy coding!

