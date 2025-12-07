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
   <img width="1222" height="994" alt="Scree Plot PCA" src="https://github.com/user-attachments/assets/db863dd8-483b-4bb8-8ee0-9d16b9c2ba3f" />

3. Varianza Explicada PCA
<img width="1014" height="824" alt="Varianza explicada Scree Plot" src="https://github.com/user-attachments/assets/847f356e-97da-4612-be93-53a24929bddd" />

   
5. Indicador 1 PCA **Intensidad/Energía** por Eras
<img width="1386" height="994" alt="Indicador PC1 por Era" src="https://github.com/user-attachments/assets/448c9294-8296-4fa2-aa97-02d8995e9ca4" />
   
7. Relación entre observaciones y variables
<img width="1334" height="994" alt="Relación entre observaciones y variables" src="https://github.com/user-attachments/assets/fa403f63-7b3c-402c-a53b-a9b806e97291" />

9. Heatmap
<img width="1652" height="994" alt="Heatmap de cargas" src="https://github.com/user-attachments/assets/d2b71e5f-7a92-4b59-b8eb-ddf8053a092c" />
   
11. Mapa **Intensidad/Energía** vs **Bailabilidad/Positividad** de las canciones
<img width="1652" height="994" alt="Mapa Intensidad Energía vs Bailabilidad Positividad de canciones" src="https://github.com/user-attachments/assets/1bd59505-8e98-4fbd-a00d-039e7939a0c2" />


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


