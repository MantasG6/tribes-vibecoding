# Skaičiuotuvas

Vienas iš paprasčiausių projektų pradedantiesiems yra **skaičiuotuvas**. <br><br>
Tavo užduotis - sukurti skaičiuotuvą galintį atlikti **sudėties**, **atimties**, **daugybos** ir **dalybos** operacijas su bet kokio dydžio sveikaisiais skaičiais (skaičius *x ∈ Q*)

## Funkciniai reikalavimai
- Galima atlikti `sudėties(+)`, `atimties(-)`, `daugybos(*)` ir `dalybos(/)` operacijas
- Operacijas galima atlikti su bet kokio dydžio sveikaisiais skaičiais (*x ∈ Q*)
- Operacijas ir skaičius vartotojas nurodo per komandinę eilutę


## Nefunkciniai reikalavimai
- Programą galima įvykdyti naudojant 3.17.7+ Python versiją
- Klaidų atveju vartotojas turėtų gauti lengvai suprantamą atsakymą
- Vartotojui naudojantis programa netinkamai pateikiamos programos naudojimo instrukcijos

## Testavimas
Sukūrus programą darbas dar nebaigtas. Norint įsitikinti, kad programa atitinka visus reikalavimus, programą privaloma tinkamai ištestuoti.

Testavimui galite naudoti mano sukurtą testavimo failą [TEST.txt](./TEST.txt)

Testavimo faile rasite skaičiuotuvui skirtas operacijas kiekvienoje eilutėje tokius formatu: 
```
x {operacija} y

čia {x, y} ∈ Q - sveikieji skaičiai,

{operacija} - skaičiuotuvo operacija: sudėtis (+), atimtis (-), dalyba (/), daugyba (*)

```

Ranka atlikti visas operacijas gali būti daug nuobodaus darbo, tai pasirinkite ir ištestuokite keletą operacijų, kurios atrodo pačios svarbiausios.

## Papildomi iššūkiai
Jei pavyko sėkmingai sukurti programą ir liko laiko, turiu idėjų kaip būtų galima dar patobulinti skaičiuotuvą.

- Pilną operaciją galima nurodyti kaip `String` argumentą paleidžiant programą (pvz. `py skaiciuotuvas.py "1 + 1"`) 
- Skaičiuotuvas turi galėti nuskaityti `TEST.txt` failą, sėkmingai įvykdyti visas nurodytas operacijas ir grąžinti jų sumą (suma = 477)
- Sukurti automatizuotus testus naudojant `Pytest` karkasą. Šie testai turėtų užtikrinti ne tik ar operacijas pavyksta įgyvendinti, bet ir klaidų atveju grąžinamus programos atsakymus

**PASTABA** Papildomų įššūkių naujos funkcijos privalo veikti neįtakojant originalios skaičiuotuvo paskirties. Programa turėtų būti ne keičiama, o plečiama.

