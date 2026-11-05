
# Ficha de registro: Laboratorio Integrador II-B

**Curso:** ICT401 – Dibujo Técnico Asistido por Computadora  
**Semana:** 16  
**Laboratorio:** Integrador II-B  
**Valor del laboratorio:** 10 %  
**Estudiante o equipo:** Manuel Alejandro Corrales Casanova y Francella Madrigal Vargas  
**Proyecto:** Sistema de calibración de diámetros para tornillos en procesos de producción automotriz  
**Fecha:** 05 de noviembre de 2026  
**Versión inicial:** `ICT401_Ensamblaje_Fase3`  
**Versión evaluada:** `ICT401_Ensamblaje_Fase3` (diseño revisado)

## Propósito y alcance

Esta ficha registra la evidencia del Laboratorio Integrador II-B: integración del modelo, ensamblaje, documentación, exportaciones, tolerancias introductorias y control dimensional básico.

La ficha **no sustituye la entrega de la Fase 4 del Proyecto Integrador**, cuyo valor oficial es 7 % y cuyos requisitos se definen en su propia rúbrica. Algunas evidencias pueden reutilizarse si cumplen ambos propósitos, pero deben conservarse separados el registro del laboratorio y la entrega de la fase.

No se evalúan mediante esta ficha la fabricación física, la metrología avanzada, los procesos completos de manufactura ni la presentación final de la Semana 17.

## Instrucciones

1. Complete la ficha durante las cuatro lecciones.
2. Registre la versión exacta del proyecto utilizada.
3. Conserve una copia de respaldo antes de modificar o exportar.
4. Registre el propósito, formato y comprobación de cada archivo de salida.
5. No invente tolerancias cuando no estén indicadas.
6. Cada medición debe incluir característica, unidad, método y limitación.
7. Use nombres o rutas verificables para las evidencias.

Los textos que comienzan con **Ejemplo:** muestran el nivel de detalle esperado. Sustitúyalos por los datos reales de su proyecto; no los copie como resultados propios.

### Ruta general en Fusion

1. Abra el **Data Panel**, localice el proyecto y abra el diseño vigente.
2. En el **Browser**, confirme componentes, cuerpos y el componente raíz.
3. Revise **Document Settings > Units** y anote las unidades activas.
4. Para el plano, abra el **Drawing** correspondiente y revise sus hojas.
5. Para medir, utilice **Inspect > Measure** y seleccione caras, aristas, puntos o diámetros.
6. Para exportar, utilice **File > Export** cuando el formato esté disponible. Para STL, seleccione el cuerpo o componente y use **Save As Mesh**.
7. Si una orden tiene otro nombre, use el buscador de comandos y registre la orden equivalente.

## Lección 1. Auditoría del proyecto y documentación

| Elemento | Registro |
|---|---|
| Archivo o enlace principal | Fusion 360, Data Panel: `ICT401_Ensamblaje_Fase3` |
| Versión revisada | `ICT401_Ensamblaje_Fase3` |
| Fecha de la versión | Revisión realizada el 05-11-2026 |
| Unidades del proyecto | Milímetros (mm), revisados mediante `Document Settings > Units` |
| Plano o Drawing utilizado | Planos del calibrador, soporte y ensamblaje de la Fase 4 |
| Ensamblaje utilizado, si corresponde | `ICT401_Ensamblaje_Fase3` |
| Lista básica de componentes, si corresponde | Calibrador y soporte |
| Ubicación del respaldo inicial | `ICT401_S16_Ensamblaje_Respaldo_Inicial` |
| Problema prioritario encontrado | Durante la auditoría se detectó el aviso «La referencia 1 no está actualizada» |

### Revisión de coherencia

| Control | Sí | No | N.A. | Evidencia o corrección |
|---|:---:|:---:|:---:|---|
| El modelo y la documentación corresponden a la misma versión. | [ ] | [ ] | [ ] | Se utilizaron los archivos de Fase 4 y el ensamblaje de Fase 3; no se registró el identificador interno de versión |
| El plano contiene las vistas, cotas y datos que corresponden. | [x] | [ ] | [ ] | Capturas de revisión de los tres planos |
| El cajetín o identificación está completo según la plantilla. | [ ] | [ ] | [ ] | No se documentó la comprobación de todos los campos |
| La lista coincide con el ensamblaje, cuando corresponde. | [ ] | [ ] | [x] | Se identificaron calibrador y soporte; no se registró una `Parts List` formal |
| La orientación y la escala son coherentes. | [ ] | [ ] | [ ] | Se revisaron visualmente los planos, sin registrar las escalas exactas |

