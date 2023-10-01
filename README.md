Editor Config

spaces_around_operators = true # Indica si deben haber espacios alrededor de los operadores aritméticos y booleanos.

typescript.organizeImports = true # Aplica un ordenamiento alfabético a las importaciones



eslint

"no-unused-vars": "error", // Advierte sobre variables no utilizadas
"no-var": "error", // Prefiere let o const en lugar de var
"eqeqeq": "error" // Requiere el uso de === en lugar de ==


prettier

"endOfLine": "auto" //Agregar un salto de línea al final del archivo
"noSpaceBlankOperators": true // Evitar el espaciado en blanco alrededor de los operadores
"noTrailingWhitespace": true // No usar espacios en blanco finales en las líneas

ts-config

"noImplicitReturns": true, /* Advierte sobre declaraciones de funciones sin retorno*/
"strictNullChecks": true, /* Realiza comprobaciones estrictas de nulos*/
"strictPropertyInitialization": true, /* Exige inicialización estricta de propiedades de clase*/


Nodemon
"signal": "SIGTERM", // Señal para reiniciar la aplicación
