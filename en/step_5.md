## Choose your font

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
You will now use Google's online font library to import a decorative font into your webpage. 
</div>
<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/flip-treat-webcards-step-5" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Web designers**</span> need to consider how a website looks and how it reflects the brand of the company, product, or person that they design the website for. Standard web safe fonts are recommended for the majority of text on a webpage. When a designer wants to create an impact, a more unique font can be used. Designers can import <span style="color: #0faeb0">**web fonts**</span> from an online font library to make their website attract people's attention.</p>

[[[web-fonts]]]

Google has a free online font library with over 1500 fonts to choose from. The site allows you to use your own sample text to browse different fonts and help you find the right font. Google then gives you the **HTML** that you need to **import** the font into your website. 

--- task ---

Open [fonts.google.com](https://fonts.google.com/){:target="_blank"}. The link will open in a new tab. 

--- /task ---

--- task ---

Type some sample text in the **Preview** box. The example uses the treat name in this project, `Lapis Sarawak`.

![The Google Fonts search page. The words 'Lapis Sarawak' have been entered in the Preview box.](images/custom.png)

**Notice** that the examples show your sample text. You can see how your words will look in all of the fonts available. 

--- /task ---

There are many different search filters to use. You can search by language, or different font properties. 

--- task ---

Enter the font name `Bangers` into the 'search fonts' box. 

!['Bangers' has been typed into the search box.](images/bangers.png)

**Notice** that you can now see an example of the Bangers font that has been applied to the sample text. 

--- /task ---

--- task ---

Click on the Bangers card that has appeared in the search results.

![The Bangers card.](images/bangers-card.PNG)

--- /task ---

--- task ---

Click on the 'Select' link (our example shows 'Select Regular 400').

![A screenshot highlights the 'Select' link.](images/select-style.png)

**Notice** that a pane pops in from the side. The pane gives you the code that you need.

--- /task ---

--- task ---

Click the copy icon to copy the HTML code.

![The HTML to copy.](images/html.png)

--- /task ---

--- task ---

Expand the `<head>` section of `index.html`, if it is collapsed. 

Find the comment in your `index.html` document that says `<!-- Import fonts from Google -->`.

Paste the HTML code that you have just copied below the comment.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 15
line_highlights: 16-18
---
  <!-- Import fonts from Google -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Bangers&display=swap" rel="stylesheet">

--- /code ---

--- /task ---

You have now imported the fonts that you need from the Google Fonts library. Next, add in the correct CSS so that the web browser knows when to use this font. 

--- task ---

Go to your `default.css` file and find the `header-font` and `title-font` variables. 

**Replace** the current font `Verdana` with `Bangers`. 

--- code ---
---
language: css
filename: default.css
line_numbers: true
line_number_start: 15
line_highlights: 16-17
---
  --body-font: 1.1rem Verdana, sans-serif;
  --header-font: lighter 3rem Bangers, cursive;
  --title-font: lighter 2rem Bangers, cursive;

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

Hover over (or tap) your flip card in the preview pane. You should see your new font applied to the heading of the back of the card.

<div>
<iframe src="https://editor.raspberrypi.org/en/embed/viewer/flip-treat-webcards-step-5" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>

--- /task ---

--- task ---

**Choose:** To choose your own font, go back to [fonts.google.com](https://fonts.google.com/){:target="_blank"}.

**Remove** the Bangers style in Google Fonts before you select your new font. 

**Tip** Don't forget to update your `default.css` file to include the new font name.

--- /task ---

--- collapse ---

---
title: Completed project
---

You can view the [completed project here](https://editor.raspberrypi.org/en/projects/flip-treat-webcards-step-5){:target="_blank"}.

--- /collapse ---
