# CFD - 16 dic 2020 
## Problemas con el modelo

El modelo se puede bajar completo haciendo clic en bajar code.

## Para correr el modelo

Se debe correr de la siguiente manera:
- ```blockMesh``` 
- ```surfaceFeatureExtract```
- ```snappyHexMesh -overwrite``` Se demora harto, aproximadamente unos 8 minutos
- ```checkMesh -allGeometry -allTopology```
- ```simpleFoam```
## Cuál es el problema?

El problema es que conforme se itera el modelo pasa esto

![Pucha](/assets/images/uwu.png)


Al correr paraview con el comando ```paraFoam``` 




