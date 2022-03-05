Gérée par le système d'exploitation, il s'agit que du cadrage d'une fenêtre:

![Fenêtre](Images/SDLWindow.png)

# Instanciation

Pour créer une instance de fenêtre en mémoire:

![Création de fenêtre](Images/SDLCreateWindow.png)

## Indicateurs

Plusieurs options (flags) sont disponibles pour une fenêtre:

|Flag                 |Description                              |
|---------------------|-----------------------------------------|
|SDL_WINDOW_RESIZABLE |Redimensionnement de la fenêtre possible.|
|SDL_WINDOW_FULLSCREEN|Fenêtre plein-écran.                     |
|SDL_WINDOW_OPENGL    |OpenGL comme moteur de rendu.            |
|...                  |...                                      |

# Libération

Pour libérer une instance de fenêtre:

![SDL destroy window](Images/SDLDestroyWindow.png)

# Informations

Plusieurs propriétés d'une fenêtre peuvent être manipulées.

## Taille

Afin d'obtenir la taille d'une fenêtre:

![SDL window size](Images/SDLWindowSize.png)