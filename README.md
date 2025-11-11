## 👨‍💻 Información del Estudiante

- **Nombre:** [Angel Abraham Lugo Saenz]
- **Matrícula:** [SW2409052]
- **Grupo:** [B]
- **Cuatrimestre:** Primer Cuatrimestre
- **Carrera:** TSU en Desarrollo e Innovación de Software
- **Profesor:** Jorge Javier Pedrozo Romero

---

## 📋 Descripción del Proyecto

Este repositorio contiene mi solución a la práctica de **Fundamentos de Programación**, donde implemento funciones en JavaScript para resolver problemas de álgebra básica, preparándome para trabajar con operaciones matriciales más complejas.

## 🎯 Objetivos Alcanzados

- ✅ Dominar variables y tipos de datos en JavaScript
- ✅ Implementar estructuras condicionales
- ✅ Utilizar bucles y funciones
- ✅ Manipular arrays unidimensionales
- ✅ Trabajar con arrays bidimensionales (matrices)
- ✅ Aplicar control de versiones con Git y GitHub

---

## 📊 Progreso de Ejercicios

### Sección 1: Variables y Tipos de Datos (10 pts)
- [x] 1.1 Mi Información (2 pts) ✅
- [x] 1.2 Operaciones Básicas (3 pts) ✅
- [x] 1.3 Área de Rectángulo (2 pts) ✅
- [x] 1.4 Conversión Celsius a Fahrenheit (3 pts) ✅

**Puntos obtenidos: 10/10**

### Sección 2: Condicionales (15 pts)
- [x] 2.1 Par o Impar (3 pts) ✅
- [x] 2.2 Evaluar Nota (4 pts) ✅
- [x] 2.3 Mayor de Tres (4 pts) ✅
- [x] 2.4 Clasificar Edad (4 pts) ✅

**Puntos obtenidos: 15/15**

### Sección 3: Funciones y Bucles (20 pts)
- [x] 3.1 Factorial (5 pts) ✅
- [x] 3.2 Suma Hasta N (4 pts) ✅
- [x] 3.3 Tabla de Multiplicar (5 pts) ✅
- [x] 3.4 Números Pares (6 pts) ✅

**Puntos obtenidos: 20/20**

### Sección 4: Arrays (25 pts)
- [x] 4.1 Suma de Array (4 pts) ✅
- [x] 4.2 Promedio de Array (5 pts) ✅
- [x] 4.3 Encontrar Máximo (6 pts) ✅
- [x] 4.4 Filtrar Mayores (5 pts) ✅
- [x] 4.5 Invertir Array (5 pts) ✅

**Puntos obtenidos: 25/25**

### Sección 5: Arrays Bidimensionales - Matrices (30 pts)
- [x] 5.1 Crear Matriz (6 pts) ✅
- [x] 5.2 Suma de Matriz (6 pts) ✅
- [x] 5.3 Obtener Fila (5 pts) ✅
- [x] 5.4 Obtener Columna (7 pts) ✅
- [x] 5.5 Transponer Matriz (6 pts) ✅

**Puntos obtenidos: 30/30**

---

## 📈 Calificación Final

```
┌────────────────────────────────────────┐
│  REPORTE DE CALIFICACIÓN               │
├────────────────────────────────────────┤
│  Puntos obtenidos: 100/100             │
│  Porcentaje: 100%                      │
│  🎓 Calificación: A - Excelente        │
└────────────────────────────────────────┘
```

