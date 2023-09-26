# GODOT Nodes

Une node peut contenir d'autres nodes. 
Les nodes enfants sont soumis aux transformations 
subit par les nodes parents (rotation, translation, scale...).

## Node2D

Un point avec des coordonnées. 
Utile pour instantier de nouveaux objets à une coordonnée précise
ou grouper plusieurs objets ensemble dans une scène.

## AudioStreamPlayer

Lecteur de fichier audio.

## AnimationPlayer

Anime une node dans la scène grâce à des clées sur une timeline.

## Sprite2D

Affiche une image dans le jeu.

## AnimatedSprite2D

Découpe une image suivant une grille définit en paramêtre.
Affiche ensuite les images contenus dans chaque cellule 
de cette grille successivement. (Grossomodo comme un dessin animé)

## Polygon2D

Applique un masque vectoriel sur une image. Utile pour réaliser des jauges.

## GPUParticles2D

Génère des particules (des Sprite2D) suivant des paramètres définit (vitesse, fréquence, nombre...).

## Area2D

Doit contenir une ou plusieurs nodes de collision (CollisionPolygon2D, CollisionShape2D).
L'Area2D émet un signal lors d'une collision avec un autre Area2D.

## CollisionPolygon2D

Doit être enfant de Area2D. Dessine un polygone à N côtés de collision.

## CollisionShape2D

Doit être enfant de Area2D. Dessine une forme prédéfinit de collition (cercle, rectangle, capsule...).

## PathAnimated

Doit contenir des PathFollow2D. Contraint ses enfants (PathFollow) à suivre une courbe (ensemble de vecteurs).

## PathFollow2D

Doit être enfant de PathAnimated. Suit la courbe définit par son parent.

## Label

Écrit du texte à l'écran.

## Button

Affiche un bouton à l'écran possédant des signals appropriés à l'intéraction utilisateur.
