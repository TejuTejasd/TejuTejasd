empname=input()
empdesig=input('designation:')
basicsalary=int(input())
da=int(input('daily allowance:'))
ta=int(input('traveling allowance:'))
hra=int(input('house rantle allowance:'))
net=basicsalary+da+ta+hra
if net>100000:
    tax=net*10/100
    print(tax)
elif (net>50000):
    tax=net*7/100
    print(tax)
elif (net>40000 and net<50000):
    tax=net*4/100
    print(tax)
elif (net>20000 and net<40000):
    tax=net*2/100
    print(tax)
else:
    tax=0
    print(tax)
  print(tax)
elif (net>50000):
    tax=net*7/100
    print(tax)
elif (net>40000 and net<50000):
    tax=net*4/100
    print(tax)
elif (net>20000 and net<40000):
    tax=net*2/100
    print(tax)
else:
    tax=0
    print(tax)
