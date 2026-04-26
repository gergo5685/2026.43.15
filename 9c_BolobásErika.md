# Káosz csapat munkája

### Csapattagok: 
- *Bolobás Erika*
- *Csapó Mátyás*
- *Jevcsák Gergő*

# *Python*
## **Bevezetés a pythonba**
![pythonlogo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdjwGOMN8Vy9U0483zwEeoCmAQ2zL8tUyr0g&s)
#### Ez a teteje.
[ugorj az aljára](#ez-az-alja)
## **Mi a Python?** 
### - A Python nyelv egy magas szintű **programozási nyelv**, amelyet általában könnyen érthető szintaxisa és sokoldalú felhasználhatósága miatt kedvelnek mindenhol a világon. 
## **Python előnyei**
1. ### **Könnyen tanulható és olvasható**
   - letisztult szintaxis
   - olvasható kód, könnyebb hibakeresés
   - gyorsan elsajátítható
2. ### **Sokoldalúság**
   - webfejlesztés
   - adatelemzés
   - mesterséges intelligencia
   - automatizálás
   - hálózati programozás
3. ### **Nagy közösség és rengeteg könyvtár**
   - hatalmas fejlesztői közösség
   - sok kész megoldás és dokumentáció 
4. ###  **Gyors fejlesztés**
   - gyors prototípus-készítés
   - hatékony fejlesztés

|***programozási nyelv***|***feltaláló***|***kiadás éve***|
|----------------|----------|--------|
|Python|Guido van Rossum|1991|

# Python Működése ( Alap programozás )

## 1. Változók - Bemenet
### A változó egy névvel ellátott "doboz" , amiben egy adatot tárolunk , ennek értéket ( = ) lehet adni
## Alap Adattípusok
- `int` &rarr; egész szám (pl.: 2, 8, 15)
- `float` &rarr; tizedes szám (pl.: 3.14)
- `string` &rarr; szöveg (pl.: "hello")
- `bool` &rarr; logikai (pl.: True vagy False)
---

### A Bemenet (`input`) működését könnyű megérteni , ez egy adatot kérbe a félhasználótól. Ez mindig egy `string` adattípusú értékkel tér vissza.
```python
nev = input("Add meg a neved")
print(nev)
```
---

## 2. Operátorok
#### Az operátorok olyan "jelek" , amikkel műveleteket végzünk. 
### Matematikai operátorok
- Összeadás(+)
- Kivonás(-)
- szorzás(*)
- osztás(/)
- egész osztás(//)
- maradékos osztás(%)

### Pl.:
```python
a = 10 + 5
b = 10 - 3
c = 10 * 1
d = 10 / 9 
e = 10 // 10
f = 10 % 5
```
---

## 3. Feltétel Vizsgálat és Elágazás ( **If-Elif-Else** )
### A program eldönti hogy mit csináljon a neki megadott feltételek szerint.
``` python 
kor = 18 
kor = input("Add meg az életkorodat")  #Ez bekér egy értéket a felhasználótól

if kor >= 18:
if kor >= 18:    # nagyobb vagy egyenlő ( >= )
    print("felnőtt vagy")
else:
    print("Még kiskorú vagy")
```
### Több ága is lehet amennyiben használjuk az `elif` parancsot , ezt a parancsot ha `if` után használjuk akkor elöszőr megvizsgálja hogy az `if` feltétel teljesül-e , utánna megnézi az `elif` agákat és hogy ha egyiksem teljesül akkor az `else` parancs fog lefutni.

---

### Pl.:
``` python
pontszam = 75 

if pont >= 90:
    print("Ez egy 5-ös érdemjegy")
elif pont >=70:
    print("Ez egy 4-es érdemjegy")
elif pont >= 50:
    print("Ez egy 3-as érdemjegy")
elif pont >= 30:
    print("Ez egy 2-es érdemjegy")
else:
    print("Ez sajnos egy 1-es , érdemjegy")
```

---

## 4. Ciklusok 
 ### A ciklus egy olyan folyamat ami akár **többször** is lefuthat. 2 Típusa van a `for` és a `while`. 
- #### A `for` ciklust akkor használjuk amikor pontosan tudjuk hányszor kell ismétlődjön
- #### A `while` ciklus addig ismétlődik míg a feltétele nem teljesül.
---
## Pl.:
```python
for i in range(5):    # 5 alkalommal fogja kiírni hogy "hello world"
    print("hello world")
```
---
```python 
i = None  # Az i változóhoz nincsen érték rendelve

while i < 5:
    print(i)
    i += 1  # Mindig mikor kiíratja az i változót , megnöveli az értékét 1-el.
```
### **FONTOS ha a feltétel mindig igaz marad , akkor infinite loop-ba kerül a program.**
---

## 5. Függvények 
### A `függvény` egy bármikor használható parancs amit te magad hozhatsz létre.
``` python
def osszeadas(a,b):
    return a + b  #Ha nem tér vissza valamilyen értékkel akkor nem tudom majd használni.
```

# Összefoglaló

### Az előző részekben már láthattátok az alapokat, de az igazi „varázslat" itt kezdődik. A Python nemcsak egyszerű, hanem rengeteg kész könyvtár is van hozzá, így nem kell mindent nulláról megírni (pl. math, random). A valóságban a Pythont szinte minden menő területen használják.ebfejlesztéshez ott van a Flask és a Django, de még fontosabb az AI és az adatfeldolgozás, ahol kifejezetten erős.
### [Python web]: https://www.python.org/ 

### [Trello web]: https://trello.com/b/vJFc06qD/it
### [GitHub web]: https://github.com/gergo5685/2026.43.15/tree/Matyas
## Köszönöm a figyelmet
#### Ez az alja
💡
[Ugorj a tetejére](#ez-a-teteje)