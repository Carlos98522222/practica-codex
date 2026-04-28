# Actividad de GitHub Classroom: Propuesta de Práctica Temática Pequeña

## 1) Título de la práctica
**Diseña un título claro y específico para tu propuesta.**

Ejemplos de título:
- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

> Tu título final debe reflejar el problema que quieres resolver y el alcance pequeño del proyecto.

---

## 2) Descripción general
En esta actividad vas a **diseñar la propuesta de un proyecto pequeño** orientado a programación de sistemas y trabajo en terminal.  
La meta principal **no es programar mucho**, sino **documentar, planear y justificar** correctamente el proyecto antes de implementar.

Debes elegir **un solo lenguaje principal**:
- ARM64 Assembly
- C
- Python
- Bash

### Reglas de alcance
- El proyecto debe ser **pequeño y realizable** en poco tiempo.
- Si eliges **ARM64 Assembly**, limita la idea a un programa **muy pequeño** (por ejemplo: operaciones básicas, manejo simple de entrada/salida o automatización mínima).
- Evita proyectos grandes y complejos.
- No uses frameworks pesados.
- No uses APIs pagadas, bases de datos, servicios de nube ni contenedores.
- Prioriza soluciones locales, simples y con pocas dependencias.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir **como mínimo** los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Carpetas opcionales (si decides avanzar a implementación):
- `src/`
- `scripts/`
- `tests/`

### Contenido esperado por archivo

#### `README.md`
Incluye:
- Título del proyecto.
- Resumen de 1 párrafo.
- Lenguaje principal elegido y justificación breve.
- Alcance delimitado (qué sí incluye y qué no incluye).
- Instrucciones básicas de ejecución (aunque sea preliminar).

#### `docs/propuesta.md`
Incluye:
- Problema que se quiere resolver.
- Objetivo general y 2-4 objetivos específicos.
- Descripción funcional de la solución.
- Requisitos mínimos (funcionales y no funcionales simples).
- Restricciones técnicas (sin nube, sin dependencias complejas, etc.).

#### `docs/caso_de_uso.md`
Incluye:
- Usuario objetivo.
- Escenario principal de uso.
- Flujo paso a paso del caso principal.
- Entradas esperadas.
- Salidas esperadas.
- Criterios de aceptación del caso.

#### `docs/estructura_repositorio.md`
Incluye:
- Árbol de carpetas propuesto.
- Propósito de cada carpeta y archivo.
- Convenciones de nombres (archivos, scripts, pruebas).
- Estrategia de crecimiento controlado del repositorio.

#### `docs/plan_de_pruebas.md`
Incluye:
- Lista de pruebas mínimas (5 a 10 casos).
- Pruebas nominales, de borde y de error.
- Formato de evidencia (captura de terminal, logs o tablas).
- Criterio para considerar “funcional” la práctica.

---

## 4) Estructura recomendada del repositorio
Usa como base la siguiente estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende de tu lenguaje principal: `s` (ARM64), `c`, `py` o `sh`.

---

## 5) Guía para Codex (uso sugerido por el estudiante)
Si usas Codex u otra IA con límites, trabaja por pasos pequeños:

1. Planifica primero la estructura completa del repositorio.
2. Genera cada archivo de forma independiente.
3. Asegúrate de incluir **todos** los archivos solicitados.
4. Verifica:
   - ¿Hay múltiples archivos?
   - ¿Cada archivo tiene contenido?
   - ¿Se respetó el formato de delimitadores?
5. Mantén la salida debajo de 500 líneas.

---

## 6) Criterios de evaluación sugeridos
- **Claridad de la propuesta (30%)**: problema y objetivos bien definidos.
- **Calidad de documentación (30%)**: estructura, redacción técnica y completitud.
- **Coherencia técnica (20%)**: lenguaje elegido y alcance realista.
- **Plan de pruebas (20%)**: casos útiles, verificables y alineados al caso de uso.

---

## 7) Restricciones finales
- Proyecto pequeño, ejecutable en entorno local.
- Sin dependencias complejas.
- Sin servicios externos de pago.
- La prioridad es documentación y diseño de la práctica.

---

## 8) Setup Script
No se requiere configuración adicional.

---

## 9) Entrega
Sube tu propuesta al repositorio asignado en GitHub Classroom con todos los archivos requeridos y documentación completa.
