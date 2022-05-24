## Add gradients

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will add colour gradients to your cards. You will also add rounded corners to make them look more like cards and vertical centering so that content appears in the middle of the card. 
</div>
<div>
Image, gif or video showing what they will achieve by the end of the step. ![](images/image.png){:width="300px"}
</div>
</div>

--- task ---

Another step of tasks to complete. 

--- /task ---

--- task ---

Add the `gradient1` class to the card front and the `gradient2` class to the back of the card. 

--- /task ---

--- task ---

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 29
line_highlights: 33-36
---

    <section class="wrap">
        <div class="card">
          <div class="card-inner">
            <div class="card-front rounded gradient1 ycenter">
              <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
            </div>

            <div class="card-back flipme rounded gradient2 ycenter">
              <h2>Lapis Sarawak</h2>
              <p>A cake baked in layers to make colourful patterns.</p>
            </div>
          </div>
        </div>
    </section>

--- /code ---

--- /task ---

