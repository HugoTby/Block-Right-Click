
# Block Bad Actions



Ce code est en JavaScript et il est utilisé pour bloquer les clics droits ainsi que la touche F12 sur une page Web. La première ligne de code dans la balise HTML <body>, définit une fonction JavaScript qui sera appelée lorsque l'utilisateur clique avec le bouton droit de la souris sur la page. La fonction renvoie "false", ce qui empêche le menu contextuel par défaut de s'afficher.

Le reste du code définit une fonction JavaScript appelée "document.onkeydown", qui est activée lorsque l'utilisateur appuie sur une touche du clavier. L'argument "e" représente l'événement qui déclenche la fonction.

La fonction vérifie ensuite si la touche appuyée est égale à F12 (123), ou si la touche appuyée est "I" en utilisant Ctrl + Shift, ou "J" en utilisant Ctrl + Shift, ou "C" en utilisant Ctrl + Shift, ou "U" en utilisant Ctrl. Si l'une de ces conditions est remplie, la fonction renvoie "false", ce qui empêche l'utilisateur d'accéder au code source de la page ou de copier le contenu de la page en utilisant les raccourcis clavier.

En résumé, ce code est utilisé pour protéger le contenu d'une page Web en bloquant les clics droits et les raccourcis clavier couramment utilisés pour accéder au code source d'une page.




## FAQ

#### Ce code fonctionne-t-il sur MAC OS ?

**Oui**, ce code devrait fonctionner sur Mac ainsi que sur d'autres systèmes d'exploitation tels que Windows et Linux. En général, JavaScript est un langage de programmation qui s'exécute sur le navigateur, et non sur le système d'exploitation, ce qui signifie que le code JavaScript peut fonctionner de manière similaire sur différents systèmes d'exploitation. Cependant, il peut y avoir des différences mineures entre les navigateurs, donc il est toujours bon de tester votre code sur plusieurs navigateurs et systèmes d'exploitation pour vous assurer qu'il fonctionne correctement.


## Auteur(s)

- [Hugo T 🇫🇷](https://www.github.com/HugoTby)


![Logo](https://i0.wp.com/www.jeremysmola.com/wp-content/uploads/2019/04/cropped-logo-javascript-logo-png-transparent-1.png?ssl=1)


## Utilisé par

Ce projet est utilisé par les entreprises suivantes :

- Beta Games France
- Beta Games USA
- Providence1
