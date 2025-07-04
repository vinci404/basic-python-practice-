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


# july 4

# while loops are used to repeat the block of code

i = 1
while i < 5:
	print(i)
	i = i + 1

# it can be also multiply a number by string
i = 1
while i <= 5:
	print(i * '*')
	i = i + 1
	
# let me try
# waitttt
# should I always use "i"??? let me try a different one
z = 10
while z <= 15:
	print(z)
	z = z + 2
# it worksssssss

w = 1
while w <= 5:
	print(w * 'z')
	w = w + 1

# [list]
names = ["vinci", "meow", "arff", "vinnyyyyyyy"]
print(names)
print(names[0])  # this will show 'vinci' bc it is the first index
print(names[-1])  # this will show the lasttt
# for misspelled spelling
names[0] = "vinciey"
print(names)
# customize print
print(names[0:3])   # the elements always starts with zero, this should execute vinci to arff (start:end)


# list methods
# .append for adding in end
# .insert for add ons
# .remove for erasing certain part
# .clear for removing all
# .in for finding inside
# (Len()) it is a function, for no. of items

numbers = [1, 2, 3, 4, 5]
numbers.append(6)   # this one adds 6 in the end
print(numbers)
numbers.insert(0, -1)
print(numbers)    # this will executed the numbers with -1 in the bag inning
numbers.remove(4)
print(numbers)    # this removes 4 from the result
numbers.clear()
print(numbers)   # this will print none like nothing becauseit will clear/erase all the numbers

numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9]
print(3 in numbers)   # this will check if 3 is in there, true or false
print(len(numbers))   # this will show the number of items

# for loops
names = ["a", "b", "c", "d", "e"]
for items in names:
	print(items)

#let me try
students = ["vinci", "meoww", "arff"]
for students in students:
	print("Hello,", students + "!")
# idea from chatgpt, strings can't be concatenated with list

# let me try again
rizz = ["summer", "winter", "spring", "fall"]
for rizz in rizz:
	print("have you eaten,", rizz + "?")

# range function 
numbers = range(5)
print(numbers)
# this will execute 0, 5 use loops to see all the numbers
numbers = range(8)
for number in numbers:
	print(number)
# this will print 1 to 8
# for two values (start, end)
numbers = range(2, 5)
for number in numbers:
	print(number)
#this can be three
numbers = range(6,18,2)
for number in numbers:
	print(number)
# this will print 6, 8, 10, 12... so on the 2 is the step
# you can also do it like this
for number in range(20):
	print(number)
# this will print 1 to 20


# tuples (use to store a sequence like list but this is unchangeable or immutable)
# () for tuples
numbers = (1, 2, 3, 3, 4, 5)
print(numbers.count(3))
# this will show 2 because 3 appears two times, count is used to know the number of appearance of the elements 
print(numbers.index(5))
# this will show 5 because the number 5 is in the fifth place, index is used to know the first appear of the elements 
