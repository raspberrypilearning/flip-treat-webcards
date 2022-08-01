## Reflection

Well done, you have learned a lot! Now it's time to reflect &mdash; reflecting is an important part of learning because it helps make new connections in your brain.

Answer the three questions below to reflect on what you've learned.

After each question, press submit. You will be guided towards the correct answer. You can do this activity as many times as you want to.

Have fun!

--- question ---

---
legend: Question 1 of 3
---

In this project, you made a card that flipped over. The `flipme` class rotates a HTML element when the page is loaded.

--- code ---
---
language: css filename: animation.css
line_numbers: false
---

.flipme { transform: rotateY(180deg); }

--- /code ---

Where should the `flipme` class be applied?

--- choices ---

- ( ) The `<div>` for the front of the card

  --- feedback ---

  Not quite. This would flip the front of the card over when you loaded the page.

  --- /feedback ---

- (x) The `<div>` for the back of the card

  --- feedback ---

  That's correct. You need the back of the card to be rotated 180 degrees when the page is loaded. This means that when the full card is flipped, when you hover or tap the card, the back is rotated to face the front.

  --- /feedback ---

- ( ) Both the `<div>` for the front and back of the card

  --- feedback ---

  Not quite. This would mean that the front and back of the card were flipped over when you loaded the page.

  --- /feedback ---

--- /choices ---

--- /question ---
