# Office Management System – OOP Project

This project simulates an office environment using Object-Oriented Programming (OOP) in Python. It includes managing employees, their vehicles, work routines, salaries, and office operations like hiring, firing, and checking lateness.

## Project Description

The project uses four main classes:

  - Person – Represents a general person with attributes like name, mood, health rate, and money.

  - Employee – Inherits from Person and adds attributes like ID, email, salary, and a Car object.

  - Car – Simulates a car with fuel and velocity management.

  - Office – Manages employee operations like hiring, firing, salary management, and attendance checking.

The goal is to model real-life office interactions using OOP principles like inheritance, encapsulation, and polymorphism.

## Features

 - Employee management (hire, fire, reward, deduct)

 - Simulate commuting and fuel usage via Car objects

 - Sleep, eat, and work routines affecting mood and health

 - Lateness calculation with automatic salary deduction/reward

 - Track total number of employees with class-level data

## Project Structure

```

OOP_Project/
│
├── OOP Project.py        # Main Python script with all classes and logic
├── README.md             # Project documentation (this file)

```



## How It Works
  ##### Classes & Methods

  - Person Class
   **__init__(name, money=0)**

   **sleep(hours)**

   **eat(meals)**

   **buy(items)**

