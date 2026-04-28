# Actividad: Propuesta de Práctica Temática Pequeña (Enfoque en Documentación)

## 1) Título de la práctica

**Diseño de Propuesta: Mini Proyecto en Terminal (ARM64, C, Python o Bash)**

> Ejemplos de títulos válidos para tu propuesta:
> - “Mini Toolkit en ARM64”
> - “Asistente de Estudio en Terminal”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general

En esta actividad **no vas a desarrollar un sistema grande**, sino a **diseñar y documentar** una propuesta clara de práctica temática pequeña.

Tu objetivo es plantear un proyecto **realista, acotado y ejecutable en poco tiempo**, pensando en que podrás apoyarte en herramientas como Codex (versión gratuita) u otra IA con límites de uso.

Debes elegir **un lenguaje principal**:

- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante:** Si eliges **ARM64 Assembly**, limita tu alcance a programas **muy pequeños** (por ejemplo, utilidades mínimas de consola), priorizando claridad y factibilidad.

La prioridad de esta entrega es:

1. Documentar la idea.
2. Justificar su utilidad.
3. Definir la estructura del repositorio.
4. Presentar un plan básico de pruebas.

No se evaluará cantidad de código, sino **calidad de propuesta, claridad técnica y viabilidad**.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir **como mínimo**:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Directorios opcionales (si decides incluir prototipo):

- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio

Usa esta base mínima:

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

> `main.<ext>` debe corresponder al lenguaje elegido (`.s`, `.c`, `.py`, `.sh`).

---

## Instrucciones detalladas para cada documento

### A) `README.md`
Incluye:

1. **Nombre del proyecto**.
2. **Resumen de 5 a 8 líneas**: qué problema atiende y para quién.
3. **Lenguaje principal elegido** y por qué.
4. **Alcance pequeño definido** (qué sí hará y qué no hará).
5. **Cómo ejecutar** (aunque sea un prototipo mínimo).
6. **Estatus actual**: “Propuesta” o “Prototipo inicial”.

---

### B) `docs/propuesta.md`
Estructura sugerida:

- **Tema y título tentativo**.
- **Objetivo general** (1 párrafo).
- **Objetivos específicos** (3 a 5 bullets).
- **Justificación técnica** (por qué ese lenguaje y por qué ese tamaño).
- **Alcance funcional**:
  - Funcionalidades mínimas (MVP).
  - Fuera de alcance (explícito).
- **Supuestos y limitaciones**:
  - Sin frameworks complejos.
  - Sin APIs pagadas.
  - Sin base de datos.
  - Sin nube ni contenedores.
- **Riesgos y mitigación** (ej. tiempo, complejidad del lenguaje, pruebas).

---

### C) `docs/caso_de_uso.md`
Incluye:

1. **Contexto de uso** (quién lo usaría y en qué situación).
2. **Problema específico** que resolverá.
3. **Escenario principal paso a paso** (5 a 10 pasos).
4. **Entradas esperadas** (argumentos, archivos, texto).
5. **Salidas esperadas** (mensajes, reportes, archivos).
6. **Criterio de éxito** medible (ej. “reduce tiempo de tarea repetitiva en X% aproximado”).

---

### D) `docs/estructura_repositorio.md`
Describe y justifica:

- Qué va en cada carpeta.
- Convención de nombres de archivos.
- Organización por módulos simples (si aplica).
- Flujo básico de trabajo:
  - editar
  - ejecutar
  - probar
  - documentar

Incluye un diagrama tipo árbol actualizado a tu propuesta.

---

### E) `docs/plan_de_pruebas.md`
Debe tener una tabla mínima con:

- ID de prueba.
- Objetivo.
- Entrada.
- Resultado esperado.
- Resultado obtenido (puede quedar “pendiente” si aún no implementas).

Incluye al menos:

- 3 pruebas funcionales positivas.
- 2 pruebas de manejo de error.
- 1 prueba de límite (caso borde).

---

## Restricciones del proyecto

Para mantener la práctica pequeña y viable:

- ❌ No usar frameworks grandes.
- ❌ No usar servicios de paga.
- ❌ No usar bases de datos.
- ❌ No usar despliegue en nube.
- ❌ No usar Docker/containers.
- ✅ Priorizar CLI (línea de comandos) y archivos locales.
- ✅ Priorizar claridad documental sobre cantidad de código.

---

## Criterios de evaluación (rúbrica sugerida)

| Criterio | Porcentaje |
|---|---:|
| Claridad de la propuesta (`docs/propuesta.md`) | 25% |
| Calidad del caso de uso (`docs/caso_de_uso.md`) | 20% |
| Estructura y organización del repositorio | 20% |
| Plan de pruebas y calidad de escenarios | 20% |
| Calidad global del `README.md` (claridad, ejecución, alcance) | 15% |

---

## Entrega

1. Sube tu repositorio a GitHub Classroom.
2. Verifica que todos los archivos mínimos existan.
3. Asegúrate de que la propuesta sea **coherente con un proyecto pequeño**.
4. Si incluyes código, que sea mínimo, ejecutable y consistente con la documentación.

---

## Recomendaciones finales

- Empieza por escribir la documentación antes del código.
- Evita prometer funcionalidades que no podrás validar.
- Si eliges ARM64, mantén el problema extremadamente acotado.
- Usa ejemplos concretos de entradas y salidas para mostrar madurez técnica.

> En resumen: una propuesta pequeña, clara y bien justificada vale más que un repositorio grande e incompleto.
