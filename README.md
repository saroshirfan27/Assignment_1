# Assignment_1
//q1 
Num = int(input("Enter a number to be checked : "))
print(Num)

if( Num >= 0 and Num <= 10 ):
    print("LOW")
elif( Num >= 11 and Num <= 50 ):
    print("MEDIUM")
elif( Num >= 51 and Num <= 100 ):
    print("HIGH")
else:
    print("OUT OF RANGE")


//q2
Year = int(input("Enter Year : "))

if( Year % 4 == 0 and Year % 100 != 0  ):
    print("Leap year")
else:
    print("Not a Leap year")
