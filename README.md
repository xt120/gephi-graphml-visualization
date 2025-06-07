# Visualización de grafo en Gephi (.graphml)

Este repositorio contiene un archivo de red social en formato `.graphml`, listo para ser cargado en Gephi y visualizado con herramientas básicas.

## 📁 Archivo incluido

- `facebook.graphml`: Grafo de conexiones (ejemplo tipo Facebook)

## ⚙️ Pasos para visualizar en Gephi

1. **Abrir Gephi**
2. **Cargar el archivo** `facebook.graphml`
3. En la pestaña **Layout**, seleccionar `ForceAtlas 3D` y ejecutarlo unos segundos
4. Ir a **Estadísticas** y ejecutar `Modularity` para detectar comunidades
5. En la pestaña **Apariencia**, aplicar color por comunidad
6. Ir a **Preview**, activar bordes, etiquetas si quieres, y exportar la imagen

## 🎯 Resultado

Una red clara, con nodos distribuidos espacialmente y coloreados según su comunidad detectada.

## ✅ Objetivo

Este archivo está pensado **solo para practicar visualización en Gephi**.
