![o](https://github.com/user-attachments/assets/44e810eb-7921-4bb3-92a9-42961343e436)
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
