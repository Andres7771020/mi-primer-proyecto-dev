# mi-primer-proyecto-dev
mi-primer-proyecto-dev es un repositorio de práctica para aprender Git y GitHub, explorar el trabajo colaborativo y aplicar buenas prácticas de desarrollo. Incluye configuración básica, .gitignore, README.md y licencia MIT
git clone https://github.com/usuario/mi-primer-proyecto-dev.git
cd mi-primer-proyecto-dev
git checkout -b feature/calculadora-basica
function sumar(a, b) {
  return a + b;
}

function restar(a, b) {
  return a - b;
}

function multiplicar(a, b) {
  return a * b;
}

function dividir(a, b) {
  if (b === 0) {
    throw new Error("No se puede dividir por cero");
  }
  return a / b;
}

module.exports = { sumar, restar, multiplicar, dividir };
# Calculadora Básica

Calculadora simple en JavaScript con funciones de suma, resta, multiplicación y división.

## Instalación

```bash
git clone https://github.com/usuario/mi-primer-proyecto-dev.git
cd mi-primer-proyecto-dev
npm installconst calc = require('./calculadora');
console.log(calc.sumar(2, 3)); // 5
##### 📦 `package.json`

```json
{
  "name": "calculadora-basica",
  "version": "1.0.0",
  "description": "Calculadora simple en JavaScript",
  "main": "calculadora.js",
  "scripts": {
    "test": "echo \"Sin pruebas definidas aún\""
  },
  "author": "Andrés",
  "license": "MIT"
}
