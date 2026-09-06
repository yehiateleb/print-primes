# print-primes
print primes from x to y , x and y included 
def printprimes(x,y):
...     for i in range(x,y+1):
...         j = isprime(i)
...         if j == "prime" :
...            print(i)

def isprime(m):
...     p = 0
...     if m <= 1 :
...        return "not prime"
...
...     for i in range(2,m+1):
...         if m%i == 0 :
...                 p = p + 1
...     if p > 1 :
...         return " not prime"
...     else :
...         return "prime"
