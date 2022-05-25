## Style your card

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will add colour gradients, rounded corners and vertical centering to your cards. 
</div>
<div>
Image, gif or video showing what they will achieve by the end of the step. ![](images/image.png){:width="300px"}
</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Colour gradients**</span> are a gradual change from one colour to another. Computers process how to display a smooth colour gradient by working out the positions and colour shades needed to go from the starting colour through to the end colour. 

![4 examples of gradients in squares transitioning from one colour to another.](images/gradients.png)

</p>

Gradients will be used to make your card stand out on the page. 

--- task ---

Add the `gradient1` class to the `<div>` that displays the image. 

The `gradient1` class uses a linear gradient transitioning from one colour at the top to another colour at the bottom. 

![Examples of gradient1 in a square transitioning from one colour at the top to another colour at the bottom.](images/gradient1.png)


--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 31
---
    <section class="wrap">
        <div class="card">
          <div class="card-content">
            <div class="card-face gradient1">
              <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
            </div>

            <div class="card-face flipme">
              <h2>Lapis Sarawak</h2>
              <p>A cake baked in layers to make colourful patterns.</p>
            </div>
          </div>
        </div>
    </section>

--- /code ---

--- /task ---

--- task ---

Add the `gradient2` class to the `<div>` that displays the heading and paragraph. 

The `gradient2` class uses a linear gradient transitioning diagonally from one colour at the top to another colour at the bottom right. 

![Examples of gradient2 in a square transitioning from one colour at the top to another colour at the bottom right.](images/gradient2.png)

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 35
---
    <section class="wrap">
        <div class="card">
          <div class="card-content">
            <div class="card-face gradient1">
              <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
            </div>

            <div class="card-face flipme gradient2">
              <h2>Lapis Sarawak</h2>
              <p>A cake baked in layers to make colourful patterns.</p>
            </div>
          </div>
        </div>
    </section>

--- /code ---

--- /task ---

--- task ---

**Test:** Hover over (or tap) the card in your webpage to see that both gradients have been added. 

<iframe src="https://trinket.io/embed/html/8d08027bea?outputOnly=true" width="400" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---

--- task ---

Add the `rounded` class to each of your card faces to add rounded corners to your card. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 31, 35
---
    <section class="wrap">
        <div class="card">
          <div class="card-content">
            <div class="card-face gradient1 rounded">
              <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
            </div>

            <div class="card-face flipme gradient2 rounded">
              <h2>Lapis Sarawak</h2>
              <p>A cake baked in layers to make colourful patterns.</p>
            </div>
          </div>
        </div>
    </section>

--- /code ---

--- /task ---

--- task ---

**Test:** Hover over (or tap) the card in your webpage to check that both sides of the card have rounded corners. 

<iframe src="https://trinket.io/embed/html/8d3a67a764?outputOnly=true" width="400" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---

--- task ---

The text on the card is vertically aligned to the top. 

![The text side of the card with text aligned to the top.](images/ytop.png)

Add the `ycenter` class to align the text in the centre along the `y` axis. 

![The text side of the card with text aligned to the center verically.](images/ycenter.png)

<mark>Add Mr C's animation here </mark>

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 35
---
    <section class="wrap">
        <div class="card">
          <div class="card-content">
            <div class="card-face gradient1 rounded">
              <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
            </div>

            <div class="card-face flipme gradient2 rounded ycenter">
              <h2>Lapis Sarawak</h2>
              <p>A cake baked in layers to make colourful patterns.</p>
            </div>
          </div>
        </div>
    </section>

--- /code ---

--- /task ---

--- task ---

**Test:** Hover over (or tap) the card in your webpage to check that the text on the second face has been aligned in the centre of the `y` axis. 

<iframe src="https://trinket.io/embed/html/d885c71711?outputOnly=true" width="400" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---



