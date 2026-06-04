# 6b)   Python OOP: Encapsulation with Private Members

##  AIM

To create a class robot in python with the version as private member initialized with the value as 22 change the value of the private member using getter and setter methods and also display the value of the version variable.

##  ALGORITHM

1.Start the program.

2.Define a class Robot.

3.Inside the class, define the constructor __init__() that initializes a private attribute __version with value 22.

4.Define the method get_version() that returns the value of __version.

5.Define the method set_version(version) that updates __version with the given value.

6.Create an object r of the Robot class.

7.Call r.get_version() and print the returned version (22).

8.Call r.set_version(23) to update the version to 23.

9.Call r.get_version() again and print the updated version (23).

10.End.

##  Program
```
class Robot:
   def __init__(self):
      self.__version = 22

   def get_version(self):
      return self.__version

   def set_version(self, version):
      self.__version = version
r=Robot()
print(r.get_version())
r.set_version(23)
print(r.get_version())
```
## Output
<img width="517" height="181" alt="image" src="https://github.com/user-attachments/assets/615c2ead-2198-46b8-abe6-541b5baeaa82" />

## Result
Program execured Successfully.
