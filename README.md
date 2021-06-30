# Assignment-2

Code:

#to take no. of tickets value from user
maxticketavailable=int(input ("Total no.of tickets:"))
participants=[]
#to take no. of participants from the user
for i in range (maxticketavailable):
  participants.append(input ())

import random
n=random.randint(0, maxticketavailable-1)
print("Lottery winner is:",participants [n])

Output:

Total no.of tickets:3
Yash
Raj
Ajay
Lottery winner is: Raj
