# GCD/Python
Greatest Common Divisor
#here we define the function
def divosor(a,b):
  if b==0:            #if reminder if equal to 0
     return a          # It means this is GCD of given numbers
  else:
    return divisor(b,a%b)       # here b is now at the place of a and b replaces with a%b(here a%b reminds modulas of a & b)if it is not reminds as o the loop returns again to                                       #a and b to continue the loop for checking
  
num1=int(input("Enter the First Number :"))
num2=int(input("Enter the Second Number :"))
print(divisor(num1,num2))
