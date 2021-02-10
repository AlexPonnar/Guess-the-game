#!/usr/bin/env python
# coding: utf-8

# In[3]:


userchoice = True
while userchoice == True:
    
    print('           WELCOME TO THE NUMBER GUESSING GAME\n\n')
    print('The computer will think a number and you have to guess it')
    print('The computer will tell you "warmer" or "colder" if you are getting closer or away from the number')
    print('It will also tell you that whether your guess is very far or close to the number by telling "warm" or "cold"\n\n')
    from random import randint
    number = randint(0,101)

    user = input('Guess the number: ')
    user = int(user)

    b=0
    a=user

    while True:
        b=b+1
        if user<0 or user>100:
            print('OUT OF BOUNDS')
            print('Try again and guess number between 0 and 100')
            a=user        
            user = input('Guess again: ')
            user = int(user)
            c=abs(a-user)

        elif user == number:
            print(f'\n\nCongratulations!\nYou have guessed the number correctly with {b} attempts')
            break

        elif user>-1 and user<101 and user>=number-10 and user<=number+10:
            print('warm')
            a=user
            user = input('Guess again: ')
            user = int(user)
            if b>1 and user>number and a> number and (user-number)>(a-number) :
                print('getting cold')
            elif b>1 and user> number and a<number and (user-number)>(number-a):
                print('getting cold')
            elif b>1 and user<number and a<number and (number-user)>(number-a):
                print('getting cold')
            elif b>1 and user<number and a>number and (number-user)>(a-number):
                print('getting cold')
            else: 
                print('getting warm')

        elif user>-1 and user<101 and user<=number-11 or user>=number+11:
            print('cold')
            a=user
            user = input('Guess again: ')
            user = int(user)
            if b>1 and user>number and a> number and (user-number)>(a-number) :
                print('getting cold')
            elif b>1 and user> number and a<number and (user-number)>(number-a):
                print('getting cold')
            elif b>1 and user<number and a<number and (number-user)>(number-a):
                print('getting cold')
            elif b>1 and user<number and a>number and (number-user)>(a-number):
                print('getting cold')
            else: 
                print('getting warm')

    z = True
    while z == True:
        option = input('\nWould you like another game?\nPress "y" for yes or press "n" for no.')
        option.isupper()
        if option == 'y':
            z = False
            break
        elif option == 'n':
            z = False
            break
        else:
            print('Please enter "y" or "n"')
            z = True
            
    if option == 'y':
        userchoice = True
    elif option == 'n':
        userchoice = False
        break


# In[ ]:





# In[ ]:




