# factorial_ten (Python)
A simple project that performs factorial of ten.

fact_num = 10

mult = 1
for i in range(1, fact_num + 1):  #in range from 1 to 11 since Python will not add the 11th term.
    mult = mult * i  #The idea here is that variable mult will be replaced by the new number and subsequently will be multiplied to bring new number.
    print(i)

print("Factorial for number",fact_num, "is" ,mult,".")
