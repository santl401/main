# main
def fibonacci(n):   if n &lt;= 0:     return []   elif n == 1:     return [0]    sequence = [0, 1]   while len(sequence) &lt; n:     sequence.append(sequence[-1] + sequence[-2])    return sequence  print(fibonacci(10))
