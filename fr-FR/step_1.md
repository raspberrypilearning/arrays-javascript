Un **tableau** est une collection de données en programmation.

Imagine une série de variables toutes liées entre elles, les composants individuels sont appelés **éléments**.

Les éléments sont accessibles à l’aide d’un **index**.

Le premier élément du tableau correspond à l'index 0.

```
 ___________   ___________   ___________  
| Élément 1 | | Élément 2 | | Élément 3 |
 ‾‾‾‾‾‾‾‾‾‾‾   ‾‾‾‾‾‾‾‾‾‾    ‾‾‾‾‾‾‾‾‾‾‾
|  Index 0  | |  Index 1  | |  Index 2  |
```

Tu as utilisé un tableau dans \*\*Personnage de Comics \*\* pour le slider Hero.

Les crochets `[]` sont utilisés pour faire référence à la position de l'élément dans la liste.

## --- code ---

language: js
filename: scripts.js
----------------------------------------------------

heroSlides[0].classList.remove("active");

\--- /code ---
