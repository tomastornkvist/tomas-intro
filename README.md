# Tomas verktygsuppgift

Den här uppgiften visar att jag kan hantera **filsystemet**, **terminalen**, ***Visual Studio Code*** och ***GIT/Github***.

## Använda GIT kommandon
* **git init** Skapar ett repository i mappen jag är i.
* **git add** GIT add lägger till filer till staging area, där de väntar på ***commit***. **git add .** betyder att alla filer i nuvarande mapp läggs till.
* **git status** visar nya och ändrade filer i staging area och som behöver läggas till om de ska komma med i nästa ***commit***.
* **git commit** sparar alla ändringar i staging area till en ny commit i mitt repository. **git commit -m "message"** skickar med commit-meddelandet direkt, annars poppar det upp en editor där man kan skriva meddelandet istället. Första ***commit*** efter ***git init*** är en initial ***commit***, som blir startpunkten för repots historik.
* **git log** visar vilka ***commit***s jag har gjort i mitt repository.
* **git remote** hanterar repository på en server, som t.ex. Github eller en LAN-lokal eller egen online server. **git remote add** lägger kopplar mitt lokala repository till ett repository på en server, Github för den här uppgiften.
* **git push** kopierar datan i mitt repository till mitt remote repository. Om mitt remote repository är tomt, kopieras all data, annars kopieras alla nya ***commit***s, d.v.s. de ändringar som är gjorda sen senaste ***commit***en på mitt remote repository.
