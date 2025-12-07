# 🎵 Análisis PCA del Eras Tour de Taylor Swift

Este proyecto explora patrones musicales en canciones del **Eras Tour** mediante **Análisis de Componentes Principales (PCA)**. El objetivo es identificar dimensiones latentes como **Intensidad/Energía**, **Bailabilidad/Positividad** y **Textura Acústico–Vocal**, y visualizar cómo se agrupan las canciones por era.

---

## 📂 Estructura del proyecto
├── data/                # Datos originales y procesados
├── scripts/             # Código en R para análisis y visualización
│   ├── 01_preprocesamiento.R
│   ├── 02_pca.R
│   ├── 03_visualizaciones.R
├── outputs/             # Gráficos (biplot, scree plot, heatmap)
├── README.md            # Este archivo

---

## 🔍 ¿Qué incluye?

- **Preprocesamiento**: Limpieza y etiquetado de canciones por era.
- **Análisis PCA**: Reducción de dimensionalidad y cálculo de varianza explicada.
- **Visualizaciones**:
  - Scree Plot con % de varianza.
  - Biplot PC1 vs PC2 con subtítulo dinámico.
  - Heatmap de cargas (PC1–PC3) con etiquetas descriptivas.
  - Barras por era con paleta personalizada inspirada en el Eras Tour.

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

## 📊 Visualización de datos

1. Scree Plot PCA
3. Varianza Explicada PCA
4. Indicador 1 PCA **Intensidad/Energía** por Eras
5. Relación entre observaciones y variables
6. Heatmap
7. Mapa **Intensidad/Energía** vs **Bailabilidad/Positividad** de las canciones
