# 🎵 Análisis PCA del Eras Tour de Taylor Swift

Este proyecto explora patrones musicales en canciones del **Eras Tour** mediante **Análisis de Componentes Principales (PCA)**. El objetivo es identificar dimensiones latentes como **Intensidad/Energía**, **Bailabilidad/Positividad** y **Textura Acústico–Vocal**, y visualizar cómo se agrupan las canciones por era.

En este análisis, la era se usó para etiquetar y agrupar las observaciones en las visualizaciones (por ejemplo, colorear puntos en el biplot o crear gráficos de barras por era).
Esto permite interpretar los patrones encontrados en las componentes principales en relación con categorías relevantes, sin alterar el modelo PCA.

Fue un gran desafío, pero fue una forma entretenida de aprender a hacer PCA.

---

## 📂 Estructura del proyecto
-    ├── data/                # Datos originales y procesados
-    ├── script/             # Código en R para análisis y visualización
-    ├── outputs/             # Gráficos (no están en una carpeta aparte) 
-    ├── README.md            # Este archivo

---

## 🔍 ¿Qué incluye?

- 🧹 **Preprocesamiento**: Limpieza y etiquetado de canciones por era.
- 📋 **Análisis PCA**: Reducción de dimensionalidad y cálculo de varianza explicada.
- 📊 **Visualizaciones**: Los gráficos revelan cómo se organiza la diversidad musical del Eras Tour en dos dimensiones clave acá los vamos a revisar:
1. **Scree Plot PCA**
- Este gráfico muestra la proporción de varianza explicada por cada componente principal, destacando que PC1 (Intensidad/Energía) y PC2 (Acústico/Folk) concentran la mayor parte de la información.
   <img width="1222" height="994" alt="Scree Plot PCA" src="https://github.com/user-attachments/assets/db863dd8-483b-4bb8-8ee0-9d16b9c2ba3f" />

2. **Varianza Explicada PCA**
   - Este gráfico muestra la proporción de varianza explicada por cada componente principal, destacando que PC1 (Intensidad/Energía) y PC2 (Acústico/Folk) concentran la mayor parte de la información.
<img width="1014" height="824" alt="Varianza explicada Scree Plot" src="https://github.com/user-attachments/assets/847f356e-97da-4612-be93-53a24929bddd" />
   
3. **Indicador 1 PCA **Intensidad/Energía** por Eras**
- Este gráfico también muestra el promedio de PC1 (Intensidad/Energía) por era, evidenciando qué álbumes son más dinámicos y cuáles más acústicos.
<img width="1386" height="994" alt="Indicador PC1 por Era" src="https://github.com/user-attachments/assets/448c9294-8296-4fa2-aa97-02d8995e9ca4" />
   
4. **Relación entre observaciones y variables**
- Este gráfico revela qué variables influyen en cada componente: PC1 está dominado por métricas de energía y volumen, mientras PC2 refleja atributos acústicos y de positividad. Permite interpretar cómo cada característica contribuye a la estructura del PCA. 
<img width="1334" height="994" alt="Relación entre observaciones y variables" src="https://github.com/user-attachments/assets/fa403f63-7b3c-402c-a53b-a9b806e97291" />

5. **Heatmap**
- Evidencia patrones por era, destacando cómo álbumes contrastan en energía y atmósfera. En conjunto, el PCA explica cómo estas dimensiones capturan las diferencias esenciales entre eras y estilos.
<img width="1652" height="994" alt="Heatmap de cargas" src="https://github.com/user-attachments/assets/d2b71e5f-7a92-4b59-b8eb-ddf8053a092c" />
   
6. **Mapa **Intensidad/Energía** vs **Bailabilidad/Positividad** de las canciones**
- Este biplot combina PC1 (Intensidad/Energía) y PC2 (Acústico/Folk), mostrando cómo se distribuyen las canciones entre potencia y atmósfera. Canciones más bailables y positivas se agrupan hacia un extremo, mientras las más introspectivas se ubican en el otro.
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


