# Diego · Midnight Soft Glass

Rediseño visual realizado **sobre la aplicación original proporcionada**. Se conserva la estructura y las funcionalidades existentes: Inicio, Alimentos, Recetas, Favoritos, Pauta, Historial, Perfil, PWA y exportación/importación de datos.

## Qué cambió
- `index.html`: capa CSS de diseño *Midnight Soft Glass*; título y metadatos visuales de la versión de prueba.
- `manifest.json`: nombre e identidad de instalación distintos de la app original.
- `sw.js`: versión nueva del caché para recibir el rediseño.

## Qué NO cambió
- `app.js`, `calc.js` y `store.js` permanecen idénticos a los del ZIP anterior.
- No se modifican cálculos nutricionales, fórmulas de insulina, reglas, registros guardados, controladores de eventos ni IDs de elementos.

## Cómo publicar SIN reemplazar la app original
1. Crear o usar el repositorio **Simon7921/Diego-Midnight** (separado de `Pauta-Diabetes-Diego`).
2. En ese repositorio abrir **Add file → Upload files**. Subir **los archivos descomprimidos** a la raíz; `index.html` debe verse junto a `app.js`.
3. Confirmar los cambios con **Commit changes**.
4. Ir a **Settings → Pages → Build and deployment** y seleccionar `Deploy from a branch`, `main`, `/(root)`.
5. Abrir `https://simon7921.github.io/Diego-Midnight/` cuando GitHub indique que la publicación se completó.
6. En el iPhone, abrir la dirección en Safari y usar **Compartir → Agregar a pantalla de inicio**.

**Precaución:** nunca subir esta prueba al repositorio de la aplicación principal por error. La nueva instalación usa otro origen si se publica en `Diego-Midnight`; por eso los datos locales de la app original no se transfieren automáticamente. Exportar el respaldo en la aplicación original y verificarlo antes de importar información en la de pruebas. No eliminar la original.

**Seguridad clínica:** este trabajo es exclusivamente visual. No supone validación clínica de fórmulas ni autorización de uso para dosificar insulina. Confirmar siempre la pauta con el equipo tratante.
