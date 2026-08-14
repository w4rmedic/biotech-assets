# BIOTECH Corporation — Documento maestro de continuidad

**Estado de referencia:** versión 17, 14 de agosto de 2026  
**Objetivo:** permitir que el proyecto pueda retomarse sin depender de la conversación original.  
**Regla principal:** ante cualquier contradicción, prevalecen los activos y textos marcados como **CANÓNICOS** en este documento. Los archivos denominados `propuesta`, `preview`, `v1–v5`, `generated` o almacenados como borradores no sustituyen a un activo canónico.

## 0. Texto para reanudar el proyecto en una conversación nueva

> Retomamos el proyecto BIOTECH Corporation de Star Citizen. Usa como fuente de verdad el documento `BIOTECH_MASTER_CONTINUIDAD.md` y la versión 17 de la web. Conserva exactamente el logotipo oficial, la estructura de tres divisiones, los enlaces oficiales, las fuentes Rajdhani e Inter alojadas localmente y la estética sci-fi corporativa negra/grafito y dorada. No reutilices borradores ni reinterpretaciones del emblema. Antes de modificar cualquier activo canónico, indica qué archivo y qué regla del documento se verán afectados.

## 1. Identidad canónica

- Nombre completo: **BIOTECH Corporation**.
- Forma gráfica habitual: **BIOTECH CORP**.
- Localización identitaria: **STANTON · HURSTON**.
- Universo: **Star Citizen**; organización hispanohablante.
- Lema corporativo: **EXPANDING HUMANITY · EXPANDING LIFE**.
- Mensaje principal de la web: **Construimos el futuro entre las estrellas.**
- Enfoque: ciencia, industria, logística y protección al servicio de una comunidad nacida para crear.

### Regla absoluta del logotipo

El emblema circular triádico dorado debe utilizarse **exactamente como fue aprobado**. No debe redibujarse, reinterpretarse, simplificarse ni sustituirse por una aproximación generada. Siempre que aparezca un logo visible debe partir de uno de los archivos oficiales.

### Activos canónicos de la web

| Uso | Archivo de referencia |
|---|---|
| Emblema sin texto / favicon | `public/biotech-favicon.png` y `public/biotech-logo.png` |
| Cabecera con emblema y nombre | `public/biotech-header-logo.png` |
| Tarjeta de enlaces / Open Graph | `public/biotech-social-card.png` |
| Botón enlazable externo | `BIOTECH_Boton_Web_Oficial_600x160.png` |
| Logo oficial maestro disponible | `BIOTECH_Logo_Oficial_Dorado_Profundo_1536x1024.png` |

El favicon definitivo es el emblema aislado, transparente y ampliado hasta aprovechar prácticamente todos los límites del icono.

## 2. Enlaces oficiales

| Destino | URL |
|---|---|
| Website oficial | https://biotech-corporation.hurston.workers.dev/ |
| Copia publicada en ChatGPT | https://biotech-corporation.manuteran.chatgpt.site |
| Discord | https://discord.gg/WXZWr2rrne |
| Organización RSI / adhesión | https://robertsspaceindustries.com/en/orgs/BIOTECHESP |
| Repositorio público de activos | https://github.com/w4rmedic/biotech-assets |

No deben guardarse tokens, contraseñas ni credenciales de Cloudflare, Discord, RSI o GitHub dentro de este dossier.

## 3. Website oficial — estado definitivo

- Versión base definitiva: **v17 — Fuentes corregidas**.
- Paquete local: `BIOTECH_Web_v17_Fuentes_Corregidas.zip`.
- La versión de escritorio conserva la composición cinematográfica original.
- La implementación responsive agresiva afecta solamente a dispositivos móviles, con punto principal de corte en `620px`.
- En móvil, las imágenes se muestran como escenas reconocibles antes del contenido para no perder protagonistas, naves o entornos.
- No deben aplicarse reglas móviles al escritorio ni modificar la composición desktop para compensar un problema móvil.

### Tipografías — incidencia resuelta

- Titulares: **Rajdhani**, pesos 400, 500, 600 y 700.
- Texto y utilidades: **Inter**, peso variable 100–900.
- Las fuentes se alojan localmente en `public/fonts/`.
- No volver a usar `next/font/google` en este proyecto: el empaquetado anterior produjo rutas internas inválidas en Cloudflare.
- No confiar en fuentes de reserva. La fuente genérica hacía el titular más ancho, pero rompía el encaje del resto de textos.

