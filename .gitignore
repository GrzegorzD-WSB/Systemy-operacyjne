def dodawanie(x, y):
    return x + y

def odejmowanie(x, y):
    return x - y

def mnozenie(x, y):
    return x * y

def dzielenie(x, y):
    if y != 0:
        return x / y
    else:
        return "Nie można dzielić przez zero."

def kalkulator():
    print("Prosty Kalkulator")
    print("1. Dodawanie")
    print("2. Odejmowanie")
    print("3. Mnożenie")
    print("4. Dzielenie")

    try:
        wybor = int(input("Wybierz operację (wpisz numer): "))
        liczba1 = float(input("Podaj pierwszą liczbę: "))
        liczba2 = float(input("Podaj drugą liczbę: "))

        if wybor == 1:
            print("Wynik dodawania: ", dodawanie(liczba1, liczba2))
        elif wybor == 2:
            print("Wynik odejmowania: ", odejmowanie(liczba1, liczba2))
        elif wybor == 3:
            print("Wynik mnożenia: ", mnozenie(liczba1, liczba2))
        elif wybor == 4:
            print("Wynik dzielenia: ", dzielenie(liczba1, liczba2))
        else:
            print("Nieprawidłowy wybór operacji.")
    except ValueError:
        print("Wprowadzono nieprawidłowe dane. Upewnij się, że podajesz liczby.")

# Uruchomienie kalkulatora
kalkulator()
