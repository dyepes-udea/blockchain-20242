# blockchain-20242

# Blockchain en Python

Este proyecto implementa una blockchain simple en Python que incluye características básicas como el bloque génesis, minería con prueba de trabajo, transacciones, y validación de la cadena.

## Características
- Bloque génesis
- Prueba de trabajo con parámetro de dificultad
- Encadenamiento de bloques usando el hash del bloque anterior
- Transacciones incluyendo una transacción Coinbase
- Validación de la cadena de bloques

## Requisitos

- Python 3.x
- Bibliotecas incluidas en la instalación estándar de Python

## Instalación y Ejecución

### Ejecución en Entorno Local

1. **Clonar el repositorio**:
   Abre tu terminal y clona este repositorio en tu máquina local.

   ```bash
   git clone https://github.com/usuario/blockchain-python.git
   cd blockchain-python
2. **Ejecutar el proyecto:**:
No es necesario instalar bibliotecas adicionales. Simplemente puedes ejecutar el script Python que contiene la implementación de la blockchain

Esto ejecutará el archivo blockchain.py, donde se creará la blockchain y se agregarán bloques a la cadena. Puedes ajustar el nivel de dificultad dentro del script según tus preferencias.
  ```bash
  python blockchain.py
  ```

### Ejecución en Google Colab

1. **Abrir Google Colab**:
   Ve a [Google Colab](https://colab.research.google.com) y crea un nuevo notebook.

2. **Cargar el código del proyecto**:
   Puedes copiar y pegar el código del archivo `blockchain.py` en una celda de tu notebook de Google Colab.

3. **Ejecutar el código**:
   Una vez pegado el código, puedes ejecutar las celdas del notebook y ver los resultados directamente en el entorno de Google Colab.

   Si prefieres cargar el archivo desde tu computadora, puedes subir el archivo `blockchain.py` a Colab siguiendo estos pasos:
   
   - En Colab, haz clic en el ícono de carpeta en el panel lateral.
   - Haz clic en el botón de carga (`Upload`) para subir el archivo `blockchain.py`.
   - Luego ejecuta el siguiente código para ejecutar el archivo:

   ```python
   !python blockchain.py
