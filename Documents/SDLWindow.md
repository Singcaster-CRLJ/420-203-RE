Gérée par le système d'exploitation, il s'agit du cadrage d'une fenêtre, sans contenu:

# Instanciation

Pour déclarer et instancier une fenêtre:

![Fenêtre](Images/SDLCreateWindow.png)

## Indicateurs

Plusieurs indicateurs (flags) sont disponibles pour une fenêtre:

|Indicateur           |Description                              |
|---------------------|-----------------------------------------|
|SDL_WINDOW_BORDERLESS|Fenêtre sans bordures.                   |
|SDL_WINDOW_FULLSCREEN|Fenêtre plein-écran.                     |
|SDL_WINDOW_MAXIMIZED |Fenêtre maximisée.                       |
|SDL_WINDOW_OPENGL    |OpenGL comme moteur de rendu.            |
|SDL_WINDOW_RESIZABLE |Redimensionnement de la fenêtre possible.|
|...                  |...                                      |

Ces indicateurs se manipulent « bit à bit », ils peuvent donc être combinés à l'aide d'opérateurs booléens:

![Indicateurs](Images/SDLWindowFlags.png)

# Libération

Pour libérer une instance:

![SDL destroy window](Images/SDLDestroyWindow.png)

# Propriétés

Une fenêtre comporte plusieurs propriétés.

## Identificateur

Toutes les fenêtres possèdent un identificateur, entier non signé, unique:

![Identificateur](Images/SDLGetWindowID.png)
