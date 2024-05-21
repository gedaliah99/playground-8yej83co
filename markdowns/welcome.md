# PYTHON: Program to Check if a Number is Prime.
If you're like me, then you might come across clashes on CodinGame where you need to check if a number is prime or not.
In my case, I can never remember how to write the code.

Here is a simple function you can create to check if a number is prime:

### PROGRAM: isPrime()
```python runnable
def isPrime(n):
    for i in range(2, n):
        if (n%i) == 0:
            return False
    return True

# Let's test it out:
print(isPrime(2)) # = True
print(isPrime(7)) # = True
print(isPrime(60)) # = False
```

Try it for yourself by changing the code and test-lines above.

Happy Coding,
Code-Parser