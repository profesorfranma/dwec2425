# Librería de Acciones Épicas

Esta librería proporciona funciones para generar frases relacionadas con el uso de armas en diferentes contextos de fantasía épica. Es útil para juegos o aplicaciones donde se requieran diálogos o interacciones de personajes basadas en sus armas.

## Instalación

Para usar esta librería, asegúrate de incluir el archivo donde se encuentran definidas estas funciones en tu proyecto.

Si estás trabajando con un entorno moderno de JavaScript, puedes importar las funciones desde el archivo correspondiente. Por ejemplo:

```javascript
import { gritoDeGuerra, conjuroMagico, susurroElfico } from './accionesEpicas.js';
Funciones Disponibles
1. gritoDeGuerra(arma)
Genera una frase que representa el espíritu combativo de un personaje.

Parámetros:

arma (objeto o null): El arma que el personaje porta.
Si arma es un objeto, debe tener una propiedad nombre que describe el arma.
Si arma es null, indica que el personaje no tiene arma y no está dispuesto a luchar.
Ejemplo de Uso:

javascript
Copiar código
const espada = { nombre: "Espada Legendaria" };
console.log(gritoDeGuerra(espada)); // Nada puede parar la furia de mi Espada Legendaria
console.log(gritoDeGuerra(null));   // Hoy no puedo luchar, tengo un dolor en el brazo.
2. conjuroMagico(arma)
Genera una frase que describe el uso de un arma mágica.

Parámetros:

Igual que en gritoDeGuerra.
Ejemplo de Uso:

javascript
Copiar código
const varita = { nombre: "Varita de los Antiguos" };
console.log(conjuroMagico(varita)); // Cuan poderoso es el poder de mi Varita de los Antiguos
console.log(conjuroMagico(null));   // Mis poderes están agotados, necesito un descanso.
3. susurroElfico(arma)
Proporciona una frase basada en un tono más místico y reservado, ideal para personajes élficos.

Parámetros:

Igual que en las funciones anteriores.
Ejemplo de Uso:

javascript
Copiar código
const arco = { nombre: "Arco del Bosque Eterno" };
console.log(susurroElfico(arco)); // No hay objetivo lejano para mi Arco del Bosque Eterno
console.log(susurroElfico(null)); // No puedo ir a la batalla, el bosque me necesita para meditar.
Exportación
Todas las funciones están exportadas en un solo objeto para facilitar su uso:

javascript
Copiar código
export { gritoDeGuerra, conjuroMagico, susurroElfico };
Puedes importar las funciones de manera individual o todas juntas según tus necesidades.

Contribuciones
Si deseas contribuir a esta librería, por favor sigue las siguientes reglas:

Mantén la consistencia en los nombres y estilos de las funciones.
Asegúrate de que cada función nueva tenga un propósito claro y esté bien documentada.
Haz pruebas con diferentes escenarios para garantizar un comportamiento esperado.
Licencia
Esta librería está disponible bajo MIT License. Puedes usarla, modificarla y distribuirla libremente siempre que incluyas esta nota de crédito.

Copiar código





