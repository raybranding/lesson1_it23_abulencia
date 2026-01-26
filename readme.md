# Python Development Calculator

def calculations(a, b, c):
    if a == 1:
       return b + c
    elif a == 2:

    elif a == 3:
    
    elif a == 4:
      
    else:
        return "invalid"
        
def Program():
    num1 = int(input("Enter 1st number: "))
    num2 = int(input("Enter 2nd number: "))
    print("choose an option(number)")
    print("1. Add\n2. Subtract\n3. Multiply\n4. Divide\n---------")
    option = int(input(""))
    print(f"\n\n\nComputed Ammount: {calculations(option, num1, num2)}")

if __name__  == "__main__":
    Program()
        

