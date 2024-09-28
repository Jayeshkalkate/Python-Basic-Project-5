# Python-Basic-Project-5
By using python programming language

# In this stage we are import the math for perform the square root operation .

import math 

# Now we are define the calculator class .
class calculator :

# Under the calculator class we are define def __init__ and get user input number by using  number atribute .
    def __init__ (self , number) :

# In this time we are store number into the self .
        self.number = number

# Now create a another function def calculate which used to calculate the cube , square , square root of number .

    def calculate(self) :

        square = self.number * self.number
        print(f"The square of number {self.number} is : {square}")

        cube = self.number * self.number * self.number
        print(f"The cube of number {self.number} is : {cube}")

        square_root = math.sqrt(self.number)
        print(f"The square root of {self.number} is : {square_root}")

# In this stage we are get a input number from the users for perform the operation .
number = (int(input("Enter the number to find there sauare , square root and cube of the number : ")))

# Now we are call the class calculator with putting it is input value , by declaring variable number .
cal = calculator(number)

# In this stage we are add function def calculate into the cal variable which is alerady stored calculator(number)
cal.calculate()
