
## SAAC-Web-Inteligente

# Descarga del proyecto completo

https://drive.google.com/drive/folders/1P-y0EpdKilspUHf-VNBwcTGiyrR5pCpu?usp=sharing 

* Todo el proyecto se encuentra dentro de la carpeta compartida. Los notebooks de prueba ejecutados en Google Colab fueron utilizados para generar secuencias sin el uso del SAAC; estos forman parte de las pruebas y experimentación del proyecto. El SAAC fue desarrollado con el propósito de permitir la interacción directa del usuario final con el sistema.
* También se encuentran los manuales técnicos y de usuario, al igual que los resultados de las pictosecuencias preconstruidas.

* En caso de no contar con acceso a la carpeta, solicitar autorización a la persona responsable del proyecto.

* El SAAC se encuentra en la ruta:
  RESULTADOS > SITIO PICTOSEQ > DEMO_ACTUALIZACION.zip

Pasos para ejecutar el proyecto:

1. Descargar y descomprimir el archivo DEMO_ACTUALIZACION.zip.

2. Instalar Visual Studio Code.

3. Abrir la carpeta del proyecto en Visual Studio Code.

4. Activar el entorno virtual siguiendo el comando indicado en el apartado “Instalación”.

5. Ejecutar el proyecto desde Visual Studio Code (python run.py).

Nota:
Si el entorno virtual presenta errores o no funciona correctamente, eliminar la carpeta del environment (.venv) y seguir nuevamente los pasos de instalación mostrados abajo.


# Requisitos

* Python 3.11.5 
* 8 GB RAM mínimo
* Internet en la primera ejecución para descargar modelos IA

# Instalación

1. Crear entorno virtual

python -m venv .venv

2. Activar entorno virtual
Windows:

.\.venv\Scripts\activate

4. Instalar dependencias

pip install -r requirements.txt

4. Ejecutar aplicación

python run.py

Nota: La primera ejecución descargará automáticamente los modelos CLIP y BETO de Hugging Face.

Así deberia quedar el orden de carpetas del SAAC, lo anterior dentro de esta carpeta flask_pictos_site:
<br>
<img width="138" height="128" alt="image" src="https://github.com/user-attachments/assets/35394cdd-dc86-4cc5-849a-3aee64db964e" />

NOTA: Los pictogramas no son de auditoria, por lo que se pide descargarlos previamente de ARASAAC.
- Dentro del archivo config.py se tienen que definir las rutas a los datos (json de candidatos y secuencias, pictogramas, bootstrap y donde se guardara el cache al crear los embeddings).
- <img width="975" height="477" alt="image" src="https://github.com/user-attachments/assets/3183671e-02c4-4cce-8f8c-ce95efa6f42e" />

