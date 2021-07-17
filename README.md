- 👋 Hi, I’m @rororomanroro, 10 years old
- 👀 I’m interested in programming
- 🌱 I’m currently learning english, japanese and programming
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me brawl stars = jochen der lll

<!---
rororomanroro/rororomanroro is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


and this is my guess the number programm(in german): 

from random import randint

zahl = randint (1, 1000)

gess = int(input("errate eine zahl von 1 bis 100. wenn deine Angabe keine ganze zahl ist, taucht ein fehler auf: "))

if gess < zahl:
    print("gib eine höhere zahl ein. ")
if gess > zahl:
    print("gib eine kleinere zahl ein. ")

if gess == zahl:
    print("richtig!")

while not  gess == zahl:
    gess = int(input("errate eine zahl von 1 bis 100 ein: "))
    if gess < zahl:
        print("gib eine höhere zahl ein. ")
    if gess > zahl:
        print("gib eine kleinere zahl ein. ")

    if gess == zahl:
        print("richtig!")


