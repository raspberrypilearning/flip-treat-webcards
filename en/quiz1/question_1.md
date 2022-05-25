## Reflection

Well done, you have learned a lot! Now it's time to reflect - reflecting is an important part of learning because it helps make new connections in your brain.

Answer the three questions below to reflect on what you've learned.

After each question, press submit. You will be guided towards the correct answer. You can do this activity as many times as you want to.

Have fun!

--- question ---

---
legend: Question 1 of 3
---

In this project, you made cards that flip over. The flipme class rotates an HTML element when the page is loaded. 

--- code ---
---
language: html
filename: index.htmlline_numbers: false
---

.flipme {
  transform: rotateY(180deg);
}

--- /code ---

Should the `flipme` class be applied to:

--- choices ---

- ( ) The `<div>` for the front of the card

  --- feedback ---

  Not quite. This would flip the front of the card over when you loaded the page. 

  --- /feedback ---

- (x) The `<div>` for the back of the card

  --- feedback ---

  That's correct. You need the back of the card to be rotated 180 degrees when the page is loaded so that when the full card is flipped, on hover or tap, the back will be rotated to face to the front. 

  --- /feedback ---

- ( ) Both the `<div>` for the front and back of the card

  --- feedback ---

Not quite. This would mean that the front and back of the card were flipped over when you load the page. 

  --- /feedback ---

--- /choices ---

--- /question ---