### Compilación y publicación

Desde la raíz del proyecto:

```bash
npm install
npm run build
npm run deploy
```

El comando abreviado habitual es:

```bash
npm run publish
```

### Metadatos sociales

- Favicon: `/biotech-favicon.png`.
- Cabecera web: `/biotech-header-logo.png`.
- Open Graph y Twitter: `/biotech-social-card.png`, 1200 × 630.
- La tarjeta debe mantener el logo original, **BIOTECH CORP**, **STANTON · HURSTON** y texto suficientemente grande para Discord y redes.

## 4. Estructura corporativa canónica

BIOTECH es la organización matriz y se divide en tres divisiones. La jerarquía general de miembros es independiente de los cargos operativos de cada sección.

### I. División de Ciencias

**Propósito:** comprender lo desconocido para hacer posible el futuro.

1. **Exploración — Sección Prometheus**  
   Expediciones, cartografía, búsqueda de recursos y reconocimiento de rutas.  
   Lema: «Allí donde termina el mapa, comienza nuestra misión».
2. **Medicina — Grupo Ex’Hel**  
   Investigación biológica, diagnóstico, tratamiento, rescate y evacuación.  
   Lema: «Comprender la vida es aprender a protegerla».
3. **Ingeniería — Sistemas e infraestructuras**  
   Mantenimiento de flota, reparación de sistemas e infraestructuras.  
   Lema: «Si puede romperse, aprenderemos a reconstruirlo».

### II. División de Logística

**Propósito:** convertir recursos, distancia y tiempo en capacidad operativa.

1. **Minería — Grupo Iridius**  
   Prospección planetaria, extracción coordinada y procesamiento.  
   Lema: «La próxima gran obra comienza con el primer mineral».
2. **Transporte — Red de flota**  
   Carga, mercancías, pasajeros, datos y convoyes interplanetarios.  
   Lema: «Cada destino importa. Cada entrega construye algo mayor».
3. **Reciclaje — Sección Juggernaut**  
   Exploración de pecios, recuperación de componentes y desmantelamiento orbital.  
   Lema: «Nada termina mientras aún conserve valor».

### III. División de Operaciones Estratégicas

**Propósito:** proteger aquello que merece un futuro.

1. **Defensa — Protección y seguridad**  
   Seguridad corporativa, protección de personal y control de instalaciones.  
   Lema: «Defendemos todo lo que BIOTECH construye».
2. **Asalto — Respuesta y neutralización**  
   Respuesta táctica, rescate de rehenes y neutralización de amenazas.  
   Lema: «Cuando la amenaza avanza, nosotros damos el paso al frente» — sin punto final en piezas gráficas.
3. **Inteligencia — Información y anticipación**  
   Reconocimiento avanzado, análisis de amenazas y contrainteligencia.  
   Lema: «La mejor victoria comienza antes del primer disparo».

Usar **ASALTO**, nunca «Ataque», en la versión definitiva. Defensa debe mostrar seguridad corporativa y urbana, no una fuerza militar indiscriminada.

## 5. Trayectoria, rangos y narrativa

### Historia resumida utilizada en la web

- **2904:** Magda Hurston adquiere Stanton I. Especialistas y antiguos terraformadores de microTech fundan BIOTECH.
- **2914:** la finalización de Central Tower consolida la reputación de la corporación.
- **Hoy:** Ciencia, Logística y Operaciones convergen para abrir una nueva etapa de crecimiento.

La narrativa ampliada contempla que Operaciones sostuvo a BIOTECH durante la guerra y posteriormente transfirió autoridad al cuerpo ejecutivo. La nueva etapa prioriza construir, crecer y avanzar.

### Rangos generales

1. Aspirante
2. Iniciado
3. Profesional
4. Experto
5. Élite

El rango general expresa experiencia, autonomía y compromiso. El cargo de sección expresa la responsabilidad asumida durante una operación.

## 6. Principios, admisión y convivencia

- Organización hispanohablante bajo la ley y protección de la UEE.
- BIOTECH ha nacido para crear, no para destruir.
- Cordialidad, neutralidad, respeto, responsabilidad y colaboración.
- No se admite piratería, vandalismo, abuso ni conductas que perjudiquen a la comunidad.
- Evitar debates políticos, religiosos o ideológicos conflictivos.
- No realizar publicidad masiva ni actividades que dividan o deterioren el entorno común.
- Usar una identificación coherente entre RSI y Discord cuando sea requerida.
- Respetar el logotipo, la identidad y los uniformes corporativos en las actividades oficiales.
- Principio de referencia: **Respeto antes que rango**.
- Mensaje de captación: no se busca un currículum perfecto; se buscan personas dispuestas a aprender, colaborar y formar parte de algo mayor.

