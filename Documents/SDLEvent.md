Structure contenant les informations de tous les événements possibles:

# Instanciation

Pour déclarer et instancier un conteneur d'informations d'événement:

![Conteneur événement](Images/SDLEvent.png)

# Type

La donnée membre « type » permet d'identifier le type d'événement:

|Type               |Description                                   |
|-------------------|----------------------------------------------|
|SDL_KEYDOWN        |Touche du clavier enfoncée                    |
|SDL_KEYUP          |Touche du clavier relâchée                    |
|SDL_MOUSEMOTION    |Mouvement de souris                           |
|SDL_MOUSEBUTTONDOWN|Bouton de souris enfoncé                      |
|SDL_MOUSEBUTTONUP  |Bouton de souris relâché                      |
|SDL_MOUSEWHEEL     |Molette de la souris                          |
|SDL_QUIT           |Fin du programme                              |
|SDL_WINDOWEVENT    |Événement de fenêtre du système d'exploitation|
|...                |...                                           |

# Parcours

Le système d'exploitation enfile tous les événements qui se sont produits. La fonction « SDL_PollEvent » permet de défiler un événement, stocker ses informations dans le conteneur passé en paramètre, et retourner s'il reste des événements, ou non, dans la file:

![File événements](Images/SDLPollEvent.png)
