# Tekstimuuttujat

## JOHDANTO
- Koodin rakenne muistuttaa läheisesti "Hello Nimi" harjoituksen koodia - voit hyödyntää aiemmin oppimaasi tässä harjoituksessa.
- Pääsääntöisesti muuttujat ovat joko teksti- tai numeromuuttujia.
- Tekstimuuttujassa voi olla sekä numeroita että tekstiä, ohjelma käsittelee kuitenkin tekstimuuttujan sisältämät numerot tekstinä eikä niitä voi hyödyntää matemaattisesti.
- String- tyyppisen tekstimuuttujan sisältö on aina hipsuissa, eli " " merkkien sisällä.
    - Jos " " merkkien sisällä on vain välilyönti, sen sisältö on tyhjä välilyönti -> " "
    - Jos " " merkkien sisällä ei ole edes välilyöntiä, sen sisältö on tyhjä -> ""
   -  Välilyönnit merkitsevät koodissa
## TEHTÄVÄNANTO
- Tee konsolisovellus, jossa on kaksi muuttujaa ja konsoliin tulostava "write line" -tyyppinen konsolitoiminto.
- Muuttujat: nimi ja kaupunki ovat arvoiltaan sinun nimesi ja sinun kotikaupunkisi.
  - String- eli tekstityyppisiä muuttujia
- Toiminto: tulostaa muuttujat nimi ja kaupunki tekstin mukana
- Tuloste: "Minun nimeni on nimi ja asun kaupungissa kaupunki"
- Tämän jälkeen laita konsoli tulostamaan WriteLine metodilla vain molemmat muuttujat
- Tee vielä kolmas tulostusrivi. Se on muutoin sama kuin edellinen rivi, lisää muuttujien väliin välilyönti tulosteeseen.
- Esimerkkituloste alla:

  
```
Minun nimeni on Jenny kaupungissa Helsinki
JennyHelsinki
Jenny Helsinki
```
> [!IMPORTANT]
> Koodin kirjoittamisen johdanto
1. Kloonaa projekti omalle koneellesi.
2. Avaa `ConsoleApp.sln`.
3. Solution-ikkunasta valitse "ConsoleApp".
4. Pääkoodi löytyy `Program.cs`-tiedostosta. Jos tarvitset, luo uudet itemit `ConsoleApp`-projektiin.
