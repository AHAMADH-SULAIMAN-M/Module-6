# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program

```python
class Rectangle:
 
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

        # Print values from inside the class 
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)
        
rect = Rectangle(10, 5)

```

## Output

<img width="837" height="227" alt="image" src="https://github.com/user-attachments/assets/f73673a9-452d-4797-93a5-f2ecedee8e39" />

## Result
the python program that implement encapsulation in python by defining a class rectangle with private member variable is executed successfully and verified.