**Captura del estado inicial:** `S16_E1_Estado_Inicial.png`

### Evidencia 1. Estado inicial

<img src="S16_E1_Estado_Inicial.png" width="350" alt="Estado inicial del ensamblaje">

### Evidencia 2. Respaldo inicial

<img src="S16_E1_Respaldo_Inicial.png" width="350" alt="Respaldo inicial del proyecto">

### Evidencia 3. Revisión del plano del calibrador

<img src="S16_E1_Revision_Plano_Calibrador.png" width="350" alt="Plano del calibrador">

### Evidencia 4. Revisión del plano del ensamblaje

<img src="T16_E1_Revision_Plano_Ensamblaje.png" width="350" alt="Plano del ensamblaje">

### Evidencia 5. Revisión del plano del soporte

<img src="S16_E1_Revisión_Plano_Soporte.png" width="350" alt="Plano del soporte">

### Evidencia 6. Verificación de unidades

<img src="S16_E1_Verificacion_Unidades.png" width="350" alt="Verificación de unidades en Fusion">

**Corrección prioritaria antes de exportar:** Se identificó la necesidad de actualizar la referencia del ensamblaje y comprobar su relación con los planos. No se documentó una confirmación definitiva de que desapareciera el aviso.

## Lección 2. Exportaciones y comprobación de archivos

En Fusion, seleccione primero el objeto correcto en el **Browser**. No exporte todo el proyecto si solo se solicita una pieza o un componente.

| Formato | Propósito | Configuración relevante | Archivo generado | Comprobado |
|---|---|---|---|:---:|
| STL | N.A. No se requirió una malla para impresión 3D | No se utilizó `Save As Mesh` | No generado | N.A. |
| STEP | N.A. No se requirió intercambio de geometría 3D | No se realizó exportación STEP | No generado | N.A. |
| DXF | Intercambio de geometría bidimensional | Exportación de planos en formato DXF | `ICT401_Fase4_Plano_Calibrador Plano1.dxf` y `ICT401_Fase4_Plano_Soporte Plano dxt.dxf` | [x] |
| PDF | Presentación y consulta de planos técnicos | Exportación de los tres Drawings a PDF | `ICT401_Fase4_Plano_Calibrador.pdf`, `ICT401_Fase4_Plano_Soporte.pdf` y `ICT401_Fase4_Plano_Ensamblaje.pdf` | [x] |
| Otro | N.A. | N.A. | No generado | N.A. |

Marque `N.A.` cuando un formato no corresponda al proyecto y justifique la decisión.

### Comprobación de cada salida

| Archivo | Geometría | Unidades | Escala/orientación | Versión | Ubicación | Resultado |
|---|:---:|:---:|:---:|:---:|---|---|
| `ICT401_Fase4_Plano_Calibrador.pdf` | [x] | [x] | [ ] | [ ] | Archivos Fase 4 | PDF abierto y revisado |
| `ICT401_Fase4_Plano_Soporte.pdf` | [x] | [x] | [ ] | [ ] | Archivos Fase 4 | PDF abierto y revisado |
| `ICT401_Fase4_Plano_Ensamblaje.pdf` | [x] | [x] | [ ] | [ ] | Archivos Fase 4 | PDF abierto y revisado |
| `ICT401_Fase4_Plano_Calibrador Plano1.dxf` | [x] | [ ] | [ ] | [ ] | Archivos Fase 4 | DXF abierto y revisado |
| `ICT401_Fase4_Plano_Soporte Plano dxt.dxf` | [x] | [ ] | [ ] | [ ] | Archivos Fase 4 | DXF abierto y revisado |

### Evidencia 1. Comprobación del PDF del calibrador

<img src="S16_E2_Comprobacion_PDF_Calibrador.png" width="350" alt="Comprobación del PDF del calibrador">

### Evidencia 2. Comprobación del PDF del ensamblaje

<img src="S16_E2_Comprobacion_PDF_Ensamblaje.png" width="350" alt="Comprobación del PDF del ensamblaje">

### Evidencia 3. Comprobación del PDF del soporte

<img src="S16_E2_Comprobacion_PDF_Soporte.png" width="350" alt="Comprobación del PDF del soporte">

