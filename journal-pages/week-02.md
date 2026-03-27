<h1>Week 02</h1>
<p>DES240 Making Journal</p>

<h2>Introduction</h2>
<p>
This week I learned the basics of p5.js. I focused on interactivity.
The goal was to understand how code can respond to user input.
I used mouse movement, mouse clicks, and keyboard input.
I also started building my Making Journal as a website.
</p>

<h2>Interactive Sketch</h2>
<p>
I made an interactive bubble sketch.
The bubbles move when the user moves the mouse.
The bubbles increase when the user clicks.
The user can also press keys to control the sketch.
</p>

<p>
Instructions: Move the mouse, click to add bubbles, press C to clear, press S to save.
</p>

<p>
<a href="https://editor.p5js.org/lyin032/embed/Va-tU3Vne" target="_blank">
Open my p5.js sketch
</a>
</p>

<h2>Process</h2>
<p>
I started with basic p5.js functions.
I used setup() to create the canvas.
I used draw() to update the screen.
</p>

<p>
Then I tested simple shapes with ellipse().
At first, the result was very simple.
</p>

<p>
After that, I added mouse interaction.
I used mouseX and mouseY to control the position.
The circles followed the cursor.
</p>

<p>
Then I added mousePressed().
The sketch created more bubbles when I clicked.
I also used keyPressed() to clear the screen.
</p>

<p>
I tested the sketch a few times.
Sometimes the screen looked messy.
I changed the size and speed to improve it.
</p>

![alt text](../assets/week-02/Screenshot%202026-03-20%20at%203.44.56 PM.png)
<p>Early test with simple circles.</p>

![alt text](../assets/week-02/Screenshot%202026-03-21%20at%207.28.24 AM.png)

![alt text](../assets/week-02/Screenshot%202026-03-21%20at%207.28.31 AM.png)

![alt text](../assets/week-02/Screenshot%202026-03-21%20at%207.28.45 AM.png)
<p>Final result of the sketch.</p>

<h2>Ideas</h2>
<p>
I chose bubbles because they are simple.
They are easy to control.
They also create interesting movement.
</p>

<p>
I did not try to make a complex system.
I focused on basic interaction.
I wanted to understand how the code works.
</p>

<h2>Tools and Techniques</h2>
<p>
I used p5.js as the main tool.
It helped me test ideas quickly.
</p>

<ul>
<li>setup()</li>
<li>draw()</li>
<li>ellipse()</li>
<li>random()</li>
<li>mouseX and mouseY</li>
<li>mousePressed()</li>
<li>keyPressed()</li>
</ul>

<h2>Code Snippet</h2>
<p>
function setup() { createCanvas(800, 500); }
</p>
<p>
function draw() { ellipse(mouseX, mouseY, 50); }
</p>

<h2>Challenges</h2>
<p>
The sketch had too many bubbles at first.
The screen looked messy.
</p>

<p>
I fixed this by limiting the number of bubbles.
I also adjusted the size and speed.
</p>

<h2>Reflection</h2>
<p>
This experiment helped me understand interactivity.
I learned how user input changes the visual result.
</p>

<p>
At the beginning, I felt unsure about the code.
After testing, I understood it better.
</p>

<p>
I think p5.js is useful for testing ideas.
It is fast and easy to use.
</p>

<h2>Next Steps</h2>
<p>
Next, I want to try more interaction.
I want to add sound.
I also want to change colors over time.
</p>s