Los textos legales o normativos completos deben contrastarse con las imágenes/documentos fuente `Normas de Biotech Corporation.png`, manifiesto y Charter antes de modificarlos.

## 7. Narrativa visual canónica

### Dirección artística

- Ciencia ficción corporativa cinematográfica y realista.
- Negro profundo, grafito y charcoal como base.
- Dorado metálico y luz ámbar como acentos.
- Alto contraste, sombras profundas y fuentes de luz cálida controladas.
- Marcos tecnológicos elegantes, líneas finas, hexágonos y HUD discretos.
- Composiciones limpias, legibles y premium; evitar saturación de interfaces.
- Tecnología avanzada, exploración, organización, aventura y capacidad operativa.
- Personal diverso trabajando profesionalmente; hombres y mujeres.
- Como pauta general del banco visual, al menos un 60 % de las imágenes puede tener un hombre en primer plano, sin excluir protagonismo femenino cuando la escena lo requiera.

### Entornos

- Hurston y especialmente Lorville: ciudad industrial monumental, atmósfera densa, luz ámbar, arquitectura pesada, metal, polvo y escala corporativa.
- Hangares, bases, interiores industriales y centros de operaciones.
- Planetas, lunas y espacios exteriores plausibles dentro de Star Citizen.
- Evitar fondos genéricos de ciencia ficción que no parezcan pertenecer al universo de Star Citizen.

### Personajes y uniformes

- Uniformes negros elegantes con detalles dorados discretos.
- Las marcas BIOTECH visibles deben usar el logotipo oficial exacto.
- No utilizar logotipos azules ni reinterpretaciones del emblema.
- Armaduras: preservar geometría, proporciones, placas, casco, mochila, articulaciones y aspecto de las referencias aportadas.
- Para nuevas perspectivas complejas conviene utilizar varias referencias de la misma armadura; no inventar una armadura «parecida».

### Naves y vehículos

- Conservar exactamente la silueta, escala, geometría y rasgos identificables del modelo de referencia.
- No inventar modelos ni mezclar geometrías de distintas naves.
- Las referencias pueden usarse para tamaño, perspectiva y construcción; el color puede adaptarse a BIOTECH si no altera la identidad del modelo.
- Elementos reales de Star Citizen deben seguir siendo reconocibles.

### Reglas particulares ya aprobadas

- Minería: protagonista femenina de perfil o tres cuartos, equipo de apoyo, vehículos mineros y nave de carga; encuadre nítido que no oculte a la protagonista.
- Asalto: oficial protagonista sin casco, rapado y ojos azules; médico atendiendo a un civil; resto del equipo con casco; combate de escala media.
- Defensa: seguridad corporativa urbana, profesional y proporcionada.
- Reciclaje: grandes naves abandonadas, drones de corte y sensación épica de recuperación industrial.

## 8. Material gráfico para RSI

Piezas trabajadas: Banner/bienvenida, Historia, Manifiesto, Charter/reglamento, transferencia de autoridad/nuevo comienzo, divisiones, rangos y botón de Discord.

### Reglas de maquetación RSI

- Formato vertical cuando se inserta en las secciones narrativas de RSI.
- Texto reconstruido con tipografía nítida; no confiar en texto generado dentro de una imagen.
- Resaltar únicamente las palabras o frases previstas. No aplicar resaltados aleatorios ni destacar repetidamente «de».
- Mantener márgenes interiores suficientes; el texto no puede invadir las líneas doradas del borde.
- Los encabezados alternativos aprobados son **EXPANDING HUMANITY** en blanco y **EXPANDING LIFE** en dorado.

### Colección canónica publicada en RSI

El usuario confirmó el 14 de agosto de 2026 que las siguientes diez imágenes son las utilizadas en la página RSI. Esta colección sustituye como referencia a todos los borradores anteriores:

