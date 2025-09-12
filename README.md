# Milestone Assignment 1: Policy Management System for an Insurance Company

## Project Description
This project is a simple **Object-Oriented Programming (OOP)**-based system built with Python.  
Its purpose is to simulate basic processes in an insurance company, such as managing policyholders, insurance products, and payment transactions.

The system consists of several interacting classes, covering functionalities such as:
* Registering and managing policyholders.
* Defining and updating insurance products.
* Processing payments, sending reminders, and applying penalties.
* Demonstrating the system’s functionality with sample data.

---

## Project Structure
The project is divided into several Python files, each with a specific responsibility:

* `policyholder.py`: Contains the **`Policyholder`** class to manage policyholder data and status (register, suspend, reactivate).
* `product.py`: Contains the **`Product`** class to define insurance products and methods to update or suspend products.
* `payment.py`: Contains the **`Payment`** class, responsible for handling payment transactions, including processing, sending reminders, and applying penalties.
* `policy_management.ipynb`: A Jupyter Notebook that acts as the main *driver*. It imports the classes above, creates objects, and demonstrates the system workflow.

---

## How to Run the Project

### 1. Requirements
Make sure you have Python installed.  
This project also requires the external library `prettytable` to display data in a tabular format.

Install it using pip:
```bash
pip install prettytable

### 2\. Running the Code

1.  Open the `policy_management.ipynb` file using Jupyter Notebook.
2.  Run the code.

The output will display a table containing:
	•	Policyholder details
	•	The products they own
	•	Total premium
	•	Payment status

-----

## Key Features

  * **Separate Classes**: Each main entity (Policyholder, Product, Payment) is represented by its own class, promoting modularity and readability.
  * **Encapsulation**: Object attributes (e.g., `name`, `amount`, `status`) re managed through class methods such as `process_payment()` or `suspend()`, demonstrating the principle of encapsulation.
  * **Functional Demonstration**: The code in `policy_management.ipynb` provides a practical example of how methods and objects interact to achieve the desired results.

<!-- end list -->

