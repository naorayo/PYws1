# Напишите программу, которая принимает на вход цифру, обозначающую день недели, и проверяет, является ли этот день выходным.
# Пример: - 6 -> да - 7 -> да - 1 ->нет

def InputNumbers(inputText):
    num_OK = False
    while not num_OK:
        try:
            number = int(input(f"{inputText}"))
            num_OK = True
        except ValueError:
            print("Вводить нужно числа!")
    return number

def checkNumber(num):
    if 6 <= num <= 7:
        print("Ура! Выходной! :)")
    elif 0 < num < 6:
        print("К сожалению, это не выходной :(")
    else:
        print("Вводить нужно числа от 1 до 7")

num = InputNumbers("Введите число от 1 до 7: ")
checkNumber(num)