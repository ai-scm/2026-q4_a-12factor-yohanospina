# The Twelve Factor

## I. Codebase:
- Mantiene el código en un único repositorio, se puede acceder a él desde cualquier lugar permitiendo desplegar la misma base de código en entorno local o en servicios de prueba. Idéntico a Houndoc para construir aplicaciones nuevas sin escribir código nuevamente.
## II. Dependencies:
- Son todas las herramientas que el programa necesita para funcionar, especifica exactamente qué requiere la aplicación para correr.
## III. Config:
- Funciona principalmente para guardar contraseñas o código delicado que necesita una aplicación para funcionar que en caso de filtrarse podría comprometer los datos o información importante.
## IV. Backing Services:
- Son servicios externos que necesita la aplicación para funcionar, como bases de datos en la nube. Seguir este factor nos permite acoplar distintos servicios de forma sencilla, si en algún momento necesitamos cambiar de servicios externos, la implementacion de estos servicios no sera complicada.
