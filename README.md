# Calidad de Software

Este repositorio tiene como objetivo servir como referencia básica para la materia de calidad de software. Aquí se presentan conceptos clave sobre la validación de software, la importancia de las pruebas y los distintos tipos de pruebas que ayudan a asegurar que una aplicación cumpla con los requisitos y la calidad esperada.

## 1. ¿Qué es la calidad de software?

La calidad de software se refiere al grado en que un sistema cumple con:

- Los requisitos funcionales y no funcionales.
- Las necesidades del usuario.
- Los estándares de desarrollo y seguridad.
- La mantenibilidad, confiabilidad y facilidad de uso.

Un software de calidad no solo funciona, sino que además es estable, seguro, testeable y fácil de mantener.

## 2. Conceptos básicos

### Requisito
Un requisito es una necesidad o condición que debe cumplir el sistema. Puede ser funcional (qué debe hacer) o no funcional (rendimiento, seguridad, usabilidad, disponibilidad, etc.).

### Defecto
Un defecto es un problema que provoca un comportamiento incorrecto, inesperado o no conforme con el requisito.

### Verificación y validación
- Verificación: comprobar si el producto se está construyendo correctamente.
- Validación: comprobar si el producto cumple con las necesidades del usuario y los requisitos esperados.

### Pruebas de software
Las pruebas son actividades orientadas a detectar fallas y asegurar que el sistema funciona de acuerdo con lo esperado. Pueden ejecutarse en diferentes niveles del desarrollo.

## 3. Tipos de pruebas

### Pruebas unitarias
Las pruebas unitarias validan componentes o funciones individuales de forma aislada. Su objetivo es comprobar que cada unidad del código funciona correctamente en condiciones específicas.

Características principales:
- Se enfocan en una sola función, método o clase.
- Deben ser rápidas y repetibles.
- Ayudan a detectar errores lógicos desde etapas tempranas.
- Se suelen automatizar con frameworks como JUnit, pytest, Jest o PHPUnit.

Ejemplo de objetivo:
- Verificar que una función de suma retorne el valor esperado.
- Validar una validación de correo electrónico.

### Pruebas de integración
Las pruebas de integración verifican que varios módulos o componentes del sistema interactúan correctamente entre sí. Aquí se prueba la conexión entre partes del software, como APIs, bases de datos o servicios.

### Pruebas de sistema
Estas pruebas revisan el comportamiento del sistema completo, considerando la interacción entre módulos y el entorno real de funcionamiento.

### Pruebas end-to-end (E2E)
Las pruebas end-to-end simulan escenarios reales del usuario final para validar que el flujo completo del sistema funciona correctamente, desde la interfaz hasta el backend y la base de datos.

Características principales:
- Validan el recorrido completo del usuario.
- Detectan errores en integración y experiencia de usuario.
- Son más lentas que las pruebas unitarias.
- Se utilizan para validar flujos críticos como login, compra, registro o navegación.

## 4. Pruebas unitarias

Las pruebas unitarias son la base de la estrategia de automatización de pruebas. Se centran en verificar la lógica de cada parte del código con datos de entrada y salida esperados.

Ventajas:
- Son rápidas de ejecutar.
- Permiten detectar errores tempranos.
- Facilitan la refactorización segura.
- Mejoran la calidad del código.

Buenas prácticas:
- Probar casos normales y casos límite.
- Usar nombres descriptivos en las pruebas.
- Mantener las pruebas simples y enfocadas.
- No depender de datos externos o de terceros.

## 5. Pruebas E2E

Las pruebas E2E permiten validar el sistema desde la perspectiva del usuario. Son útiles para comprobar que los flujos reales funcionan sin fallos visibles.

Ventajas:
- Validan la experiencia real del usuario.
- Detectan problemas de integración que pueden no verse en pruebas unitarias.
- Ayudan a reducir errores en producción.

Desventajas:
- Suelen ser más lentas.
- Exigen más infraestructura o entornos de prueba.
- Pueden requerir mayor mantenimiento.

## 6. Relación entre pruebas unitarias y E2E

La estrategia ideal suele combinar ambos tipos de pruebas:

- Pruebas unitarias: validan la lógica y el comportamiento interno.
- Pruebas E2E: validan la experiencia completa del usuario en un flujo real.

Como regla general, se suele seguir una pirámide de pruebas:

- Más pruebas unitarias.
- Menos pruebas de integración.
- Un número menor de pruebas E2E.

Esto permite mantener un equilibrio entre velocidad, costo y cobertura.

## 7. Objetivos del curso

El propósito principal de esta materia es entender que la calidad de software no depende solo del código, sino también de:

- La disciplina del proceso.
- La correcta planificación de pruebas.
- La automatización de validaciones.
- La revisión continua y la mejora del producto.

## 8. Recomendaciones

- Automatizar pruebas siempre que sea posible.
- Diseñar casos de prueba claros y útiles.
- Probar tanto escenarios correctos como errores.
- Revisar la calidad del software en cada iteración.
- Priorizar la cobertura de flujos críticos.

## 9. Conclusión

La calidad de software se logra mediante una estrategia sólida de pruebas, análisis y mejora continua. Las pruebas unitarias permiten verificar componentes individuales, mientras que las pruebas E2E validan el funcionamiento real del sistema completo. Ambas son esenciales para entregar software confiable y de valor para el usuario.

---

## 10. Referencias rápidas

- Calidad de software: conjunto de atributos que hacen que un sistema sea confiable, seguro, mantenible y útil.
- Prueba unitaria: validación aislada de una función o módulo.
- Prueba E2E: validación del flujo completo desde la perspectiva del usuario.
- Cobertura de pruebas: porcentaje de código o comportamiento probado.
- Automatización: ejecución de pruebas de forma repetitiva y consistente.
