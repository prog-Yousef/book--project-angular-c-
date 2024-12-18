
 
 ### Krav:

- Implementera en webbapplikation med en sida som visar en lista över alla böcker.
- Skapa en startsida med en knapp för att lägga till en ny bok.
- Om du klickar på knappen "Lägg till ny bok" bör användaren omdirigeras till ett formulär där de kan ange information om en ny bok (t.ex. titel, författare, publiceringsdatum).
- Efter att ha skickat in formuläret ska användaren omdirigeras tillbaka till startsidan, där de kan se den nya boken som lagts till i listan.
- Varje bok i listan bör ha en "Redigera"-knapp som tar användaren till ett formulär där de kan redigera detaljerna i boken.
- Efter att ha skickat in formuläret ska användaren omdirigeras tillbaka till startsidan, där de kan se de uppdaterade bokdetaljerna i listan.
- Varje bok i listan bör ha en "Radera"-knapp som låter användaren ta bort boken.
- Efter att ha tagit bort en bok bör användaren se boken borttagen från listan.

### Tokenhantering:

- Implementera användarautentisering med JWT (JSON Web Tokens).
- Skapa en enkel inloggningssida där användare kan ange sina referenser (t.ex. användarnamn och lösenord).
- Efter lyckad inloggning bör back-end generera en token och skicka tillbaka den till front-end.
- Front-end bör lagra token säkert (t.ex. i lokal lagring eller en cookie) och använda den för efterföljande API-förfrågningar till back-end.
- Implementera token-validering på back-end för att säkerställa att endast autentiserade användare kan komma åt CRUD-operationerna.

### Mina citatsida:

- Skapa en separat vy som heter "Mina citat".
- Visa listan på 5 citat du gillar.
- Det ska finnas en meny så att man kan gå mellan bokvyn och citatvyn.

### Responsiv designtestning:

- Se till att applikationens layout och komponenter smidigt anpassar sig till olika skärmstorlekar, inklusive stationära datorer, surfplattor och mobila enheter.
- Testa applikationen genom att ändra storlek på webbläsarfönstret och verifiera att alla element justeras på rätt sätt.
- Kontrollera att navigeringsmenyer kollapsar till en responsiv mobilmeny på mindre skärmar.
- Verifiera att formulärfält, knappar och andra UI-element bibehåller korrekt avstånd och justering över olika visningsportar.
- Testa applikationen på olika enheter (t.ex. smartphones, surfplattor) och webbläsare för att säkerställa konsekvent beteende.

### Bootstrap och Font Awesome:

- Använd Bootstrap för att skapa en lyhörd och visuellt tilltalande layout för applikationen.
- Använd Bootstrap-klasser för att utforma knappar, formulär och andra UI-komponenter.
- Inkludera Font Awesome-ikoner för att förbättra programmets visuella element.
- Verifiera att Font Awesome-ikonerna visas korrekt och används korrekt i hela programmet.

### Ytterligare utmaning:

- Implementera en knapp som gör att användaren kan växla mellan ljusa och mörka UX-design för applikationen.
