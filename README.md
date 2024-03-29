# ZOO-Management-System

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
   - [Download through Git](#download-through-git)
   - [Download through ZIP file](#download-through-zip-file)
6. [Usage](#usage)
7. [Database](#database)
8. [Troubleshooting](#troubleshooting)
9. [Contributions](#contributions)
10. [License](#license)
11. [Acknowledgments](#acknowledgments)

## Overview
This graphical application serves as a comprehensive Zoo Management System, providing an intuitive interface for managing various aspects of a zoo. The system is built using CustomTkinter for a visually appealing and customized GUI. It incorporates SQLite3 for efficient and secure data storage.

## Features
- **CustomTkinter GUI:** The application utilizes CustomTkinter, a customized version of the Tkinter library, to create an intuitive and aesthetically pleasing user interface for managing the zoo.
- **SQLite3 Database:** The system employs SQLite3 as the underlying database to store and manage information about animals, staff, exhibits, and other essential zoo-related data.
- **Manage Animals:** Users can add, view, edit, and delete information about the animals in the zoo, including their species, habitat, and feeding details.
- **Staff Management:** The system allows for the management of zoo staff, including their roles, responsibilities, and contact information.
- **Exhibit Tracking:** Users can keep track of different zoo exhibits, their descriptions, and the animals residing in each exhibit.

## Requirements
- Python 3.9 or later
- CustomTkinter library
- SQLite3 library (usually included with Python)

## Installation
## Download through Git:
1. **Open a Terminal or Command Prompt:**
   - On Windows, you can use the Command Prompt or PowerShell.
   - On macOS or Linux, use the Terminal.
2. **Navigate to the Directory Where You Want to Clone the Repository:**
   ```bash
   cd path/to/your/directory
   ```
3. **Clone the Repository:**
   ```bash
   git clone https://github.com/UltraDeveloper7/ZOO-Management-System.git
   ```
4. **Navigate into the Cloned Directory:**
   ```bash
   cd ZOO-Management-System
   ```
Now, you have successfully cloned the repository to your local machine. You can proceed with the next steps, such as installing dependencies and running the application.

## Download through ZIP file:
1. Download the project as a zip file. You can do this by clicking on the "Code" button on the [GitHub repository page](https://github.com/UltraDeveloper7/ZOO-Management-System) and selecting "Download ZIP."
2. Extract the downloaded zip file to a location of your choice.
3. Open your terminal or command prompt and navigate to the extracted directory.
   ```bash
   cd path/to/extracted/folder
   ```
4. Run inside that folder te following command:
   ```bash
   python GUI.py
   ```
   
## Usage
1. Launch the application using the provided instructions.
2. Use the graphical interface to navigate through different sections, such as Animals, Staff, and Exhibits.
3. Add, view, edit, or delete information as needed.

## Database
- The SQLite3 database file (`ZOO.db`) is created automatically upon running the application.
- You can explore and manage the database using SQLite tools if needed.

## Troubleshooting
- Check for updates to the CustomTkinter library or other dependencies that may impact the application.

## Contributions
Contributions are welcome! Feel free to fork this repository and submit a pull request with your enhancements.

## License
This project is licensed under the [MIT License](LICENSE). You can find the full text of the license [here](https://opensource.org/licenses/MIT).

## Acknowledgments
- CustomTkinter: [https://github.com/TomSchimansky/CustomTkinter]
- SQLite: [https://www.sqlite.org/index.html]
