# Expediente Dieline · Fase 3: Conceptualización abstracta

Landing gamificado de un solo archivo HTML para la fase de Conceptualización abstracta (CA) del ciclo de Kolb, con enfoque DUA-Experiencial (modelo MPI-DUAE).

- **Curso:** Producción y publicación de piezas gráficas · Diseño Publicitario · IDC `[CONFIRMAR semana y sesión]`
- **Tema:** packaging: plano técnico (dieline / keyline), cálculo dimensional, pre-prensa y marco normativo peruano
- **Docente:** Mg. Mario Quiroz Martínez
- **Fecha de construcción:** 2026-11-11

## Archivos

| Archivo | Uso | Peso |
|---|---|---|
| `fase3_conceptualizacion_abstracta.html` | Versión del estudiante | ≈ 0,86 MB |
| `fase3_conceptualizacion_abstracta_DOCENTE.html` | Versión docente: estaciones desbloqueadas y solucionario completo al final | ≈ 0,87 MB |
| `README.md` | Este documento | — |

La versión docente se genera a partir de la del estudiante. Si se edita una, hay que regenerar la otra.

## Objetivo de aprendizaje

Al terminar la fase, el estudiante explica con reglas, fórmulas y normas por qué el arte impreso debe coincidir con su plano técnico, y calcula las medidas y los márgenes que lo aseguran.

| Criterio de logro | Evidencia en la página | Estación |
|---|---|---|
| Lee un plano técnico: cotas, paneles y zonas restringidas | 4 datos correctos del keyline n.º 1143 | Preámbulo |
| Nombra sangrado, zona de seguridad, tolerancia y holgura desde un caso | 4 casos y 5 anagramas resueltos | 3 y 5 |
| Calcula cotas internas y externas desde el contenido | Reto A con 4 respuestas correctas | 4 · simulador A |
| Predice el defecto que produce un descalce | 3 misiones cumplidas | 4 · simulador B |
| Relaciona dato obligatorio, norma y entidad | Tarjetas, clasificador y enigmas | 2, 3 y 6 |
| Formula dos hipótesis verificables | Hipótesis A y B validadas | 7 |

Vínculo curricular propuesto: indicador 2 de la capacidad, «prepara archivos según requerimientos técnicos» `[CONFIRMAR]`. Componente de la competencia: saber conocer.

## Estructura

| # | Estación | Mecánica | Puntos |
|---|---|---|---|
| 0 | Preámbulo y registro | Objetivo, 3 planos industriales ampliables, lectura de plano (4 preguntas), registro | 0 |
| 1 | Activación | Animación del descalce, **mesa de control de las tres piezas reales** (guías, corte simulado y matriz de 9 chequeos), hipótesis sin clave, predicción en mm | 5 |
| 2 | Mapa de la fase | 3 ejes desplegables, vista ampliada, **tres planos de troquel reales con resaltado de cortes y hendidos** + 2 preguntas, entregables, 3 confirmaciones | 5 |
| 3 | Definición viva | Video de apoyo (YouTube), 4 casos de elección de formulación, 4 tarjetas giratorias con instrucciones paso a paso, contador y tabla resumen, clasificador ISO Tipo I / II / III | 20 |
| 4 | Simuladores | A: cálculo dimensional + escena 3D + esquema paramétrico **junto a un plano de producción real seleccionable** + reto numérico. B: arte contra troquel + 3 misiones | 30 |
| 5 | Anagrama | 5 términos con pista, mezclar y «dame una letra» | 10 |
| 6 | Enigmas | Candado de 3 dígitos, mensaje cifrado, tres testigos (se exigen 2 de 3) | 15 |
| 7 | Cierre | Hipótesis A y B, dos hallazgos y una duda, autoevaluación de 4 filas, constancia | 15 |

Las estaciones se abren en orden. El puntaje es de avance (100 puntos): los intentos fallidos no restan.

### Elementos transversales

- **Refuerzo ante el error:** panel Pausa → Pista → Dato → Contexto → Reintento. No existe «incorrecto» sin pista ni fin de partida.
- **Ayudas:** bloque «Cómo se juega / Cómo se responde» en cada actividad y ayuda plegable de tres niveles (cómo empezar, qué mirar, ejemplo de otra situación).
- **Glosario:** 30 términos, buscador en vivo, botón flotante y términos enlazados en el texto.
- **Lectura en voz alta:** botón 🔊 por estación (Web Speech API, voz en español del navegador).
- **Constancia:** vista breve en pantalla, versión completa para impresión y botón «Copiar resumen».
- **Panel «Para el docente»** (estación 7): objetivo, justificación DUA, datos por confirmar y modo revisión.

## Planos del preámbulo

| Ejemplo | Origen | Contenido |
|---|---|---|
| 1 · Keyline vacío | `11431.pdf` | Plantilla Tetra Pak TBA 1000S, keyline n.º 1143, escala 1:1 |
| 2 · Keyline con arte | `MLEKO_UHT_30__1l_5901432002097.pdf` | Plantilla TBA 1000S, keyline n.º 1247, con arte montado |
| 3 · Estuche plegadizo | `manzanillahornimansimpresion…pdf` | Arte final con troquel, marcas de registro y tira de control |

