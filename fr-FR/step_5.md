## Attente du gagnant

Ajoute du code pour attendre jusqu'à ce qu'un bouton soit appuyé.

+ Après avoir affiché une image, tu as besoin d'attendre jusqu'à ce que quelqu'un appuie sur son bouton.

Une autre façon de le dire serait que tu dois attendre aussi longtemps que le bouton A __et__ le bouton B n'ont __pas__ été appuyés.

Pour se faire, ajoute une boucle `lorsque` depuis la section 'Contrôle'. La boucle `lorsque` doit être ajoutée juste après le bloc `montrer Leds`.

![screenshot](images/reaction-while.png)

+ Place un `et` de 'Logique' dans ton bloc `lorsque`&nbsp;:

![screenshot](images/reaction-and.png)

+ Place un `pas` de 'Logique' dans la partie gauche de ton `et`&nbsp;:

![screenshot](images/reaction-not.png)

+ Place un bloc `bouton A est pressé` de 'Entrées' après le `pas`&nbsp;:

![screenshot](images/reaction-button-a.png)

+ Répète les 2 étapes précédentes et ajoute un `pas bouton B est pressé` dans la partie `droite` de ta boucle tant que.

![screenshot](images/reaction-button-b.png)

+ Tu peux ensuite ajouter un délai très court (20 ms), pour que ta boucle `tant que` attende aussi longtemps qu'un bouton n'est pas appuyé.

![screenshot](images/reaction-delay.png)

+ Teste ton projet. Ton jeu devrait maintenant afficher une image et attendre aussi longtemps que les boutons A __et__ B n'ont __pas__ été appuyés.
