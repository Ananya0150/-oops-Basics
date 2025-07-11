# -oops-Basics

class Dog():
   species = 'mammal'
   def __init__(self,breed,name):
      self.breed = breed
      self.name = name

   def bark(self,number):
      print("WOOF! My name is {} and the number is {}".format(self.name,number))
my_dog = Dog(breed='lab',name='Frankie')
print(type(my_dog))
print(my_dog.species)
print(my_dog.bark(10))



class Circle():
   pi = 3.14

   def __init__(self,radius=1):
      self.radius = radius
      self.area = radius*radius*Circle.pi
   def get_circumfrence(self):
      return self.radius * self.pi * 2
my_Circle = Circle(30)
print(my_Circle.pi)
print(my_Circle.radius)
print(my_Circle.area)
print(my_Circle.get_circumfrence())
