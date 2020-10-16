# Proyecto Individual

_Diseño e implementación de una aplicación de desencriptación RSA_

## Desarrollado con:

_Para la parte del procesamiento de la imagen se implementaron las siguientes herramientas:_

* [NASM](https://www.nasm.us/) - El compilador asm usado.
* [Sublime](https://www.sublimetext.com/3) - Editor de texto utilizado.
* [Linux Mint](https://linuxmint.com/) - Sistema operativo.

_Para la parte de la visualización de la imagen se implementaron las siguientes herramientas:_

* [Python](https://www.python.org/) - Lenguaje de alto nivel utilizado.
* [Jupyter NoteBook](https://jupyter.org/install.html) - IDLE con interprete para Python 3.
* [NumPy](https://numpy.org/install/) - Librería para crear las imagenes con la matriz de Bytes.

### Instalación

_A continuación se muestra como instalar nasm en linux_

```
sudo apt-get update -y
```

_Y finalmente_

```
sudo apt-get install -y nasm
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_

### Ejecucion

_A continuación se muestra como ejecutar el programa con NAMS_

```
nasm -f elf64 proyecto1.asm
```
_Luego_
```
ld proyecto1.o -o proyecto1
```
_Finalmente_
```
./proyecto1
```

## Autor

* **Gerald Mora Mora** - *Desarrollo completo* - [GeraldFMoraMora](https://github.com/GeraldFMoraMora)

