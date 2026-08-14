BIOTECH CORPORATION — INSTRUCCIONES PARA RECUPERAR Y CONTINUAR EL PROYECTO
============================================================================

CONTENIDO DE ESTE PAQUETE
-------------------------

1. BIOTECH_Web_v17_Fuentes_Corregidas.zip
   Proyecto completo de la website oficial. Es la versión base definitiva v17,
   con la implementación responsive aprobada y las fuentes Rajdhani e Inter
   alojadas localmente.

2. BIOTECH_MASTER_CONTINUIDAD.md
   Fuente de verdad del proyecto: identidad, narrativa, estructura corporativa,
   enlaces, reglas visuales, website, RSI, errores descartados y restricciones.

3. BIOTECH_INVENTARIO_RSI_DEFINITIVO.csv
   Inventario de las diez imágenes canónicas publicadas en RSI, incluyendo
   nombres, funciones, dimensiones, tamaños y huellas SHA-256.

4. INSTRUCCIONES.txt
   Este documento.


PROCEDIMIENTO RECOMENDADO EN UN CHAT NUEVO
------------------------------------------

1. Extraer este ZIP en el equipo. No es necesario extraer todavía el ZIP
   interior de la web.

2. Abrir una conversación nueva en ChatGPT.

3. Adjuntar inicialmente estos dos archivos:

   - BIOTECH_MASTER_CONTINUIDAD.md
   - BIOTECH_INVENTARIO_RSI_DEFINITIVO.csv

4. Si el trabajo afecta a la website, adjuntar también:

   - BIOTECH_Web_v17_Fuentes_Corregidas.zip

5. Pegar exactamente el prompt incluido en el siguiente apartado.

6. Esperar a que ChatGPT confirme qué archivos ha leído y cuál considera la
   versión canónica antes de solicitar cambios.

7. Para modificar una imagen concreta de RSI, adjuntar también la imagen
   canónica correspondiente. El inventario identifica cuál es mediante nombre,
   dimensiones y SHA-256.


PROMPT EXACTO DE RECUPERACIÓN
----------------------------

Retomamos el proyecto BIOTECH Corporation, una organización hispanohablante de
Star Citizen. Lee completamente los archivos BIOTECH_MASTER_CONTINUIDAD.md y
BIOTECH_INVENTARIO_RSI_DEFINITIVO.csv antes de proponer o realizar cualquier
cambio. Considéralos la fuente de verdad del proyecto y prioriza siempre las
decisiones marcadas como canónicas o definitivas sobre cualquier borrador,
recuerdo, nombre anterior o interpretación propia.

Si se ha adjuntado BIOTECH_Web_v17_Fuentes_Corregidas.zip, considéralo el código
base oficial y definitivo de la website. Debes trabajar directamente sobre esa
versión, conservando íntegramente la composición de escritorio, la
implementación responsive móvil aprobada y las fuentes Rajdhani e Inter
alojadas localmente. No reconstruyas la web desde cero ni intentes aproximarla
visualmente mediante otro proyecto.

Reglas obligatorias: utiliza siempre los logotipos oficiales exactos; no
redibujes ni reinterpretes el emblema; no introduzcas azul en la identidad;
mantén la paleta negro/grafito y dorado metálico; respeta la estructura de tres
divisiones y sus nueve especialidades; usa “Asalto” y no “Ataque”; conserva la
geometría reconocible de armaduras, naves y elementos de Star Citizen; separa
los activos canónicos de todos los borradores descartados; y no modifiques un
elemento definitivo sin indicar previamente qué archivo y qué regla del
documento maestro se verán afectados.

Antes de continuar, responde únicamente con:

1. Los archivos que has podido leer.
2. La versión de la web que tomarás como base.
3. Los enlaces oficiales de website, Discord y organización RSI.
4. Las tres divisiones y sus nueve especialidades.
5. Las reglas críticas de identidad visual que aplicarás.
6. Cualquier archivo que falte para ejecutar con seguridad el siguiente cambio.

No realices todavía modificaciones. Espera a que te indique la siguiente tarea.


DATOS DE REFERENCIA RÁPIDA
--------------------------

Website oficial:
https://biotech-corporation.hurston.workers.dev/

Copia publicada en ChatGPT:
https://biotech-corporation.manuteran.chatgpt.site

Discord:
https://discord.gg/WXZWr2rrne

Organización RSI:
https://robertsspaceindustries.com/en/orgs/BIOTECHESP

Repositorio público de activos:
https://github.com/w4rmedic/biotech-assets


COMPILACIÓN Y PUBLICACIÓN DE LA WEB
-----------------------------------

Después de extraer BIOTECH_Web_v17_Fuentes_Corregidas.zip, ejecutar desde la
raíz del proyecto:

  npm install
  npm run publish

El proceso ejecuta la compilación y la publicación configuradas en el proyecto.
No deben añadirse credenciales, tokens ni contraseñas a este paquete.


CRITERIO DE SEGURIDAD
---------------------

Si una imagen, texto o decisión no aparece en el documento maestro o en el
inventario canónico, debe tratarse como no confirmado. Antes de sustituir un
activo publicado, hay que compararlo con su archivo canónico y conservar una
copia recuperable de la versión anterior.

