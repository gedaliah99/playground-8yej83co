# PYTHON: Program to Check if a Number is Prime.
If you're like me, then you might come across clashes on CodinGame where you need to check if a number is prime or not.
In my case, I can never remember how to write the code.

Here is a simple function you can create to check if a number is prime:

### PROGRAM: Defining 'isPrime()'
```python runnable
def isPrime(n):
    for i in range(2, n):
        if (n%i) == 0:
            return False
    return True

# Let's test it out:
print(isPrime(2)) # True
print(isPrime(7)) # True
print(isPrime(60)) # False
```
Try it for yourself by changing the code and test-lines above.


### PROGRAM: Using 'isPrime()'.
Let's use this function to check which numbers from ```0``` to ```n``` are prime.

You may notice that instead of returning ```True``` or ```False```, we are now printing "is a Prime" or ```pass```.
```pass``` means that we skip that part. This is useful for if we do not want to output or return anything.

```python runnable
def isPrime(n):
    for i in range(2, n):
        if (n%i) == 0:
            pass
    print(f"{n} is a Prime")

n = 20 # Change this value to expirement.

for i in range(0, n):
    isPrime(i)
```
Try it for yourself.


#### Conclusion:
We have defined a function ```isPrime()``` and we have used it to find all the numbers from ```0``` to ```n``` that are prime.

Happy Coding,
Code-Parser