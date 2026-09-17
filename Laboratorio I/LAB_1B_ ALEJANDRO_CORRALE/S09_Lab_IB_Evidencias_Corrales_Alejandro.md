# ICT401 · Semana 9 — Laboratorio integrador I-B

**Reconstrucción 3D a partir de un plano o conjunto de vistas — 10 %**

- Estudiante: [Respuesta]
- Grupo: [Respuesta]
- Fecha: [Respuesta]
- Nombre del archivo de Fusion: `ICT401_S09_LabIB_Apellido_Nombre`
- Carpeta/proyecto de Fusion Cloud con acceso docente: [Respuesta]
- Commit de entrega: [Respuesta]

## Instrucciones de uso de esta ficha

Complete esta ficha durante el laboratorio. No borre respuestas iniciales aunque luego las corrija. Cuando cambie una decisión, explique qué evidencia del plano o del modelo motivó la modificación.

La ficha debe quedar en `Portafolio/semana09/` con el nombre `S09_Lab_IB_Evidencias_Apellido_Nombre.md`. Las imágenes enlazadas deben estar en la misma carpeta. El archivo nativo permanece en Fusion Cloud con acceso docente.

Esta ficha forma parte de la evidencia evaluable del Laboratorio integrador I-B y está estructurada para facilitar una revisión posterior por la persona docente o mediante ChatGPT. La calificación final corresponde siempre al instrumento oficial del curso.

---

## A. Interpretación inicial del plano

### A1 · Dimensiones generales

- X total: [90mm]
- Y total: [60mm]
- Z total: [42mm]

### A2 · Características geométricas identificadas

| Nº | Característica | Descripción | Vista(s) que la definen | Dimensiones asociadas |
|---|---|---|---|---|
| 1 | Base | Parte principal de la pieza | Front, Top y Right | 90 × 60 mm |
| 2 | Plataforma | Parte elevada ubicada atrás | Front, Top y Right | X = 0–60, Y = 25–60 |
| 3 | Torre | Parte más alta de la pieza | Front, Top y Right | X = 0–25, Y = 25–60 |
| 4 | Agujero | Agujero circular que atraviesa la pieza | Top | Ø14 mm, centro (42,42) |
| 5 | Ranura | Corte rectangular que atraviesa la pieza | Top | 14 × 12 mm, X = 68–82, Y = 10–22 |

### A3 · Describa la pieza en una frase técnica antes de abrir Fusion

[Es una pieza rectangular que tiene diferentes niveles de altura, con una parte elevada, una torre, un agujero circular y una ranura rectangular.]

### A4 · ¿Qué plano de boceto utilizará primero y por qué?

[Empezaría usando el plano XY (Top), porque desde ahí puedo hacer la forma de la base con sus medidas de ancho y profundidad, y después darle la altura necesaria.]

### A5 · Estrategia inicial de modelado

1. Comenzaría haciendo la parte de abajo de la pieza.
2. Luego le daría la altura que muestra el plano.
3. Después haría la plataforma en la posición indicada.
4. Agregaría la torre para formar la parte más alta.
5. Haría el agujero circular con su medida y ubicación.
6. Al final haría la ranura rectangular y el corte correspondiente.

---

## B. Desarrollo del modelo

### B1 · Boceto base

- Plano seleccionado: Plano XY (Top).
- Geometría principal: Hice un rectángulo para comenzar la pieza.
- Restricciones aplicadas: Usé restricciones horizontales y verticales para mantener la forma.
- Dimensiones aplicadas: Coloqué 90 mm de ancho y 60 mm de profundidad.
- Estado del boceto: El boceto quedó completamente definido.
  
### B2 · Operaciones realizadas

| Nº | Operación | Qué hice |
|---|---|---|
| 1 | Extrude | Le di altura a la base de la pieza. |
| 2 | Sketch + Extrude | Dibujé la plataforma y después la levanté. |
| 3 | Sketch + Extrude | Hice la torre para completar la parte más alta. |
| 4 | Sketch + Cut | Dibujé el círculo de Ø14 mm y realicé el agujero. |
| 5 | Sketch + Cut | Hice la forma de la ranura y luego realicé el corte. |
| 6 | Verificación | Comparé la pieza con el plano para revisar que estuviera correcta. |

### B3 · Cambios realizados durante el modelado

| Nº | Cambio realizado | Razón |
|---|---|---|
| 1 | Cambié un poco la posición de la plataforma. | Para acomodarla mejor según el plano. |
| 2 | Moví el agujero a la ubicación correcta. | Para que quedara donde indican las medidas. |
| 3 | Ajusté la ranura rectangular. | Para que su posición coincidiera con el plano. |
---

## C · Verificación del modelo

### C1 · Comparación de vistas

| Vista | ¿Coincide con el plano? | Qué revisé |
|---|---|---|
| Front | Sí | Comparé el ancho y las alturas de la pieza con el plano. |
| Top | Sí | Revisé que cada parte estuviera ubicada en el lugar correcto. |
| Right | Sí | Comparé la profundidad y la forma de los diferentes niveles. |

