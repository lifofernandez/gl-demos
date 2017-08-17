# Xlib y GLX 

## Instalar headers y herramientas necesarias

## en Debian
```bash
sudo apt-get install build-tools freeglut3 freeglut3-dev build-essential
```

## en Arch
```bash
pacman -S base-devel glu
```

## Compilar con GCC
```bash
gcc -o  bin/animation src/animation.c -lX11 -lGL -lGLU -std=c99 && ./bin/animation
```
./utils/capture out/output.mp4
