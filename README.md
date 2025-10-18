# Random-Pin-Generator
Can be used to randomly generate code for things like application 2 factor authentication messages.
def pinPicker(number):
    import random
    pin = ""
    for i in range(number):
        pin += str(random.randint(0, 9))
    return pin
myPin = pinPicker(4)
print("Your new PIN is:", myPin)
