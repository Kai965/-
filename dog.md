import math

def calculate_z(x, y):
    numerator = (x**2 + y) / (x**2 - 1)
    denominator = y + math.sqrt(x**2 + 10)
    return numerator / denominator

def calculate_q(x, y):
    return 2.8 * math.sin(x) + abs(y)
