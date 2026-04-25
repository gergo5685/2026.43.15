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


## 2. Operátorok
#### Az operátorok olyan "jelek" , amikkel műveleteket végzünk. 
### Matematikai operátorok
- Összeadás(+)
- Kivonás(-)
- szorzás(*)
- osztás(/)
- egész osztás(//)
- maradékos osztás(%)

## 2. Operátorok
### Az operátorok olyan "jelek" , amikkel műveleteket végzünk. 
## Matematikai operátorok
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
## 3. Feltétel Vizsgálat ( If-Elif-Else )
### A program eldönti hogy mit csináljon a neki megadott feltételek szerint.
``` python 
kor = 18 

if kor >= 18:
    print("felnőtt vagy")
else:
    print("Még kiskorú vagy")
```
### Több ága is lehet amennyiben használjuk az `elif` parancsot , ezt a parancsot ha `if` után használjuk akkor elöszőr megvizsgálja hogy az `if` feltétel teljesül-e , utánna megnézi az `elif` agákat és hogy ha egyiksem teljesül akkor az `else` parancs fog lefutni.
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