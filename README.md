Projet Morpion en Réseau
Introduction
Ce projet vise à développer une compréhension approfondie des applications client-serveur à travers la réalisation d'un jeu de morpion jouable à distance. Les applications client-serveur sont essentielles dans divers secteurs, y compris l'industrie, les finances et les divertissements numériques. En permettant à deux joueurs de participer à une partie de morpion via des ordinateurs connectés en réseau, ce projet sert de fondement à des applications plus complexes et illustre les principes de communication réseau.

Règles du Jeu
Le morpion est un jeu pour deux joueurs, utilisant une grille de 3x3. Les joueurs choisissent chacun un symbole (X ou O) et alternent pour marquer une case vide de la grille. Le premier joueur à aligner trois symboles horizontalement, verticalement ou diagonalement remporte la partie. Si toutes les cases sont remplies sans qu'un joueur ait aligné trois symboles, la partie est déclarée nulle.

Fonctionnalités
Modes de Jeu : Les utilisateurs peuvent choisir de regarder une partie en tant que spectateur, rejoindre une partie en tant que client, ou héberger une partie en tant que serveur.
Gestion des Utilisateurs : Les joueurs peuvent sélectionner un pseudo et un pion pour être identifiables.
Support Multi-Spectateur : Plusieurs spectateurs peuvent rejoindre une partie en cours à tout moment pour observer sans interagir.
Affichage du Vainqueur : À la fin de chaque partie, le vainqueur est affiché.
Architecture Technique
Classes Principales
MorpionReseau : Gère la logique du réseau, y compris la connexion des joueurs et des spectateurs.
Morpion : Contient la logique du jeu, y compris la vérification des coups valides et la détermination du gagnant.
ThreadServeurEcouteSpectateur : Gère les connexions entrantes des spectateurs.
Technologies Utilisées
Sockets TCP : Utilisés pour établir une connexion réseau entre les machines.
Threads : Permettent la gestion simultanée de multiples clients et spectateurs.

Interface Graphique
L'interface graphique affiche une grille de morpion où les joueurs peuvent cliquer sur une case pour jouer leur coup. La grille est mise à jour en temps réel à mesure que la partie progresse.

Conclusion
Ce projet illustre l'importance des applications client-serveur et fournit une base solide pour comprendre la communication réseau à travers un jeu interactif et engageant. Il montre également comment des concepts simples peuvent être étendus à des jeux et des applications plus complexes.
