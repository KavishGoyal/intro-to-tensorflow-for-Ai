# intro-to-tensorflow-for-Ai
deep learning.ai@coursera
import tensorflow as tf
import numpy as np
from tensorflow import keras
model = tf.keras.Sequential([keras.layers.Dense(units=1, input_shape=[1])]) # Your Code Here#
model.compile(optimizer='sgd', loss='mean_squared_error')
xs = np.array([1.0, 2.0, 3.0, 4.0], dtype=float) # Your Code Here#
ys =  np.array([100.0, 150.0, 200.0, 250.0], dtype=float) # Your Code Here#
model.fit(xs, ys, epochs=1200)
print(model.predict([7.0]))
