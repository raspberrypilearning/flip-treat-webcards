## Style your card

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will add colour gradients, rounded corners and vertical centering to your cards. 
</div>
<div>
<iframe src="https://trinket.io/embed/html/d885c71711?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
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

<iframe src="https://trinket.io/embed/html/8d08027bea?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---

--- task ---

Click on the `style.css` file and find the colour palette near the top of the page.

**Choose:**  The colour gradients use variables from the colour palette. You can choose new colours for:
    + `secondary` and `detail` variables to change the front card face
    + `tertiary` and `detail2` variables to change the back card face

**Tip:** You might also need to change `onsecondary` and `ontertiary` colours so your text stands out on the new colour gradients. 

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 5-6, 9-10, 12-13
---
  /* Set up colour palette and fonts using variables */

:root {
  --primary: #ffffff;
  --secondary: #aa076b;
  --tertiary: #43cea2; /*#3a96dd;*/
  --page: #ffffff;
  --onprimary: #664300;
  --onsecondary: #664300;
  --ontertiary: #ffffff;
  --onpage: #000000;
  --detail: #ffb88c;
  --detail2: #185a9d;

--- /code ---

--- /task ---

--- task ---

Find the `gradient1` and `gradient2` classes.

**Choose:** update the gradient to the direction you like best try `top`, `right` or `bottom left`.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 240
line_highlights: 242, 251
---
  .gradient1 {
  background-image: linear-gradient(
    to bottom,
    var(--secondary),
    var(--detail)
  );
  color: var(--onsecondary);
}

.gradient2 {
  background-image: linear-gradient(
    to bottom right,
    var(--tertiary),
    var(--detail2)
  );
  color: var(--ontertiary);
}

--- /code ---

--- /task ---


--- task ---

Click on `index.html`. Add the `rounded` class to each of your card faces to add rounded corners to your card. 

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

<iframe src="https://trinket.io/embed/html/8d3a67a764?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

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

<iframe src="https://trinket.io/embed/html/d885c71711?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

--- /task ---



