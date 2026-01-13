# factorial-of-a-number-using-recursion-71-100

def fact(n):
    if n == 0 or n == 1:  # handle 0! and 1!
        return 1
    else:
        return n * fact(n - 1)

num = int(input("Enter an integer: "))
result = fact(num)
print("The factorial of", num, "is:", result)
