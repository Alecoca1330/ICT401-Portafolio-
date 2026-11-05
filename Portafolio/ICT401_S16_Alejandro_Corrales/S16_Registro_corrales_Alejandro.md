# Ficha de registro: Laboratorio Integrador II-B

**Curso:** ICT401 – Dibujo Técnico Asistido por Computadora
**Semana:** 16
**Laboratorio:** Integrador II-B
**Valor del laboratorio:** 10 %
**Estudiante o equipo:** Manuel Alejandro Corrales Casanova y Francella Madrigal Vargas
**Proyecto:** Sistema de calibración de diámetros para tornillos en procesos de producción automotriz
**Fecha:** 05 de noviembre de 2026
**Versión inicial:** `ICT401_Ensamblaje_Fase3` — número de versión interno pendiente de confirmar
**Versión evaluada:** `ICT401_Ensamblaje_Fase3` — ensamblaje revisado; número de versión interno pendiente de confirmar

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

| Elemento                                    | Registro                                                                                                                                          |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Archivo o enlace principal                  | Fusion 360, Data Panel: `ICT401_Ensamblaje_Fase3`                                                                                                 |
| Versión revisada                            | `ICT401_Ensamblaje_Fase3`. Identificador interno `v__` pendiente de confirmar                                                                     |
| Fecha de la versión                         | Fecha de revisión: 05-11-2026. Fecha de creación de la versión interna: no confirmada                                                             |
| Unidades del proyecto                       | Milímetros (mm), utilizados en la documentación y las mediciones. Evidencia: `S16_E1_Verificacion_Unidades.png`                                   |
| Plano o Drawing utilizado                   | `ICT401_Fase4_Plano_Calibrador`, `ICT401_Fase4_Plano_Soporte` y `ICT401_Fase4_Plano_Ensamblaje`                                                   |
| Ensamblaje utilizado, si corresponde        | `ICT401_Ensamblaje_Fase3`, con calibrador y soporte                                                                                               |
| Lista básica de componentes, si corresponde | Componentes identificados en el ensamblaje: calibrador y soporte. No se confirmó una tabla `Parts List` independiente                             |
| Ubicación del respaldo inicial              | Fusion 360: `ICT401_S16_Ensamblaje_Respaldo_Inicial`                                                                                              |
| Problema prioritario encontrado             | En la revisión inicial apareció la advertencia «La referencia 1 no está actualizada». La confirmación de su resolución definitiva quedó pendiente |

### Revisión de coherencia

| Control                                                       |  Sí |  No | N.A. | Evidencia o corrección                                                                                                                                                                                  |
| ------------------------------------------------------------- | :-: | :-: | :--: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| El modelo y la documentación corresponden a la misma versión. | [x] | [ ] |  [ ] | Pendiente: comparar los identificadores internos de versión del ensamblaje y de los planos. Los nombres de los archivos están identificados, pero no demuestran por sí solos que sean la misma revisión |
| El plano contiene las vistas, cotas y datos que corresponden. | [x] | [ ] |  [ ] | Se revisaron los tres planos. Evidencias: `S16_E1_Revision_Plano_Calibrador.png`, `S16_E1_Revision_Plano_Soporte.png` y `S16_E1_Revision_Plano_Ensamblaje.png`                                          |
| El cajetín o identificación está completo según la plantilla. | [x] | [ ] |  [ ] | Pendiente de confirmar todos los campos exigidos en los cajetines de los tres planos                                                                                                                    |
| La lista coincide con el ensamblaje, cuando corresponde.      | [x] | [ ] |  [x] | Se identificaron calibrador y soporte en el ensamblaje, pero no se verificó una `Parts List` formal                                                                                                     |
| La orientación y la escala son coherentes.                    | [x] | [ ] |  [ ] | Se revisaron visualmente los planos. Falta registrar las escalas exactas y confirmar su coherencia con las vistas                                                                                       |

**Captura del estado inicial:** `evidencias/S16_E1_Estado_Inicial.png`