Los PDF se convirtieron a JPEG (1400–1500 px de ancho) y están incrustados en base64. Contienen marcas y diseños de terceros; se incluyen como referencia de estudio con una nota visible.

Datos leídos del ejemplo 1 y usados en la lectura de plano: desarrollo de 305 × 270 mm; paneles de 49 · 58,5 · 90 · 58,5 mm; franjas verticales de 29,25 · 195,5 · 37,25 mm.

## Modelo de cálculo (simulador A)

```
Alto del bloque  = N × alto de la unidad
Largo interno    = largo de la unidad + holgura
Ancho interno    = ancho de la unidad + holgura
Alto interno     = alto del bloque + prospecto + cuna + holgura
Cota externa     = cota interna + 2 × calibre
Cara principal   = la cara de mayor área (se muestran las tres)
```

Caso A (blísteres 96 × 42 × 5 mm, N = 3, prospecto 2 mm, holgura 2 mm, calibre 0,4 mm): internas 98 × 44 × 19 mm; externas 98,8 × 44,8 × 19,8 mm; cara principal 44,26 cm².
Caso B (barras 140 × 60 × 12 mm, N = 4): cara principal 142,8 × 62,8 mm = 89,68 cm².

## Reglas del simulador B

| Condición | Resultado |
|---|---|
| Descalce (derecha o arriba) > margen de seguridad | Advertencia cortada |
| \|Descalce\| > sangrado | Filo blanco |
| \|Descalce\| > tolerancia del sector | Lote rechazado, aunque no haya defecto visible |

Tolerancias de trabajo: ±1,0 mm (alimentos) y ±0,5 mm (farmacéutico).

## Decisiones técnicas

- Un solo archivo HTML. CSS, JavaScript, logos y planos van incrustados.
- Lógica principal en ES5 dentro de una IIFE. Estado en memoria: no usa `localStorage` ni `sessionStorage`.
- Escena 3D en un `<script type="module">` aparte con `importmap`: `three@0.186.1` y `animejs@4.5.0` con su adaptador de three, desde cdn.jsdelivr.net. Comunicación con la lógica principal mediante `window.CA_DIMS` y el evento `ca:dims`.
- Sin conexión, la escena 3D no carga y se muestra un aviso; el cálculo, el plano 2D y el resto de estaciones funcionan.
- Animaciones de interfaz en CSS: duración finita, `animation-fill-mode: both`, solo `transform` y `opacity`, escalonado con `--i`, y desactivación con `prefers-reduced-motion`.
- Mecánicas de arrastre con alternativa «tocar ficha → tocar destino» y teclado.
- Tipografías: Syne, DM Sans y DM Mono (Google Fonts) con respaldo del sistema. Paleta IDC: `#f3a100`, `#0072b9`, `#555553`, `#868686`.
- Logo de color en el encabezado y la constancia; logo blanco en el pie.

## Las tres piezas de la estación 1

Archivos entregados: `error_1.svg`, `error_2.svg`, `error_3.svg`. Son tres piezas verticales de promoción (SUPER SALE, BIG SALE, 50% DISCOUNT), incrustadas como SVG en línea con sus clases e identificadores renombrados para que no colisionen entre sí ni con el resto de la página.

Escala declarada en la página: el archivo no trae unidades; leído en puntos, cada pieza mide 71,4 × 141,2 mm. Las cifras siguientes se midieron rasterizando cada capa por separado sin recorte y comparándola con el borde del documento.

| Medida | Pieza 1 (azul) | Pieza 2 (rosa) | Pieza 3 (amarilla) |
|---|---|---|---|
| Sangrado izq. / arr. / der. / abj. (mm; negativo = el fondo se queda dentro del corte) | −0,4 / −0,8 / +0,9 / +0,9 | −1,0 / +0,1 / −1,5 / +0,0 | −1,1 / +0,0 / −1,4 / −0,0 |
| Texto más cercano al corte | 14,2 mm | 2,5 mm | 10,1 mm |
| Filtro declarado | ninguno | `drop-shadow-1` | `drop-shadow-1` |
| Falla sangrado / texto / transparencia | ✗ · ✓ · ✓ | ✗ · ✗ · ✗ | ✗ · ✓ · ✗ |

La matriz de 9 casillas se comprueba completa; el panel de refuerzo cita la medida de la primera pieza que no coincide. El botón «Simular el corte» desplaza el arte 1,5 mm dentro del `viewBox`, que recorta, y el fondo del contenedor pasa a una trama diagonal que representa el cartón sin tinta.

## Los tres planos de troquel

Archivos entregados: `SP238`, `SP306`, `SP230` (nombres de archivo; su código de catálogo no está verificado). Son planos reales de caja plegadiza, incrustados en línea.

