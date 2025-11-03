# Apuntes del Profesor — Proyecto base (MkDocs Material)

## Requisitos
- Python 3.9+
- `pip`

## Instalación
```bash
pip install -r requirements.txt
```

## Servir en local (desarrollo)
```bash
mkdocs serve
```
Abre el enlace que aparece (por defecto `http://127.0.0.1:8000`).

## Publicar
- **GitHub Pages:**
  ```bash
  mkdocs gh-deploy --force
  ```
- **Netlify/Vercel:** Comando de build `mkdocs build` y carpeta de salida `site/`.

## Notas
- Thebe + Pyodide permite ejecutar **Python** en el navegador.
- Para otros lenguajes, inserta iframes de Replit/StackBlitz/CodeSandbox en tus `.md`.
- Ajusta navegación y opciones en `mkdocs.yml`.
