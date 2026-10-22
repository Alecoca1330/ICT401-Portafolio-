# Ficha de registro: Semana 14

**Curso:** ICT401 – Dibujo Técnico Asistido por Computadora
**Semana:** 14
**Tema:** Vista explosionada, lista de componentes y documentación de conjuntos
**Estudiante:** Apellido, Nombre
**Fecha:** 22 de octubre de 2026
**Archivo o enlace del conjunto:** `ruta/al/archivo-o-enlace`

## Propósito

Esta ficha registra las decisiones, comprobaciones, dificultades y evidencias de la documentación del conjunto. Se trabaja con el ensamblaje validado en la Semana 13. No sustituye la rúbrica oficial de la Fase 3 ni la Prueba Corta 3.

## Criterios normativos de revisión

La aplicación de estas normas es didáctica y selectiva; no constituye una certificación integral de conformidad normativa. Registre la evidencia o la limitación encontrada.

| Referencia | Criterio que se aplica | Evidencia o limitación registrada |
|---|---|---|
| INTE/ISO 128-1:2024 | La vista comunica el conjunto sin ambigüedad y conserva la identidad de sus componentes. |  |
| INTE/ISO 128-2:2023 | Contornos, ejes, líneas ocultas y líneas de trayectoria se distinguen; las trayectorias no sustituyen los contornos. |  |
| INTE/ISO 128-3:2025 / ISO 5456-2 | La orientación, las vistas y el método de proyección son coherentes. |  |
| ISO 5457 | La hoja, orientación, escala y distribución permiten leer la documentación. |  |
| INTE/ISO 7200:2008 | El cajetín o encabezado identifica conjunto, estudiante, fecha, unidades, escala y versión cuando estén disponibles. |  |
| ISO 7573 / ISO 6433 | La lista, las cantidades y los números de referencia corresponden a componentes reales. |  |
| ISO 16792:2021 | Modelo, Storyboard, Drawing, lista y evidencias corresponden a la misma versión. |  |

**Alcance:** no se aplican ISO 129-1, ISO 8015 ni ISO 2768 como requisitos de esta semana porque no se solicitan cotas funcionales ni tolerancias de fabricación.

## Producto documental integrado

La entrega debe corresponder a **un único Drawing de Fusion**. Registre aquí cómo integró las representaciones:

| Elemento obligatorio | Hoja o ubicación dentro del Drawing | Comprobado |
|---|---|:---:|
| Vistas normales `Front`, `Top` y `Right` |  | [ ] |
| Proyección de primer diedro (sistema europeo) |  | [ ] |
| Símbolo o configuración del método de proyección |  | [ ] |
| Vista explosionada del `Storyboard` |  | [ ] |
| Lista de componentes |  | [ ] |
| Globos o números de referencia |  | [ ] |
| Cajetín e identificación del conjunto |  | [ ] |
| Nombre y versión del modelo de origen |  | [ ] |

Las vistas pueden distribuirse en varias hojas, pero deben permanecer dentro del mismo Drawing. No entregue la vista explosionada y las vistas ortogonales como documentos independientes.

### Distribución de la hoja

| Control de distribución | Registro o evidencia |
|---|---|
| Vista principal utilizada como referencia |  |
| `Top` colocado debajo de `Front` |  |
| `Right` colocado a la izquierda de `Front` |  |
| Alineación y separación entre vistas ortogonales |  |
| Zona reservada para la vista explosionada |  |
| Ubicación de la lista y los globos |  |
| Cajetín libre de superposiciones |  |
| Hoja adicional utilizada dentro del mismo Drawing, si corresponde |  |

## Lección 1. Análisis del ensamblaje y planificación

### 1. Estado inicial

| Elemento | Registro |
|---|---|
| Nombre del archivo original | Ensamblaje de la Semana 13 |
| Nombre de la copia de trabajo | [pon aquí el nombre con el que guardaste la copia de Semana 14] |
| Versión o fecha de respaldo | 22/10/2026 |
| Número de componentes | 3 |
| Componente de referencia | Base |
| Estado inicial del ensamblaje | Ensamblaje completo, con base, soporte y pasador colocados y relacionados correctamente. |

**Captura del conjunto antes de crear la vista explosionada:**

![Conjunto inicial de la Semana 13](evidencias/S14_E1_Conjunto_Inicial.png)

| Análisis de referencia | Registro |
|---|---|
| ¿Por qué se mantiene ese componente como referencia? | La base se mantiene como referencia porque sostiene las demás piezas y permite entender la posición del soporte y del pasador dentro del conjunto. |

### 2. Componentes del conjunto

| ID | Nombre del componente | Función | Cantidad | Referencia o archivo | Observaciones |
|---|---|---|---:|---|---|
| 1 | Base | Servir como apoyo y referencia principal del ensamblaje. | 1 | Pieza de Semana 13 | Se mantiene fija. |
| 2 | Soporte vertical | Sostener y ubicar el alojamiento donde pasa el pasador. | 1 | Pieza de Semana 13 | Unido de forma rígida a la base. |
| 3 | Pasador | Atravesar el alojamiento del soporte y permitir el giro. | 1 | Pieza de Semana 13 | Conserva movimiento de revolución. |