El resaltado de cortes y hendidos no es decorativo: sale de las clases del propio archivo. El trazo con `stroke-dasharray` es el hendido y el trazo continuo es el corte; al preparar los SVG se les añadió una clase semántica (`dl-crease` / `dl-cut`) sin tocar su geometría. Aparecen en la estación 2 con dos preguntas de lectura (línea discontinua = hendido; cuatro bandas en la columna central) y en el simulador A junto al esquema paramétrico, para comparar un esquema que responde a las medidas con un plano de geometría fija.

## Video de apoyo

- «Líneas de troquel y pruebas: preimpresión de embalaje 101»: https://www.youtube.com/watch?v=Lax3QODXpY8
- Ubicación: estación 3, antes de los casos; acompaña los casos 1 (sangrado) y 2 (zona de seguridad).
- El reproductor se inserta al pulsar «Reproducir aquí». En el visor de artefactos de Claude los marcos de otros sitios están bloqueados; ahí funciona el botón «Abrir en YouTube». En un servidor web (por ejemplo, GitHub Pages) se reproduce dentro de la página.
- Contenido, idioma y duración del video: no verificados `[CONFIRMAR]`.

## Verificación realizada

- `node --check` sobre el script principal y el módulo 3D de ambos archivos.
- Recorrido automatizado completo en Chrome sin interfaz (Playwright): registro → constancia con 100 puntos, incluido un intento fallido por mecánica para comprobar el panel de refuerzo.
- Sin errores de página. Sin desbordamiento horizontal a 390 px de ancho.
- Unicidad del candado comprobada por fuerza bruta (única solución: 305).

No verificado: lectura en voz alta (depende de las voces instaladas) e impresión de la constancia (el visor de artefactos la bloquea; funciona al abrir el archivo en el navegador).

## Datos por confirmar antes de usar en clase

| Dato | Estado |
|---|---|
| Tope de multa de la Ley 29571 | El documento base indicaba 700 UIT; las fuentes consultadas indican 450 UIT. La página usa 450. |
| Cara principal | El documento base usaba ancho × alto externos; la página usa la cara de mayor área. |
| Tamaño del octógono según área | No se fijó tabla. Se aplica el umbral de 50 cm² y se remite al Manual de Advertencias Publicitarias. Los lados de 2 / 2,5 / 3 cm son solo de dibujo. |
| Tamaño mínimo de letra de 6 a 8 pt («NTS 122») | Sin verificar. No aparece en el contenido del estudiante. |
| Tolerancias ±0,5 / ±1,0 mm por sector | Sin verificar. Se presentan como parámetros de trabajo de la sesión. |
| SIGRE | Sistema español; retirado del contenido. |
| Curso, semana y vínculo con el indicador 2 | Asumidos por el tema. |
| Escala de las tres piezas (1 unidad = 1 punto → 71,4 × 141,2 mm) | Lectura por omisión del programa que generó los archivos; el archivo no declara unidades. |
| Códigos SP238 / SP306 / SP230 | Son los nombres de los archivos entregados; no se verificó a qué catálogo de estructuras corresponden. |
| Descripción estructural de los tres planos | Redactada solo con lo que se ve en el dibujo (bandas, solapas, ranuras, dobleces en diagonal). |
| Tiempos por estación (90 min) | Propuesta del diseño. |

## Limitaciones

- El simulador A calcula un estuche plegadizo, no la geometría de un envase Tetra Pak. El keyline se trabaja en el preámbulo como lectura de plano.
- El plano desplegado del simulador A es un esquema didáctico, no un troquel de producción.
- La página no envía resultados a ningún servidor ni por correo. El estudiante entrega la constancia impresa o el resumen copiado.
- Las respuestas están en el código fuente de la versión del estudiante; quien inspeccione el archivo puede verlas.

## Cómo modificar

| Qué cambiar | Dónde (script principal) |
|---|---|
| Planos y sus notas | `PLANS` |
| Respuestas de la lectura de plano | manejador de `#pqGo` |
| Casos de definición | `DEFS` |
| Tarjetas y clasificador | `FLIPS`, `CLS`, `BINS` |
| Casos y rangos del simulador A | `PRE`, `CTL`, manejador de `#qaCheck` |
| Palabras del anagrama | `ANA` |
| Candado y mensaje cifrado | `CLUES`, `KEYQ`, `KEYS` |
| Glosario | `GLO` |
| Puntos por estación | `PTS` (debe sumar 100) |

Después de cualquier cambio: validar con `node --check`, repetir el recorrido completo y regenerar la versión docente.

## Referencias

- Kolb, D. A. (1984). *Experiential learning: Experience as the source of learning and development*. Prentice Hall.
- CAST (2024). *Universal Design for Learning Guidelines version 3.0*.
- Ley N.º 30021 y D.S. N.º 012-2018-SA (Manual de Advertencias Publicitarias); INACAL, GP 110:2022.
- Ley N.º 29459 y D.S. N.º 016-2011-SA; D.S. N.º 007-98-SA; Ley N.º 29571.
- ISO 14021, ISO 14024, ISO 14025.
