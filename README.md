# less-voor-beginners
Less oefenen

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
