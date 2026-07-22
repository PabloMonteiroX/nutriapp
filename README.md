# 🥗 Nutriapp

Plan nutricional interactivo de Elizabeth (JM Team, julio 2026), pensado para consultarse rápido desde el iPhone como si fuera una app nativa.

**Demo:** https://pablomonteirox.github.io/nutriapp/

## Qué hace

- Detecta el día de la semana automáticamente y muestra el plan correspondiente.
- Permite cambiar manualmente entre lunes, martes, miércoles, jueves, viernes, sábado y domingo.
- Cada día se asocia a un tipo de entrenamiento:
  - **Lunes / Viernes** → Glúteo
  - **Martes / Miércoles / Jueves** → CrossFit
  - **Sábado / Domingo** → Descanso
- Muestra horarios, cantidades en gramos y macros estimados por comida.
- Incluye un bloque de constantes nutricionales de referencia.

## Stack

HTML + CSS + JavaScript puro. Sin frameworks, sin build step, sin dependencias — un solo archivo (`index.html`). Fuentes vía Google Fonts (Bebas Neue + Work Sans).

Desplegado con **GitHub Pages** desde la rama `main` en la raíz del repositorio.

## Uso en iPhone

1. Abrir el link en **Safari**.
2. Botón compartir → **Añadir a pantalla de inicio**.
3. Se abre como icono nativo, a pantalla completa.

## Actualizar el plan

```bash
cd ~/dev/nutriapp
# editar index.html con los cambios
git add index.html
git commit -m "actualiza plan nutricional"
git push
```

Elizabeth no tiene que reinstalar nada: al abrir el icono, Safari carga la versión más reciente directamente desde GitHub Pages.

## Nota

Los valores de kcal y macronutrientes son una **estimación** calculada con tablas nutricionales estándar por ración, no valores exactos de laboratorio ni datos provistos por JM Team.

---

Diseñado y mantenido por [pmonteir](https://github.com/PabloMonteiroX)
