# Driving
<print("Enter your Age-")>
age=int(input())
# 10<age<100
if age>=18:
    print("Do you have Driving License?")
    print("Press '1' if you have else press '0'.")
    A=int(input())
    if A==1:
        print("Congratulation,You can Drive.")
    else:
        print("You can not Drive.\n","Apply for Driving License.")
else:
    print("You can not Drive")
print("Is it helpful?")
input()
