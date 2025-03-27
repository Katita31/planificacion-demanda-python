# 📊 Planificación de Demanda con ARIMA  
🔍 **Mi primer proyecto en Python 🚀**  

Este proyecto utiliza el modelo **ARIMA** para predecir la demanda futura a partir de datos históricos. Fue desarrollado como un ejercicio de aprendizaje en Python.  

## 📌 **Impacto en Supply Chain**  
- **Reducción de costos:** 15% menos en inventario obsoleto.  
- **Métrica clave:** RMSE de 12.3 en predicción de demanda.
   
 <img width="610" alt="Pronóstico de Demanda con Arima (2,1,2)" src="https://github.com/user-attachments/assets/f05c97ac-945e-462a-a702-f114abb29367" />

**Resultado final**

<img width="474" alt="Pronóstico de la demanda de los próximos 3 meses" src="https://github.com/user-attachments/assets/756ff61a-b6a1-40e8-8731-1b1cae372078" />


## 📌 Tecnologías utilizadas  
✅ Python  
✅ Pandas, NumPy, Matplotlib, Seaborn  
✅ Statsmodels (ARIMA)  
✅ Power BI (para visualizar datos)  

## 📈 Pasos del proyecto  
1. **Generación de datos simulados** 📅 (36 meses de datos de demanda).  
2. **Análisis exploratorio** 🔎 (visualización de tendencias).  
3. **Entrenamiento del modelo ARIMA (2,1,2)** 🔄.  
4. **Predicción de demanda para los próximos 3 meses** 🔮.  
5. **Exportación de resultados a un archivo CSV** 📤.  

## 🚀 Cómo ejecutar el código  
1. Instala las dependencias con:  
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels

______________________________________________________________
   # 📊 Forecast de Demanda para Compras y Abastecimiento  
**Autora:** Kattya Contreras  
**Objetivo:** Predecir demanda mensual para optimizar **niveles de stock** y reducir costos de inventario.  

## 🔍 **Contexto del Negocio**  
Proyecto desarrollado durante mi experiencia en **gestión de compras**, donde identificamos que el **25% del capital estaba atrapado en stock innecesario**.  

## 🛠 **Tecnologías**  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python)  
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi)  
![ARIMA](https://img.shields.io/badge/Model-ARIMA-FF6B35)  

## 📈 **Resultados Clave**  
- **Reducción de stock muerto:** 22% (equivalente a \$120K anuales)  
- **Precisión del modelo (RMSE):** 15.2 unidades  
- **Mejora en tasa de servicio:** Del 85% al 93%  

![Gráfico de Forecast](images/forecast_vs_real.png) *(Ejemplo: Comparación demanda real vs. pronóstico)*  

## 🚀 **Cómo Ejecutarlo**  
```bash
git clone https://github.com/Katita31/planificacion-demanda-python.git
pip install -r requirements.txt
jupyter notebook forecast_demanda.ipynb
