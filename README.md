![640px-Windows_2000_architecture](https://github.com/user-attachments/assets/942b913f-ff92-41e7-90e2-08674a0bf92c)![o](https://github.com/user-attachments/assets/44e810eb-7921-4bb3-92a9-42961343e436)
![oo](https://github.com/user-attachments/assets/8140493b-edd2-407d-b244-eaffe40ed3d4)

---

# Python Data Structures Comparison

| Data Structure | Ordered | Mutable | Allows Duplicates | Key-Value Pairs | Syntax Example |
|---------------|---------|---------|------------------|----------------|----------------|
| **List**      | ✅ Yes  | ✅ Yes  | ✅ Yes           | ❌ No          | `[1, 2, 3]` |
| **Dictionary** | ✅ Yes  | ✅ Yes  | ❌ No (Keys)     | ✅ Yes         | `{'a': 1, 'b': 2}` |
| **Set**       | ❌ No   | ✅ Yes  | ❌ No            | ❌ No          | `{1, 2, 3}` |
| **Tuple**     | ✅ Yes  | ❌ No  | ✅ Yes           | ❌ No          | `(1, 2, 3)` |

## Summary
- **Lists**: Ordered, mutable, and allows duplicates. Best for sequences.
- **Dictionaries**: Key-value pairs, ordered (since Python 3.7), mutable, and keys must be unique.
- **Sets**: Unordered, mutable, and only unique elements. Great for membership tests.
- **Tuples**: Ordered, immutable, and allows duplicates. Used for fixed collections of items.

---

# 🚀 **Object-Oriented Programming (OOP) in Python**  

## 🔍 **What is OOP?**  
OOP is a programming paradigm that organizes code into objects, which combine **data** and **behavior**. It makes code more modular, reusable, and easier to maintain.  

---

## 🛠️ **Key Concepts Demonstrated in this Project**  

1. **Classes and Objects**  
   - **Class**: A blueprint for creating objects.
   - **Object**: An instance of a class.  

   _Example:_  
   ```python
   class Car:
       def __init__(self, make, model):
           self.make = make
           self.model = model

       def display_info(self):
           return f"This car is a {self.make} {self.model}."

   # Creating an object
   my_car = Car("Toyota", "Camry")
   print(my_car.display_info())  # Output: This car is a Toyota Camry.
   ```  

2. **Encapsulation**  
   - Restricting access to internal variables to ensure data integrity.  

   _Example:_  
   ```python
   class BankAccount:
       def __init__(self, balance):
           self.__balance = balance  # Private variable

       def deposit(self, amount):
           self.__balance += amount
           return f"New Balance: ${self.__balance}"

   account = BankAccount(1000)
   print(account.deposit(500))  # Output: New Balance: $1500
   ```

3. **Inheritance**  
   - Reusing functionality by deriving a new class from an existing class.  
   ```python
   class Animal:
       def speak(self):
           return "Animal sound"

   class Dog(Animal):
       def speak(self):
           return "Woof!"

   dog = Dog()
   print(dog.speak())  # Output: Woof!
   ```  

4. **Polymorphism**  
   - Allowing methods to behave differently depending on the calling object.  

   _Example:_  
   ```python
   class Bird:
       def fly(self):
           return "Birds can fly."

   class Penguin(Bird):
       def fly(self):
           return "Penguins cannot fly."

   bird = Bird()
   penguin = Penguin()
   print(bird.fly())     # Output: Birds can fly.
   print(penguin.fly())  # Output: Penguins cannot fly.
   ```  

---
# Software Characteristics Overview

## 1. Operational Characteristics
These define how the software behaves during its normal use and operations.

- **Reliability:** Ensures the software consistently performs without errors.
- **Efficiency:** Measures the optimal use of resources (memory, CPU, etc.).
- **Usability:** Describes how easy it is for users to operate the software.
- **Security:** Protects data and systems from unauthorized access or attacks.
- **Availability:** Ensures the software is available for use when required.

---

## 2. Transitional Characteristics
These characteristics deal with how the software adapts to changes, migrations, or different environments.

- **Portability:** The ability to run on different hardware, operating systems, or environments.
- **Scalability:** The capacity to grow in size, users, or functionality without performance degradation.
- **Interoperability:** Ensures compatibility and integration with other systems and software.
- **Adaptability:** Allows for changes and improvements without significant rework or disruptions.
- **Migration/Upgradability:** The ease of transitioning to new versions or migrating data and users to a new system.

---

## 3. Maintainability Characteristics
These characteristics determine how easily the software can be updated or modified over its lifecycle.

- **Modularity:** The software is broken down into manageable, self-contained components.
- **Testability:** The ease with which the software can be tested to ensure quality.
- **Changeability:** How easily the software can be modified to accommodate new requirements or fix issues.
- **Flexibility:** The software’s ability to accommodate changes without significant impact on other parts of the system.
- **Correctability:** The ease of identifying and fixing defects or bugs.

---

These characteristics are essential for evaluating software performance, future-proofing, and ensuring ongoing improvements throughout its lifecycle.
---

![image](https://github.com/user-attachments/assets/09511ae9-0738-4be9-8af9-b6db15f79cdb)

---
# What are APIs?
APIs, or Application Programming Interfaces, are sets of rules and protocols that allow different software applications to communicate with each other. They act as bridges that enable interaction between different systems, software, or services without needing to understand the internal workings of each. APIs can be thought of as messengers that take a request, relay it to another system, and then return the response.

![APIs](https://github.com/user-attachments/assets/ffc09e24-c03b-4f86-9be6-35bcc8167444)
---

# Software Diagrams

---
## Block Diagram

![640px-Windows_2000_architecture](https://github.com/user-attachments/assets/0c2f2402-1656-4762-896e-bec18553f768)

---
## State Diagram

![what-is-a-state-diagram](https://github.com/user-attachments/assets/7c6ebc32-4ef1-455b-8354-ba3ccce6df6f)

---
## Flowchart

![Draw-a-flowchart-to-print-the-first-5-multiples-of-3](https://github.com/user-attachments/assets/0283f62f-8bfe-4562-960b-23437ceb5e6d)
---

