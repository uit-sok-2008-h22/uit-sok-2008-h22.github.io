{% include top-box.html %} <!-- Kode for å inkludere boksen på toppen av siden. Se _config.yml for å gjøre endringer. -->
{% include navbar.html %} <!-- Kode for navigasjonsmeny. Se navbar.html for å gjøre endringer. -->
<!-- Gjør endringer under her -->

# Innlevering 3
### <span style="color:OrangeRed;">Frist: 4. oktober 2022 kl 23:59</span>
Du finner detaljert informasjon og tips om hvordan skrive en god besvarelse nederst på denne siden.
På seminarene knyttet til Tema 3 har du tilfelle å jobbe med oppgavene sammen med dine studentkolleger. Forelesere på kurset vil være tilstede for å svare på spørsmål. 

**Førberedelser og støtte:**

Litteratur: Boeri og van Ours, kapittel 2 og 8. Barr, kapittel 10-11

[Forelesinger](forelesninger.md#f_t3)

[Videoer](video.md#v_t3)

## Utfordring 3.1
1. I Norge har vi ikke en lagfestet minstelønn. Likevel er arbeidsgivere bundne av kollektive avtaler som setter rammer for lønnsnivået. Rammeavtalene fungerer derfor litt som en minstelønn. Lag en graf som viser arbeidsløsheten i prosent blant ungdommer i alderen 15-24 og voksne i alderen 20-64 (begge kjønn, alle utdanningsnivåer). Du finner data her: [SSB](https://www.ssb.no/statbank/table/11155). Bruk økonomisk teori om effekten av minstelønn på et perfekt arbeidsmarked for å forklare forskjellen i arbeidsledighet mellom de to gruppene. Bruk gjerne grafisk illustrasjon av de økonomiske mekanismene. 

2. Lag en graf som viser sammenhengen mellom minstelønn som prosent av medianlønn og arbeidsledighet i prosent i Frankrike (FRA), Tyskland (DEU), USA (USA), Storbritannia (GBR), og Nya Zeeland (NZL) for perioden 2008-2018. Du finner støtte til hvordan du gjør denne i script-filen [Utf_3.1.R](Assets/Utf_3.1.R). Diskuter hva du ser. 

3. Bruk økonomisk teori for å gi en forklaring til den observerte sammenhengen mellom arbeidsledighet og minstelønn for Storbritannia.

4. Diskuter hvorfor det å sammenlikne ulike land kan føre til at vi drar feil konklusjoner om sammenhengen mellom nivået på minstelønn og arbeidsledighet. Gi forslag på en bedre metode å teste hvordan minstelønn påvirker arbeidsledighet og sysselsetting. 

## Utfordring 3.2

Investeringer i utdanning gir avkastning til individet som gjør investeringen. Likevel er offentlig finansiert utdanning (både grunnskole og høyere utdanning) en viktig del av den nordiske modellen. 
Bruk økonomisk teori for å diskutere hvorfor vi har offentlig finansiert utdanning når individene selve tjener på sine investeringer i humankapital. Diskuter også eventuelle ulemper med offentlig finansiert utdanning. Din diskusjon skal være basert på økonomisk teori og eventuelt empirisk forskning. 


## Slik leverer du:
Hver innleveringsoppgave leveres som en pdf-fil i en individuell mappe på Canvas. Eventuell kode leveres som pdf-fil på Canvas (gjerne i samme pdf-fil som løsningen på oppgaven) og lastes opp til GitHub. 

[Se her](howtogithub.md) for å lese mer om hvordan man leverer på GitHub.

Bruk følgende navn på: SOK-2008-2022-oppgave3

Innleveringene skal skje individuelt. 
## Evaluering
Du kan få 0, 1 eller 2 poeng. Din besvarelse blir evaluert etter regelen i tabell 1. 

**Tabell 1.** Evalueringsmatrise for utfordringer

| Poeng | Beskrivelse |
|-------| ----------- |
| 2 | Svært godt gjennomført. Alle spørsmål er fullstendig besvarte. Det er enkelt å følge resonnementene. Det gis god økonomisk intuisjon til alle oppgaver. Matematikken er i stort korrekt og enkel å følge. Eventuell kode er lastet opp på GitHub. Det finnes ikke store feil. Oppgaven og koden er ryddig skreven. |
| 1 | Tilstrekkelig godt gjennomført. Alle spørsmål er besvarte eller så er nesten alle spørsmål besvarte OG det gis en god gjennomgang av problemer med ubesvarte oppgaver. Det går å følge resonnementene. Det gis økonomisk intuisjon. Det kan finnes små feil i matematikken, men ikke store feil. Eventuell kode er lastet opp på GitHub. Oppgaven og kode er ryddig skreven.  |
| 0 | Ikke tilstrekkelig godt gjennomført. Ikke alle spørsmål er besvarte og studenten gir ikke en god gjennomgang av problemer med ubesvarte oppgaver ELLER det er svært vanskelig å følge resonnementene i oppgaven ELLER det gis ikke økonomisk intuisjon ELLER det finnes store feil i matematikken, og/eller den økonomiske intuisjonen.  |

## Tips og triks for hvordan du skriver en god besvarelse

### Generelle tips

1. Skriv kortfattet og tydelig
2. Gå igjennom språket. Oppgaven skal skrives på godt akademisk språk, ikke i taleform.
3. Ha samme inndeling på ditt svar som det er i oppgaven.
4. Det er lov å bruke bilder på håndtegnede grafer og ligninger men jeg anbefaler å prøve å lage både ligninger og grafer digitalt. Hvis du bruker håndtegnede grafer eller ligninger, se til at både grafen i seg selv, og bildet av grafen er svært tydelig. Hvis jeg ikke kan se hva grafen viser kan jeg ikke gi poeng. 
5. Definere dine symboler hvis du bruker andre symboler enn de vi bruker under kurset.
6. Referere i teksten til de symboler som du analyserer, og beskriv dem i ord. F eks, en økning i arbeidstilbudet ($L^s$) fører til at…
7. Forklare dine ligninger og utledninger. Det er viktig at det går å følge dine utledninger og beregninger. 
8. Gi alltid økonomisk intuisjon (forklaring til dine svar). Det å skrive "Kurven skifter og vi går ifra A til B" er ikke tilstrekkelig. Et svar som gir økonomisk intuisjon forklarer effekten i økonomiske termer, f eks.; "Hvis innvandringen øker vil dette føre til at mengden arbeidere som er villige til å jobbe til en gitt timelønn øker, arbeidstilbudet ($L^s$) øker. Ved likevektslønna $w_0$ finnes det nå arbeidere som ønsker jobb men som ikke har jobb. Dette fører til en press nedåt på lønna. Når lønna synker finnes det flere bedrifter som er villige å ansette. Sysselsettingen øker. Den nye likevekts lønna gis av $w_1$. Sysselsettingen i den nye likvekten gis av $L_1$" 

### Ligninger
Det er mulig å skrive ligninger i de fleste ordbehandlingsprogrammer. I word velger du «insert» og deretter «equation». Du får da opp en boks i teksten og en meny med symboler og funksjoner. Et tips er at «underscore» etter et tegn gir subscript hvis du trykker på mellomslag etterpå , og tegnet «’» gir superscript. 

Du finner flere tips og triks her:
* [Kort-kommandoer til Microsoft Equation Editor[(https://mathiho.sitehost.iu.edu/doc/equation-editor-shortcut-commands.pdf)

### Grafer
Det går å lage grafer ved bruk av en rekke verktøy. Vår erfaring er at Power-point er bedre enn Word. Når du har laget en graf i Power-point kan du enten lagre denne som et bilde ved å høyre-klikke på den, eller kopiere den direkte og lime inn den som et bilde (lime inn spesial) i Word.

I noen oppgaver på kurset vil du lage grafer i R ved bruk av empiriske data. Når du laget en graf velger du først «eksportere» og deretter enten «save as image» eller «save as pdf». Du kan deretter lime in bildet i ditt Word-dokument. 

### Tabeller

Det går å lage tabeller ved bruk av en rekke verktøy, f.eks. Excel og R. Det går å kopiere tabeller fra Excel og R og lime inn i Word. Hvis du er flink i f eks LaTeX så går det å skrive kode i R som lager TeX filer. 


### Referanser
 Hvis du bruker materiale utenfor pensum skal du bruke referanser, både i teksten, og i en referanseliste. Referanser i tekst skal inneholde etternavn på forfatter og år. Hvis det er flere enn to forfatter er det lov å bruke «et al». Det finnes to forskjellige måten å skrive referanser i tekst. Iblant henviser vi til en studie i teksten, f eks at Acemoglu et al (2001) fant at land en signifikant lenke mellom kolonial historie og nåværende økonomisk vekst. Et annet måte er å skrive at det ser ut å va en lenke mellom kolonial historie og nåværende økonomisk vekst (Acemoglu et al, 2001). Lengst ned i dokumentet skriver du en referanseliste. I Tabell 2 her nede ser du hvordan du refererer til ulike typer av skrevet materiale. 
 
 **Tabell 2.** Referanser
 
 
 | Type | Referanse |
|-------| ----------- |
| Vitenskapelige artikler og working-papers | Acemoglu, D., Johnson, S., and Robinsom, J. (2001). The Colonial Origins of Comparative Development: An Empirical Investigation. *American Economic Review*, 91(5), pp. 1369-1401 |
| Bøker | Lucas, R. E. (1976). Econometric Policy Evaluation: A Critique, in Brunner, K., and Metzer, A (eds), *The Phillips Curve and Labor Markets*, Carnegie Rochester Conference Series, New York, North Holland, pp. 19-46 |
| Artikler i aviser | Weisman, J. (2015). Deal Reached on Fast-Track Authority for Obama on Trade Accord. *The New York Times*, p.A1 |
| Artikler fra Internett | Messer, L. (2015). 'Fancy Nancy' Optioned by Disney Junior. [online] ABC News. Available at: http://abcnews.go.com/Entertainment/fancy-nancy-optioned-disney-junior-2017/story?id=29942496#.VRWbWJwmbs0.twitter (Accessed 31 Mar. 2015)|

