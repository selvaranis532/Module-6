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
```
class Rectangle:
    def __init__(self, length, width):
        self.__length = length  
        self.__width = width    
    
    
    def print_values(self):
        print(self.__length)
        print(self.__width)


rect = Rectangle(5, 3)
rect.print_values()

```

## Output
<img width="1104" height="257" alt="image" src="https://github.com/user-attachments/assets/24273ad2-cf61-4486-baca-0a8941c4ee0a" />

## Result
Thus, the program is executed successfully
