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

#### _20-21/01/2026_

- Funciones básicas
- Expresiones funcionales
- Arrow functions
- Funciones puras
  - No dependen de valores exteriores a la función, pasamos los valores como parámetros
  - No pueden tener efectos (por ejemplo, _console.log_ sería un efecto)
  - Con los mismos argumentos produce el mismo resultado
- Scoope o ámbito de las variables en JS. let y const VS var.
- Redondeos:
  ```js
  Math.floor(5.999); // 5
  Math.trunc(5.999); // 5
  Math.ceil(5.001); // 6
  Math.round(5.6); // 6
  ```
- Generación de números aleatorios entre 0 y 1
  `Math.random();`
- Operadores
- Bucles

#### _22/01/2026_

- Operador ternario --> num % 2 === 0 ? 'par' : 'impar'
- Valores por defectos en parámetros de funciones --> function(parametro = 'valor por defecto') {...}
- Iteración e índices en strings --> string[i]
- Arrays --> const array = [elemento1, elemento2, elemento3]
- Recorrer arrays, inyectar items...
- Instalación de dependencias con `npm i <nombre-libreria>`
- Instalar prompt-sync en nuestro proyecto _demo-js_ `npm i prompt-sync` para poder hacer promts en la consola de node de manera sencilla
- Package.json y package-lock.json
- [gitignore.io](https://www.toptal.com/developers/gitignore)
- Control + Espacio --> preguntar a Intellisense de VSCode
- Operadores lógicos `&&` y `||`

#### _23/01/2026_

- Debugger VSCode
- Case
- Tipos de datos (null, undefined, bigint)
- Objetos -> propiedades, valores, anidamiento de objetos, array de arrays (matrices multidimensionales)
- Acceso a propiedades de objetos con punto `.` y a items de arrays con corchetes `[i]`
- Métodos de array
- clonado de objetos (shallow vs depp) --> structuredClone(object)
