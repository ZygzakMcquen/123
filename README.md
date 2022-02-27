#Działania z warunkiem dzielenie przez zero\
a = int(input("a = "))
b = int(input("b = "))

suma = a + b 
print ("a + b =", suma)
roznica = a - b
print("a - b =", roznica)
iloczyn = a * b
print("a * b =", iloczyn)

if b!= 0:
  iloraz = a/b
  print("a/b=", iloraz)
else:
  print("Nie dzielimy przez zero")
  
#Średnia dwóch liczb
a = float(input("Podaj pierwszą liczbę: "))
b = float(input("Podaj drugą liczbę "))
srednia = (a+b)/3
print ("Średnia wynosi:", srednia)

#Pola figór - trapez
a = float(input("Podaj długośc pierwszej podstawy: "))
b = float(input("Podaj długość drugiej podstawy: "))
h = float(input("Podaj wysokośc: "))
if h > 0 and b > 0 and a > 0:
  pole = (a+b) / 2 * h
  print("Pole trapezu wynosi: ", pole)
else:
  print("błędna dana")
  
#Pole kwadratu
  a = float(input("Podaj długośc boku: "))
if a > 0:
  pole = (a**2)
  print("Pole trapezu wynosi: ", pole)
else:
  print("błędna dana")

#Podzielnośc liczb
a = int(input("Wprowadź wartość dzielnej a: "))
b = int(input("Wprowadź wartość dzielnika b: "))
if a % b==0:
  print("a jest podzielnej przez b")
else:
  print("a nie jest podzielne przez b")
