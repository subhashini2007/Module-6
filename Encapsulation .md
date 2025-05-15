# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Class1Students` with two private attributes: `__name` and `__age`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__name` and `__age`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `obj1` class to trigger the constructor.

---

## 💻 Program
```
class Class1Students:
    def __init__(self,name,age): 
        self.__name = name
        self.__age   = age
    def speak(self):
        print(f"my name is {self.__name}, and I am {self.__age} years old.")
obj1 = Class1Students("Michael", 40)
obj1.speak()
obj2=Class1Students('John',25)
obj2.speak()
```
## Output
![image](https://github.com/user-attachments/assets/9df0a592-5a51-4ef2-9d7a-91b5cb099511)


## Result
Program executed successfully.
