# program 1

a = 10
b = 5
print(a+b)
print(a-b)
print(a*b)
print(a/b)


print(a>b)
print(a<b)
print(a==b)
print(a>=b)
print(a<=b)

a = 9
a = a + 3
print(a)
a = a - 3
print(a)
a = a * 3
print(a)
a= a / 3
print(a)

a = True
b = False
print(a and b)
print( a or b)
print(not a)


# program 2

a= 70
if(a%2==0):
    print("Number is Even")
else:
    print("Number is Odd")
    
   
# program 3

year = 2000
if((year % 400 == 0) or
     (year % 100 != 0) and
     (year % 4 == 0)):
    print("Leap year");
else:
    print ("Not a leap Year")
    
    
# program 4

list1=[1,'drishya',3,4]
list1.append('db')
print(list1)

list1.remove(1)
print(list1)

list2=[2,'anu',5]
list1.extend(list2)
print(list1)

list1.insert(2,'manu')
print(list1)

list1.clear()
print(list1)


# program 5

i = 1
for i in range(1, 6):
    print(i)

i=1
while i<=5:
    print(i)
    i+=1

