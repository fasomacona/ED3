# Tema 3: Estructuras Lineales

Material didáctico completo para **GitHub Pages** del **Tema 3** de **Estructura de Datos (AED-1026)** — Tecnológico Nacional de México.

## Contenido

| Página | Descripción |
|--------|-------------|
| [index.html](index.html) | Portada y navegación |
| [pilas.html](pilas.html) | 3.1 Pilas: representación, operaciones, aplicaciones |
| [colas.html](colas.html) | 3.2 Colas: simples, circulares, bicolas, prioridad |
| [listas.html](listas.html) | 3.3 Listas: simples, dobles, circulares |
| [practica.html](practica.html) | Guía de la práctica |
| [notebooks/practica_tema3.ipynb](notebooks/practica_tema3.ipynb) | Jupyter Notebook (6 ejercicios) |

## Ver localmente

```bash
python -m http.server 8000
# http://localhost:8000
```

## Publicar en GitHub Pages

```bash
git init
git add .
git commit -m "Tema 3: Estructuras Lineales"
git remote add origin https://github.com/TU_USUARIO/estructura-datos-tema3.git
git push -u origin main
```

**Settings → Pages → Source:** `main` / root  
URL: `https://TU_USUARIO.github.io/estructura-datos-tema3/`

## Notebook

1. Pila estática y dinámica  
2. Historial de navegador + paréntesis balanceados  
3. Cola, cola circular y restaurante  
4. Cola de prioridad (aeropuerto)  
5. Lista simplemente enlazada  
6. Reto: elegir la estructura adecuada  

```bash
pip install jupyter
jupyter notebook notebooks/practica_tema3.ipynb
```

## Competencia

> Comprende y aplica estructuras de datos lineales para la solución de problemas.

## Licencia

Material educativo basado en el programa AED-1026 del TecNM (mayo 2016).
