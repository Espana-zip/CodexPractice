# Actividad: Propuesta de Práctica Temática Pequeña (Enfoque en Documentación)

## 1) Título de la práctica

**Diseña un título claro y concreto para tu práctica temática.**

Ejemplos (puedes usar uno o crear el tuyo):
- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general

En esta actividad **no se evalúa primero “cuánto código escribes”**, sino **qué tan bien planeas, documentas y justificas** una idea de proyecto pequeño.

Vas a diseñar una **propuesta de práctica temática** que pueda implementarse en un tiempo corto y con recursos limitados (por ejemplo, usando versión gratuita de Codex u otra IA con límites de uso).

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Recomendación importante:** Si eliges **ARM64 Assembly**, limita tu propuesta a un programa **muy pequeño** y de alcance controlado (por ejemplo: operaciones simples, lectura básica de entrada, manipulación mínima de datos o utilerías muy específicas de terminal).

### Prioridad de la actividad
1. Documentación clara.
2. Planeación realista.
3. Estructura del repositorio.
4. Explicación del caso de uso.
5. Código mínimo necesario (si decides incluirlo).

### Restricciones del proyecto
Para mantener la práctica viable y enfocada:
- Evita proyectos grandes.
- No uses frameworks pesados.
- No uses APIs pagadas.
- No uses bases de datos.
- No uses servicios en la nube.
- No uses contenedores.
- Evita dependencias complejas.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcionales (si aplica a tu idea):
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio

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

> `<ext>` depende del lenguaje principal que elijas:
> - `S` o `s` para Assembly (según toolchain)
> - `c` para C
> - `py` para Python
> - `sh` para Bash

---

## 5) Contenido esperado por archivo

### `README.md`
Debe incluir:
1. Título del proyecto.
2. Resumen en 1–2 párrafos.
3. Lenguaje principal elegido y justificación breve.
4. Instrucciones mínimas para ejecutar (aunque sea un prototipo).
5. Alcance (qué sí hace y qué no hace).

### `docs/propuesta.md`
Debe incluir:
1. Problema que quieres atender.
2. Objetivo general y 2–4 objetivos específicos.
3. Alcance funcional mínimo (MVP).
4. Supuestos y limitaciones.
5. Entregable técnico esperado al final (ejecutable/script/prototipo).

### `docs/caso_de_uso.md`
Debe incluir:
1. Contexto del usuario (quién lo usaría y para qué).
2. Flujo principal de uso paso a paso.
3. Entradas y salidas esperadas.
4. Al menos 2 casos de error (ej. entrada inválida, archivo inexistente).

### `docs/estructura_repositorio.md`
Debe incluir:
1. Árbol del repositorio (actualizado).
2. Propósito de cada carpeta/archivo.
3. Convenciones de nombres (archivos, scripts, funciones).
4. Estrategia mínima de versionado (commits sugeridos por avance).

### `docs/plan_de_pruebas.md`
Debe incluir:
1. Qué vas a probar (funcionalidades mínimas).
2. Casos de prueba en tabla: ID, entrada, resultado esperado.
3. Criterios de aceptación.
4. Riesgos técnicos y cómo mitigarlos.

---

## 6) Requisitos de tamaño y complejidad

Tu propuesta debe ser **pequeña, realizable y evaluable** en un periodo corto.

### Límites sugeridos
- 1 problema principal.
- 1 flujo principal de uso.
- 3 a 6 funcionalidades máximas.
- Dependencias externas: idealmente 0.
- Interfaz: terminal/CLI.

### Ejemplos de alcance adecuado
- Script que organiza archivos por extensión con reporte en texto.
- Programa en C/Python que procesa un log simple y da estadísticas.
- Utilería Bash para verificar estructura de carpetas de una materia.
- Programa ARM64 mínimo para operaciones aritméticas básicas y salida en terminal.

---

## 7) Criterios de evaluación (rúbrica sugerida)

| Criterio | Porcentaje |
|---|---:|
| Claridad y coherencia de la propuesta (`docs/propuesta.md`) | 25% |
| Calidad del caso de uso (`docs/caso_de_uso.md`) | 20% |
| Estructura y organización del repositorio (`docs/estructura_repositorio.md`) | 20% |
| Plan de pruebas realista y verificable (`docs/plan_de_pruebas.md`) | 20% |
| Calidad general de `README.md` y consistencia global | 15% |

---

## 8) Checklist de entrega

Antes de entregar, verifica:

- [ ] Elegí un solo lenguaje principal (ARM64 Assembly, C, Python o Bash).
- [ ] Mi idea es pequeña y realista.
- [ ] Completé todos los archivos obligatorios en `docs/`.
- [ ] El `README.md` explica claramente el proyecto.
- [ ] Definí al menos un flujo principal y casos de error.
- [ ] Incluí plan de pruebas con criterios de aceptación.
- [ ] La estructura del repositorio coincide con lo documentado.

---

## 9) Recomendaciones finales para estudiantes

- Primero define bien **qué problema resolverás**.
- Recorta alcance sin miedo: un proyecto pequeño pero sólido vale más que uno grande e incompleto.
- Si usas IA de apoyo, úsala para iterar documentos y validar claridad, no para inflar complejidad.
- Mantén trazabilidad: que cada archivo de `docs/` tenga relación directa con lo que construirás.

---

## 10) Formato de entrega en GitHub Classroom

1. Crea tu repositorio desde la asignación.
2. Sube la estructura mínima solicitada.
3. Completa los documentos en `docs/`.
4. (Opcional) agrega un prototipo mínimo en `src/` y/o `scripts/`.
5. Realiza commits con mensajes claros (ej.: `docs: define caso de uso`, `docs: agrega plan de pruebas`).
6. Entrega la liga del repositorio según las instrucciones del curso.

> **Nota docente:** Esta actividad está enfocada en diseño técnico y documentación. El objetivo es que primero pienses y estructures bien la solución antes de escalarla a implementación.
