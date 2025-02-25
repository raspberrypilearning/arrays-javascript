Een **array** is een verzameling gegevens in programmeren.

Stel je een reeks variabelen voor die allemaal met elkaar verbonden zijn. De individuele items worden **elementen** genoemd.

Elementen worden benaderd met behulp van een **index**.

Het eerste element in de array bevindt zich op index 0.

     ___________   ___________   ___________  
    | Element 1 | | Element 2 | | Element 3 |
     ‾‾‾‾‾‾‾‾‾‾‾   ‾‾‾‾‾‾‾‾‾‾    ‾‾‾‾‾‾‾‾‾‾‾
    |  Index 0  | |  Index 1  | |  Index 2  |

Je hebt dit gebruikt in het **Stripfiguur** project voor de Hero slider.

Vierkante haakjes `[]` worden gebruikt om te verwijzen naar de positie van het element in de lijst.

--- code ---
---
language: js
filename: scripts.js
---
  
heroSlides[0].classList.remove("active");

--- /code ---