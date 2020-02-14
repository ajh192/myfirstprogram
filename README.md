# myfirstprogram
# this program takes the user's name and age and calculates the generation they are part of
name = input("What's your name?")
age = input("What's your age?")
name = str(name)
age = int(age)

if (age>=75):
    print(name+", You are from the Silent Generation")
elif (56 <= age <= 74):
    print(name+", You are a baby boomer")
elif (41 <= age <= 55):
    print(name+", You are Gen X")
elif (26 <= age <= 40):
    print(name+", You are a millenial")
elif (8 <= age <= 25):
    print(name+", You are Gen Z")
else:
    print(name+", You are a Gen Alpha")
