from yan import calculate_expression

x = float(input("Введите значение x для вычисления выражения √(1 - sin²(x)): "))
result = calculate_expression(x)
print(f"Результат вычисления: {result}")