[![Tests](https://github.com/Angel-Lugo97/fundamentos-programacion-practica-1/actions/workflows/test.yml/badge.svg)]




## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- Git

### Clonar el repositorio
```bash
git clone https://github.com/TU-USUARIO/fundamentos-programacion-practica-1.git
cd fundamentos-programacion-practica-1
```

### Instalar dependencias
```bash
npm install
```

### Ejecutar tests
```bash
npm test
```

### Ejecutar tests en modo watch
```bash
npm run test:watch
```

### Ver cobertura de código
```bash
npm run test:coverage
```

---

## 📁 Estructura del Proyecto

```
fundamentos-programacion-practica-1/
│
├── ejercicios.js           # ⭐ Archivo principal con mis soluciones
├── ejercicios.test.js      # Tests automatizados (no modificar)
├── package.json            # Configuración del proyecto
├── README.md               # Este archivo
├── GUIA_ESTUDIANTES.md     # Guía de referencia
├── GUIA_INSTRUCTOR.md      # Guía del profesor
│
└── .github/
    └── workflows/
        └── test.yml        # Configuración de GitHub Actions
```

---

## 💡 Aprendizajes Clave

### Lo que más me costó
- **Ejercicio 5.5 (Transponer Matriz)**: Entender cómo intercambiar filas por columnas requirió visualizar bien el proceso.
- **Ejercicio 3.1 (Factorial)**: Al principio olvidé el caso base cuando n=0.

### Lo que más me gustó
- **Arrays Bidimensionales**: Ver cómo las matrices se relacionan con estructuras de datos reales como imágenes.
- **Testing Automático**: Es increíble ver los tests correr y obtener retroalimentación inmediata.

### Técnicas aplicadas
- Uso de `for` loops para iteraciones
- Operador módulo `%` para determinar paridad
- Arrays dinámicos con `.push()`
- Bucles anidados para matrices

---

## 🔧 Ejemplos de Código

### Función Favorita: Transponer Matriz
```javascript
function transponer(matriz) {
  const filas = matriz.length;
  const columnas = matriz[0].length;
  const transpuesta = [];
  
  for (let j = 0; j < columnas; j++) {
    const fila = [];
    for (let i = 0; i < filas; i++) {
      fila.push(matriz[i][j]);
    }
    transpuesta.push(fila);
  }
  
  return transpuesta;
}
```

**Por qué me gusta:** Demuestra cómo manipular estructuras bidimensionales de forma elegante.

---

## 📚 Recursos Utilizados

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [JavaScript.info](https://es.javascript.info/)
- [Stack Overflow](https://stackoverflow.com)
- Guía del estudiante incluida en el repositorio

---

## 🎯 Próximos Pasos

Este proyecto me prepara para:
- ✨ Operaciones matriciales avanzadas (multiplicación, determinantes)
- 🖼️ Desarrollo de editores de imágenes
- 🔐 Implementación de algoritmos de encriptación
- 📊 Creación de calculadoras científicas

---

## 📝 Historial de Commits
```bash
# Ver mi historial completo
git log --oneline --graph --decorate
```

**Commits destacados:**
* 7e9efb4 Utilizand el metodo Array.from(), solucionamos el ejercicio 5.5
* bc071c5 Utlizamos el metodo map(), para solucionar el ejercicio 5.4
* 278c20b Utilizamos el metodo find(), para solucionar el ejercicio numero 5.3
* d084ff6 Utilizando dos For..of, resolvemos el ejercicio 5.2
* 307898c Utilizamos el metodo Array.from(), para solucionar el ejercicio 5.1
* f7dee71 Utilizamos el metodo .reverse(), para solucionar el ejercicio 4.5
* f880e13 Utilizamos el bucle for..of, para solucionar el ejercicio 4.4
* 740c10f Con el metodo Math.max, solucionamos el ejercicio 4.3
* 28435e9 Con un bucle For y Condiconal IF, resolvemos el ejercicio 4.2
* a9a56eb Utilizamos un bucle for para solucionar el ejercicio 4.1
* 0b1f443 Modificamos el error de par a tabla
* 1216a92 Modificando el codigo del 3.3, solucionamos el ejercicio 3.4
* f6d310e Con un bucle For y con con tabla[i] = (i + 1) * numero, resolvemos el ejercicio 3.3
* f58b5ae Arreglo el problema de sintaxis del ejercicio 3.2
* 327986e Utilizamos el bucle For para usarlo de contador y resolver el ejericio 3.2
* d7ef35a Utilizamos un el bucle For para solucionar el ejercicio 3.1
* 22b0292 Utiliamos operadores ternarios anidados para solucionar el ejercicio 2.4
* 926ead3 Usamos el metodo Math.max() para resolver el ejercicio 2.3
* 60e807d Vuelvo a verifiar el error del ejercicio 2.2
* 50bb042 Corrijo el mensaje del return
* 6a84187 Utilizando el condicional IF, resuelvo el ejercicio 2.2
* e29ae1e Resuelvo el ejercicio 2.1, utilizando el condicional if
* 3718631 Compruebo los ejercicio 1.3 y 1.4, por error de sintaxis
* 964ee06 Aregle el return del area del ejercicio 1.3
* 2b4e0f9 Arregle el ejericio1, 2 y 3



## 🤝 Agradecimientos

- **Profesor Jorge Javier Pedrozo Romero** por la estructura del curso y la práctica
- **Compañeros del Grupo [A/B/C]** por el apoyo mutuo
- **Tecnológico de Software** por la formación integral

---

## 📧 Contacto

- **Email Institucional:** [tu-correo@institucional.edu.mx]
- **GitHub:** [@TU-USUARIO](https://github.com/TU-USUARIO)

---

## 📄 Licencia

Este proyecto es parte de las actividades académicas del **Tecnológico de Software** y está bajo la licencia MIT.

---

<div align="center">

**⭐ Si te gustó este proyecto, dale una estrella ⭐**

Hecho con 💙 por [Tu Nombre] - 2025

</div>
