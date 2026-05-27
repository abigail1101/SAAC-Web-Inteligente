
## SAAC-Web-Inteligente

# Descarga del proyecto completo

https://drive.google.com/drive/folders/1P-y0EpdKilspUHf-VNBwcTGiyrR5pCpu?usp=sharing 

Solicitar acceso con la persona responsable de este proyecto

El SAAC se encuentra en la carpeta RESULTADOS > SITIO PICTOSEQ > DEMO_ACTUALIZACION.zip
- Descargar y descomprimir la carpeta DEMO_ACTUALIZACION.zip
- Instalar Visual Studio Code
- Abrir el proyecto en Visual y ejecutar activando el environment con el comando del punto 2. Activar entorno virtual del apartado Instalación
- Nota: Si no funciona, elimina el environment de la carpeta y sigue los pasos que se muestran abajo.

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

3. Instalar dependencias

pip install -r requirements.txt

4. Ejecutar aplicación

python run.py

Nota: La primera ejecución descargará automáticamente los modelos CLIP y BETO de Hugging Face.

Así deberia quedar el orden de carpetas del SAAC:
<img width="138" height="128" alt="image" src="https://github.com/user-attachments/assets/35394cdd-dc86-4cc5-849a-3aee64db964e" />

