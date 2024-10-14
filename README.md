s = "У лукоморья 123 дуб зеленый 456"
print("Индекс 'я':", s.find('я'))
print("Количество 'у':", s.count('у'))
if not s.isalpha():
    print(s.upper())
if len(s) > 4:
    print(s.lower())
print('О' + s[1:])
