<h1>MIT xPRO Pac-Man Movement Exercise </h1>

<h2>
Project Description
</h2>
<p>
This code builds a feature of the Pac-Man game, which displays and moves PacMan from one side of the screen to the other and back within a rectangular box area on the page.
</p>

<h2>
Project Details
</h2>
<p>
The application includes
</p>
<ol>
    <li> an array of 4 Pacman images,  2 looking right with open and closed mouth and 2 facing the opposite direction </li>
    <li> uses setInterval to call a function Run() </li>
    <li> function Run() sets the right Pacman image, sets direction to left to right and moves the image by 20px.  It then calls checkPageBounds to see if direction should be changed. </li>
    <li> function checkPageBounds(direction, imgWidth, pos, pageWidth) checks where the Pacman image is in relation to the left or right page border and changes direction when reaches the pageWidth. </li>
</ol>

<h2>
How To Install and Run the Project
</h2>
<ol>
    <li> Move the pacman.js and index.html into a project directory  </li>
    <li> Create a subdirectory called images and move the 4 Packman images here </li>
    <li> Run the index.html from your browser </li>
</ol>
<h2>
Project Credits
</h2>
<p>
The starter code set originated from MIT xPRO full stack development course
</p>
