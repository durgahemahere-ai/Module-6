# 6c)   Method Overriding-Fish and Shark Class Inheritance in Python

##  AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

##  ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

##  PROGRAM:
```
class Fish:
    @classmethod
    def type(cls):
        print("fish")
class Shark(Fish):
    @classmethod
    def type(cls):
        print("shark")
fish_obj=Fish()
shark_obj=Shark()
fish_obj.type()
shark_obj.type()
```

## OUTPUT
<img width="469" height="199" alt="image" src="https://github.com/user-attachments/assets/25bdea2c-784d-4e18-a5ae-22603e3824fe" />

## RESULT
Program executed Successfully.
