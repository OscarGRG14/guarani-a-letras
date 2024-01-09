# GuaraniALetras

La biblioteca GuaraniALetras proporciona funciones para convertir números a letras en guaraníes, la moneda de Paraguay. Esto puede ser útil para generar representaciones de cantidades en palabras, especialmente en contextos relacionados con la escritura de cheques, facturas o documentos financieros.

## Instalación

```bash
npm install guarani-a-letras
```
## Ejemplo de uso
```javascript
const guaranialetras = require('guaraniAletras');

// Ejemplo de uso
const numero = 12345.67;
const enLetras = guaranialetras.NumeroALetras(numero, true);
console.log(enLetras);
// Salida: "DOCE MIL TRESCIENTOS CUARENTA Y CINCO GUARANÍES CON SESENTA Y SIETE"

// Otro ejemplo
const otroNumero = 7890123.45;
const enLetrasOtro = guaranialetras.NumeroALetras(otroNumero, true);
console.log(enLetrasOtro);
// Salida: "SIETE MILLONES OCHOCIENTOS NOVENTA MIL CIENTO VEINTITRÉS GUARANÍES CON CUARENTA Y CINCO"
```
