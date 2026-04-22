# parking-management-system
## 📌 Description
This project is a Parking Management System developed using Java Swing and MySQL. It manages vehicle parking with advanced features like time-based billing and slot tracking.

## 🚀 Features
- Add Vehicle (INSERT)
- Remove Vehicle (DELETE)
- View Records (SELECT)
- Update Vehicle (UPDATE)
- Search Vehicle using Vehicle Number (Key-based search)
- Time-Based Parking Charges
- Slot Management:
  - Total Capacity
  - Available Slots
  - Occupied Slots

## 🛠 Technologies Used
- Java (Swing for GUI)
- JDBC (Database Connectivity)
- MySQL

## ⚙️ How It Works
1. User enters vehicle details
2. System assigns parking slot
3. Entry time is recorded
4. On exit, time difference is calculated
5. Charges are generated based on duration
6. Slot availability is updated dynamically

## 🗄 Database
Table: cars  
Fields:
- brand
- no_plate
- slots_no
- phone_no
- entry_time
- exit_time
- charge

## ▶️ How to Run
1. Setup MySQL database
2. Import table structure
3. Run the Java file
4. Use GUI to manage parking
