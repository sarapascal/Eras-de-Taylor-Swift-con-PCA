# 🎵 Análisis PCA del Eras Tour de Taylor Swift

Este proyecto explora patrones musicales en canciones del **Eras Tour** mediante **Análisis de Componentes Principales (PCA)**. El objetivo es identificar dimensiones latentes como **Intensidad/Energía**, **Bailabilidad/Positividad** y **Textura Acústico–Vocal**, y visualizar cómo se agrupan las canciones por era.

En este análisis, la era se usó para etiquetar y agrupar las observaciones en las visualizaciones (por ejemplo, colorear puntos en el biplot o crear gráficos de barras por era).
Esto permite interpretar los patrones encontrados en las componentes principales en relación con categorías relevantes, sin alterar el modelo PCA.

Fue un gran desafío, pero fue una forma entretenida de aprender a hacer PCA.

---

## 📂 Estructura del proyecto
├── data/                # Datos originales y procesados
├── script/             # Código en R para análisis y visualización
├── outputs/             # Gráficos (biplot, scree plot, heatmap)
├── README.md            # Este archivo

---

## 🔍 ¿Qué incluye?

- 🧹 **Preprocesamiento**: Limpieza y etiquetado de canciones por era.
- 📋 **Análisis PCA**: Reducción de dimensionalidad y cálculo de varianza explicada.
- 📊 **Visualizaciones**:
1. Scree Plot PCA
2. Varianza Explicada PCA
3. Indicador 1 PCA **Intensidad/Energía** por Eras
4. Relación entre observaciones y variables
5. Heatmap
6. Mapa **Intensidad/Energía** vs **Bailabilidad/Positividad** de las canciones


---

## 🖌 Paleta y tema visual

El proyecto utiliza una **paleta Swifty** y un tema personalizado (`eras_theme`) inspirado en las estéticas del tour, con tipografía serif y colores por era:

- Lover: tonos rosados
- Reputation: negro/gris
- Red: rojo intenso
- 1989: azul pastel
- Midnights: azul oscuro
- Folklore: gris neutro
- Evermore: beige cálido
- Fearless: dorado
- TTPD: tonos neutros

---

## ▶️ Cómo reproducir el análisis

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/eras-tour-pca.git
   cd eras-tour-pca
2. Ejecuta el script

---
## 👩🏽‍💻 ¿De dónde son los datos?

Los datos fueron obtenidos de https://www.kaggle.com/datasets/yukawithdata/taylor-swift-the-eras-tour-official-setlist-data


