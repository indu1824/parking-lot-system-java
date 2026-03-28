# 🚗 Parking Lot Management System (Java)

## 📌 Project Overview

This project is an **Advanced Parking Lot Management System** developed using Java.
It simulates a real-world parking system by efficiently managing vehicle parking, slot allocation, and removal operations.

The system is designed using **Data Structures (Queue, HashMap)** and **Object-Oriented Programming (OOP)** concepts.

---

## 🚀 Features

* 🚗 Park vehicles (Car, Bike, Truck)
* 🅿️ Efficient slot allocation using Queue
* 🔍 Search vehicle by number
* 🎫 Ticket generation for each vehicle
* ⏱️ Time-based parking and fee calculation
* 💰 Total revenue tracking
* 📊 Display parking lot status
* 🚫 Prevent duplicate vehicle entry

---

## 🧠 Concepts Used

### 🔹 Data Structures

* **Queue (LinkedList)** → Manages free parking slots (FIFO)
* **HashMap** → Stores slot-to-vehicle mapping for fast lookup

### 🔹 Object-Oriented Programming

* Classes and Objects
* Encapsulation
* Enum for vehicle types

### 🔹 System Design Concepts

* Slot allocation strategy
* Ticket-based tracking
* Multi-vehicle support

---

## ⚙️ How It Works

1. Parking slots are initialized and divided for different vehicle types

2. When a vehicle arrives:

   * System checks for duplicate entry
   * Allocates nearest available slot using Queue
   * Generates a ticket

3. When a vehicle exits:

   * Slot is freed and added back to Queue
   * Parking fee is calculated based on time

---

## ▶️ How to Run

### Step 1: Compile

```bash
javac UltimateParkingLotApp.java
```

### Step 2: Run

```bash
java UltimateParkingLotApp
```

---

## 📂 Project Structure

* `Vehicle` → Stores vehicle details
* `ParkingLot` → Core logic (DSA operations)
* `UltimateParkingLotApp` → Main class (User Interface)

---

## 📸 Sample Output

```
=== Ultimate Parking Lot System ===

1. Park Vehicle
2. Remove Vehicle
3. Search Vehicle
4. Display Status
5. Show Revenue
6. Exit
```

---

## 🎯 Key Highlights

* ✅ O(1) time complexity for parking & removal
* ✅ Real-world system simulation
* ✅ Clean and modular design
* ✅ Easy to extend (GUI / Database / Backend)

---

## 📈 Future Enhancements

* 🖥️ GUI using Java Swing
* 🌐 Web backend using Spring Boot
* 💾 Database integration (MySQL)
* 📊 Admin dashboard

---

## 👩‍💻 Author

**Padala Indira Bhavani**
Java Developer | Software Developer

---

## ⭐ Conclusion

This project demonstrates how **DSA concepts can be applied in real-world applications**, combining efficiency with practical system design.