**Captura del conjunto antes de crear la vista explosionada:**
![Conjunto inicial de la Semana 13](evidencias/S14_E1_Conjunto_Inicial.png)

| Análisis de referencia | Registro |
|---|---|
| ¿Por qué se mantiene ese componente como referencia? | La base se mantiene como referencia porque sostiene las demás piezas y permite entender la posición del soporte y del pasador dentro del conjunto. |

### 2. Componentes del conjunto

| ID | Nombre del componente | Función | Cantidad | Referencia o archivo | Observaciones |
|---|---|---|---:|---|---|
| 1 | Base | Servir como apoyo y referencia principal del ensamblaje. | 1 | Pieza de Semana 13 | Se mantiene fija. |
| 2 | Soporte vertical | Sostener y ubicar el alojamiento donde pasa el pasador. | 1 | Pieza de Semana 13 | Unido de forma rígida a la base. |
| 3 | Pasador | Atravesar el alojamiento del soporte y permitir el giro. | 1 | Pieza de Semana 13 | Conserva movimiento de revolución. |

### 3. Plan de montaje y separación

**Orden previsto de montaje y desmontaje:**

| Orden | Acción | Componente | Referencia o contacto | Dirección | Función comunicada | Comprobado |
|---:|---|---|---|---|---|:---:|
| 1 | Montar | Base | Superficie de apoyo | Se mantiene fija | Sirve como referencia principal del conjunto. | [x] |
| 2 | Montar | Soporte vertical | Cara inferior del soporte con cara superior de la base | Vertical | Muestra cómo el soporte se coloca sobre la base. | [x] |
| 3 | Montar | Pasador | Alojamiento circular del soporte | Siguiendo su eje | Muestra cómo el pasador atraviesa el soporte. | [x] |

| Decisión | Respuesta |
|---|---|
| Componente que se colocaría primero | La base. |
| Componente que se retiraría al final | La base, porque se mantiene como referencia del conjunto. |
| Criterio utilizado para definir el orden | Se siguió la forma en que las piezas se apoyan y se relacionan entre sí durante el montaje. |

| Orden | Componente | Dirección o referencia de separación | Razón funcional | Distancia aproximada | Comprobado |
|---:|---|---|---|---:|---|
| 1 | Pasador | A lo largo de su propio eje | Permite mostrar claramente cómo atraviesa el alojamiento del soporte. | Se definirá en L2 según la legibilidad. | [x] |
| 2 | Soporte vertical | Verticalmente hacia arriba desde la base | Permite mostrar las superficies de contacto entre soporte y base. | Se definirá en L2 según la legibilidad. | [x] |
| 3 | Base | Se mantiene fija | Funciona como referencia principal del ensamblaje. | 0 mm | [x] |

| Pregunta de análisis | Respuesta |
|---|---|
| ¿Qué relación de montaje comunica la secuencia? | La secuencia muestra que primero se tiene la base como apoyo, luego se coloca el soporte y finalmente se introduce el pasador en el alojamiento. |
| ¿Qué dificultad o duda debe comprobarse durante la Lección 2? | Se debe comprobar qué distancia de separación permite ver claramente las tres piezas sin perder la relación visual entre ellas. |

## Lección 2. Construcción de la vista explosionada

### 4. Construcción en Fusion

**Herramienta utilizada:** Animation > Transform > Transformar componentes  
**Storyboard:** Storyboard de Semana 14  
**Vista u orientación principal:** Vista isométrica  
**Criterio para separar los componentes:** Se mantuvo la base como referencia, el soporte se desplazó verticalmente y el pasador se separó siguiendo su propio eje.

**Captura de la vista explosionada:**

![Vista explosionada inicial](evidencias/S14_E2_Vista_Explosionada.png)

**Captura de la posición o versión intermedia:**

![Posición o storyboard intermedio](evidencias/S14_E2_Posicion_Intermedia.png)

### Decisiones realizadas en Fusion

| Decisión | Acción realizada | Resultado observado | Evidencia |
|---|---|---|---|
| Orientación principal | Se utilizó una vista isométrica para observar mejor las tres piezas. | Los componentes se distinguen con claridad. | S14_E2_Vista_Explosionada.png |
| Dirección de separación | El pasador se movió siguiendo su eje y el soporte se desplazó hacia arriba. | Se mantiene clara la relación entre las piezas. | S14_E2_Vista_Explosionada.png |
| Distancia o posición | El pasador se separó aproximadamente 50 mm y el soporte se alejó lo suficiente de la base. | La separación permite entender el conjunto sin alejar demasiado las piezas. | S14_E2_Vista_Explosionada.png |
| Captura de posición / storyboard | Se registró una posición intermedia del proceso de separación. | Permite observar cómo se fue construyendo la vista explosionada. | S14_E2_Posicion_Intermedia.png |

**¿Se modificó alguna geometría?** Sí [ ] No [x]

**¿Se capturó la posición o el storyboard?** Sí [x] No [ ]

**¿Las líneas de trayectoria se distinguen de contornos, ejes y líneas ocultas?** Sí [x] No [ ]

