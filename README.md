class Comparator:


   def compare(self):
    num=int(input("Place a Number: "))
    num2=int(input("Place Another Number: "))

    if num > num2:
        print("The First Number is higher than the Second number")
    elif num2 > num:
        print("The Second number is higher than the First number")
    else:
        print("The Numbers are Equal.")


com=Comparator()
com.compare()
