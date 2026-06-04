# 6a)   Python OOP: Abstract Class & Method Example

##  AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

##  ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

##  Program
```
from abc import ABC
class Shape(ABC):
    def area(self):
        pass
class Rectangle(Shape):
    length = 5
    breadth =3 
    def area(self):
        return self.length * self.breadth

class Circle(Shape):
  radius = 4
  def area(self):
      return 3.14 * self.radius **2

r=Rectangle()
c=Circle()
print("Area of a rectangle:", r.area()) #call to 'calculate_area' method defined inside the class 'Rectangle'
print("Area of a circle:", c.area()) #call to 'calculate_area' method defined inside the class 'Circle'.
```
## Output
<img width="669" height="198" alt="image" src="https://github.com/user-attachments/assets/e6f8457f-db9d-4893-bf43-8e1a56ec40e7" />

## Result
Program executed Successfully.
