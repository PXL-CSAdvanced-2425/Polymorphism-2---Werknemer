# Werknemer

Deze toepassing maakt gebruik van een tekstbestand *Werknemers.txt*
waarin de gegevens van het kader, bedienden en het personeel dat op
commissie werkt, zijn opgenomen.

![Afbeelding met tekst, schermopname, Lettertype, nummer Automatisch
gegenereerde
beschrijving](./media/image1.png)

De verschillende kolommen hebben respectievelijk een vaste lengte van:
[15, 20, 2, 9, 7, 9, 6 en 9]{.mark} karakters lang.

Je mag er van uitgaan dat bij deze structuur nooit fouten zijn en dat
het bestand aanwezig is op de door u bepaalde locatie. Het aantal
records in het tekstbestand is niet vast.

Maak voor deze toepassing een ***abstracte klasse*** ***Werknemer*** en
3 afgeleide klassen: ***Bedienden***, ***Commissie*** en ***Kader***.

![Afbeelding met tekst, schermopname, nummer Automatisch gegenereerde
beschrijving](./media/image2.png)

Bij de knop Werknemer worden alle records uit het bestand
*Werknemers.txt* gelezen en bewaard in List\<Werknemer\>. Daarna wordt
de knop uitgeschakeld.

![Afbeelding met tekst, schermopname, scherm, software Automatisch
gegenereerde beschrijving](./media/image3.png)

De klasse ***Werknemer*** omvat 2 abstracte methoden die in de afgeleide
klassen overgeërfd en voor de betreffende werknemers moet uitgewerkt
worden.

Klasse ***Kader*** omvat:

-   *Wedde()* geeft salaris uit tekstbestand.

-   *Info()* geeft onderstaande afdruk.

![Afbeelding met tekst, schermopname, scherm, software Automatisch
gegenereerde beschrijving](./media/image4.png)

Klasse ***Bedienden*** omvat:

-   *Wedde()* berekent uurloon \* aantal gewerkte uren.

-   *Info()* geeft onderstaande afdruk.

![Afbeelding met tekst, schermopname, software, scherm Automatisch
gegenereerde beschrijving](./media/image5.png)

Klasse ***Commissie*** omvat:

-   *Wedde()* berekent salaris + commissie.

-   *Info()* geeft onderstaande afdruk.

![Afbeelding met tekst, schermopname, scherm, software Automatisch
gegenereerde beschrijving](./media/image6.png)