**Corrección prioritaria antes de exportar:** Revisar y actualizar la referencia señalada por Fusion 360, guardar el diseño y comprobar que los planos utilizados correspondan a la revisión vigente. La advertencia fue identificada, pero no se dispone de confirmación suficiente para declarar que quedó resuelta.

## Lección 2. Exportaciones y comprobación de archivos

En Fusion, seleccione primero el objeto correcto en el **Browser**. No exporte todo el proyecto si solo se solicita una pieza o un componente.

| Formato | Propósito                                                                          | Configuración relevante                                                                           | Archivo generado                                                                                            | Comprobado |
| ------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | :--------: |
| STL     | N.A. No se requirió una malla para impresión 3D durante este laboratorio           | N.A.; no se utilizó `Save As Mesh`                                                                | No generado                                                                                                 |    N.A.    |
| STEP    | N.A. No se requirió intercambio adicional de geometría 3D durante este laboratorio | N.A.; no se efectuó exportación STEP                                                              | No generado                                                                                                 |    N.A.    |
| DXF     | Intercambio de geometría bidimensional del calibrador y del soporte                | Exportación de los planos a DXF. Configuración detallada no registrada                            | `ICT401_Fase4_Plano_Calibrador Plano1.dxf` y `ICT401_Fase4_Plano_Soporte Plano dxt.dxf`                     |     [x]    |
| PDF     | Consulta y presentación de la documentación técnica                                | Exportación de los tres Drawings a PDF. Escalas y orientación específicas pendientes de registrar | `ICT401_Fase4_Plano_Calibrador.pdf`, `ICT401_Fase4_Plano_Soporte.pdf` y `ICT401_Fase4_Plano_Ensamblaje.pdf` |     [x]    |
| Otro    | N.A. No se utilizó otro formato de salida                                          | N.A.                                                                                              | No generado                                                                                                 |    N.A.    |

Marque `N.A.` cuando un formato no corresponda al proyecto y justifique la decisión.

### Comprobación de cada salida

| Archivo                                    | Geometría | Unidades | Escala/orientación | Versión | Ubicación                                                            | Resultado                                                                            |
| ------------------------------------------ | :-------: | :------: | :----------------: | :-----: | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| `ICT401_Fase4_Plano_Calibrador.pdf`        |    [x]    |    [x]   |         [ ]        |   [ ]   | Archivos de Fase 4; captura `S16_E2_Comprobacion_PDF_Calibrador.png` | Apertura y revisión reportadas; escala y versión exactas pendientes                  |
| `ICT401_Fase4_Plano_Soporte.pdf`           |    [x]    |    [x]   |         [ ]        |   [ ]   | Archivos de Fase 4; captura `S16_E2_Comprobacion_PDF_Soporte.png`    | Apertura y revisión reportadas; escala y versión exactas pendientes                  |
| `ICT401_Fase4_Plano_Ensamblaje.pdf`        |    [x]    |    [x]   |         [ ]        |   [ ]   | Archivos de Fase 4; captura `S16_E2_Comprobacion_PDF_Ensamblaje.png` | Apertura y revisión reportadas; escala y versión exactas pendientes                  |
| `ICT401_Fase4_Plano_Calibrador Plano1.dxf` |    [x]    |    [ ]   |         [ ]        |   [ ]   | Archivos de Fase 4; captura `S16_E2_Comprobacion_DXF_Calibrador.png` | Apertura y revisión reportadas; unidades de importación, escala y versión pendientes |
| `ICT401_Fase4_Plano_Soporte Plano dxt.dxf` |    [x]    |    [ ]   |         [ ]        |   [ ]   | Archivos de Fase 4; captura `S16_E2_Comprobacion_DXF_Soporte.png`    | Apertura y revisión reportadas; unidades de importación, escala y versión pendientes |

**Archivo o captura de comprobación:**
`evidencias/S16_E2_Comprobacion_PDF_Calibrador.png`
`evidencias/S16_E2_Comprobacion_PDF_Soporte.png`
`evidencias/S16_E2_Comprobacion_PDF_Ensamblaje.png`
`evidencias/S16_E2_Comprobacion_DXF_Calibrador.png`
`evidencias/S16_E2_Comprobacion_DXF_Soporte.png`

