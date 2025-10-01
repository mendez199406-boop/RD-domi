# RD-domi
from sklearn.linear_model import LinearRegression
import numpy as np

# Datos de entrenamiento
X = np.array([[1], [2], [3], [4], [5]])
y = np.array([2, 4, 6, 8, 10])  # salida esperada

# Crear y entrenar modelo
modelo = LinearRegression()
modelo.fit(X, y)

# Probar la IA
print("Predicción para 6:", modelo.predict([[6]])[0])
