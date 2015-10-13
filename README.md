# less-voor-beginners
##Less oefenen

Less is een mooi tool om je css nog beter te structuren. oké maar waarvoor heb ik dit nodig? Nou stel je wil een class of ID veranderen in je CSS. Dan kan je naar je class toegaan en hem veranderen maar met Less kan je dit nog handiger doen. Met less pas je alleen even de gene aan wat graag wil aanpassen en de rest gaat van zelf. Zie hier onder voor een voorbeeld:

Less
```
// Declaring variables
@border-width: 1px;
@red: #842210;

// Using variables
div#header {
    border: @border-width solid @red;
} 
```
CSS
```
div#header {
  border: 1px solid #842210;
}
```
##PREPROS
Prepros is erg handig om je less te compilen. ik zal je vertellen hoe je het moet installeren en gebruiken.

Als eerste gaan naar deze link: [prepros](https://prepros.io/). (prepros standaard installeren)
Als je dat gedaan hebt sleep je je folder (bijvoorbeeld Less-voor-beginners) naar prepros. Hij zal nu aangeven dat je een aantal bestanden hebt.
Nu is het gewoon code kloppen en crtl+S(opslaan) en Prepros doet zijn werk. **SUCCES!**
