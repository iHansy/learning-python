# learning-python

## hello world
msg = "Hello World"
print(msg)

## function saying hi to person who is passed in to function argument
def helloPerson(person):
    print("Hello, how are you doing", person)
    return

## calling this function with multiple names
helloPerson("Hans")
helloPerson("Bob")
helloPerson("Dan")
helloPerson("Marie")

## variables and types (numbers, string, list, tuple, dictionary)
name = 'Hans'
age = '25'

print('My name is ' + name + ' and I am ' + age + ' years old.')

## lists, objects, and loops
numberList = [1, 2, 3, 4, 5, 6, 7]
for number in numberList:
    print(number)

numberObject = {'first': 1, 'second': 2, 'third': 3, 'fourth': 'testingfourth?!'}
print (numberObject['fourth'])

## functions, operators, conditionals
def addinator(num1, num2):
    print(num1 + num2)
    return

addinator(2, 5)
addinator(55, 77)
addinator(44, 323424324)
addinator(2263464, 51342141514)

## and - returns true if both statements are true, example: x < 5 and x < 10
## or - returns true if one of the statements is true, example: x < 5 or x < 4
## not - reverse the result, returns false if the result is true, example: not(x < 5 and x < 10)


