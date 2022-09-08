srp:

# LED bedž sa mogućom kontrolom od strane MCU (Mikrokontroler)

## Ovo je opis projekta LED bedž. Isplaniran, projektovan i realizovan u ISPetnica. 
### http://petnica.rs/

```markdown
<-------------------------------------------------------->
    Autori projekta:

        Jovana Janjatović:
            Email: jovana.janjatovic.05@gmail.com
            Github: https://github.com/jovanajanjatovic

        Mihajlo Ninkov:
            Email: mih.nin05@gmail.com
            Github: https://github.com/MihajloNin

        Kosta Jovanović:
            Email: kosta.jovanovic@gmail.com
            Github: https://github.com/KostaJovanovic
<-------------------------------------------------------->
```

## Cilj i opis projekta


Cilj projekta je kompletno dizajniranje PCB ploče sa LED diodama u obliku logo-a ISPetnice, gde mikrokontroler omogućava kontrolu nad osvetljenjem pojedinačnih boja.

Izrada prve verzije projekta trajala je od 31.8.2022. do 10.9.2022 na letnjem seminaru elektronike u IS Petnica.
Dizajnirano je za okrugli PCB poluprečnika 3cm, koristeći SMD (surface-mounted device) i TH (through-hole) komponente.

Dizajnirano je sa idejom da se nosi kao bedž, ali to nije ograničenje.

Korišćen softver: 
    Proteus 8 Professional


## Hardver

```markdown
Korišćene komponente:
    22 LED diode:
        plave: 7 ()
        zelene: 3 ()
        žute: 5 ()
        crvene: 3 ()
        tamno plave (zamena za ljubičaste): 3;
    5 dioda;
    19 otpornika;
    5 NPN Bipolarnih tranzistora;
    3 držača za 3V Dugmaste baterije;
    1 CONN-SIL2 konektor;
    1 CONN-SIL7 konektor;
```

### Ideje i planovi:

Potrebno je napraviti kućište od klirita (mlečne plastke), na koje će sa unutrašnje strane biti zalepljeni držači za baterije, sa spoljne prekidač, a prednja strana bi koristila isključivo za difuziju svetla sa dioda.

Trenutni plan je da pošaljemo prvu stabilnu verziju ploče na izradu, kako bismo fizički mogli videti prednosti i mana našeg projekta, kako bismo ga optimizovali za širu proizvodnju.

Krajnji cilj projekta je da LED bedževi budu prodavani u petnici, do čega još uvek imamo dug put pred sobom.



### unapređenje:

Plan je da prilagodimo napajanje kako bi baterije činile manji udeo bedža.
Posle prve izrade ploče da ustanovimo prednosti i mane kako bismo imali jasnu sliku stvari koje možda moraju da budu drugačije.

<------>
<------>
<------>

en:

# LED badge optionally controlled with an MCU

## Project description


The goal of the project is the complete design of a PCB board with LEDs in the form of the ISPetnica logo, where the microcontroller enables control over the lighting of individual colors.


The development of the first version of the project lasted from August 31, 2022. until September 10, 2022 at the summer electronics seminar.
It is designed for a round PCB with a radius of 3cm, using SMD (surface-mounted device) and TH (through-hole) components

It's designed with the idea of being worn as a badge, but that's not a limitation.

Used software: 
    Proteus 8 professional



```markdown

──▒▒▒▒▒▒───▄████▄
─▒─▄▒─▄▒──███▄█▀
─▒▒▒▒▒▒▒─▐████──█─█
─▒▒▒▒▒▒▒──█████▄
─▒─▒─▒─▒───▀████▀

```
