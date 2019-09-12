# wu1-layout

I det här report plockade vi ut layout-delarna från Lovecraft berättelsen för att det skulle vara tydligare.

## Filer

Vi jobbar med en standardstruktur.

  projektnamn
    css/main.css
    index.html
  
Alla sökvägar är då relativa i projektet.
Så om du ska komma åt css filen från index.html så blir sökvägen css/main.css.
Mappen först och sedan filnamnet.

## Struktur

Öva på att komma igång snabbt med ett html dokument.
Visual Studio Code hjälper oss med detta, bli vän med att skriva en del av taggens namn och sedan trycka tabb.

Du behöver första skapa en fil med ändelsen .html, spara.

Så i ordning för att skapa grunden för dokumentet.

1. skriv html -> välj :5 -> tabb
2. Flytta markören till inne i body taggen
3. main -> tabb
4. Markören är i main taggen
5. nav -> tabb
6. Flytta markören till efter nav taggen
7. section -> tabb
8. Markören är nu i section taggen, för att lägga till text
9. p -> tabb -> lorem -> tabb

## CSS Fil

Se till att du har skapat en mapp, css och en fil i den, main.css

Innuti head taggen i ditt .html dokuement så skriver du
link och väljer link:css
Sedan skriver du in sökvägen till filen i href="" attributet.

  href="css/main.css"
  
### Stilar

För att skapa en 2 spaltig layout så kan vi skriva följande i main.css

  main {
    width: 80%;
    display: flex;
    margin: 0 auto;
  }
  nav {
    width: 20%;
  }
  section {
    width: 80%;
  }

## GIT

Som med allt annat vill vi spara vårt arbete på GIT.

1. Surfa till github.com
2. Klicka + och välj New repository
3. Döp det till något relevant.
4. Skapa
5. Kopiera den stora klumpen text genom att trycka på iconen.
6. Öppna powershell
7. Navigera till din projektmapp.
8. cd c:\code
9. cd projektnamn
10. Klistra in den stora text-klumpen från git
11. Skriv du fel lösen/user, tryck pil upp och kör om git push -u origin master
12. skriv git add .
13. skriv git commit -m "meddelande"
14. skriv git push

Lycka till!
