# Password-Generator-
Generating Password using Python 

import random

lower = "abcdefghijklmnopqrstuvwxyz"
upper = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
numbers = "012345678"
symbols = "[]{}()*;/,_-"

all = lower + upper + numbers + symbols
length = 16
password = "".join(random.sample(all,length))
print(password)


