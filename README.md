shoe=100
chocolates=150
biscuits=100
shampoo=200
beauty creams=500
cno=int(input("enter customer number:"))
cname=input("enter customer name:")
sh=int(input("no of shoe:"))
c=int(input("no of chocolates:"))
b=int(input("no of biscuits:"))
s=int(input("no of shampoo:"))
bc=int(input("no of beauty creams:"))
bill=(shoe*sh)+(chocolates*c)+(biscuits*b)+(shampoo*s)+(beauty creams*bc)
print("your bill is:",bill)
if(bill>5000):
    disc=bill*10/100
    tax=bill*10/100
elif(bill>3000):
    disc=bill*8/100
    tax=bill*10/100
elif(bill>2000):
    disc=bill*5/100
    tax=bill*18/100
else:
    disc=bill*3/100
    tax=bill*18/100

print("your discount is:",disc)
print("your tax is:",tax)
finalbill=bill-disc+tax
print("your final bill is:",finalbill)
print("thank you for shopping***")
