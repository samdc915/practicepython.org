# practicepython.org
My answers to Practice Python Exercises

def repeat_statement():
    name=input('what is your name?: ')
    age=int(input('what is your age?: '))
    current_year=int(input('what is the year now?: '))
    times_what = int(input('how many times do you want me to repeat my statement?: '))
    turn_100=current_year-age+100
    for i in range(times_what):
        print(name, 'you will turn 100 in', turn_100)
repeat_statement()

number=int(input('give me a number: '))
if number % 4 == 0:
    print(number, 'is a multiple of 4 and it is even')
elif number % 2 == 0:
    print(number, 'is even but not a multiple of 4')
else:
    print(number, 'is odd')
    
    
num=int(input('give me a number: '))
check=int(input('what do you want to divide this number by?: '))
if num % check == 0:
    print('there is no remainder. the numbers divide evenly')
else:
    print('sorry, mate. try other numbers')
