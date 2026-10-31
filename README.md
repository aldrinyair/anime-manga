# Dartotsu · español primero

Selección preliminar de catálogos Mangayomi para Dartotsu, revisada el 31 de octubre de 2026 (Perú).

Repositorio de extensiones: selección preliminar con español primero. Las limitaciones de verificación se detallan abajo.

## Qué se ha verificado

Se revisaron 123 entradas en español, español latinoamericano, inglés y japonés. Se comprobaron respuestas HTTP, títulos de las páginas, disponibilidad del archivo de extensión y, cuando fue posible, coincidencia del catálogo con los selectores del código, capítulos e imágenes de muestra.

No se ejecutó Dartotsu ni sus extensiones. No se certifica reproducción de vídeo, funcionamiento de todos los servidores, compatibilidad con la versión instalada ni lectura de todo el catálogo. Los fallos de red, desafíos de navegador y cambios de estructura se excluyen de la selección; no se interpretan automáticamente como cierre permanente.

## Selección

| Tipo | Fuente | Idioma | Evidencia alcanzada |
|---|---|---|---|
| Anime | AnimeOnline.Ninja | es | Catálogo, episodios y opciones de reproductor; vídeo pendiente |
| Anime | TioAnime | es | Catálogo y datos de episodios |
| Manga | Ragnarok Scanlation | es | Catálogo y capítulos; imágenes pendientes |
| Anime | DonghuaStream | en | Catálogo, episodios y opciones de reproductor; vídeo pendiente |
| Manga | KSGroupScans | en | Catálogo, capítulos e imagen de muestra accesible |
| Manga | MangaRead.org | en | Catálogo, capítulos e imagen de muestra accesible |
| Manga | Mangasushi | en | Catálogo, capítulos e imagen de muestra accesible |

El orden del archivo prioriza español, después inglés. La aplicación puede aplicar su propio orden; selecciona español en su filtro de idiomas.

## Japonés

No se confirmó una fuente con catálogo japonés utilizable en estas pruebas. Las cuatro entradas candidatas están en `japanese_pending.json`, fuera del índice recomendado. No las presentes como funcionales. Las fuentes de anime en español pueden incluir audio japonés con subtítulos españoles; esto depende del título y servidor y no equivale a un catálogo etiquetado `ja`.

## Enlace para Dartotsu

Índice combinado (añadir la misma URL en anime y manga, con el gestor Mangayomi):

https://raw.githubusercontent.com/aldrinyair/anime-manga/main/index.json

Si la versión instalada requiere índices separados:

- Anime: https://raw.githubusercontent.com/aldrinyair/anime-manga/main/anime_index.json
- Manga: https://raw.githubusercontent.com/aldrinyair/anime-manga/main/manga_index.json

Después de añadir el repositorio, instalar las extensiones y seleccionar español en el filtro de idiomas. Comprobar reproducción y lectura en el dispositivo antes de considerar una fuente completamente funcional.

La compatibilidad del índice combinado se contrastó con `_parseExtensions` de `MangayomiExtensions.dart` en el proyecto público `aayush2622/DartotsuExtensionBridge`: recibe una lista JSON y filtra por `itemType`.

## Archivos

- `index.json`: índice combinado, 7 entradas.
- `anime_index.json`: 3 fuentes de anime/animación (DonghuaStream contiene animación china con traducción inglesa).
- `manga_index.json`: 4 fuentes de manga.
- `japanese_pending.json`: candidatos japoneses NO verificados, no incluidos por defecto.
- `audit.json`: resultados por fuente y evidencias públicas; `runtime_tested` es falso en todos los casos.
- `REVISION.md`: resumen de la decisión para cada fuente.
- `NOTICE.md`: atribución a los repositorios originales.

## Mantenimiento

Es una instantánea, sin actualización automática. Los archivos de extensión siguen alojados en sus repositorios de origen. No se han copiado vídeos ni páginas de manga. Una futura modificación del proveedor puede alterar la disponibilidad.
