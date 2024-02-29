# create-a-matrix in python
# Approach-1
for i in range(3):
  for j in range(3):
    print(f"{i}{j}",end=" ")
  print()

# Approach-2
for i in range(3):
  for j in range(3):
    print("*",end=" ")
  print()
  
# Approach-3 using list concept
a=[]
for i in range(3):
  x=[]
  for j in range(3):
    x.append("*")
  a.append(x)
#print(a)
for i in a:
  print(*i,sep=" ")
  
# Approach-4
for i in range(3):
  print(" * "*3)

# Approach-5
for i in range(3):
  for j in range(3):
    print("*",end=" ")
  print()

# Approach-6
r=int(input())
c=int(input())
for i in range(r):
  for j in range(c):
    print("*",end=" ")
  print()

