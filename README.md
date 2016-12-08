<html>
<head>
<i>This is a Jeopardy-style game that teaches the basics of financial literacy to adolescence.</i>
</head>
<body>
Materials: 

- Makey Makey Standard Kit(2)
- Allegator clips (<i>usually included in the Makey Makey Standard Kit</i>)
- Wires (<i>usually included in the Makey Makey Boards</i>) 
- Computer 
- Brackets (or any other progamming software)

- Canvas (preferrably 8" by 14", but any size larger can work)
- Scissors
- Play-Doh
- Magnetic stickers 
- Card stock 
<br>
INSTRUCTIONS: 
1. Folder Setup
<ul>

    <li> i. Create a folder that includes the following documents: "index.html", "main.css", "main.js" </li>
    <li> ii. Within that folder, create another folder and label it as "questions" (this is where you will place all the questions - each question page will be a seperate html file. ) </li>

Your folder setup should look like this: <img src="folder_setup.png">
</ul>
2. Coding the Game
<ul>index.html: is the main page that will include 4 categories and 4 buttons under each category that will link to the respective question. When coding the page, questions are categorized in 4 different div classes (each div class represents a category), and these divs are all inside one div class ("questions"). 
    <li> <img src="indexhtml.png"></li>
<ul> main.css: Now that you have set up your index.html, style your buttons using css. Since we have already placed questions inside div containers, setting up buttons into rows and columns should be simple, using flexbox. Here is how I set up mine <img src="maincss"></ul>
</ul>

</body>
</html>

