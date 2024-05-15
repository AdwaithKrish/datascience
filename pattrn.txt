a=int(input("Enter Limit"))
i=1
while i<=a:
    j=1
    while j<=i:
        print("*",end='')
        j=j+1
    print()
    i=i+1

a=int(input("Enter A Number"))
f=0
for i in range(2,a):
    if(i%2==0):
       f=0
    else:
        f=1
if f==1:
    print("Not prime")
else:
    print("Prime")
   