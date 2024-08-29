# AWS Serverless Framework Bootcamp

## Innan du sätter igång

**Samtliga övningar kräver att du har installerat Serverless Framework på din dator. Det gör du genom nedanstående kommando i valfri terminal. Notera att Mac-användare antagligen måste lägga till "sudo" framför kommandot för att kunna köra det.**

```
npm i serverless -g
```

**Ange följande kommando för att verifiera installationen:**

```
serverless -v 
```

## Övning 1 - Where it's @

Du ska i denna övning göra ett API för Where it's @ där du kan "köpa" biljetter till ett evenemang. Tips! Du kan använda *events.json* ovan och spara datan i en variabel i dina Lambda-funktioner. Du ska göra övningen med `serverless framework` och använda dig av API Gateway samt Lambda-funktioner.

### Funktionalitet

Det ska finnas endpoints för följande:
* Det ska gå att kunna hämta alla evenemang.
* Kunna beställa biljett för ett evenemang och få tillbaka information om det evenemanget samt biljettnummer.
* När man beställt en biljett för ett evenemang ska en bekräftelse returneras. 

#### Bonus!
* På endpointen ```/admin/events``` skall man kunna lägga till ett nytt event i listan.
* När man gjort sin beställning skall alla biljetter returneras. Då skall alla biljetter vara på samma sektion, och alla i sällskapet ska sitta bredvid varandra.


### Skiss
För att få en överblick över vad varje API-endpoint ska göra så finns det en Figmaskiss och utgå ifrån. 
Du kan använda den för att se vad frontend ska visa och vad som kan behövas skickas med till backend. Du ska alltså inte bygga en frontend utan skissen är som sagt mer hjälp för att få en överblick.

Skissen hittar du [här](https://www.figma.com/file/y8IN8UsL5Jteu59XucldVY/Where-its-%40---S%C3%A4ker-kommunikation).

## Övning 2 - Valfritt

Du får här helt fria tyglar att skapa vad du vill där du använder dig av `Serverless Framework` för att bygga och deploya ditt egna API till `AWS`. Kanske vill du bygga ditt eget film-API, ett pokemon-API, eller en tjänst som krypterar och dekrypterar lösenord? Möjligheterna är oändliga.
