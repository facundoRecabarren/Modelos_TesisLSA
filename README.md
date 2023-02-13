# Modelos_TesisLSA
Datos, modelos, entrenamiento

Como primer paso se instalan los paquetes/librerias necesarias para realizar el entrenamiento y obtencion de datos.

Luego se encuentra una primer instancia donde realicé un acercamiento a la generacion de videos, almacenamiento, procesamiento y por ultimo entrenamiento.

Siguiente a esto se encuentra una instancia de: 
- Definicion de Palabras
- Armado de Directorios/Archivos
- Procesamiento de los videos del set de datos LSA64
- Almacenamiento de los resultados para cada video
- Construccion de Distintos modelos
- Configuraciones para el entrenamiento
- Por ultimo codigo para controlar como se comporta el modelo que se entrenó sobre todo el set de datos.

Al final de todo se encuentran distintos tipos de pruebas realizadas, tambien pruebas sobre OpenPose para compararlo con MediaPipe.


[Link a los datos de videos ya procesados](https://drive.google.com/file/d/1Q1A94UmeEYExCOpjysJc996Ozx8jX9Ao/view?usp=share_link). 
Este .zip contiene un archivo .npy para cada video, cada archivo consituye un arreglo de 201 frames, donde algunos videos pasaron por una instancia de
padding (valor 3 a la derecha del arreglo) para alcanzar la longitud de 201.

Para poder ejecutar la Notebook "Modelos.ipynb" es necesario tener el .zip descargado y descomprimido, se recomienda descomprimir en una carpeta "LSA64_data" para evitar  tener que modificar la ruta en el codigo.
