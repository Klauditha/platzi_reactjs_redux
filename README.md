# Curso Profesional de Reacj.js y Redux

## Conceptos claves de Redux

REDUX: LibrerÍa nos ayuda a manejar de mejor manera el estado de nuestra aplicación. Para usarlos se necesita:

- Dónde almacenar: Store
- Cómo acceder: Mediantes métodos, ejempo: selectores.
- Cómo actualizar: Disapradores, actions ó reducers.
  
Consta de tres principios:

- Única fuente de verdad (store)
- El estado es de solo lectura, no modificarlo directamente sino atraves de actions.
- Los cambios deben realizarse através de funciones puras (reducers)

Funciones Puras caractesristicas: -Valor de entrada cambia si la entrada cambia.

- Misma entrada, misma salida.
- No tener lógica síncrona

