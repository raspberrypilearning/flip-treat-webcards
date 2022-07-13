## Create your card

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step you will create an infocard for a tasty treat with an image, heading and text.
</div>
<div>
<iframe src="https://trinket.io/embed/html/0ea70b025f?outputOnly=true" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
</div>

--- task ---

Open the [Flip treat webcards starter project](https://trinket.io/library/trinkets/79387829ef){:target="_blank"}.

--- /task ---

--- task ---

The `<title>` tag within your code is used to display text in title bar of your web browser and should be relevant to your page.

The `<title>` can be found in the `<head>` element at the top of your `index.html` file.

**Change** your title to 'Treat flip cards':

--- code ---
---
language: html filename: index.html line_numbers: true line_number_start: 1
line_highlights: 11
---

  <!-- This part is for extra information the browser needs to load the page correctly--> 

<head>
  <meta charset="utf-8" />
  </p> 
  
  <pre><code>&lt;!-- Don't shrink the page on mobile --&gt;
&lt;meta name="viewport" content="width=device-width, initial-scale=1.0" /&gt;

&lt;!-- Appears on the web browser tab and search results --&gt;
&lt;title&gt;Treat flip cards&lt;/title&gt;
</code></pre>
  
  <p spaces-before="0">
    --- /code ---
  </p>
  
  <p spaces-before="0">
    --- /task ---
  </p>
  
  <p spaces-before="0">
    --- task ---
  </p>
  
  <p spaces-before="0">
    Click on the small triangle next to the 
    
    <head>
      tag to collapse the 
      
      <head>
        . </p> 
        
        <p spaces-before="0">
          Collapsing parts of the code you don't need to focus on helps to make your code easier to read.
        </p>
        
        <p spaces-before="0">
          --- /task ---
        </p>
        
        <p spaces-before="0">
          --- task ---
        </p>
        
        <p spaces-before="0">
          Add a <code>&lt;section&gt;</code> to the <code>&lt;main&gt;</code> part of your page, give it the <code>wrap</code> class to make your website responsive:
        </p>
        
        <p spaces-before="0">
          --- code ---
        </p>
<hr />
        
        <p spaces-before="0">
          language: html filename: index.html line_numbers: true line_number_start: 25
        </p>
<h2 spaces-before="0">
  line_highlights: 28-30
</h2>

<p spaces-before="0">
  </p> 
  
  <pre><code>&lt;main&gt;
  &lt;section class="wrap"&gt;

  &lt;/section&gt;
</code></pre>
  
  <p spaces-before="0">
    --- /code ---
  </p>
  
  <p spaces-before="0">
    --- /task ---
  </p>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Graphic designers**</span> are people that create engaging physical or digital visual content. Some examples of graphic design work include company logos, product packaging and website banner design. Our graphic designer Kate has made some images of treats from around the world for you to use in your project. 

![A collage of treats images for use in the project](images/treats.png)
</p>

  
  <p spaces-before="0">
    The <code>&lt;div&gt;</code> element is used to group other elements. They are used when there isn't a more appropriate tag such as <code>&lt;section&gt;</code> and <code>&lt;blockquote&gt;</code>.
  </p>
  
  <p spaces-before="0">
    --- task ---
  </p>
  
  <p spaces-before="0">
    Create a <code>&lt;div&gt;</code> that contains an image. The first image is <code>LapisSarawak02.png</code> a sweet treat from Malaysia:
  </p>
  
  <p spaces-before="0">
    <img src="images/LapisSarawak02.png" alt="A cartoon style graphic of Lapis Sarawak, a colourful, geometric cake." />
  </p>
  
  <p spaces-before="0">
    --- code ---
  </p>
<hr />
  
  <p spaces-before="0">
    language: html filename: index.html line_numbers: true line_number_start: 28
  </p>
<h2 spaces-before="0">
  line_highlights: 29-31
</h2>

<section class="wrap">
  <div>
    <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
  </div>
</section>

<p spaces-before="0">
  --- /code ---
</p>

<p spaces-before="0">
  --- /task ---
</p>

<p spaces-before="0">
  --- task ---
</p>

<p spaces-before="0">
  Add another <code>&lt;div&gt;</code> with a heading and short paragraph about Lapis Sarawak:
</p>

<p spaces-before="0">
  Heading: <code>Lapis Sarawak</code> Paragraph: <code>A cake baked in layers to make colourful patterns.</code>
</p>

<p spaces-before="0">
  --- code ---
</p>
<hr />

<p spaces-before="0">
  language: html filename: index.html line_numbers: true line_number_start: 29
</p>
<h2 spaces-before="0">
  line_highlights: 33-36
</h2>

<section class="wrap">
        <div>
          <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
        </div>
        <div>
          <h2>Lapis Sarawak</h2>
          <p>A cake baked in layers to make colourful patterns.</p>
        </div>
</section>

<p spaces-before="0">
  --- /code ---
</p>

<p spaces-before="0">
  --- /task ---
</p>

<p spaces-before="0">
  --- task ---
</p>

<p spaces-before="0">
  <strong x-id="1">Test:</strong> View your webpage. You should be able to see an image of a Lapis Sarawak and your text describing it.
</p>

<div>
<iframe src="https://trinket.io/embed/html/0ea70b025f?outputOnly=true" width="500" height="450" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

<p spaces-before="0">
  --- /task ---
</p>