## Lección 3. Lista de componentes y rotulación

### 5. Lista básica de componentes

| Ítem | Identificador visible | Nombre en la lista | Cantidad | Componente correspondiente | Verificado |
|---:|---|---|---:|---|---|
| 1 |  |  |  |  | [ ] |
| 2 |  |  |  |  | [ ] |
| 3 |  |  |  |  | [ ] |
| 4 |  |  |  |  | [ ] |
| 5 |  |  |  |  | [ ] |

![Lista básica de componentes e identificadores](evidencias/S14_E3_Lista_Componentes.png)

| Comparación | Resultado |
|---|---|
| Diferencia encontrada entre el Browser, la vista y la lista |  |
| Corrección aplicada |  |
| ¿Cada globo o número de referencia corresponde una sola vez a un componente? |  |

## Lección 4. Documentación y evaluación

### 6. Documentación del conjunto

| Criterio | Sí | No | Corrección necesaria |
|---|:---:|:---:|---|
| La vista muestra todos los componentes importantes | [ ] | [ ] |  |
| La separación sigue una lógica de montaje | [ ] | [ ] |  |
| El mismo Drawing contiene Front, Top y Right del ensamble normal | [ ] | [ ] |  |
| Las vistas ortogonales están organizadas en primer diedro europeo | [ ] | [ ] |  |
| El mismo Drawing contiene también la vista explosionada | [ ] | [ ] |  |
| `Top` está debajo de `Front` y `Right` a la izquierda de `Front` | [ ] | [ ] |  |
| Las vistas relacionadas están alineadas y suficientemente separadas | [ ] | [ ] |  |
| La vista explosionada, lista y globos tienen una zona propia | [ ] | [ ] |  |
| Ningún elemento invade el cajetín | [ ] | [ ] |  |
| Se comprobó el símbolo o configuración de primer diedro | [ ] | [ ] |  |
| Los identificadores se leen con claridad | [ ] | [ ] |  |
| La lista coincide con el modelo | [ ] | [ ] |  |
| Los contornos, ejes, ocultas y trayectorias se distinguen | [ ] | [ ] |  |
| Los globos o identificadores coinciden una sola vez con la lista | [ ] | [ ] |  |
| La hoja, escala, orientación e identificación son coherentes | [ ] | [ ] |  |
| El modelo, Storyboard y Drawing corresponden a la misma versión | [ ] | [ ] |  |
| La orientación facilita la interpretación | [ ] | [ ] |  |
| La escala permite leer textos y componentes | [ ] | [ ] |  |
| No hay superposiciones innecesarias | [ ] | [ ] |  |
| El título y los datos del conjunto están completos | [ ] | [ ] |  |
| La versión del modelo, Storyboard, Drawing y evidencias coincide | [ ] | [ ] |  |

**Archivo o captura de la documentación final:** <br>
![Documentación final del conjunto](evidencias/S14_E4_Documentacion_Final.png)

| Resultado de la revisión con la rúbrica | Registro |
|---|---|
| Criterio que cumple mejor |  |
| Criterio que requiere corrección |  |
| Corrección prioritaria |  |

### 7. Problemas y correcciones

| Problema observado | Causa probable | Corrección aplicada | Evidencia |
|---|---|---|---|
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### 8. Autoevaluación

| Pregunta | Respuesta |
|---|---|
| ¿Qué componente funcionó como referencia y por qué? |  |
| ¿Qué criterio utilizó para definir el orden de separación? |  |
| ¿Qué diferencia existe entre mover una pieza y documentar una vista explosionada? |  |
| ¿Cómo comprobó que la lista coincide con el conjunto? |  |
| ¿Qué corrección mejoró más la legibilidad de la documentación? |  |

## Cierre de las cuatro lecciones

### 9. Evidencias finales

| Evidencia | Nombre o ruta del archivo | Completa | Observaciones |
|---|---|:---:|---|
| Archivo o enlace verificable del conjunto en Fusion |  | [ ] |  |
| Vista explosionada | `evidencias/S14_E2_Vista_Explosionada.png` | [ ] |  |
| Lista básica de componentes | `evidencias/S14_E3_Lista_Componentes.png` | [ ] |  |
| Documentación del conjunto | `evidencias/S14_E4_Documentacion_Final.png` | [ ] |  |
| Captura del estado inicial | `evidencias/S14_E1_Conjunto_Inicial.png` | [ ] |  |
| Tabla y justificación del componente de referencia |  | [ ] |  |
| Plan de montaje y separación de la Lección 1 |  | [ ] |  |
| Registro de la dificultad o duda comprobada |  | [ ] |  |
| Capturas del proceso o de las correcciones |  | [ ] |  |
| Registro de la posición o storyboard | `evidencias/S14_E2_Posicion_Intermedia.png` | [ ] |  |
| Ficha completa y nombrada correctamente |  | [ ] |  |
| Revisión de la rúbrica de la Fase 3 |  | [ ] |  |

### 10. Cierre

| Cierre | Registro |
|---|---|
| Dificultad principal |  |
| Decisión técnica más importante |  |
| Pendiente antes de entregar |  |
| Nombre final de la versión entregada |  |
