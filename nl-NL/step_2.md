## Maak je card

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In deze stap maak je een infocard voor een lekkere traktatie met een afbeelding, kop en tekst.
</div>
<div>
<iframe src="https://editor.raspberrypi.org/nl-NL/embed/viewer/flip-treat-webcards-step-2" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

--- task ---

Open het [Webcards met lekkernijen startproject](https://editor.raspberrypi.org/nl-NL/projects/flip-treat-webcards-starter){:target="_blank"}.

--- /task ---

--- task ---

De `<title>` tag binnen je code wordt gebruikt om tekst in de titelbalk van je webbrowser weer te geven. Deze tekst moet relevant zijn voor je webpagina.

Je kunt de `<title>` binnen het `<head>` element vinden bovenaan je `index.html` bestand.

**Verander** je titel in `Lekkernijen flip cards`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 13
---
<!DOCTYPE html>
<html lang="nl-NL">

<!-- Dit deel is bedoeld voor extra informatie die de browser nodig heeft om de pagina correct te laden -->
<head>

  <meta charset="utf-8">

  <!-- De pagina op mobiel niet verkleinen -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Verschijnt op het tabblad van de webbrowser en in de zoekresultaten -->
  <title>Flip cards met lekkernijen</title> 

--- /code ---

--- /task ---

--- task ---

Klik op het kleine driehoekje naast de tag `<head>` om de `<head>` samen te vouwen.

Je kunt delen van de code samenvouwen waarop je je niet hoeft te concentreren om je code gemakkelijker te kunnen lezen.

--- /task ---

--- task ---

Voeg een `<section>` toe aan het `<main>` deel van je pagina. Geef de `<section>` een `wrap` class om je webpagina te laten reageren.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 26
line_highlights: 29-31
---
<body>

    <main>
      <section class="wrap">
        
      </section>

--- /code ---

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Grafische ontwerpers**</span> zijn mensen die aantrekkelijke fysieke of digitale visuele inhoud creëren. Enkele voorbeelden van grafisch ontwerp zijn bedrijfslogo's, productverpakkingen en website banner ontwerp. Onze grafisch ontwerper Kate heeft een aantal afbeeldingen gemaakt van lekkernijen van over de hele wereld die je in je project kunt gebruiken. 

![Een collage van lekkernijen om in het project te gebruiken.](images/treats.png)

</p>

Het `<div>` element wordt gebruikt om andere elementen te groeperen. Het `<div>` element wordt gebruikt als er geen andere geschikte tag is, zoals `<section>` en `<blockquote>`.

--- task ---

Maak een `<div>` die een afbeelding bevat. Het eerste beeld is `LapisSarawak02.png`, een zoete lekkernij uit Maleisië.

![Een cartoonachtige afbeelding van Lapis Sarawak, een kleurrijke, geometrische taart.](images/LapisSarawak02.png)

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 29
line_highlights: 30-32
---

    <section class="wrap">
      <div>
          <img src="LapisSarawak02.png" alt="Lapis Sarawak." />
      </div>
    </section>

--- /code ---

--- /task ---

--- task ---

Voeg nog een `<div>` toe met een kop en een korte paragraaf over Lapis Sarawak:

Kop: `Lapis Sarawak`
Paragraaf: `Een cake die in lagen wordt gebakken om kleurrijke patronen te maken.`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 29
line_highlights: 33-36
---
         
    <section class="wrap">
      <div>
        <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
      </div>
      <div>
        <h2>Lapis Sarawak</h2>
        <p>Een cake die in lagen wordt gebakken om kleurrijke patronen te maken.</p>
      </div>
    </section>
        
--- /code ---

--- /task ---

--- task ---

**Test:** Klik op de **Run** knop.

Bekijk jouw webpagina. Je zou een afbeelding van een Lapis Sarawak moeten kunnen zien en je tekst die de afbeelding beschrijft.

<div>
<iframe src="https://editor.raspberrypi.org/nl-NL/embed/viewer/flip-treat-webcards-step-2" width="500" height="450" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

</div>

--- /task ---
