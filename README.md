# Analisis-del-mercado-de-Steam
Usando el dataset de Kaggle llamado "Steam Games Dataset 2021-2025 (65k+)" se hizo un análisis básico de distintos factores.

## Descripción del Proyecto
Este proyecto analiza el dataset extraido de Kaggle, "Steam Games Dataset 2021-2025 (65k+)" para identificar tendencias en los géneros más populares y determinar si existe una relación entre el precio de venta y el éxito del juego (medido en recomendaciones).

# Herramientas Utilizadas
**Python:** Lenguaje principal.

**Pandas:** Limpieza y transformación de datos (uso de .explode() para manejo de géneros).

**Seaborn & Matplotlib:** Visualización de datos y análisis estadístico.

# Hallazgos Principales

## **1. Dominio de Géneros**
El género Indie es aquel que lidera el mercado en volumen, seguido del género de 'Casual' y del de 'Aventura'
<img width="911" height="548" alt="image" src="https://github.com/user-attachments/assets/2e44a400-e2f6-46ab-b6b9-5216a8f76f9f" />

## **2. Análisis de precios** 
A pesar de ser el más común, el género Indie mantiene precios promedio bajos.
Géneros como los de 'Deportes' 'RPG' y 'Simulación' presentan precios promedio superiores, lo que indica nichos de mercado más costosos.
<img width="1298" height="548" alt="image" src="https://github.com/user-attachments/assets/0e217e66-10c7-41b1-a23d-7b3c070ca685" />

## **¿El precio garantiza el éxito?** 
¿El precio garantiza el éxito?
Tras analizar la correlación entre el precio y las recomendaciones, se obtuvo un coeficiente de 0.06.

Conclusión: Existe una correlación positiva casi nula. El precio no es un indicador de la popularidad de un juego en la plataforma, de esto se puede deducir que factores como la jugabilidad, la duración u otros podrían ser más importantes
<img width="1017" height="1011" alt="image" src="https://github.com/user-attachments/assets/97cfe43d-2bd8-4802-84d7-9ee3f1c5a974" />



