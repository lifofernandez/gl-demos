# Xlib y GLX 

## Instalar headers y herramientas necesarias

## en Debian
```
# sudo apt-get install build-tools freeglut3 freeglut3-dev build-essential
```

## en Arch
```
# pacman -S base-devel glu
```

## Compilar con GCC
```
gcc -o  bin/animation src/animation.c -lX11 -lGL -lGLU -std=c99 && ./bin/animation
```
