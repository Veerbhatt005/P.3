
import random
import string

size = int(input("Enter the size of the password: "))
allchar = string.ascii_letters + string.digits + string.punctuation
password = ''.join(random.choice(allchar) for _ in range(size))
print(password)
