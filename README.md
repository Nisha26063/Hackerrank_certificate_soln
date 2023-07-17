# Hackerrank_certificate_soln
# AREA CLASS
#!/bin/python3

import math
import os
import random
import re
import sys


class Rectangle:
    def __init__(self,breadth,length):
        self.breadth=breadth
        self.length=length
    def area(self):
        return self.breadth*self.length

    
    pass

class Circle:
    def __init__(self,radius):
        self.radius=radius
    def area(self):
        return math.pi*(self.radius**2)
    
    pass

if __name__ == '__main__':  

# VENDING MACHINE
#!/bin/python3


import math
import os
import random
import re
import sys


class VendingMachine:
    def __init__(self,variable1,variable2):
        self.variable1=variable1
        self.variable2=variable2

    def buy(self,x,y):
        if(self.variable1>=x and x*self.variable2<=y):
            self.variable1-=x
            return y-(x*self.variable2)
        else:
            if(self.variable1<x):
                return "Not enough items in the machine"
            else:
                return "Not enough coins"
            
            
         
        
    pass
if __name__ == '__main__':
    
