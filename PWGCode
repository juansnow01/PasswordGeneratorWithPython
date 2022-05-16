import random

print("Welcome to Your Password Generator")

chars = 'abcefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*()-=_+,.<>/;'

number = input('Amount of passwords to generate: ')
number = int(number)

length = input('Desired password length: ')
length = int(length)

print('\nHere are your password combinations:')

for pwd in range(number):
    passwords = ''
    for c in range(length):
        passwords += random.choice(chars)
    print(passwords)
