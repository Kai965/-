def contains_digit_two(N):
    while N > 0:
        digit = N % 10
        if digit == 2:
            return True
        N //= 10
    return False
N = int(input("Введите число N (> 0): "))
if contains_digit_two(N):
    print(True)
else:
    print(False)