**Discrepancia encontrada:** No se reportó una discrepancia específica al abrir los PDF o DXF. Permanecen pendientes la comprobación documentada de escalas, orientación y correspondencia exacta de versiones.

**Corrección aplicada:** No se registró una corrección de exportación. Se documentó la apertura de los archivos fuera del comando de exportación.

## Lección 3. Tolerancias y control dimensional básico

En Fusion, la ruta de comprobación es **Design > Inspect > Measure**. En el resultado de la medición deben poder reconocerse la geometría seleccionada y la unidad.

No agregue una tolerancia que no esté indicada en el plano, la rúbrica o la instrucción correspondiente.

| Característica                       | Dimensión nominal |  Tolerancia | Límite inferior | Límite superior | Valor observado | Unidad |
| ------------------------------------ | ----------------: | ----------: | --------------: | --------------: | --------------: | ------ |
| Diámetro circular del calibrador Ø6  |                 6 | No definida |            N.A. |            N.A. |            6,00 | mm     |
| Diámetro circular del calibrador Ø8  |                 8 | No definida |            N.A. |            N.A. |            8,00 | mm     |
| Diámetro circular del calibrador Ø10 |                10 | No definida |            N.A. |            N.A. |           10,00 | mm     |
| Diámetro circular del calibrador Ø12 |                12 | No definida |            N.A. |            N.A. |           12,00 | mm     |

### Método y resultado

| Característica | Herramienta o método                                       | Resultado                                                       | Limitación de la comprobación                                             |
| -------------- | ---------------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Diámetro Ø6    | `Inspect > Measure`, selección de arco circular del boceto | Coincide con nominal: 6,00 mm. Conformidad de tolerancia: N.A.  | Medición digital del boceto; no verifica físicamente un agujero fabricado |
| Diámetro Ø8    | `Inspect > Measure`, selección de arco circular del boceto | Coincide con nominal: 8,00 mm. Conformidad de tolerancia: N.A.  | No existe tolerancia de aceptación definida para este diámetro            |
| Diámetro Ø10   | `Inspect > Measure`, selección de arco circular del boceto | Coincide con nominal: 10,00 mm. Conformidad de tolerancia: N.A. | La medición digital no permite determinar errores de manufactura          |
| Diámetro Ø12   | `Inspect > Measure`, selección de arco circular del boceto | Coincide con nominal: 12,00 mm. Conformidad de tolerancia: N.A. | No certifica dimensiones ni ajustes de una pieza física                   |

**Ejemplo de cálculo, si corresponde:**

Para el diámetro nominal de 6 mm:

Diferencia = valor observado − valor nominal
Diferencia = 6,00 mm − 6,00 mm = **0,00 mm**

De igual manera, los diámetros de 8, 10 y 12 mm presentan una diferencia de **0,00 mm** respecto a sus valores nominales, considerando la precisión mostrada por Fusion 360.

No es posible calcular límites de aceptación sin tolerancias definidas.

**Captura o referencia de la medición:** `evidencias/S16_E3_Control_Dimensional_4_Agujeros.png`

**¿Qué valor o criterio no pudo comprobarse?**

No pudo comprobarse la conformidad dimensional respecto a límites de tolerancia para los cuatro diámetros, porque no se establecieron tolerancias específicas. Tampoco se comprobó el diámetro real de piezas fabricadas, ya que las mediciones se realizaron sobre arcos de boceto en Fusion 360.

El plano del soporte contiene algunas tolerancias propuestas preliminares, pero no se consideran tolerancias definitivas de aceptación para los diámetros del calibrador.

## Lección 4. Integración y cierre del laboratorio

Después de corregir, guarde la versión evaluada desde **File > Save** o la orden equivalente. Compruebe que el archivo exportado y la ficha se refieran a esa misma versión.

