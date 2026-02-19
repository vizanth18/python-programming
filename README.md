#avg of postive and negative numbers
pos = []
neg = []

while True:
    n = int(input("Enter number (-1 to stop): "))
    
    if n == -1:
        break
    
    if n > 0:
        pos.append(n)
    elif n < 0:
        neg.append(n)

if pos:
    print("Positive Average =", sum(pos) / len(pos))
else:
    print("No positive numbers")

if neg:
    print("Negative Average =", sum(neg) / len(neg))
else:
    print("No negative numbers")

