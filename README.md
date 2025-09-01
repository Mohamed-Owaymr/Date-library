# 📅 Date Library (C++)

A robust and extensible **C++ Date Library** designed to simplify handling, validating, and formatting dates.  
It provides utilities for **date validation, calendar display, leap year detection, date arithmetic, and formatting** in an object-oriented style.  

---

## 🎯 Purpose of This Project

This library was created as a **learning project** to help me:

- ✅ Understand how **date libraries** are built and work internally.  
- ✅ Practice **Object-Oriented Programming (OOP)** concepts in C++.  
- ✅ Get hands-on experience with **constructors, methods, validation, and formatting**.  
- ✅ Build confidence before moving on to using the **C++ built-in date/time libraries**.  

By re-inventing the wheel, I can understand the design and challenges behind date manipulation rather than just using ready-made functions.

---

## 🚀 What I Learned

Through this project, I practiced important OOP concepts:

- **Constructors Overloading**  
  - Different ways to initialize a date (current date, day/month/year, from string, from day of year).
- **Encapsulation**  
  - Keeping date fields private and exposing only safe operations through methods.
- **Validation**  
  - Ensuring dates are valid (e.g., February has 28 or 29 days).
- **Static vs Non-Static Methods**  
  - Some utilities don’t need an object (like checking leap years), while others depend on a specific object’s state.
- **Error Handling**  
  - Using exceptions (`invalid_argument`, `out_of_range`) for invalid input.
- **Abstraction**  
  - Creating methods like `displayMonthCalendar()` that hide the complex internal logic.

This helps me connect theory with practice.

---
## 🚀 Features

- ✅ Multiple constructors for date creation:
  - Current system date
  - Day/Month/Year
  - String with delimiter (e.g., `"01/09/2025"`)
  - Day of year + Year
- 🔍 Validation helpers:
  - Check valid days, months, and years
  - Leap year detection
- 📆 Calendar utilities:
  - Display month and year calendars in the console
  - Get first day of the month
  - Day of week calculation
- ⏳ Time-related conversions:
  - Days, hours, minutes, and seconds in months and years
- 📜 Formatting:
  - Convert date objects to string formats
  - Get day names (`Sun`, `Mon`, …)
  - Get month names (`Jan`, `Feb`, …)
- 📈 Arithmetic:
  - Increase date by one month safely (handles overflow of days)
