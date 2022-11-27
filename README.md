# Best-activity-for-me

a=input("""What shift are you?
A. Shift A
B. Shift B
C. Shift C
:""")
if a=="A":
    a=input("""What day is today?
    A. Monday
    B. Tuesday
    C. Wednesday
    D. Thursday
    E. Friday
    F. Saturday
    G. Sunday
    :""")
    if a=="A"or a=="B":
        a=int(input("""Did you wear your Uniform and ID? 1.Yes 2.No
        :"""))
        if a==1:
            print("Come in!")
        else:
            print("You are not allowed to enter the school")
    elif a=="C":
        a=input("Did you wear wash day outfit and ID?  Yes or No : ")
        if a=="yes" or a=="no":
            print("Come in!")
    else:
        print("You are not allowed to enter the school")
elif a=="B":
    a = input("""What day is today?
        A. Monday
        B. Tuesday
        C. Wednesday
        D. Thursday
        E. Friday
        F. Saturday
        G. Sunday
        :""")
    if a=="D"or a=="E":
        a=int(input("""Did you wear your Uniform and ID? 1.Yes 2.No
        :"""))
        if a==1:
            print("Come in!")
        else:
            print("You are not allowed to enter the school")
    elif a=="F":
        a=input("Did you wear your wash day and ID? Yes or No :")
        if a=="yes" or a=="no":
            print("Come in!")
    else:
        print("You are not allowed to enter the school")
elif a=="C":
    a = input("""What day is today?
            A. Monday
            B. Tuesday
            C. Wednesday
            D. Thursday
            E. Friday
            F. Saturday
            G. Sunday
            :""")
    if a=="G":
        a = input("Did you wear your wash day and ID? Yes or No :")
        if a=="yes" or a=="no":
            print("Come in!")
    elif a=="A" or a=="B":
        a = int(input("""Did you wear your Uniform and ID? 1.Yes 2.No
                :"""))
        if a == 1:
            print("Come in!")
        else:
            print("You are not allowed to enter the school")
    else:
        print("You are not allowed to enter the school")
else:
    print("Invalid")
