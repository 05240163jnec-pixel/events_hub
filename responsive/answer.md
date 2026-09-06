
Quick Check Q1:  You change the footer colour in styles.css. How many pages update? What if the same 
colour was only set with an inline style on index.html? 
ANS: Changing the footer colour in styles.css updates all pages linked to that stylesheet. If it’s set with an inline style in index.html, then only that page updates.

Quick Check Q2:  Which is more specific: h1 or #welcome? If both set color, which wins? Write a one-line 
proof from your page.  
ANS: #welcome is more specific than h1, so #welcome wins if both set a color.
Proof:
html
<h1 id="welcome">Hello World</h1>

Quick Check Q3:  Convert #0369a1 into an approximate rgb(...) value (you may use a colour picker). Why 
do designers often prefer hex in stylesheets?  
ANS: #0369a1 is approximately rgb(3, 105, 161). Designers often prefer hex codes because they are shorter, easier to copy, and widely standardized across CSS and design tools.

Quick Check Q4:  Set a nav link to display: none, then to visibility: hidden. What is the difference in the 
layout?   
ANS: display: none removes the nav link completely from the layout, so the space it occupied disappears. visibility: hidden makes the nav link invisible but still keeps its space in the layout.
So the difference is: display: none collapses the element, visibility: hidden keeps the empty gap.

Quick Check Q5:  In your wireframe, how many event cards appear side-by-side at phone width? At 
desktop width?   
ANS: At phone width, usually only one event card appears side by side (stacked vertically). At desktop width, typically three event cards appear side by side in a row.
So: Phone → 1 card per row; Desktop → 3 cards per row.

Quick Check Q6:  Why must styles.css be linked AFTER the Bootstrap CSS file? What happens if you reverse 
the order and both set h1 colour?  
ANS: You must link styles.css after Bootstrap’s CSS so that your custom rules override Bootstrap’s defaults.
If you reverse the order and both set h1 colour, then Bootstrap’s rule wins because it loads later and takes precedence.
So: Last stylesheet linked controls the final style.

