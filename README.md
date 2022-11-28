# Largest-Number 
num1 = float(input("Please enter the first number:"))
num2 = float(input("Please enter the second number:"))
num3 = float(input("Please enter the third number:"))

if (num1 > num2 and num3):
		print("The largest number between these three numbers is", num1)
elif (num2 > num1 and num3):
		print("The largest number between these three numbers is", num2)
elif (num3 > num1 and num2):
	print("The largest number between these three numbers is", num3)
else:
	print("All are equal")
	
