# dev1
def fibonacci(n):
    fib_series = [0, 1]
    while len(fib_series) < n:
        fib_series.append(fib_series[-1] + fib_series[-2])
    return fib_series

n = int(input("Enter the number of terms in the Fibonacci series: "))
print(f"Fibonacci series up to {n} terms: {fibonacci(n)}")
