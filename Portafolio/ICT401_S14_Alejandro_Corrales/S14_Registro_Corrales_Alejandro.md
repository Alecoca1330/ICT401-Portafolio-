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
|---:|---|---|---:|---|:---:|
| 1 | 1 | Base | 1 | Base del ensamblaje | [x] |
| 2 | 2 | Soporte | 1 | Soporte vertical | [x] |
| 3 | 3 | Pasador | 1 | Pasador del alojamiento | [x] |

![Lista básica de componentes e identificadores](evidencias/S14_E3_Lista_Componentes.png)

| Comparación | Resultado |
|---|---|
| Diferencia encontrada entre el Browser, la vista y la lista | Al inicio la tabla mostraba el número de pieza en lugar del nombre de cada componente. |
| Corrección aplicada | Se ajustó la información de la tabla para que aparecieran los nombres Base, Soporte y Pasador. |
| ¿Cada globo o número de referencia corresponde una sola vez a un componente? | Sí, cada identificador apunta a una pieza diferente y coincide con la lista. |
## Lección 4. Revisión y documentación final

### 6. Revisión del dibujo técnico

| Elemento revisado | Estado |
|---|:---:|
| Vista frontal incluida | [x] |
| Vista superior incluida | [x] |
| Vista lateral derecha incluida | [x] |
| Vista explosionada incluida | [x] |
| Lista de componentes incluida | [x] |
| Globos o identificadores incluidos | [x] |
| Cajetín visible | [x] |
| Información legible | [x] |
| Vistas sin traslapes | [x] |
| Lista y globos relacionados correctamente | [x] |

**Evidencia final:**

![Documentación final del conjunto](evidencias/S14_E4_Documentacion_Final.png)

### 7. Problemas encontrados y correcciones realizadas

| Problema encontrado | Corrección realizada |
|---|---|
| La lista mostraba inicialmente el número de pieza en lugar del nombre. | Se ajustó la información de la tabla para mostrar Base, Soporte y Pasador. |
| Fue necesario organizar los elementos del Drawing para mantener la lectura clara. | Se acomodaron las vistas, la lista de piezas y los globos sin tapar el cajetín. |
| La vista explosionada debía mantenerse relacionada con el conjunto original. | Se utilizó el Storyboard creado en Animation y se integró en el mismo Drawing. |

### 8. Autoevaluación

| Criterio | Valoración |
|---|---|
| Identificación de los componentes | Cumplido |
| Secuencia de separación | Cumplido |
| Vista explosionada | Cumplido |
| Lista de componentes | Cumplido |
| Globos de referencia | Cumplido |
| Organización del Drawing | Cumplido |
| Evidencias solicitadas | Cumplido |

### 9. Cierre de la Semana 14

Durante esta semana se trabajó con el ensamblaje realizado anteriormente y se creó una vista explosionada para representar de mejor manera la relación entre sus componentes. Se mantuvo la base como referencia, se desplazó el soporte verticalmente y el pasador siguiendo su propio eje.

Después se creó el Drawing con las vistas normales del conjunto y se agregó la vista explosionada, la lista de componentes y los globos de identificación. Finalmente, se revisó que toda la información quedara ordenada, legible y relacionada correctamente con cada pieza del ensamblaje.
