# Trabajo Practico N4 - IHS

Este repositorio esta destinado para la entrega del trabajo practico de la materia Interacción Hombre Sistema de la Universidad Tecnologica Nacional - Facultad Regional La Plata.

## Descripción 

La Escena de la Realidad Aumentada se realizo dentro de la plataforma Unity, creando un proyecto con Unity Hub 2.4.5, utilizando la versión de Unity 2020.3.20f1. 
Como complemento se ha agregado Vuforia, un SDK para poder realizar las escenas de RA en dispositivos móviles. 
Vuforia además de permitió crear una base de datos en la cual cargue las imágenes a utilizar dentro de la aplicación. 

## Tracking
El método elegido de Tracking es el ImageTracking. Lo que realiza la aplicación es detectar por medio de la cámara 3 imágenes, cargada en la base de datos de Vuforia. Cuando se detecta la imagen, que en este caso son el frente de unas cajas como se ve en el video de presentación, se renderizan los objetos en 3D. 
