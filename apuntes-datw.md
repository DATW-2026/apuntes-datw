# APUNTES DATW

#### _Desarrollo de aplicaciones con tecnologías web_

#### _14/01/2026_

- Instalar nvm o similar (control de versiones de node)
  [nvm](https://github.com/coreybutler/nvm-windows) o
  [fnm](https://github.com/Schniz/fnm)

- Instalar node versión LTS (24) desde la consola del sistema <br>
  `node install lts`

#### _15/01/2026_

- Instalar [Git](https://git-scm.com/install/windows)

- Configurar Git <br>
  `git config --global user.name "Eduardo Yeves"` <br>
  `git config --global user.email "yevestevez.cg@gmail.com"`

- Crear repositorio de Git en la carpeta elegida (Documents/IFCD*210_2026) <br>
  `git init demo-git` <br>
  \_Para eliminar un repositorio de Git borramos la carpeta .git del repositorio.*

- Crear fichero _.gitignore_

- Crear repositorio en GitHub, enlazar con el repositorio local
  `git remote add origin https://github.com/Yevestevez/demo-git.git` y subir el repositorio `git push -u origin main`

- Instalar la extensión [Editor Config](https://editorconfig.org/) para VSCode, es importante cuando trabajas en equipo para que las configuradores del editor sean similares.

#### _19/01/2026_

- Instalar extensión VSCode [Prettier](https://prettier.io/). Lo configuramos como formateador predeterminado y activamos formatOnSave, De este modo aseguramos que el formato de nuestro código sigue las buenas prácticas más habituales.

- Inicializamos package.json desde `npm init` en nuestro proyecto y cambiamos a comillas simples en Prettier desde el archivo package.json de nuestro proyecto.

```
  prettier": {
  "singleQuote": true
  }
```

- Instalamos [ESLint](https://eslint.org/).
