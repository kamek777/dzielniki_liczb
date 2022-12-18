# lista z dzielnikami liczb:
liczba= int(input("Wprowadź dowolną liczbę:"))
dzielniki = []
zakres_liczby = list(range(1,liczba+1))
for element in zakres_liczby:
    if liczba % element == 0:
        dzielniki.append(element)
        
print(dzielniki)