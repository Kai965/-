#1 
from kai import kai
a = float(input("Введите сторону a: "))
b = float(input("Введите сторону b: "))
c = float(input("Введите сторону c: "))
area = kai(a, b, c)
print(f"Площадь треугольника: {area}")

#2
import math
def calculate_semiperimeter(a, b, c):
    return (a + b + c) / 2
def kai(a, b, c):
    p = calculate_semiperimeter(a, b, c)
    return math.sqrt(p * (p - a) * (p - b) * (p - c))
