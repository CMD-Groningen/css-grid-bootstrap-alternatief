# CSS grid Bootstrap alternatief

## Voorbeeld bestanden
Bestanden **downloaden** naar je laptop? [Klik hier](https://github.com/CMD-Groningen/css-grid-bootstrap-alternatief/archive/refs/heads/master.zip)     
Preview in de browser? [Klik hier](https://cmd-groningen.github.io/css-grid-bootstrap-alternatief)  
Speel live met deze code in **CodeSandbox** > [Klik hier!](https://codesandbox.io/s/github/CMD-Groningen/css-grid-bootstrap-alternatief) 

Voorbeeld van hoe je het complete column grid met spans van Bootstrap (of Foundation) kunt klonen door alleen vanilla CSS grids te gebruiken! Je kunt eenvoudig je eigen rastersysteem maken door slechts een paar regels CSS-code te gebruiken. Begin met het maken van een rasterdefinitie van 12 kolommen in je CSS-bestand (het kan willekeurig **elk** aantal kolommen zijn dat je wilt!) 🙂

```CSS
display:grid;
grid-template-columns: repeat(12,1fr);
```

En definieer dan de column spans voor de kolommen in je lay-outs:

```CSS
header { grid-column:span 12;}
nav { grid-column: span 3;}
main { grid-column:span 9;}
footer { grid-column:span 12;}
```

**David van den Bor**  
CMD Team  

Docent Communicatie & Multimedia Design @ Hanzehogeschool Groningen  
d.b.p.van.den.bor@pl.hanze.nl  

https://github.com/CMD-Groningen  
https://github.com/davidvandenbor
