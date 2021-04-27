Här sprar du alla dokumentationsfiler. Skisser på Gui, grafik, flödesdiagram

Idé:
En form av singleplayer version av battleship.
![Battleship_example](https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Battleship_game_board.svg/800px-Battleship_game_board.svg.png)
(bilden tagen från wikipedia)  
Spelet går ut på att helt enkelt skjuta ner alla skepp.  
Skeppen är från början osynliga och delar av ett skepp blir synligt när man träffar den.  
Spelet är gjort i en grid och man har en specifik mängd med skott innan man förlorar.  
På kanten får man se mängden skepp kvar, hur stora/långa dom är, och ifall man sänkt dom.  

Planering:
Börja med att skapa själva griden som man spelar på. Kanske dela in allting i rektanglar som båtarna ligger i.  
Tanken är att själva griden bara är en stor fyrkant sedan har jag en lista med alla individuella fyrkanter.  
När man "skjuter" på en fyrkant kommer spelet kolla musens nuvarande position och kolla om en båt ligger i det området.  
