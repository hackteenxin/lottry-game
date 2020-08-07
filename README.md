# lottry-game
Draw lottry


from random import randint 
lottrynum = int(input("select number "))
print ("lottrynum" )

N = 110
array = []

for i in range(N): 
     array.append(randint(0, 110)) 
     
for i in array: 
    print(i, end=' ') 
print()

import random

print ("lottry number is ")

print (random.randrange(0,10))
print (random.randrange(0,10))

if lottrynum >=110:
    print ("congratulation")
else:
    print ("try next time")

