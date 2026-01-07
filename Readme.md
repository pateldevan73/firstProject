# 📊 Interactive Personal Data Collector

Welcome to the **Personal Data Collector**, a Python-based CLI tool designed to capture, process, and display user information while demonstrating fundamental programming concepts.

---

## 🚀 Overview
This project serves as a practical exploration of Python's core features. It interactively collects user data, performs type analysis, and reveals the underlying memory management of variables.

### ✨ Key Features
* **Dynamic Input:** Captures name, age, height, and favorite numbers.
* **Type Inspection:** Uses the `type()` function to display the data category of each input.
* **Memory Mapping:** Utilizes the `id()` function to show the unique memory address of variables.
* **Data Processing:** Includes a logic block to calculate the user's approximate birth year.

---

## 🛠️ Technical Stack
* **Language:** Python 3.x
* **Concepts:** Type Casting (`int`, `float`), Variable Assignment, String Formatting, and Memory Addresses.

---

## 📁 Project Structure
| File | Description |
| :--- | :--- |
| `project1.py` | The main source code containing the logic and user prompts. |
| `README.md` | Documentation for the repository. |

---

## 💻 How to Run
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/personal-data-collector.git](https://github.com/YourUsername/personal-data-collector.git)
    ```
2.  **Navigate to the Directory:**
    ```bash
    cd personal-data-collector
    ```
3.  **Run the Script:**
    ```bash
    python project1.py
    ```

---

## 📝 Example Output
```text
Welcome to the Interactive Personal Data Collector!

Please enter your name: Devan
Please enter your age: 19
Please enter your height in meters: 1.75
Please enter your favourite number: 7

Thank you! Here is the information we collected:

Name: Devan (Type: <class 'str'> , Memory Address: 1407...
Age: 19 (Type: <class 'int'> , Memory Address: 1407...
...
Your birth year is approximately: 2006 (based on your age 19)