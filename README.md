from dog import calculate_z, calculate_q
x = float(input("Введите значение x: "))
y = float(input("Введите значение y: "))
z = calculate_z(x, y)
q = calculate_q(x, y)
print(f"Значение z: {z}")
print(f"Значение q: {q}")
