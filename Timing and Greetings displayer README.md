# Python.code.repo
import time
#for time in format of Hours,Minutes,Seconds
timestamp=time.strftime('%H:%M:%S')
print(timestamp)
#for time in format of Hours
timestamp1=int(time.strftime('%H'))
print(timestamp1)
#for time in format of Minutes
timestamp2=(time.strftime('%M'))
print(timestamp2)
#for time in format of Seconds
timestamp3=(time.strftime('%S'))
print(timestamp3)
    #To wish Good Morning 
if(00<=timestamp1<12):
    print("Good Morning sir/ma\'am")
    print("Have a nice day:) ")
    #To wish Good Afternoon
elif(12<=timestamp1<17):
    print("Good Afternoon sir/ma\'am :)")
    #To wish Good Evening
elif(17<=timestamp1<20):
    print("Good Evening sir/ma\'am:)")
    print("I think you need to go for your Home after an hour :)")
    #To wish Good Night and welcome for nightshift
else:
    print("you are still here sir/ma\'am!!!\nOk, you may have nightshift.")
    print("Ok then Good Night sir/ma\'am in advance if you had gone early")
