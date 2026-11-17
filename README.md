# Machine Learning — Edición esencial en español

Manual de estudio estático (sin build, sin dependencias) para aprender machine learning con scikit-learn y PyTorch.
Alineado temáticamente con *Hands-On Machine Learning with Scikit-Learn and PyTorch*, de Aurélien Géron, pero con texto y diagramas originales.

## Qué incluye

- **76 lecciones** en **19 módulos** (3 lecciones y 1 evaluación por módulo).
- Lectura continua: botón «Completar y seguir», navegación con ← y →, temario lateral siempre disponible.
- **19 evaluaciones** de 3 preguntas con explicaciones y **57 ejercicios** aplicados.
- Progreso guardado en `localStorage`, glosario con buscador y modo claro/oscuro.
- Buscador global con atajo `⌘K` / `Ctrl+K`.
- **57 diagramas originales** en SVG.
- Manual en PDF: `Machine-Learning-Esencial.pdf`.
- Tipografías locales (Fraunces + Inter), sin depender de Google Fonts.

## Estructura

```
index.html                 Portada y temario completo
ml1l1.html … ml19q.html      Lecciones y evaluaciones
glosario.html              Glosario con búsqueda
progreso.html              Progreso por módulo
css/curso.css              Diseño editorial responsive
js/curso.js                Navegación, progreso, búsqueda y quizzes
assets/fonts/              Tipografías locales
Machine-Learning-Esencial.pdf
```

## Publicar en GitHub Pages

```bash
cd ml-esencial
git init
git add .
git commit -m "Machine Learning en español"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/ml-esencial.git
git push -u origin main
```

Después: **Settings → Pages → Deploy from a branch → main → / (root)**.

## Regenerar

```bash
python build_site.py          # solo el sitio
python build_site.py --pdf    # sitio + manual en PDF
```

El PDF se compone con WeasyPrint a partir del mismo contenido.

## Atajos

| Tecla | Acción |
|---|---|
| `←` / `→` | Lección anterior / siguiente |
| `C` | Marcar la lección actual como completada |
| `/` o `⌘K` | Abrir el buscador |
| `Esc` | Cerrar buscador o menú |
| `?` | Recordatorio de atajos |

## Créditos

Manual original de estudio en español, alineado con los temas de *Hands-On Machine Learning* de Aurélien Géron.
No reproduce el texto ni las figuras del libro. Uso educativo.
