---
title: Voorbeeld
---
<!-- dit is tekst die niet wordt weergeven op de pagina -->
# titel
Gewone tekst.

## kleinere titel

### nog kleiner

<!-- dit is een link. Het linker deel is hoe het eruit gaat zien .. -->
<!-- .. en het rechter deel is de link waartoe het verwijst         -->
<!-- de link moet beginnen met https://                             -->
[url](https://google.com)

code blok:
``` python
def functie():
  printf("test")
```

<!-- hier is een kolom omgeving met 2 kolommen -->
<!-- dit is de start van de kolom omgeving     -->
{{< columns >}}

<!-- dit is de start van de eerste kolom       -->
{{< column >}}

<!-- binnenin is de inhoud van de eerste kolom -->
Kolom 1

<!-- dit is het einde van de eerste kolom      -->
{{< /column >}}

<!-- dit is de start van de tweede kolom       -->
{{< column >}}

<!-- binnenin is de inhoud van de tweede kolom -->
Kolom 2

<!-- dit is het einde van de tweede kolom      -->
{{< /column >}}

<!-- dit is het einde van de kolom omgeving    -->
{{< /columns >}}


<!-- Je kan het ook iets anders neerzetten voor duidelijkheid -->
{{< columns >}}
  {{< column >}}
    Kolom 1
  {{< /column >}}
  
  {{< column >}}
    Kolom 2
  {{< /column >}}
{{< /columns >}}
