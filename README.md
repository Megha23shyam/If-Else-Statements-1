# If-Else-Statements-1
this code is an example of the if else statements
age = int(input("enter your age : "))

if age == 100:
    print("you are a century old!")
elif age >=18 and age <= 60:
    print("you are a adult !")
elif age >60 and age < 100:
    print("you are a senior citizen! ")
elif age <18 and age > 12:
    print("you are an adolsecent!")
elif age <=11 and age>0:
    print("you are a child")
elif age <= 0:
    print("you haven't born yet")
else:
    print()
