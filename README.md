# 🧪 Hotel Management System – Bug Finding Challenge

## 📌 Overview

This project is a **frontend debugging and logic assessment challenge** built using **HTML, CSS, and Vanilla JavaScript**.

Candidates are given a partially working **Hotel Management System** that contains **intentional bugs**. The goal is to **identify, debug, and fix** all issues within a limited time.

This test focuses on:

* JavaScript logic
* DOM manipulation
* Date & time handling
* Price calculation accuracy
* Validation logic
* Edge case handling

---

## ⏱ Time Limit

**40–50 minutes**

---

## 🧩 Features Implemented (Buggy)

The application allows hotel staff to manage room bookings and guest data.

---

### Guest Entry Fields

Each booking entry contains:

* Guest Name
* Contact Number
* Room Number
* Room Type (Single, Double, Deluxe, Suite)
* Check-in Date
* Check-out Date
* Price per Night
* Number of Guests

---

### Displayed Per Booking

Each booking row should show:

* Guest Name
* Room Number
* Room Type
* Check-in Date
* Check-out Date
* Number of Nights
* Price per Night
* Total Bill
* Booking Status (Active / Completed / Cancelled)

---

### Dashboard Statistics

The system displays:

* Total Bookings
* Active Bookings
* Completed Bookings
* Cancelled Bookings
* Total Revenue
* Average Stay Duration
* Occupied Rooms Count
* Available Rooms Count

---

## 📜 Business Rules (Must Be Enforced)

The following rules must be implemented correctly:

1. Guest name must not be empty
2. Contact number must be valid
3. Room number must be unique for active bookings
4. Check-out date must be after check-in date
5. Number of nights must be calculated correctly
6. Total bill = nights × price per night
7. Deleting a booking must update all statistics
8. Cancelling a booking must update availability
9. No overlapping bookings for the same room
10. Prices must be numeric and positive
11. Dates must be valid
12. No NaN or undefined values in UI
13. Dashboard values must always be correct
14. UI must not crash on edge cases
15. State must remain consistent

---

## 🧠 Candidate Tasks

Candidates must:

1. Identify all bugs
2. Fix incorrect calculations
3. Enforce all validation rules
4. Fix room availability logic
5. Fix date handling
6. Ensure UI stability
7. Keep state consistent
8. Ensure accurate statistics
9. Handle edge cases properly
10. Prevent invalid data entry

---

## 🚫 Restrictions

* ❌ No external libraries
* ❌ No frameworks
* ❌ No backend
* ❌ No UI frameworks

Use only:
✔ HTML
✔ CSS
✔ Vanilla JavaScript

---

## ✅ Bonus (Optional Enhancements)

If time permits, candidates may implement:

* Room availability calendar
* Search by guest name
* Filter by booking status
* Sorting by check-in date
* Price range filtering
* LocalStorage persistence
* Booking edit functionality
* Export to CSV
* Revenue chart

---

## 📂 Project Structure

```
/project-root
│
├── index.html
└── README.md
```

---

## 📢 Important Note

This is a **logic-first debugging test**, not a UI design challenge.

Focus on:
✔ Correctness
✔ Edge cases
✔ Business rule enforcement
