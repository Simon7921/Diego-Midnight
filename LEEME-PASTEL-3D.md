# Diego Soft Pastel 3D — versión de prueba

Rediseño visual para GitHub Pages sobre el proyecto existente. Se conservan pantallas y funcionalidades: Inicio, Alimentos, Recetas, Favoritos, Historial, Pauta, Perfil, respaldos y PWA.

- Diseño: crema cálido + menta, sombras neumórficas suaves, botones lime, cabecera deportiva con ilustración SVG del futbolista/ciclista, superficies sólidas para información clínica.
- No se modificaron `calc.js` ni `store.js`. En `app.js` solo se modificó el color del tema y un texto visual. No se cambió lógica de dosis ni de nutrición.
- Las cifras de la imagen conceptual NO fueron incorporadas como datos reales.
- El tema `Pastel 3D` es el predeterminado para instalaciones nuevas; la alternativa `Claro` sigue disponible.

## Instalación GitHub Pages
1. Respaldar el repositorio de pruebas.
2. Subir TODOS los archivos descomprimidos a la raíz del repositorio `Diego-Midnight` (no solo el ZIP).
3. Confirmar el reemplazo y hacer Commit.
4. GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root).
5. Abrir la URL y comprobar por separado las secciones y la persistencia con datos de prueba.

## Advertencias
- En una PWA instalada, el service worker puede tardar en liberar el diseño anterior. Actualiza/reabre y comprueba la caché.
- No usar el prototipo como validación médica de la pauta de insulina. Esa lógica requiere revisión del equipo tratante.
- Revisa cuidadosamente los datos médicos personales antes de publicar un repositorio público.
- No importes un respaldo real hasta haber probado el funcionamiento de la app por separado.
