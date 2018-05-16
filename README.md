#2.2.1
#y= list('ACADGILD')
y=[x for x  in 'ACADGILD']
print(y)

#2.2.2
list1= [a*b for a in "xyz" for b in range(1,5) ]
print(list1)

#2.2.3
list2= [a*b for a in range(1,5) for b in 'xyz']
print(list2)

#2.2.4
list3= [[a+b] for a in range(1,4) for b in range(1,4)]
print(list3)

#2.2.5
l5= [ [a+b for a in range(1,5)] for b in range(1,5)]
print(l5)

#2.2.6
list5=[(b,a) for a in range(1,4) for b in range(1,4)]
print(list5)
