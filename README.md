num=5
sp=4
for i in range(1,num+1):
  for j in range(0,sp):
    print(" ",end="")
  for j in range(1,2*i):
    print('*',end="")
  sp-=1
  print()
num=5
sp=0
for i in range(1,num+1):
  for j in range(0,sp):
    print(" ",end="")
  for j in range(1,2*(num+1-i)):
    print('*',end="")
  sp+=1
  print()
