R = 8.314
P = input("Введите давление в паскалях (Па): ")
P = float(P)
V = input("Введите объем в литрах (л): ")
V = float(V)
temp_unit = input("Введите единицу измерения температуры (c для Цельсия,  f для Фаренгейта): ")
if temp_unit == 'c':
    T = input("Введите температуру Цельсия: ")
    T = float(T) + 273.15
elif temp_unit == 'f':
    T = input("Введите температуру Фаренгейта: ")
    T = (float(T) - 32) * 5 / 9 + 273.15
else:
    print("Неверная единица измерения температуры.")
    exit()
n = (P * V) / (R * T)
print("Количество газа: ", n, "моль")
