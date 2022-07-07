# конкулятор

what = input("что делаем? (+, -): ")

a = float( input ("Ведите первое число:") )
b = float( input ("Ведите второе число:") )

if what == "+":
    c = a + b
    print("Результат: " + str(c))
elif what == "-":
    c = a - b
    print("Результат: " + str(c))
else:
    print("Выбрана неверная операция!")