Reklamskylt
En reklamskylt-applikation byggd i Java som visar annonser baserat på kunddata. Programmet kan visa annonser i följd och uppdateras automatiskt med en timer. Projektet är uppdelat i flera klasser och använder Java Swing för det grafiska användargränssnittet.

Funktioner
Visa annonser för olika kunder med namn, reklamtext och avgift.
Använd en timer för att byta annons automatiskt var 10
sekund.
Slumpmässigt välj kund med möjlighet till viktad chans för olika kunder.
Flexibel anpassning av annonsdata med möjlighet till utökat innehåll och stil.
Projektstruktur
Projektet är organiserat i följande Java-klasser:

App.java - Huvudklassen som startar programmet och hanterar körningen.
Reklamskylt.java - Klass för att hantera skylten och visa annonser.
Message.java - Klass som representerar en annons med kundens namn, reklamtext och avgift.
Timer - Timer-objekt som byter annons automatiskt var 10
sekund.
Installation
Klona detta repo:
bash
Kopiera kod
git clone https://github.com/[ditt-användarnamn]/Reklamskylt-Grupparbete-Java.git
Öppna projektet i din Java IDE (som IntelliJ IDEA eller Eclipse).
Säkerställ att Java JDK 8 eller senare är installerat.
Användning
Starta programmet genom att köra App.java.
Annonser visas på skärmen och byts ut automatiskt var 10
sekund.
Alla annonser innehåller kundens namn, reklamtext och avgift. Om en kund har flera annonser kan de växlas slumpmässigt.
Exempel på Annonsdata
I Message.java definieras exempelannonser som innehåller följande attribut:

java
Kopiera kod
private String customer; // Kundens namn
private String ad;       // Reklamtext
private Float fee;       // Avgift
Systemkrav
Java JDK 8 eller senare
Java Swing (ingår i Java Standard Edition)
Framtida utveckling
Implementera en funktion för att redigera och lägga till annonser direkt från användargränssnittet.
Lägg till möjlighet att justera annonsens visningsintervall.
Implementera stöd för fler annonsformat och multimedia (bilder eller video).
Medverkande
Projektgruppen består av:

Tarek
Axel
Chris

Handledare: Stefan

