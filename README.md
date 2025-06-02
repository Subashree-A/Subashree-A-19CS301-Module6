# Subashree-A-19CS301-Module6

# 19CS301-Module-6

- **Name:** Subashree A  
- **Register Number:** 212222020029
  
EX.NO: 6.1   POLYMORPHISM

### AIM: To Create two specific classes- Beans and Mango. Along with that, create a generic function that tells us the type and color of the object we pass. Mind you, since we have passed only “obj” through it, this obj can be any object.


### ALGORITHM:
Step1: create class Beans and def a function type and color

Step 2: create a class Mango and def a function type and color

Step3: def a function func

Step 4: call the objects and execute the program

### PROGRAM:
```
class Beans ():
    def type(self):   
          print("Vegetable")
    def color(self):
          print("Green")
class Mango:
   def type(self):
          print("Fruit")
   def color(self):
         print("Yellow")
   def func(obj):
         obj.type()
         obj.color()
         obj_beans = Beans()
         obj_mango = Mango()
         func(obj_beans)
         func(obj_mango)
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/b41a3e12-896b-4f6c-a9b2-19045a5088f9)


### RESULT: Thus, the program has been successfully executed.



EXP.No: 6.2 OPERATOR OVERLOADING

### AIM: write a python program to overload less than operator
###ALGORITHM:
Step1 :create class A and def init	 

Step2: def it	with a condition if self.a < o.a 

Step 3: call the function and execute the program.
### PROGRAM:
```
class A :
     def     init (self,a):
             self.a=a
     def     lt (self,o):
              if self.a < o.a :
                   return "ob1 is less than ob2"
              else:
                   return "ob2 is less than ob1"
ob1 = A(2)
ob2 = A(3)
print(ob1<ob2)
```
###OUTPUT:
![image](https://github.com/user-attachments/assets/dae03d17-1004-424e-a179-ef62fd2681bd)



###RESULT: Thus, the program has been successfully executed.



EX: 6.3 ABSTRACT CLASS METHOD

### AIM: To Create the abstract method calculate_area which is of the abstract class 'Shape'

### ALGORITHM:
Step1:Get input from the user

Step2:put class function to define the function using self

Step3:By using the function to find the area of the rectangle and circle Step4:Execute the program.

### PROGRAM:
```from abc import ABC
class Shape(ABC):
            def calculate_area(self):
                Pass
class Rectangle(Shape):
               length = 5
               breadth =3
               def calculate_area(self):
                   print("Area of a rectangle:",self.length * self.breadth)
class Circle(Shape):
             radius = 4
             def calculate_area(self):
                     print("Area of a circle:",3.14 * self.radius * self.radius)
a=Rectangle()
b=Circle()
a.calculate_area()
b.calculate_area()
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/a4c70e22-b3e0-417a-86d7-41f547c9d60d)


### RESULT: Thus, the program has been successfully executed.



EXP.No: 6.4     ENCAPSULATION
### AIM: To Implement Encapsulation using private members –of a class rectangle with private variables length,width.
###ALGORITHM: Step1: put class function to define the function using self Step2: By using the function to find the area of the rectangle Step3: Execute the program.
###PROGRAM:
```
class Rectangle:
 	length = 0
 	breadth = 0
  def	init	(self):
       self.	length = 5
       self.	breadth = 3
  print(self.	length)
  print(self.	breadth)
rect = Rectangle()
```
### OUTPUT:
 
![image](https://github.com/user-attachments/assets/ea434dc1-3f93-4a66-8828-1d815e9ff015)



 

### RESULT: Thus, the program has been successfully executed


EXP. No: 6.5 SEB-Adding two Objetcs

### Aim:
To write a Python program to demonstrate simple operator overloading for adding two objects — integers and strings.

### Algorithm:

**STEP 1:** Start.  
**STEP 2:** Define a class `add` with a constructor accepting two integers and two strings.  
**STEP 3:** Store them as instance variables.  
**STEP 4:** Define a method `disp()` to:
- Print the sum of the two integers.
- Print the concatenation of the two strings.  
**STEP 5:** Accept input values from the user.  
**STEP 6:** Create an object of the class and call `disp()`.  
**STEP 7:** Stop.

### Program:
```python
class add:
    def __init__(self, a, b, c, d):
        self.a = a
        self.b = b
        self.c = c
        self.d = d

    def disp(self):
        print("adding integers :", self.a + self.b)
        print("adding strings :", self.c + self.d)

a = int(input())
b = int(input())
c = input()
d = input()
e = add(a, b, c, d)
e.disp()
```
### Output:
![image](https://github.com/user-attachments/assets/4670adef-35ea-4d38-93da-a300bd6c3fcd)

### Result:
Thus the program was executed Successfully.














