# i made it
```  python

# june 25

course = "vinci"
print(course.upper())

course = "FUTURE AEROSPACE ENGINEER"
print(course.lower())

course = "UP you're such a dream"
print(course.find('dream'))

course = "after all im still kind"
print(course.replace('kind', 'bad'))

course = "to break free"
print('free' in course)



# june 27

# arithmetic operation 
print(20 + 5)
print(100 - 5)
print(2 * 3)
print(10 / 5)
print(20 // 5)
print(2 ** 4)

x = 10
x = x + 10
print(x)

# augmented assignment operator 
x = 5
x += 2
print(x)
x = 6
x -= 4
print(x)


# operator precedence 
x = 10 + 3 * 2
print(x)
y = (10 + 5) * 2
print(y)
# whatever comes first in order of operations will gets evaluated first


# comparison operator it's boolean expression, True or False
# there are >,<,>=,<=,==
# so basically it will tell if it's True or False 
x = 3 > 2
print(x)
y = 2 < 2
print(y)


# july 2

# and, or, not 
price = 50
print(price > 30 and price < 40) # since both aren't true the result will be false (the price is not greater than 30 and not less than 40)

grade = 75
print(grade > 90 or grade < 70) # this is false bc the grade is not greater than 90 and not less than 70
grade_math = 80
print(grade_math > 75 or grade_math < 95) # because the grade_math is greater than 75 and less than 95

english = 90
print(not english == 99) # true because english is not equal in 99

# and (both are true)
# or ( at least one is true)
# not (inverses the result)

temperature = 38
if temperature > 35: #dont forget the colon
	print("hot day") # this will going to be executed I'd the code is true
elif temperature < 30:
	print("a bit cold") # this will executed if the code is not true
	

temperature = 25
if temperature < 35:
	print("a bit cold") # see??
	
sleep_hours = 3
if sleep_hours > 9:
	print("very healthy habit")
elif sleep_hours > 5:
	print("fix your sched")
elif sleep_hours <= 4:
	print("what the hell")
else:
	print("bro thinks have nine lives")
# both else and last elif works, those are executed if none of the conditions are meet

# another
battery = 72
if battery == 80:
	print("good")
elif battery > 75:
	print("okay")
else:
	print("not okay")
	
meow = 10
if meow < 5:
	print("food please")
elif meow > 9:
	print("nap time")
	
# let me try
name = "Vinci"
age = "17 years old"
grade = 1
gwa = 93
enrolled = False
new_student = True
print("Name;", name)
print("Age:", age)
print("Grade:", grade)
print(grade > 2 and grade < 1)
print("GWA:", gwa)
print(gwa < 90 or gwa > 85)
print(not gwa > 99)
print("Enrolled:")
if enrolled:
	print("enrollment done")
else:
	print("still not")

if new_student:
	print("freshman")
else:
	print("what the hell")
