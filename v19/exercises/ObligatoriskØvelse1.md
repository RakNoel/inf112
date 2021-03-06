# INF112 Obligatorisk oppgave 1, Våren 2019

Målet for denne oppgaven er å trene på kommunikasjon, fremstilling, samt å bli kjent med et av verktøyene vi bruker i kurset.

Oppgavesettet består av fire deloppgaver.

## Oppgave 1 - Kommunikasjonsøvelse

Gå sammen to og to, og bruk fem minutter på å bli kjent. Etterpå skal dere presentere hverandre for gruppen. Denne presentasjonen kan vare opp mot et minutt, og dere kan forklare kort om fagbakgrunn, hobbyer, interesser osv. Hvis gruppen er stor, deles gruppen opp i to mindre grupper som jobber parallelt.

## Oppgave 2 - Kommunikasjonsøvelse

Bruk 10 minutter på å lage en kort presentasjon (1 ½ - 2  minutter maks)  om noe du synes er kult. Dette kan være enten fagmessig eller fra en hobby. Etterpå skal du presentere dette for gruppen. Husk å passe tiden, og gi en person ansvar for å stoppe presentasjonene om de går over tiden. (Et vanlig triks er å begynne å klappe når tiden er ute)

## Oppgave 3 - Git og Github

I dette faget skal dere under senere øvelser jobbe i team med utvikling av en større applikasjon. For samarbeid på større prosjekter hjelper versjonskontrollsystemer ved å gi et felles lagringsområde for kildekode og andre ressurser for prosjektet. Et slikt system gjør det også lettere å holde kontroll på endringer, samt å gi dere muligheten til å rulle tilbake til tidligere versjoner. Git er et populært versjonskontrollverktøy, og vi bruker Git i dette kurset for å håndtere kildekode og dokumentasjon for programvare. Flere produkter bruker git. Dere kjenner kanskje til github, gitlab og bitbucket? I dette kurset bruker vi github siden det er det mest utbredte.

- Gå inn på https://github.com/ og registrer deg.
- Lag en mappe til git-prosjektet.
- Lag et nytt repository, enten via “git init” fra kommandolinjen (i mappen), eller i nettleser. Om du gjør det - fra github.com, må du klone repositoriet til datamaskinen din, slik at du kan jobbe med det.
- Lag en tekstfil som inneholder en oppskrift for vafler. Last så denne filen opp i repositoriet via kommandolinjen. (Nyttige kommandoer: *“add”, “commit”, “push”*)

Tips: Det er lurt å sjekke ut en guide eller et cheatsheet. For eksempel [dette](https://medium.com/@nendhruv/essential-git-commands-every-developer-should-know-1249d4d597b5).

## Oppgave 4 - FizzBuzz

I denne oppgaven skal dere gjøre en "kode-kata". kode-kataer er små programmeringsoppgaver (ikke helt ulikt [kattis](https://www.kattis.com/)), for å få mengdetrening med å programmere.

Fizz Buzz er et program som printer tallene fra 1 til 100 på separate linjer, med et par modifikasjoner:

- Om tallet er delelig på tre, skal programmet printe “fizz” istedenfor tallet
- Om tallet er delelig på fem, skal programmet printe “buzz” istedenfor tallet.
- Om tallet er delelig på tre **og** fem, skal det printe “fizzbuzz”.

- Denne oppgaven skal løses med parprogrammering, og dette kan gjøres på flere måter: Om dere vil bruke TDD (Test Driven Development), som vist under forelesning, kan den ene personen skrive test, mens den andre skriver implementasjonskode. Eller så kan dere programmere fem minutter hver.
- Det er viktig at dere er nøye med **hvordan** dere snakker sammen, og at dere begge har full kontroll på hva som skjer i koden. Tips: Les [denne](https://medium.com/@weblab_tech/pair-programming-guide-a76ca43ff389)

Etter at dere er ferdig:

- Bruk noen minutter på å diskutere hvordan det fungerte å programmere i par. 
- Lag en liten oppsummering til resten av gruppen (1-2 minutter) hvor dere nevner noe dere synes fungerte bra, noe som kunne vært bedre og hva dere kunne gjort bedre til neste gang. 

### Videre arbeid

- Generaliser fizzbuzz slik at man selv kan velge tall som fizzbuzz skal endre på, og hvilke ord som skal printes. Bruk gjerne egne metoder.
- [codekata.com](http://codekata.com/) har mange gode oppgaver, om dere ønsker å trene mer på kode-kata.
- Det kan være lurt å registrere seg som studentbruker i github. Da får man mange gode verktøy [gratis](https://education.github.com/pack).