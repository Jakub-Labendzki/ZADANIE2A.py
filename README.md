# ZADANIE2A.py
# #zad1
# a = int(input("Liczba1: "))
# b = int(input("Liczba2: "))
# if (a + b) % 2 == 0: print("TAK")
# else: print("NIE")

# #zad2
# from math import sqrt
# a = float(input("Liczba1: "))
# b = float(input("Liczba2: "))
# if (a + b) / 2 > sqrt(a * b) : print("TAK, średnia arytmetycza > geo.")
# else : print("NIE, średnia arytmetyczna < geo.")

#zad3
# a = int(input("Liczba1: "))
# b = int(input("Liczba2: "))
# c = int(input("Liczba3: "))
# if a == b or a == c or b == c :
#     print("TAK, dwie są równe")
#     if a == b and a == c and b == c : print("Wszystkie liczby są równe")
#     elif a == b : print("są to: 'Liczba1' i 'Liczba2'")
#     elif a == c : print("są to: 'Liczba1' i 'Liczba3'")
#     elif b == c : print("są to: 'Liczba2' i 'Liczba3'")
# else : print("NIE, ma równych")

# #zad4
# a = int(input("Liczba1: "))
# b = int(input("Liczba2: "))
# c = int(input("Liczba3: "))
# d = int(input("Liczba4: "))
# if a < b and a < c and a < d: print("Najmniejsza liczba to ",a)
# elif b < a and b < c and b < d : print("Najmniejsza liczba to ",b)
# elif c < a and c < b and c < d : print("Najmniejsza liczba to ",c)
# elif d < a and d < b and d < c : print("Najmniejsza liczba to ",d)
# else : print("Dwie najmniejsze liczby są równe siebie")
#
# #zad5
# a = int(input("Liczba1: "))
# b = int(input("Liczba2: "))
# c = int(input("Liczba3: "))
# if b - c < a < b + c and a - c < b < a + c and a - b < c < a + b : print("TAK")
# else : print("NIE")
#
# #zad6
# a = int(input("Liczba1: "))
# b = int(input("Liczba2: "))
# c = int(input("Liczba3: "))
# if a < b + c and b < a + c and c < a + b :
#     print("Powstanie trójkąta")
#     if a**2 + b**2 == c**2 or b**2 + c**2 == a**2 or c**2 + a**2 == b**2 : print("trójkąt prostokątny")
#     elif a**2 + b**2 < c**2 or b**2 + c**2 < a**2 or c**2 + a**2 < b**2 : print("trójkąt rozwartokątny")
#     elif a**2 + b**2 > c**2 or b**2 + c**2 > a**2 or c**2 + a**2 > b**2 : print("trójkąt ostrokątny")
# else : print("Trójkąt nie istnieje")
