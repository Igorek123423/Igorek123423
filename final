def display_menu():
    print("Меню выбора:")
    print("1. Ввести А")
    print("2. Ввести Б")
    print("3. Выполнить операцию +")
    print("4. Выполнить операцию -")
    print("5. Выполнить операцию *")
    print("6. Выполнить операцию /")

def main():
    choice = 0
    while choice != 7:
        display_menu()
        choice = int(input("Выберите пункт меню: "))
        
        if choice == 1:
            a = input("Введите значение для A: ")
        elif choice == 2:
            b = input("Введите значение для B: ")
        elif choice == 3:
            result = int(a) + int(b)
            print(f"Результат сложения: {result}")
        elif choice == 4:
            result = int(a) - int(b)
            print(f"Результат вычитания: {result}")
        elif choice == 5:
            result = int(a) * int(b)
            print(f"Результат умножения: {result}")
        elif choice == 6:
            result = int(a) / int(b)
            print(f"Результат деления: {result}")
        elif choice == 7:
            print("Выход из программы")
        else:
            print("Неверный выбор. Попробуйте снова.")

if __name__ == "__main__":
    main()
