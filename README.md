## Assignment Overview

Parul Mital
00:36 (1 minute ago)
to me

# Restaurant Menu & Order Management System

 

## Assignment Overview

This project is part of **Assignment – Part 2: Data Structures**. 

The objective is to build a **Restaurant Menu & Order Management System** using only Python’s **core data structures** such as dictionaries, lists, and nested combinations of both.

 

The assignment focuses on processing structured data, simulating customer order flows, tracking inventory safely, and analysing historical sales data — without using external libraries or advanced frameworks.

 

---

 

## Data Used

The project uses the provided datasets exactly as given:

 

- `menu` – restaurant items with category, price, and availability

- `inventory` – stock and reorder levels for each item

- `sales_log` – historical daily order data

 

No modifications were made to the initial data values; all operations work on top of the provided structures.

 

---

 

## Tasks Implemented

 

### ✅ Task 1: Menu Exploration

- Printed the complete menu grouped by **category** (Starters, Mains, Desserts)

- Displayed item price and availability status

- Computed and printed:

  - Total number of menu items

  - Total number of available items

  - Most expensive item (name and price)

  - Items priced below ₹150

 

This task demonstrates dictionary traversal, filtering, and aggregation logic.

 

---

 

### ✅ Task 2: Cart Operations

- Implemented a **cart system** using a list of dictionaries

- Supported the following cart operations:

  - Add item (with menu existence and availability checks)

  - Merge quantities for repeated items (no duplicates)

  - Remove items by name

  - Update item quantity

- Simulated the required order sequence step‑by‑step and printed cart state after each operation

- Generated a final **Order Summary** including:

  - Item totals

  - Subtotal

  - GST (5%)

  - Total payable amount

 

This task focuses on conditional logic, list operations, and real‑world order handling scenarios.

 

---

 

### ✅ Task 3: Inventory Tracking with Deep Copy

- Created a **deep copy** of the inventory before modification

- Demonstrated deep copy protection by:

  - Modifying original inventory

  - Showing the backup remained unchanged

  - Restoring original state before continuing

- Deducted stock quantities based on the final cart

- Handled insufficient stock safely (no negative stock values)

- Printed **Reorder Alerts** for items at or below reorder level

- Displayed both `inventory` and `inventory_backup` at the end to confirm data isolation

 

This task highlights mutable data handling and safe state management.

 

---

 

### ✅ Task 4: Daily Sales Log Analysis

- Calculated and printed **total revenue per day**

- Identified the **best‑selling day** based on revenue

- Found the **most frequently ordered item** across all orders

- Added a new day’s sales to the log and re‑computed statistics

- Used `enumerate()` to print a numbered list of all orders across all days in the specified format

 

This task demonstrates nested data traversal, aggregation, and reporting logic.

 

---

 

## Technologies Used

- Python 3

- Core Python data structures:

  - Dictionaries

  - Lists

  - Nested structures

- `copy.deepcopy()` for safe data duplication

 

---

 

## Files in This Repository

 
