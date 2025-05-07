# learning_python

#create a function with a single parameter
def greet(name):
    print(f"Hello, {name}!")

#call the function
greet("Raheesa")



#datatypes and variables
x = 5 #integers
y = 8.9 #float
z = "London" #string
fruits = ["apple","banana","cherry"] #list

#control flow
age = 39
if age >=18:
    print("You are an adult.")
else:
    print("You are not an adult yet.")

#function example
def add(a, b):
    return a+b

result = add(15,10)
print(result)

#import libraries and modules in the code
import math

print(math.sqrt(16)) # output is 4.0

# Classes define the blueprint for objects, and objects are instances of classes
class Dog:
    #define blueprint for objects under this class
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def bark(self):
        print(f"{self.name} is {self.age} and keeps saying wooofff.")

my_dog = Dog("Sandy",2)
#calling objects from the class
my_dog.bark() #Sandy is 2 and keeps saying wooofff.