### C2 · Verificación de dimensiones

| Medida revisada | Medida del plano | Medida del modelo | ¿Está correcta? |
|---|---:|---:|---|
| Ancho de la pieza | 90 mm | 90 mm | Sí |
| Profundidad de la pieza | 60 mm | 60 mm | Sí |
| Altura de la pieza | 42 mm | 42 mm | Sí |
| Agujero circular | Ø14 mm | Ø14 mm | Sí |
| Ranura rectangular | 14 × 12 mm | 14 × 12 mm | Sí |

### C3 · Editabilidad paramétrica

La pieza quedó hecha por partes y con sus medidas definidas. Si después necesito cambiar alguna medida, puedo entrar al Sketch de esa parte, modificarla y actualizar el modelo sin tener que comenzar desde cero.
## D. Evidencias

### D1 · Modelo final

Modelo completo en orientación pictórica, con nombre del diseño y ViewCube visibles.

![Lab I-B: Modelo final](S09_LabIB_Modelo_Apellido_Nombre.png)

### D2 · Vistas de verificación

Montaje de Front, Top y Right del modelo, presentado de manera clara para comparar con el plano base.

![Lab I-B: Vistas](S09_LabIB_Vistas_Apellido_Nombre.png)

### D3 · Boceto y restricciones

Captura del boceto más representativo con restricciones y dimensiones visibles.

![Lab I-B: Boceto](S09_LabIB_Boceto_Apellido_Nombre.png)

### D4 · Timeline / historial paramétrico

Captura donde se observen las operaciones principales del historial del modelo.

![Lab I-B: Timeline](S09_LabIB_Timeline_Apellido_Nombre.png)

### D5 · Verificación dimensional

Captura de `Inspect > Measure` con una dimensión crítica y el elemento seleccionado visibles.

![Lab I-B: Medicion](S09_LabIB_Medicion_Apellido_Nombre.png)

---

## E. Checklist de entrega

- [ ] Analicé el plano antes de comenzar el modelado.
- [ ] Registré X, Y y Z totales.
- [ ] Identifiqué las características principales y las vistas que las definen.
- [ ] Registré una estrategia inicial antes de modelar.
- [ ] El modelo final corresponde a Front, Top y Right.
- [ ] Verifiqué al menos cinco dimensiones críticas.
- [ ] Los bocetos principales tienen restricciones y dimensiones coherentes.
- [ ] El historial de operaciones es legible y editable.
- [ ] El nombre del archivo cumple la nomenclatura solicitada.
- [ ] El archivo editable está disponible en Fusion Cloud con acceso docente.
- [ ] Las cinco evidencias se visualizan correctamente en GitHub.
- [ ] Esta ficha está completa.

---

# F. Rúbrica oficial del Laboratorio integrador I-B

> Esta rúbrica reproduce los criterios y valores establecidos en el programa oficial. La persona docente puede anotar el puntaje obtenido y observaciones en las columnas finales.

| Criterio oficial | Valor máximo | Evidencia principal en esta ficha | Puntaje obtenido | Observaciones de evaluación |
|---|---:|---|---:|---|
| Interpretación correcta del plano o conjunto de vistas | 2,0 % | Secciones A1–A5 y C1 | [Evaluador] | [Evaluador] |
| Reconstrucción tridimensional coherente | 2,5 % | Secciones B1–B3, D1 y D2 | [Evaluador] | [Evaluador] |
| Aplicación de restricciones y dimensiones | 1,5 % | B1, D3 y C2 | [Evaluador] | [Evaluador] |
| Precisión geométrica y correspondencia con el plano | 2,0 % | C1, C2, D2 y D5 | [Evaluador] | [Evaluador] |
| Organización, nomenclatura y archivo editable | 1,0 % | Identificación, B2, D4 y checklist | [Evaluador] | [Evaluador] |
| Presentación y cumplimiento del enunciado | 1,0 % | Ficha completa, evidencias y checklist | [Evaluador] | [Evaluador] |
| **Total** | **10,0 %** |  | **[Evaluador]** | **[Evaluador]** |

## G. Resumen para evaluación asistida por ChatGPT

Este bloque debe permitir una revisión rápida sin tener que inferir información faltante.

- ¿El estudiante interpretó correctamente X, Y y Z? [Respuesta]
- ¿Las características listadas corresponden con el plano? [Respuesta]
- ¿La estrategia inicial es coherente? [Respuesta]
- ¿El modelo final coincide con las tres vistas? [Respuesta]
- ¿Las dimensiones críticas coinciden? [Respuesta]
- ¿Los bocetos muestran restricciones y dimensiones adecuadas? [Respuesta]
- ¿El timeline muestra una reconstrucción paramétrica razonable? [Respuesta]
- ¿El archivo y las evidencias cumplen nomenclatura y presentación? [Respuesta]
- Incidencias que el evaluador debería revisar directamente en Fusion: [Respuesta]

## H. Retroalimentación del evaluador

### Fortalezas

[Evaluador]

### Aspectos por corregir

[Evaluador]

### Calificación final

**[Evaluador] / 10,0 %**
