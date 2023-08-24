# Factoral-method
def factorial(x):                     
  if x==1:                             
    return 1
  else:
    return (x*factorial(x-1))
print("Factorial :",factorial(5))
#processing method
"""
factorial (5)
5*factorial(4)
5*4factorial(3)
5*4*3factorial(2)
5*4*3*2factorial(1)
5*4*3*2*1
"""