1. `BIOTECH_RSI_01_Banner_Principal_1140x380.png`
2. `BIOTECH_RSI_02_Cabecera_Discord_1000x400.png`
3. `BIOTECH_RSI_03_Boton_Web_Oficial_600x160.png`
4. `BIOTECH_RSI_04_Historia_878x1862.png`
5. `BIOTECH_RSI_05_Manifiesto_878x1862.png`
6. `BIOTECH_RSI_06_Charter_878x1862.png`
7. `BIOTECH_RSI_07_Reclutamiento_Discord_1140x1555.png`
8. `BIOTECH_RSI_08_Fondo_Lorville_1672x941.png`
9. `BIOTECH_RSI_09_Emblema_Oficial_Sin_Texto_1536x1024.png`
10. `BIOTECH_RSI_10_Logo_Oficial_Con_Texto_1536x1024.png`

La imagen 8 es el fondo de la página RSI. Las imágenes 9 y 10 son las referencias oficiales definitivas del emblema sin texto y del logotipo con texto. Deben emplearse también como patrón para verificar cualquier uso futuro de la marca en RSI.

Los archivos históricos `Divisiones.png`, `rangos.png`, `nuevo comienzo.png`, `discord.png`, `discord_small.png` y todas las variantes previas de Historia, Manifiesto, Charter, banners o reclutamiento quedan clasificados como **BORRADORES / NO PUBLICADOS** y no deben reutilizarse por omisión.

## 9. Inventario de imágenes definitivas de la web

La lista fuente está en `public/new/`. Las referencias activas utilizadas por `app/page.tsx` son:

- `hero.png`
- `identidad-v2.png`
- `division-ciencias-v2.png`
- `exploracion.png`
- `medicina-v2.png`
- `ingenieria.png`
- `division-logistica-v2.png`
- `mineria-v5.png`
- `transporte.png`
- `reciclaje-v2.png`
- `division-operaciones-v2.png`
- `defensa-v2.png`
- `asalto-v5.png`
- `inteligencia.png`
- `historia-lorville-v2.png`
- `ops-join.png`

Archivos como `asalto-v3/v4`, `ataque.png`, `mineria-v3/v4`, `medicina.png`, `reciclaje.png` o `defensa.png` son versiones anteriores y no deben sustituir a los activos activos sin una decisión explícita.

## 10. Errores que no deben repetirse

1. Reinterpretar o redibujar el logotipo en lugar de usar el original.
2. Usar azul en la identidad BIOTECH.
3. Modificar el escritorio para resolver un problema exclusivamente móvil.
4. Forzar una composición distinta en ChatGPT para «parecerse» al sitio oficial en vez de copiar la misma fuente.
5. Depender de una fuente de reserva o de rutas internas generadas durante el build.
6. Alterar la geometría de armaduras o naves al cambiar la perspectiva.
7. Generar texto dentro de imágenes cuando debe mantenerse perfectamente nítido.
8. Aplicar resaltados de texto aleatorios.
9. Colocar texto sobre las líneas doradas del marco.
10. Mezclar borradores con activos definitivos por usar nombres poco claros.
11. Confundir Defensa con una escena militar de asalto.
12. Volver a utilizar «Ataque» cuando la denominación definitiva es «Asalto».

## 11. Método de archivo recomendado

Mantener cinco grupos claramente separados:

1. `01_IDENTIDAD_CANONICA` — logotipos, favicon, cabecera, tarjeta social y botón.
2. `02_RSI_PUBLICADO` — únicamente las piezas que estén realmente publicadas en RSI.
3. `03_WEB_V17` — código y paquete de despliegue definitivo.
4. `04_NARRATIVA_Y_REGLAMENTO` — textos editables, historia, admisión, divisiones y rangos.
5. `99_ARCHIVO_BORRADORES` — material histórico que no debe reutilizarse por omisión.

Cada activo definitivo nuevo debe registrar: nombre, uso, dimensiones, fecha de aprobación, archivo reemplazado y motivo del cambio.

## 12. Lista de comprobación antes de continuar

- [ ] Se ha leído este documento maestro.
- [ ] Se está trabajando sobre la versión 17 o una sucesora explícita.
- [ ] Los logotipos proceden de los archivos oficiales.
- [ ] Rajdhani e Inter se sirven desde `public/fonts/`.
- [ ] Los cambios móviles no alteran el escritorio.
- [ ] Las imágenes activas coinciden con las rutas de `app/page.tsx`.
- [ ] No se está reutilizando un archivo marcado como propuesta o borrador.
- [ ] Los enlaces de Discord, RSI y la web siguen vigentes.
- [ ] Cualquier pieza RSI que se vaya a sustituir se ha comparado con la actualmente publicada.
