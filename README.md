# Min första webbplats
Webbplatsen innehåller en kort beskrivning om mig själv och varför jag vill bli en webbutvecklare, mina intressen samt en kontaktsida med ett kontaktformulär för att nå mig. 

## Tekniker
Projektet är byggt med:
-HTML 
-CSS

## Kontakt 
Ni kan nå mig på mail:
elha2612@student.miun.se

## Länkar till publicerade versionerna:
[Kolla in min webbplats på Github!](https://github.com/elha99/Min-webbplats.git),  
[Webbplatsen finns även på Netlify](https://elha99-webbplats.netlify.app/)

## Frågor om git
1. **Vad är skillnaden mellan git add och git commit?**  
Genom git add läggs ändringarna i staging area medan git commit gör en permanent sparfil i git-repot. Fördelen med git add är att man lägger till filer man är intresserad av och eventuellt ska ha i sin sparfil medan man fortfarande jobbar och ändrar i den. När man är klar med ett stycke eller en del av filen kan man git commit för att ladda upp den till git-repot och på det viset göra större sparfiler med beskrivningar på vad som har gjorts istället för att varje liten ändring ska laddas upp permanent, på det sättet
är det också enklare för andra ifall man jobbar flera stycken på ett projekt att följa vad som har gjorts.

2. **Varför använder man branches istället för att jobba direkt i main?**  
Fördelen med branches är att om man har lagt till något till koden och det inte fungerar med koden så är det bara att ta bort branchen eller fortsätta jobba på den utan att störa övriga delar i filen, medan ifall man skulle jobba direkt i main så skulle hela koden förstöras ifall något skulle gå snett och skulle det vara ett stort projekt så är det inte så enkelt att bara ta bort ändringarna. Med hjälp av branches har man alltid en backup sparat, och mergar bara med main när man vet att koden fungerar bra. 

3. **Vad händer rent praktiskt när man gör en merge?**  
Man slår ihop ändringarna som man gjort i en branch till main, alltså originalversionen. Detta sker först efter man testat koden i branchen och den fungerar som den ska.

4. **Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?**  
Github är ett digitalt arkiv, med hjälp av den kan flera jobba samtidigt på samma projekt eftersom projektet sparas digitalt, samt att det går att spara lokalt på olika enheter ifall man äger flera datorer. Genom att publicera på Netlify gör man det mer tillgängligt för andra personer att se. Det brukar vara slutprodukten man publicerar på Netlify medan på Github har man koden redan från start. 

5. **Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?**  
Genom att skapa en textfil med namnet .gitignore i rotmappen, kan man flytta filer och mappar man vill exkludera. Det kan till exempel handla om filer med känslig information eller onödiga filer som inte behövs för att koden ska fungera som vanligt.
