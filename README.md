# Hi there 👋
print("I love you Ahona")
print(123)

x = 10
y= 20
print("X=",x,"Y=",y)

name = "Ahona"
age = 19
print(f"Her name is {name} and her age is {age} ")
print("I love her\nI will marry her oneday in sha allah")
print(int(176))
print(type(int(202)))

print(float(2025.25))
print(type(float(2025.25)))
print(7/2)#division
print(5//2)#float division
#modulus
print(5%2)
#multiplication
print(5*5)

#11/23/25

X = 5
y = 5
print( X is y )

#membership operators
#in
#not in
students = ["Tasnim", "Ahona", "Gazi", "pakhi"]
print( "NESHAT" in students)

subjects = ["CSE", "SWE", "BBA", "ESDM"]
print("EEE" not in subjects)

#assignment operators
num = 5 
num += num
print(num)

num1 = 54

num1 -= num1
print(num1)

#data_type
# text -> String
#nemaric -> int, float, complex 
# boolean -> true or false , Range 
# None -> None 
def do_nothing():
    pass

print(do_nothing())

name = "Ahona"
print(name[3])

print(name[:4])

print(name.upper())

a = "hello, World!"
print(a.replace("H", "J"))
b = "Amar pakhi,Amr bou, amar ghor"
print (b.split(","))
FirstName = "Tasnim"
LastName = " Ahona"
Fullname = FirstName + LastName
print(Fullname)

name = "pakkhi"
age = 18
print(f"My name is {name} and my age is {age}") #string interpolation 

# Mini Calculator 
  
print("Welcome to Tasnim's Mini Calculator")

Num1 = float(input("Enter the First Number:"))
Num2 = float(input("Enter the Second Number:"))
print("Addition:",Num1 + Num2)
print("Substraction:",Num1 - Num2)
print("Multipy:",Num1 * Num2)
print("division:",Num1 / Num2)



#combination or , and ,not 
age = 26
has_card = False
vip_pass = False
if (age >= 18 and has_card) or vip_pass:
 print("You are Eligable to enter")
else:
 print("You are not eligable to enter") 

# if else condition
exam_pass = True
interview_pass = False


if exam_pass:
    if interview_pass:
        print("You can admit")
    else:
        print("You failed intervew")

else:
    print("You failed Exam")



  # A project of calculating grades
Name = input("Enter your name:")
Marks = int(input("Enter your Marks:"))
if Marks < 0 or Marks > 100:
    print("Mark is valid")
else:   
  
  print("---------Result--------")
  print("Name:",Name)
  
  if Marks >= 80:
     print("A+")
  elif Marks >= 60:
     print("B")   
  elif Marks >= 50: 
     print("C")
  elif Marks >= 40:
      print("D")
  else:
     print("Fail")    





     # guess the number
import random

# secret = random.randint(1,10)

# guess = int(input("Guess a number between 1 to 10:"))

# if guess == secret :
#     print("Congratulations! you guessed the number.")
# else:
#     print("You are wrong, The number was", secret)    
print("Welcome to the guess Number Game!")

for round_num in range(1,4):

    print(f"\nRound{round_num}----")


    secret_Number = random.randint(1,10)
    attempts = 0

    while attempts < 3:
        guess = int(input("Guess the number between 1 ti 10:"))
        attempts = attempts + 1
        if guess == secret_Number:
            print("congratulations! you  guessed the correct number")
            break
        elif guess < secret_Number:
            print("Too low !try again")
        else:
            print("Too High!, Try Again" )
        
    else:
        print("Sorry You used all attempts!")

print("\nThank you the Game is Over")





#author Tasnim Gazi
