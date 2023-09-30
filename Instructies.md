# Boogschieten

Hallo! Vandaag gaan we het spel *boogschieten* maken, met behulp van Scratch.

Scratch is een omgeving waarin we kunnen programmeren. Door blokken te slepen, kunnen we structuren maken die samen een spel vormen.

We beginnen helemaal leeg. Elke opdracht hieronder is een stukje van het spel. Aan het einde van de opdrachten heb je een spel gebouwd, waarmee je kunt boogschieten en kan tellen hoeveel punten je hebt gescoort.

Elke opdracht bevat uitleg, en dingen die jij zelf moet doen. De dingen die jij zelf moet doen, staan aangegeven met `▶▶▶`.

Als je helemaal klaar bent, zal het eindresultaat er ongeveer zo uit zien

![klaar](images/1.png)

### Opdracht 0: Openen van Scratch

De programmeeromgeving waarin we gaan werken heet *Scratch*. Dat is een website waarop je blokken kunt slepen om een programma te maken. Het resultaat kan je direct bekijken en uitproberen!

▶▶▶ Open Scratch door op de link te klikken: https://scratch.mit.edu/projects/editor

Er zijn meerdere dingen te zien:
- Code blokken (links)
- Het veld om in te programmeren (midden)
- Het resultaat (rechterkant)

In de volgende opdrachten zullen we de blokken van de linkerkant pakken, ze in het midden neerzetten, en aan de rechterkant het resultaat bekijken.

Dat was gemakkelijk! Nu komt het echte werk!

![scratch](images/2.png)

### Opdracht 1: Een mooie achtergrond

We hebben nu in Scratch een mooi nieuw project gemaakt. We gaan hier in ons spel programmeren.

Echter heeft Scratch ons al een begin gegeven dat we eigenlijk niet willen: een kat.

▶▶▶ Klik aan de rechterkant op het icoontje van de prullenbak om te kat te verwijderen.

Nu is de omgeving echt leeg.

Laten we een mooie achtergrond maken voor ons spel. We hebben een afbeelding nodig.

▶▶▶ Klik met de rechter muisknop op de afbeelding hieronder, en selecteer *Sla afbeelding op als...*. Sla de afbeelding ergens op de computer op.

Deze afbeelding:
![achtergrond](images/achtergrond.png)

▶▶▶ Klik aan de rechterkant in *Speelveld* op het icoontje van *Achtergronden*, en in het uitklapmenu op *upload achtergrond*. Kies de afbeelding die je zojuist hebt gedownload.

In Scratch opent nu een scherm waarin je de achtergrond verder kunt bewerken. Dat is niet nodig.

![scratch achtergrond](images/3.png)

▶▶▶ Klik aan de linkerkant op *Code* om terug te gaan naar de programmeeromgeving.

### Opdracht 2: Richten met de pijl

Met boogschieten gebruiken we een pijl om op het bord te schieten.

De pijl stellen we voor als een richtpunt.

▶▶▶ Klik met de rechter muisknop op de afbeelding hieronder, en selecteer *Sla afbeelding op als...*. Sla de afbeelding ergens op de computer op.

![pijl](images/pijl.svg)

Met de afbeelding van de richtpunt van de pijl gaan we een *sprite* maken. Een sprite is een onderdeel van ons spel.

▶▶▶ Klik aan de rechterkant op het icoontje van de afbeeldingen. Kies in het uitklapmenu *Upload sprite*. Kies de afbeelding die je zojuist hebt gedownload.

In het scherm moet nu een pijlpunt zichtbaar zijn van de sprite die net is aangemaakt. Hij heeft automatisch de naam *pijl* gekregen.

Op de achtergrond is de pijl ook op een willekeurige plek verschenen.

![](images/4.png)

We gaan de pijl iets groter maken.

▶▶▶ Vul aan de rechter kant in het veld *Grootte* het getal `400` in.

De pijl moet nu vier keer zo groot zijn als eerst.

### Opdracht 3: Bewegende pijl

Er gebeurt nog niet zoveel in ons spel. We gaan de pijl laten bewegen.

Ten eerste moeten we iets doen als het spel start.

Zodra het spel start, zetten we de pijl op een willekeurige plek.

In Scratch gebruiken we daarvoor *signalen*. Signalen geven aan dat er iets is gebeurd. In ons geval willen we een nieuwe pijl schieten, dus maken we een signaal dat `nieuwe pijl` heet.

▶▶▶ Kies aan de linker kant de categorie *Gebeurtenissen* (geel).

▶▶▶ Sleep het blok *wanneer op 🟩 wordt geklikt* in het veld.

▶▶▶ Sleep het blok *zend signaal <...>* in het veld.

▶▶▶ Kies binnen het blok *zend signaal <...>*, de optie *Nieuw bericht*, en typ `nieuwe pijl` in het tekstveld.

Nu wordt er een signaal gestuurd als het spel wordt gestart. Daar zien we alleen nog niet zoveel van.

![](images/5.png)

▶▶▶ Sleep het blok *wanneer ik signaal <...> ontvang* in het veld, en maak daarmee een nieuwe groep.

▶▶▶ Selecteer in het blok *wanneer ik signaal <...> ontvang* het signaal `nieuwe pijl`.

▶▶▶ Kies aan de linker kant de categorie *Beweging* (blauw).

▶▶▶ Sleep het blok *ga naar x: <...>, y: <...>* in het veld.

▶▶▶ Kies aan de linker kant de categorie *Functies* (groen).

▶▶▶ Sleep het blok *willekeurig getal tussen <...> en <...>* op het eerste getal in het blauwe *ga naar* blok.

▶▶▶ Sleep nog een blok *willekeurig getal tussen <...> en <...>* op het tweede getal in het blauwe *ga naar* blok.

▶▶▶ Kies voor beide *willekeurig getal* blokken de getallen `-150` en `150`.

▶▶▶ Kies aan de linker kant de categorie *Besturen* (oranje).

▶▶▶ Sleep een blok *herhaal* (alleen herhaal, geen aantal of andere vakjes) in het veld.

▶▶▶ Kies aan de linker kant de categorie *Beweging* (blauw).

▶▶▶ Sleep het blok *schuif in <...> sec. naar x: <...>, y: <...>* in de binnenkant van het oranje *herhaal* blok.

▶▶▶ Zet het eerste getal in het blauwe *schuif in...* blok op `0.5`.

▶▶▶ Kies aan de linker kant de categorie *Functies* (groen).

▶▶▶ Sleep het blok *willekeurig getal tussen <...> en <...>* op het eerste getal in het blauwe *schuif in...* blok.

▶▶▶ Sleep nog een blok *willekeurig getal tussen <...> en <...>* op het tweede getal in het blauwe *schuif in...* blok.

▶▶▶ Kies voor beide *willekeurig getal* blokken de getallen `-150` en `150`.

![](images/6.png)

Laten we het uitproberen! Klik op de groene vlag 🟩 om het spel te starten!

De pijl moet over het scherm heen en weer bewegen.

### Opdracht 4: Schieten



### Opdracht 5: Cursor vertraging bij schieten

### Opdracht 6: Punten tonen

### Opdracht 7: Feest bij bullseye

### Opdracht 8: Punten optellen

### Extra opdracht: Wind

