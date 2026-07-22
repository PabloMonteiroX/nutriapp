# 🥗 Nutriapp

Plan nutricional interactivo de Elizabeth (JM Team, Julio 2026), pensado para consultarse rápido desde el iPhone como si fuera una app nativa.

**Demo:** https://pablomonteirox.github.io/nutriapp/

## Qué hace

- Detecta el día de la semana automáticamente y muestra el plan correspondiente (lunes primero).
- Selector manual para consultar cualquier otro día.
- Cada día mapea a un tipo de entrenamiento:
  - **Lunes / Viernes** → Glúteo
  - **Martes / Miércoles / Jueves** → CrossFit
  - **Sábado / Domingo** → Descanso
- Horarios exactos y cantidades en gramos por comida.
- Kcal y macronutrientes (proteína / carbos / grasas) estimados por ración y total del día.
- Bloque de constantes nutricionales de referencia (kcal por gramo de macro, agua diaria, etc.)

## Stack

HTML + CSS + JavaScript puro. Sin frameworks, sin build step, sin dependencias — un solo archivo (`index.html`). Fuentes vía Google Fonts (Bebas Neue + Work Sans).

Desplegado con **GitHub Pages** desde la rama `main` (root).

## Instalar en iPhone

1. Abrir el link en **Safari** (no funciona igual en Chrome ni desde WhatsApp — hay que ser página web real, no archivo local).
2. Botón compartir → **Añadir a pantalla de inicio**.
3. Queda como icono nativo, a pantalla completa.

## Actualizar el plan

```bash
cd ~/dev/nutriapp
# editar index.html con los cambios
git add index.html
git commit -m "actualiza plan nutricional"
git push
```

Elizabeth no tiene que reinstalar nada — al abrir el icono, Safari carga la versión más reciente directo del repo.

## Nota

Los valores de kcal y macronutrientes son una **estimación** calculada con tablas nutricionales estándar por ración, no valores exactos de laboratorio ni datos provistos por JM Team.

---
Diseñado y mantenido por [pmonteir](https://github.com/PabloMonteiroX)
