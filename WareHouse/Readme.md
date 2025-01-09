
# Food Warehouse Management System

## Overview
This project simulates a **Food Warehouse Management System** in C++. It utilizes Object-Oriented Programming principles, including classes, inheritance, and the Rule of 5. The system manages volunteers, customers, and orders within a warehouse setting, with dynamic handling of various tasks such as collecting and delivering food packages.

---

## Features
- **Customer Management**: Handles soldier and civilian customers, each with unique characteristics.
- **Volunteer Roles**:
  - Collectors (Regular and Limited)
  - Drivers (Regular and Limited)
- **Order Workflow**: From order placement to delivery.
- **Simulation Control**: Step-based simulation for dynamic system updates.
- **Error Handling**: Comprehensive error management for invalid inputs.
- **Backup and Restore**: State persistence using a global backup.

---

## How to Run
1. Compile the program on a **CS Lab UNIX machine** using the provided skeleton files.
2. Execute the program, passing the path of a configuration file as a command-line argument.

---

## Key Commands
- `step <number_of_steps>`: Simulates warehouse steps.
- `order <customer_id>`: Places a new order.
- `customerStatus <customer_id>`: Prints customer details.
- `volunteerStatus <volunteer_id>`: Prints volunteer details.
- `log`: Prints action history.
- `close`: Closes the warehouse.

---

## Files Provided
- `Warehouse.h`, `Order.h`, `Customer.h`, `Volunteer.h`, `Action.h`, `main.cpp`
- Example configuration and execution guides.
