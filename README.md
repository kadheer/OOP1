# Random Window Title Changer

This is a simple Python application built using PyQt6 that changes the window title randomly each time a button is pressed. The application demonstrates basic usage of PyQt6 widgets, signals, and slots.

---

## **Features**

- **Button Click Event**: Each time the button is clicked, the window title changes to a randomly selected title from a predefined list.
- **Window Title Change Event**: The application listens for changes in the window title and prints the new title to the console.
- **Disable Button on Specific Title**: If the window title changes to "Something went wrong", the button is disabled.

---

## **Requirements**

- Python 3.x
- PyQt6

---

## **Installation**

1. **Install Python**: Ensure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/).

2. **Install PyQt6**: You can install PyQt6 using pip:

   ```bash
   pip install PyQt6
   ```

3. **Clone the Repository** (if applicable):

   ```bash
   git clone https://github.com/yourusername/random-window-title-changer.git
   cd random-window-title-changer
   ```

4. **Run the Application**:

   ```bash
   python main.py
   ```

---

## **Usage**

1. Launch the application by running the script.
2. A window will appear with a button labeled "Press Me!".
3. Each time you click the button, the window title will change to a random title from the list.
4. If the title changes to "Something went wrong", the button will be disabled.

---

## **Code Overview**

### **Imports**

- `sys`: Used to handle command-line arguments.
- `PyQt6.QtWidgets`: Provides the main window and button widgets.
- `random.choice`: Used to randomly select a title from the list.

### **MainWindow Class**

- **`__init__` Method**: Initializes the main window, sets the initial title, and creates a button.
- **`the_button_was_clicked` Method**: Handles the button click event, changes the window title to a random title, and prints the new title.
- **`the_window_title_changed` Method**: Listens for changes in the window title, prints the new title, and disables the button if the title is "Something went wrong".

### **Application Execution**

- The `QApplication` object is created, and the main window is displayed.

---

## **Example Output**

```
Clicked.
Setting title: This is surprising
Window title changed: This is surprising
Clicked.
Setting title: Something went wrong
Window title changed: Something went wrong
```

---

## **License**

This project is open-source and available under the MIT License. Feel free to modify and distribute it as you see fit.

---

## **Contributing**

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

---

## **Author**

Abdul Kadir Shaikh

---
