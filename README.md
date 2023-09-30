# asignmentthirdquestion
series = tuple(map(int, input("Enter Series of Numbers [Separated by Space] : ").split(" ")))

even_count, odd_count = 0, 0

for item in series:
    if item % 2 == 0:
        even_count += 1
    else:
        odd_count += 1

print("Even count in series is : ", even_count)
print("Odd count in series is : ", odd_count)