**Archivo o captura de comprobación:** Las tres capturas anteriores documentan la apertura de los PDF. También se realizaron comprobaciones de los dos DXF, cuyas capturas no aparecen en la carpeta mostrada.

**Discrepancia encontrada:** No se registraron errores de apertura de los PDF o DXF.

**Corrección aplicada:** Se comprobó la apertura de los archivos fuera del comando de exportación para revisar su visualización.

## Lección 3. Tolerancias y control dimensional básico

En Fusion, la ruta de comprobación es **Design > Inspect > Measure**. En el resultado de la medición deben poder reconocerse la geometría seleccionada y la unidad.

No agregue una tolerancia que no esté indicada en el plano, la rúbrica o la instrucción correspondiente.

| Característica | Dimensión nominal | Tolerancia | Límite inferior | Límite superior | Valor observado | Unidad |
|---|---:|---|---|---|---:|---|
| Diámetro del calibrador Ø6 | 6 | No definida | N.A. | N.A. | 6,00 | mm |
| Diámetro del calibrador Ø8 | 8 | No definida | N.A. | N.A. | 8,00 | mm |
| Diámetro del calibrador Ø10 | 10 | No definida | N.A. | N.A. | 10,00 | mm |
| Diámetro del calibrador Ø12 | 12 | No definida | N.A. | N.A. | 12,00 | mm |

### Método y resultado

| Característica | Herramienta o método | Resultado | Limitación de la comprobación |
|---|---|---|---|
| Diámetro Ø6 | `Inspect > Measure`, arco circular del boceto | Coincide con el valor nominal | Medición digital; no certifica una pieza física |
| Diámetro Ø8 | `Inspect > Measure`, arco circular del boceto | Coincide con el valor nominal | No se definió tolerancia de aceptación |
| Diámetro Ø10 | `Inspect > Measure`, arco circular del boceto | Coincide con el valor nominal | No permite comprobar errores de fabricación |
| Diámetro Ø12 | `Inspect > Measure`, arco circular del boceto | Coincide con el valor nominal | No certifica una pieza fabricada |

**Ejemplo de cálculo, si corresponde:**

Diferencia = valor observado − valor nominal

Para Ø6:

6,00 mm − 6,00 mm = **0,00 mm**

Para Ø8:

8,00 mm − 8,00 mm = **0,00 mm**

Para Ø10:

10,00 mm − 10,00 mm = **0,00 mm**

Para Ø12:

12,00 mm − 12,00 mm = **0,00 mm**

### Evidencia del control dimensional

<img src="S16_E3_Control_Dimensional_4_Agujeros.png" width="350" alt="Control dimensional de los cuatro diámetros">

**Captura o referencia de la medición:** `S16_E3_Control_Dimensional_4_Agujeros.png`

**¿Qué valor o criterio no pudo comprobarse?**

No fue posible comprobar la conformidad de los cuatro diámetros respecto a límites de tolerancia porque no se establecieron tolerancias específicas para ellos. Las mediciones corresponden a geometría digital del boceto y no a piezas fabricadas.

## Lección 4. Integración y cierre del laboratorio

Después de corregir, guarde la versión evaluada desde **File > Save** o la orden equivalente. Compruebe que el archivo exportado y la ficha se refieran a esa misma versión.

### Correcciones finales

| Problema | Acción aplicada | Resultado | Evidencia |
|---|---|---|---|
| Aviso de referencia no actualizada | Se revisó la advertencia del ensamblaje | Se identificó la referencia que requería actualización; no consta confirmación definitiva de resolución | `S16_E1_Estado_Inicial.png` |
| Necesidad de verificar los archivos exportados | Se abrieron y revisaron los PDF y DXF | Se documentó la comprobación de tres PDF y dos DXF | Capturas de la Lección 2 |
| Necesidad de comprobar dimensiones | Se utilizó `Inspect > Measure` en cuatro arcos circulares | Valores de 6, 8, 10 y 12 mm coincidentes con el diseño | `S16_E3_Control_Dimensional_4_Agujeros.png` |

### Evidencia de la documentación del ensamblaje

<img src="ICT401_Fase4_Plano_Ensamblaje.png" width="350" alt="Documentación del ensamblaje">

### Checklist del Laboratorio II-B

