# scratch-video-game
## étapes pour faire ton jeu vidéo  
### Etape1 - le game play ⭐  
- imaginer ta quête
- imaginer ton personnage
- imaginer le niveau

### Etape2 - les objets graphiques - statiques 🤴  
- faire un pixel 32 x 32 de ton héro de face
- faire ta carte 500 x 500 avec des tuiles de décor existantes (herbe, eau, montagne, pont, pierre, arbres)
- créer tes tuiles nouvelles: le trésor, les fioles de magie, autres ?
- faire un pixel 32 x 32 pour chacun de tes NPP (on commence avec 2)

### Etape3 - on attaque le code 🍗  
- animation N-S-E-O de ton personnage avec les flèches (ton personnage est fixe mais ta carte bouge)  
- animation action avec les boutons: A - magie1, B - magie2
- interdire de passer sur certaines tuiles
- interdire de sortir de la carte  
- ajouter un niveau de vie 💕

### Etape4 - pause 😁
- qu'est ce qu'il faut en plus ? - des interractions avec les autres personnages et avec les tuiles

### Etape5 - les interractions 👍  
- imaginer une tuile qui donne de la vie et coder la récupération d'une vie
- imaginer une tuile qui donne de la magie et coder le "panier de sortilèges" qui est utilisé si bouton A utilisé
- coder le fait que NPP1 donne un indice si on le rencontre: et cet indice pourrait être "la zone de la carte où se trouve le trésor" (imaginer que la carte est divisée en 9 zones)

### Etape6 - l'aléatoire à chaque partie 🎲🎲  
- pourquoi ne pas mettre le trésor aléatoirement sur la carte à chaque nouvelle partie ? comment le coder ?
- pareil pour la position du NPP

### Etape7 - le temps ⏱  
- ajouter un timer
- coder le nombre de points en fonction du timer en fin de partie
- coder le "game over" au bout du temps

### Etape8 - le game over 💀  
- dessiner la fenêtre game over et son animation
- coder le game over si plus de vie
- (note: on a déjà codé le game over si plus de temps)

### Etape9 - pause 😁  
- qu'est ce qu'il faudrait de plus pour rendre le jeu amusant ?
- ajouter des ennemis ? des bestioles qui se déplacent aléatoirement et te tuent si tu ne les évites pas sur la carte ?

## Les ressources 🚀  
1. MakeCode: https://arcade.makecode.com/  
2. GBStudio: https://github.com/chrismaltby/gb-studio/tree/main
3. scratch du MIT: https://scratch.mit.edu/projects/editor/?tutorial=getStarted
