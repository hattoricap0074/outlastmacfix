# outlastmacfix
controller support for outlast mac build (gog cracked version)


Backs up the game's libSDL2.dylib to libSDL2.dylib.bak
Replaces it with SDL2 2.30.9 from github.com/libsdl-org/SDL (official release)
Downloads the SDL controller database (github.com/mdqinc/SDL_GameControllerDB)
Re-signs the app, because changing a library invalidates its signature
