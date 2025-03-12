# DS_RustyBargain

Tipo de proyecto: DS - Data Science

Sector: E-commerce automotriz

Tecnologías implementadas: Pandas | Numpy | Matplotlib | Seaborn | Sklearn  <DecisionTreeRegressor> <RandomForestRegressor> <LinearRegression>| Lightgbm | Catboost | Xgboost

Introducción:
Rusty Bargain es un servicio de venta de coches usados ​​que está desarrollando una app para atraer nuevos clientes. Gracias a esta app, puedes conocer rápidamente el valor de mercado de tu coche. Tenemos acceso al historial, las especificaciones técnicas, las versiones de equipamiento y los precios. Necesitamos crear un modelo que determine el valor de mercado.

A Rusty Bargain le interesan:
- La calidad de la predicción
- La velocidad de la predicción
- El tiempo de entrenamiento

Conclusiones:
De los modelos entrenados XGB logró el mejor resultado entre los 6 modelos con un promedio de aproximadamente 2.02 segundos de cálculo de entrenamiento, seguido de LGBM con una métrica similar, por lo que en este caso podríamos considerar que la mejor opción para determinar el valor de un vehículo podría lograrse utilizando el método XGB, ya que su tiempo de ejecución es el segundo más bajo pero tiene el mejor RMSE.
