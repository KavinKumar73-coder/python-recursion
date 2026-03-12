# Display 1 to 100 without using loop
def sum(n):
   if n>0:
      sum(n-1)     #printing happens when return recursion
      print(n,end=\n)
sum(100)

