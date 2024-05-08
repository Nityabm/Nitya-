# Nitya-
import random
import string

def generate_password(l):
    characters = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(characters) for i in range(l))
    return password


password_l = 12
random_pas = generate_pass(password_l)
print("Random password:", random_pas)
