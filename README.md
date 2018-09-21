# character-counter.js
Script that counts characters of any field you can write on in HTML.
<h1>Character counter for text fields in HTML</h1>
Character-counter.js is a script that counts the characters in a text-input field. By default, character-counter.js looks for a text field
with "id = messagebody" and appends the counter behind it.
Also, by default, uses CSS variable 'color' from body for the color of the counter.
<ul>
<li>Character-counter.js supports copy and paste of text</li>
</ul>


<h2>HOW TO USE</h2>

Character-counter.js is designed for a specific case, but you can change it to your needs easely.
In the code case, it counts the characters from a textbox with "id=messagebody" and a not null maxlength. It uses the maxlength to create the counter, then removes it (line 9).
It also uses default body color to paint the counter.

To change ID (or way to search for input field), go to line 6.
To change CSS, go to lines 19-23.

This code supports paste of text.
