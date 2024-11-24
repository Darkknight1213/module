# module

```
def fib():
    def fibb(n):
        if n <= 1:
            return n
        else:
            return fibb(n-1) + fibb(n-2)

    n = int(input())

    if n <=0:
        print("Invalid input ! Please enter a positive value")
    else:
        for i in range(n):
            print(fibb(i), end=" ")

def ari():
    def arii(s, d, l):
        if s > l:
            return []
        else:
            return [s] + arii(s+d, d, l)
    s = d = int(input())
    l = int(input())
    print(*arii(s, d, l))

def abs():
    def a(n):
        if n >= 1:
            print("A", end=" ")
            b(n)
    def b(n):
        print("B", end=" ")
        c(n)
    def c(n):
        print("C", end=" ")
        print()
        a(n-1)
    n = 5
    a(n)

def cake():
    def c(n):
        if n==0:
            return 0
        else:
            return n + c(n-1)
    a = int(input())
    print(c(a))

def rev():
    def r(n):
        if n<=-1:
            return []
        else:
            return [n] + r(n-2)
    a = int(input())
    print(*r(a))

def sumd():
    def sum(n):
        if n==0:
            return 0
        else:
            term=n%10
            return term + sum(n//10)
    n = int(input())
    print(sum(n))

def nes():
    def f(n):
        if n == 0:
            return 0
        elif n > 4:
            return n
        else:
            return f(5 + f(2*n))
    a = int(input())
    print(f(a))

def poww():
    def po(n, p):
        if p == 0:
            return 1
        else:
            return n * po(n, p-1)
    a = int(input())
    b = int(input())
    print(po(a, b))

def binn():
    def bin(n):
        if n == 0:
            return "0"
        if n == 1:
            return "1"
        else:
            return bin(n//2) + str(n%2)
    a = int(input())
    print(bin(a))

def fa():
    def fact(n):
        if n == 0:
            return 1
        else:
            return n*fact(n-1)
    def ad(n, c=1):
        if n == 0:
            return 0
        else:
            return fact(c) + sum(n-1, c+2)
    a = int(input())
    print(fact(a))

def neve():
    def ne(n):
        if n > 0:
            if n % 2 == 0:
                print(n, end=" ")
            ne(n-1)
    a = int(input())
    print(ne(a))
# neve()

def nev():
    def nee(n):
        if n > 0:
            nee(n-1)
            if n % 2 != 0:
                print(n, end=" ")
    a = int(input())
    nee(a)

```

```
def N_to_dec():
    def n(a):
        if a == 0:
            return "0"
        elif a == 1:
            return "1"
        else:
            return n(a//2) + str(a%2)
    a = int(input())
    e = []
    for i in range(a):
        s = int(input())
        e.append(s)
    for i in e:
        print(n(i))

def NpowP():
    def np(n,p):
        if p == 1:
            return n
        else:
            return n * np(n, p - 1)
    a = int(input())
    b = int(input())
    print(f"{a} Power {4} : {np(a, b)}")

def expdd():
    def expd(n, p):
        if n == 0:
            return 0
        else:
            term = n%10
            return term**p + expd(n//10, p)
    a = int(input())
    b = int(input())
    print(expd(a, b))

def fact1t():
    def fac(n):
        if n == 0:
            return 1
        else:
            return n*fac(n-1)

    def f(n):
        if n == 1:
            return 1
        else:
            return 1/fac(n) + f(n-1)

    a = int(input())
    print(f(a))

def cube():
    def c(n):
        if n == 1:
            return 1
        else:
            return n**3 + c(n-1)
    a = int(input())
    print(f"Result is {c(a)}")

def summ():
    def sum(n):
        if n == 1:
            return 1
        else:
            return n + sum(n-1)
    n = int(input())
    print(f"Result is {sum(n)}")

def gg():
    def g(a,b):
        if b == 0:
            return a
        else:
            return g(b, a%b)
    a = int(input())
    b = int(input())
    print(f"Result is {g(a,b)}")

def fa3():
    def factorial(n):
        if n == 0 or n == 1:
            return 1
        else:
            return n * factorial(n - 1)

    def sum(n, c=1):
        if n == 0:
            return 0
        else:
            return factorial(c) + sum(n - 1, c + 2)

    n = int(input())
    print(sum(n))




```