- [ ] La versión del modelo y la documentación coincide. No se registró el identificador interno exacto.
- [x] El plano final fue revisado.
- [x] La lista básica de componentes fue identificada: calibrador y soporte. No se documentó una `Parts List` formal.
- [x] Cada archivo exportado tiene un propósito registrado.
- [x] Las salidas fueron revisadas fuera del comando de exportación.
- [ ] Se registraron unidades, escala, orientación y versión. Se registraron las unidades y los nombres de archivos, no las escalas y versiones internas exactas.
- [x] Se realizó al menos una comprobación dimensional básica.
- [x] Las tolerancias introductorias fueron interpretadas sin inventar valores.
- [x] Se registraron discrepancias y las acciones de revisión.
- [ ] La versión evaluada fue respaldada. Se conserva el respaldo inicial, sin una segunda copia evaluada.
- [x] La ficha contiene los registros de las cuatro lecciones.

### Evidencias finales del laboratorio

| Evidencia | Nombre o ruta | Completa | Observaciones |
|---|---|:---:|---|
| Estado inicial y auditoría | `S16_E1_Estado_Inicial.png` | [x] | Captura del ensamblaje inicial |
| Exportaciones y comprobación | `S16_E2_Comprobacion_PDF_Calibrador.png`, `S16_E2_Comprobacion_PDF_Soporte.png`, `S16_E2_Comprobacion_PDF_Ensamblaje.png` | [x] | Tres comprobaciones PDF visibles |
| Control dimensional | `S16_E3_Control_Dimensional_4_Agujeros.png` | [x] | Cuatro diámetros medidos digitalmente |
| Plano final o documentación | `ICT401_Fase4_Plano_Ensamblaje.png` | [x] | Plano del ensamblaje |
| Lista básica, si corresponde | `T16_E1_Revision_Plano_Ensamblaje.png` | [x] | Ensamblaje revisado; no se documentó `Parts List` formal |
| Archivo de respaldo | `S16_E1_Respaldo_Inicial.png` | [x] | Respaldo inicial |
| Ficha completa | `Léame.md` | [x] | Registro del Laboratorio Integrador II-B |

## Separación de la Fase 4

**¿Qué producto o archivo adicional exige la rúbrica de la Fase 4?**

La Fase 4 requiere una entrega independiente de documentación técnica del Proyecto Integrador. Para este proyecto se elaboraron los planos del calibrador, del soporte y del ensamblaje, junto con archivos PDF y DXF. Los demás requisitos deben comprobarse directamente con la rúbrica de Fase 4.

**¿Qué evidencia de esta ficha puede reutilizarse en la Fase 4?**

Se pueden reutilizar las capturas de los planos, los archivos PDF y DXF y la documentación del ensamblaje. También pueden utilizarse las comprobaciones dimensionales como evidencia complementaria de revisión geométrica.

**¿Qué requisito de la Fase 4 todavía no está cubierto por esta ficha?**

Esta ficha no sustituye la entrega independiente de la Fase 4 ni la verificación de todos sus criterios. No se documentó la correspondencia exacta entre las versiones internas del modelo y los planos, ni la resolución definitiva del aviso de referencia.

## Cierre reflexivo

**¿Qué exportación requirió más comprobación y por qué?**

Los archivos DXF requirieron mayor atención porque permiten intercambiar geometría bidimensional y es importante comprobar que las líneas, dimensiones y unidades se interpreten correctamente. Los PDF también se revisaron para verificar la visualización de los planos técnicos.

**¿Qué diferencia encontró entre el valor nominal, la tolerancia y el valor observado?**

El valor nominal es la dimensión establecida en el diseño. La tolerancia es la variación permitida y el valor observado es el resultado de una medición. En nuestro proyecto, los valores observados de 6, 8, 10 y 12 mm coincidieron con los nominales, pero no se definieron tolerancias de aceptación para esos diámetros.

**¿Qué corrección mejoró la confiabilidad del producto técnico?**

La revisión de los planos, la comprobación de los archivos exportados y la verificación digital de los cuatro diámetros permitieron organizar mejor la documentación y comprobar que las dimensiones medidas coincidieran con el diseño.

**¿Qué limitación debe comunicar antes de considerar terminada la Fase 4?**

Las mediciones realizadas son digitales y no certifican una pieza fabricada. Además, las tolerancias de los diámetros del calibrador no están definidas y la entrega de Fase 4 debe verificarse por separado con su rúbrica oficial.