### Correcciones finales

| Problema                                               | Acción aplicada                                                                                 | Resultado                                            | Evidencia                                                                  |
| ------------------------------------------------------ | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------- | -------------------------------------------------------------------------- |
| Referencia del ensamblaje señalada como no actualizada | Se identificó la advertencia y se indicó la revisión de la referencia en Fusion 360             | Resolución definitiva pendiente de confirmar         | `S16_E1_Estado_Inicial.png` y `S16_E4_Revision_Final_Ensamblaje.png`       |
| Necesidad de comprobar las salidas fuera de Fusion 360 | Se abrieron y revisaron los archivos PDF y DXF, según los registros del laboratorio             | Se documentó la comprobación de tres PDF y dos DXF   | Capturas `S16_E2_Comprobacion_PDF_*.png` y `S16_E2_Comprobacion_DXF_*.png` |
| Falta de registro dimensional organizado               | Se aplicó `Inspect > Measure` a cuatro arcos circulares del boceto y se registraron los valores | Diámetros observados de 6,00; 8,00; 10,00 y 12,00 mm | `S16_E3_Control_Dimensional_4_Agujeros.png`                                |

### Checklist del Laboratorio II-B

- [x] La versión del modelo y la documentación coincide.
- [x] El plano final fue revisado.
- [x] La lista básica coincide con el ensamblaje, cuando corresponde. **N.A. para una `Parts List` formal no verificada; sí se identificaron los dos componentes.**
- [x] Cada archivo exportado tiene un propósito registrado.
- [x] Las salidas fueron revisadas fuera del comando de exportación.
- [x] Se registraron unidades, escala, orientación y versión. **Parcial: unidades y nombres registrados; escalas, orientación y versiones exactas pendientes.**
- [x] Se realizó al menos una comprobación dimensional básica.
- [x] Las tolerancias introductorias fueron interpretadas sin inventar valores.
- [x] Se registraron discrepancias y correcciones, indicando expresamente lo que permanece sin confirmar.
- [x] La versión evaluada fue respaldada. **Existe un respaldo inicial, pero no se confirmó un respaldo posterior de la versión evaluada.**
- [x] La ficha está completa. **Contenido redactado; quedan verificaciones pendientes.**

### Evidencias finales del laboratorio

| Evidencia                    | Nombre o ruta                                                                                                                                                                                                                                                      | Completa | Observaciones                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------: | ---------------------------------------------------------------------------------------------- |
| Estado inicial y auditoría   | `evidencias/S16_E1_Estado_Inicial.png` y `evidencias/S16_E1_Verificacion_Unidades.png`                                                                                                                                                                             |    [x]   | Capturas registradas. Advertencia inicial de referencia no actualizada                         |
| Exportaciones y comprobación | `evidencias/S16_E2_Comprobacion_PDF_Calibrador.png`, `evidencias/S16_E2_Comprobacion_PDF_Soporte.png`, `evidencias/S16_E2_Comprobacion_PDF_Ensamblaje.png`, `evidencias/S16_E2_Comprobacion_DXF_Calibrador.png` y `evidencias/S16_E2_Comprobacion_DXF_Soporte.png` |    [x]   | Cinco comprobaciones reportadas; falta confirmar datos técnicos específicos de algunas salidas |
| Control dimensional          | `evidencias/S16_E3_Control_Dimensional_4_Agujeros.png`                                                                                                                                                                                                             |    [x]   | Cuatro mediciones digitales mediante `Inspect > Measure`                                       |
| Plano final o documentación  | `evidencias/S16_E1_Revision_Plano_Calibrador.png`, `evidencias/S16_E1_Revision_Plano_Soporte.png` y `evidencias/S16_E1_Revision_Plano_Ensamblaje.png`                                                                                                              |    [x]   | Tres planos revisados; versiones exactas pendientes                                            |
| Lista básica, si corresponde | Ensamblaje `ICT401_Ensamblaje_Fase3` y captura `evidencias/S16_E4_Revision_Final_Ensamblaje.png`                                                                                                                                                                   |    [x]   | Componentes calibrador y soporte identificados; `Parts List` formal no verificada              |
| Archivo de respaldo          | Fusion 360: `ICT401_S16_Ensamblaje_Respaldo_Inicial`; evidencia `evidencias/S16_E1_Respaldo_Inicial.png`                                                                                                                                                           |    [x]   | Respaldo inicial conservado; no se creó una segunda copia evaluada                             |
| Ficha completa               | `Ficha_Registro_Laboratorio_Integrador_II-B_S16`                                                                                                                                                                                                                   |    [x]   | Ficha redactada, pendiente de confirmar versiones, escalas y estado final de referencias       |

