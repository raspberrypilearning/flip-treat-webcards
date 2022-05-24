## Create a card

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will create an infocard for a tasty treat with an image, heading and text.
</div>
<div>
<iframe src="https://trinket.io/embed/html/0ea70b025f?outputOnly=true" width="300" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

--- task ---

Open the [Flip treat webcards starter project](http://rpf.io/flip-new){:target="_blank"}. 

--- /task ---

--- task ---

Add a `<section>` to the `<main>` part of your page, give it the `wrap` class:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 25
line_highlights: 28-30
---
<body>

    <main>
      <section class="wrap">
        
      </section>

--- /code ---

--- /task ---

--- task ---

Create a `<div>` that contains an image:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 29-31
---

<section class="wrap">
  <div>
    <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
  </div>
</section>

--- /code ---

--- /task ---

--- task ---

Add another `<div>` with a heading and text:

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
          <p>A cake baked in layers to make colourful patterns.</p>
        </div>
</section>
        
--- /code ---

--- /task ---

--- task ---

**Test:** View your webpage. You should be able to see an image of a Lapis Sarawak (a sweet treat from Malaysia) and your text describing it.

<div>
<iframe src="https://trinket.io/embed/html/0ea70b025f?outputOnly=true" width="300" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

--- /task ---
