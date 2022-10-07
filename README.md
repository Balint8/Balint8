#2. Feladat
#Készíts egy programot, ami bekér egy számot a felhasználótól, majd kiírja, hogy a megadott szám páros-e vagy páratlan!

szam = int(input('Adj meg egy számot!'))
if szam % 2==0:
  print('A megadott szám páros.')
else:
  print('A megadott szám páratlan.')
  print('A program vége')
  
#1. Feladat
#Készíts egy programot, amely a felhasználótól bekér egy egész számot, majd megvizsgálja, hogy a megadott szám- pozitív páros vagy- negatív páratlan.Az eredményről tájékoztatja a felhasználót.
  
szam = int(input('Adj meg egy számot!'))
if szam < 0:
    print('A megadott szám negatív.')
else:
  print('A megadott szám pozitív.')
print('A program vége')

#1. Feladat
#Készíts egy rövid programot, amely 1 és 3 között generál véletlenszámot, majd összehasonlítja ezt a felhasználó által megadott, szintén ebbe a tartományba eső számmal! Az összehasonlítás eredményéről tájékoztassa a felhasználót!

import random
random_szam = random.randint(1,3)
print(random_szam)

#1.1 Feladat
#Készíts egy programot, amely megkérdezi a felhasználótól, hogy jó napja van-e! A válasz kétféle lehet: igen vagy nem. A választól függően írjon ki üzenetet a gép!

print('Jó napod van?')
a = input()
if a == "igen":
    print('Ezt örömmel hallom.')
elif a == "nem":
  print('Sajnálom.')
else:
  print("Nem értem a válaszod.")
  #2. Feladat
#Készíts egy programot, amely a felhasználótól két külön kérdésben megkérdezi, hogy az ikrek (Henrik és Hanna) jönnek-e ma kosrazni! Például így: Jön Henrik ma kosarazni? (igen/nem). A program írja ki, hogy melyik állítás igaz az alábbiak közül:- egyikük sem jön kosarazni,- mind a ketten jönnek kosarazni,- csak az egyikük jön kosarazni.
  
print("Hanna jön kosarazni?")
a = str(input())
print("Henrik jön ma kosarazni?")
b = str(input())

if a =='nem'and b =='nem':
  print("egyikük sem jön kosarazni")
if a =='igen'and b =='igen':
  print("mind a ketten jönnek kosarazni")
  if a =='nem'or b =='igen':
    print("csak az egyikük jön kosarazni")
