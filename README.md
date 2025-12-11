# Autoencoder: Denoising y Superresolución con MNIST

Este proyecto implementa dos Autoencoders Convolucionales usando PyTorch:

1.  **Denoising Autoencoder:** Elimina ruido gaussiano de imágenes de dígitos manuscritos.
2.  **Super-Resolution Autoencoder:** Reconstruye imágenes de alta resolución (28x28) a partir de inputs de baja resolución (7x7).

## Resultados

### Eliminación de Ruido
(Aquí puedes pegar una captura de tus resultados de la Tarea A)

### Superresolución
(Aquí puedes pegar una captura de tus resultados de la Tarea B)

## Estructura del Código
El modelo utiliza capas `Conv2d` y `ConvTranspose2d`, con función de activación `Tanh` en la salida para normalizar el rango entre -1 y 1.