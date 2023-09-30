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

![scratch achtergrond](images/pijl.svg)

Met de afbeelding van de richtpunt van de pijl gaan we een *sprite* maken. Een sprite is een onderdeel van ons spel.

▶▶▶ Klik aan de rechterkant op het icoontje van de afbeeldingen. Kies in het uitklapmenu *Upload sprite*. Kies de afbeelding die je zojuist hebt gedownload.

In het scherm moet nu een pijlpunt zichtbaar zijn van de sprite die net is aangemaakt. Hij heeft automatisch de naam *pijl* gekregen.

Op de achtergrond is de pijl ook op een willekeurige plek verschenen.

![scratch achtergrond](images/4.png)

We gaan te pijl iets groter maken.

▶▶▶ Vul in het veld *Grootte* het getal `400` in.

De pijl moet nu vier keer zo groot zijn als eerst.

### Opdracht 3: Bewegende pijl

Er gebeurt nog niet zoveel in ons spel. We gaan de pijl laten bewegen.



### Opdracht 4: Schieten

### Opdracht 5: Cursor vertraging bij schieten

### Opdracht 6: Punten tonen

### Opdracht 7: Feest bij bullseye

### Opdracht 8: Punten optellen

### Extra opdracht: Wind


Is je al opgevallen dat er knoppen staan voor de letters `A`, `B` en `C`? Waar is de rest van het alfabet gebleven? We hebben alle 26 letters van het alfabet nodig om galgje te spelen.

--> Ga naar regel XXX aan de linker kant. Er staat 'Opdracht 1'.

Daar staat een lijstje van mogelijke letters. Alleen `A`, `B` en `C` staan erin.

--> Vul het lijstje aan met alle andere letters. In totaal moeten er 26 letters in het lijstje staan.

Zorg dat elke letter tussen twee apostrofs (`'`) staat, en een hoofdletter is (`D`, niet `d`). Tussen elke letter moet een komma (`,`) staan.

--> Controleer dat aan de rechterkant 26 knoppen met letters zijn.

// TODO afbeelding invoegen

Goed zo! We kunnen nu letters klikken om het woord te raden.

### Opdracht 2: Letters laten verschijnen

--> Klik op een letter.

Er gebeurt niet zoveel... De letter wordt alleen rood, alsof hij fout is.

--> Klik op een andere letter.

Er gebeurt nog steeds niet zoveel. De letter wordt ook rood.

Geen enkele letter wordt groen als hij goed is. Laten we dat gaan maken.

--> Ga naar regel XXX aan de linker kant. Er staat 'Opdracht 2'.

--> Verander `const letterIsGoed = false;` naar `const letterIsGoed = letterGekozen(letter);`.

--> Klik op een aantal letters.

Nu gebeurt er iets! Voor goede letters verschijnen ze in het woord. Voor foute letters verschijnen er onderdelen van de galg.

// TODO afbeelding invoegen

### Opdracht 3: Letters laten controleren

--> Ga naar regel XXX aan de linker kant. Er staat 'Opdracht 3'.

In dit stukje code staat `if`. Dat betekent dat als de letter goed is, de code op regel XXX wordt uitgevoerd, en als de letter fout is de code op regel XXX wordt uitgevoerd.

Op beide regels wordt `'fout'` gezet, waardoor de knop rood wordt!

--> Zorg ervoor dat als de letter goed is (de code in regel XXX), er `'goed'` wordt gezet in plaats van `'fout'`.

--> Klik een aantal letters aan. Als je een goede letter raadt, moet de letter groen worden

// TODO afbeelding invoegen

### Opdracht 4: Meer woorden

--> Ga naar regel XXX aan de linker kant. Er staat 'Opdracht 4'.

Tot nu toe wordt er een lijstje gebruikt van twee mogelijke woorden. Dat is saai. Gelukkig kunnen we met code extra woorden erbij maken!

--> Voeg een woord toe, onder `"programmeren"` en `"bibliotheek"`. Zorg dat de regel er net zo uit ziet als de andere regels in het lijstje: `{woord: "...", omschrijving: "..." },`. Elke regel moet eindigen met een komma (`,`).

Aan de rechterkant moet nu af en toe jouw nieuwe woord(en) verschijnen. Het spel kiest een willekeurig woord uit het lijstje.

--> Klik een aantal keer op de knop `Opnieuw` in het Galgje spel, net zolang totdat jouw woord voorbij komt. Raad met de knoppen met letters jouw eigen woord.

// TODO afbeelding invoegen




// TODO alle regelnummers invullen
