## A vos marques&nbsp;!

Commençons par afficher une image après un délai d'une durée aléatoire.

+ Va sur <a href="http://jumpto.cc/pxt-new" target="_blank">jumpto.cc/pxt-new</a> et démarre un nouveau projet dans l'éditeur PXT. Appelle ton  ouveau projet 'Reaction'. 

+ Avant d'afficher une image, le jeu doit attendre pendant une durée aléatoire.

Place un bloc `pause` dans le bloc `toujours` et change la valeur de pause en mettant 1000 ms&nbsp;:

![screenshot](images/reaction-pause.png)

+ Ajoute un autre bloc `pause` et place un bloc `choisir au hasard` dans la valeur du bloc `pause` et met sa valeur à 4000&nbsp;:

![screenshot](images/reaction-pause-random.png)

Souviens toi que 1000 ms font 1 seconde, donc il y aura une pause d'au moins une seconde et d'un maximum de 5 secondes (1000 + 4000 ms).

Tu peux faire changer les valeurs '1000' et '4000' modifier le minimum et le maximum de pause si tu le souhaites.

+ Après l'attente, le jeu doit montrer une image pour que les joueurs sachent qu'ils doivent appuyer sur leur bouton.

![screenshot](images/reaction-image.png)

+ Clique 'lancer' pour tester ton projet. Tu devrais voir apparaître une image après un délai aléatoire.

+ Ajoute du code à la fin de la boucle `toujours` pour afficher ton image pendant 1 seconde puis effacer l'affichage.

![screenshot](images/reaction-clear.png)

+ Teste ton projet. Tu doit voir ton image apparaître aléatoirement puis disparaître.
