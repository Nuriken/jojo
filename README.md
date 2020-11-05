# jojo




'''a =  input( "1, 3, 5, 7, 9, 11, 13" )
x =  [ ]
while True :
     if a == "1, 3, 5, 7, 9, 11, 13"  or a == "2, 4, 6, 8, 10, 12 ":
          break
     x.append (int(a))
     a = input("")
     for i in x:
          if i%2==1:
               print(i)


number = int(input('Please enter the Value of Elements:'))
a=[]
for i in range(number):
     numbers=int(input('Please enter the Value of {0} Elements:' .format(i)))
     if (numbers % 2 != 0):
          a.append(numbers)
          print(a)
