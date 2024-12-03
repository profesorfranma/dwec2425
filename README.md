# Librería Dialogos.JS

La librería Dialogos.JS contiene un conjunto de funciones JavaScript que reciben como parametro de entrada un objeto de tipo arma y devuelven una frase épica relacionada con ese arma.

## Importación

La librería se puede importar a través de los siguientes enlaces:

* https://raw.githubusercontent.com/profesorfranma/dwec2425/refs/heads/main/dialogos.js
  
* https://profesorfranma.github.io/dwec2425/dialogos.js


## Funciones

Las funciones disponibles en Dialogos.JS son las siguientes:

### `function gritoDeGuerra(arma)`

Genera un grito de guerra según el arma equipada. Es idonea para Barbaros.

`@param {Object|null} arma` - Objeto que representa el arma equipada. Si es `null`, indica que no hay arma.

`@returns {string}` Un mensaje de guerra si hay arma, o un mensaje de incapacidad si no la hay.

### `function susurroElfico(arma)`

Produce un susurro élfico dependiendo del arma equipada. Es idonea para Elfos.

`@param {Object|null} arma` - Objeto que representa el arma equipada. Si es `null`, indica que no hay arma.

`@returns {string}` Un mensaje que resalta las habilidades del arma o una excusa si no hay arma.

### `function conjuroMagico(arma)`

Lanza un conjuro mágico basado en el arma equipada. Es idonea para Magos.

`@param {Object|null} arma` - Objeto que representa el arma equipada. Si es `null`, indica que no hay arma.

`@returns {string}` Un mensaje sobre el poder del arma o un mensaje de agotamiento si no hay arma.


