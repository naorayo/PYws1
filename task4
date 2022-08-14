# Напишите программу, которая по заданному номеру четверти, показывает диапазон возможных координат точек в этой четверти (x и y).

def InputNumbers(inputText):
    num_OK = False
    while not num_OK:
        try:
            number = int(input(f"{inputText}"))
            num_OK = True
        except ValueError:
            print("Вводить нужно числа!")
    return number

def checkNumber(xy):
    if 1 <= xy <= 4:
        return    
    else:
        print("Вводить нужно числа от 1 до 4")    

def checkCoordinates(xy):
    if xy == 1:
        print("x>0 y>0")
    if xy == 2:
        print("x<0 y>0")
    if xy == 3:
        print("x<0 y<0")
    if xy == 4:
        print("x>0 y<0")

xy = InputNumbers("Введите номер четверти (от 1 до 4): ")
checkNumber(xy)
checkCoordinates(xy)