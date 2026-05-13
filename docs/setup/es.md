## Instalación y Configuración

Para usar **GeoTimeLapse** con Google Earth Engine y generar animaciones, necesitas instalar dos dependencias esenciales:

### Dependencias necesarias:

1. **`earthengine-api`**: Esta librería te permite acceder y trabajar con datos de **Google Earth Engine** desde Python.
2. **`imageio_ffmpeg`**: Se utiliza para generar animaciones a partir de las imágenes satelitales obtenidas.

Ambas librerías son necesarias para interactuar con los datos de Google Earth Engine y para la creación de la animación.

### Instalar las dependencias a través de QGIS

Aunque puedes instalar estas dependencias en cualquier entorno de Python, a continuación te mostramos cómo hacerlo utilizando **QGIS**:

1. **Abre QGIS**.
2. **Abre la terminal de Python** en QGIS.

   Para abrir la terminal de Python, puedes ir a **Complementos** > **Consola de python** en QGIS. Si no estás usando QGIS, abre una terminal o consola de Python en el entorno que prefieras.

3. En la terminal de Python, ejecuta el siguiente comando para instalar las dependencias necesarias:

```python
import subprocess
import sys
subprocess.run([sys.executable, "-m", "pip", "install", "earthengine-api", "imageio_ffmpeg"])
```
