# 1st
import random

answer = input("roll the dice ? (y/n)  ")


def lower(answer):
   answer = answer.lower()
   return answer

answer2 = lower(answer)
while True :
    if answer == "y" :
        print(random.randint(1,6))
        answer = input("roll the dice ? (y/n)  ")
    elif answer ==  "n" :
        print(f"ok")
        break
    else :
        print("invalid answer")
        break