**Evidencia adicional del cierre:** `evidencias/S16_E4_Revision_Final_Ensamblaje.png`.

## Separación de la Fase 4

**¿Qué producto o archivo adicional exige la rúbrica de la Fase 4?**

La Fase 4 constituye una entrega independiente de documentación técnica del Proyecto Integrador. Se trabajaron los planos del calibrador, del soporte y del ensamblaje, junto con sus archivos PDF y DXF.

La relación exacta de productos adicionales exigidos debe contrastarse con la rúbrica oficial de Fase 4, ya que esta ficha del laboratorio no permite establecer por sí sola todos sus requisitos.

**¿Qué evidencia de esta ficha puede reutilizarse en la Fase 4?**

Pueden reutilizarse, cuando correspondan a los criterios de la rúbrica, los planos técnicos del calibrador, soporte y ensamblaje, los PDF y DXF generados y las capturas de revisión documental.

Las mediciones digitales también pueden utilizarse como evidencia complementaria de revisión geométrica, siempre que se indique su método y limitación.

**¿Qué requisito de la Fase 4 todavía no está cubierto por esta ficha?**

Esta ficha no sustituye la comprobación del cumplimiento integral de la rúbrica de Fase 4 ni su entrega independiente. Quedan por confirmar la correspondencia exacta de versiones entre modelo y planos, los datos de escala y orientación, y la resolución definitiva de la advertencia de referencia del ensamblaje.

## Cierre reflexivo

**¿Qué exportación requirió más comprobación y por qué?**

Los archivos DXF requirieron especial atención porque se utilizan para intercambiar geometría bidimensional y es importante verificar que las entidades, las unidades y la escala se interpreten correctamente al abrirlos en otra aplicación.

Los PDF también se revisaron para comprobar la visualización de la documentación técnica, las vistas y las cotas.

**¿Qué diferencia encontró entre el valor nominal, la tolerancia y el valor observado?**

El valor nominal corresponde a la dimensión establecida en el diseño. La tolerancia define la variación permitida alrededor de ese valor y el valor observado corresponde al resultado obtenido mediante la medición.

En nuestro proyecto, los valores nominales de 6, 8, 10 y 12 mm coincidieron con los valores observados digitalmente. Sin embargo, al no contar con tolerancias definidas para esos diámetros, no fue posible determinar su conformidad respecto a límites de aceptación.

**¿Qué corrección mejoró la confiabilidad del producto técnico?**

La revisión organizada de los planos, la comprobación de los archivos exportados fuera del comando de exportación y la verificación de los cuatro diámetros mediante `Inspect > Measure` mejoraron la trazabilidad de la documentación técnica.

Además, la identificación de la advertencia de referencia desactualizada permitió reconocer un aspecto del ensamblaje que requiere confirmación antes de declarar completamente cerrado el proyecto.

**¿Qué limitación debe comunicar antes de considerar terminada la Fase 4?**

Debe comunicarse que las mediciones realizadas corresponden a geometría digital y no constituyen una certificación de fabricación. También debe indicarse que las tolerancias de los diámetros del calibrador no están definidas y que las tolerancias propuestas para el soporte son preliminares.

Finalmente, es necesario confirmar la correspondencia exacta entre las versiones del ensamblaje y los planos, así como verificar el cumplimiento de la rúbrica independiente de Fase 4.
