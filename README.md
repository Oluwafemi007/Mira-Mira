# Mira-Mira
print("Welcome to Tips Calculator!")
bill= float(input("What was your total bill?  $"))
tip= float(input("How much tip would you like to give? 10, 12, 20?"))
p=float(input("How many number of people to split bill?"))
Bill_5= format(((tip/100*bill+bill)/5), '.2f')
print(f"Each person should pay: ${Bill_5}")
print("Terms and conditions applies below:")
if float(Bill_5) > 30:
    print(f"The Restaurant will pay half of our ${Bill_5} bills.")
elif float(Bill_5) == 30:
    print(f"Only one person pays")
else:
    print(f"We will all pay")
    
