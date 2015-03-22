# Bourbon Structure
Estructura básica para bourbon, neat and bitters

## Requerimientos

- [HAML](http://haml.info/tutorial.html)
- [SASS](http://sass-lang.com/)

**Mac OS:**

- [BREW](http://brew.sh/)

## Uso

Entrar a la carpeta raíz y seguir los pasos

1. Compilar SASS

  ```bash
  sass --watch css/style.scss:style.css
  ```

2. Compilar HAML

  ```bash
  haml index.haml index.html
  ```

  **Mac OS:** Se puede instalar watch con 

  ```bash
  brew install watch
  ```

  Después de instalar:

  ```bash
  watch haml index.haml index.html
  ```
