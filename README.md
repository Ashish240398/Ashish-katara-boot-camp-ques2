# Ashish-katara-boot-camp-ques2

# Python Program To generate hashes of string data by using 3 algorithms from hashlib

import hashlib
#1
print('\SHA256')
m = hashlib.sha256()
m.update(b"My name is")
m.update(b" Ashish katara.")
print('Output 1 :', m.digest())
x = hashlib.sha256(b"My name is Ashish katara.")
print('Output 2 :', x.digest())

#2
print('\SHA384')
m = hashlib.sha384()
m.update(b"My name is")
m.update(b" Ashish katara.")
print('Output 1 :', m.digest())
x = hashlib.sha384(b"My name is Ashish katara.")
print('Output 2 :', x.digest())

#3
print('\ blake2b' )
m = hashlib.blake2b()
m.update(b"My name is")
m.update(b" Ashish katara.")
print('Output 1 :', m.digest())
x = hashlib.blake2b(b"My name is Ashish katara.")
print('Output 2 :', x.digest())
