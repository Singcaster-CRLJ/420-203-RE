Gérée par le système d'exploitation, il s'agit que du cadrage d'une fenêtre:

![Fenêtre](Images/SDLWindow.png)

# Instanciation

Pour instancier une fenêtre:

![Création de fenêtre](Images/SDLCreateWindow.png)

## Indicateurs

Plusieurs options (flags) sont disponibles:

|Options              |Description                              |
|---------------------|-----------------------------------------|
|SDL_WINDOW_BORDERLESS|Fenêtre sans bordures.                   |
|SDL_WINDOW_FULLSCREEN|Fenêtre plein-écran.                     |
|SDL_WINDOW_MAXIMIZED |Fenêtre maximisée.                       |
|SDL_WINDOW_OPENGL    |OpenGL comme moteur de rendu.            |
|SDL_WINDOW_RESIZABLE |Redimensionnement de la fenêtre possible.|
|...                  |...                                      |

# Libération

Pour libérer une instance:

![SDL destroy window](Images/SDLDestroyWindow.png)
