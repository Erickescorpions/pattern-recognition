# Practica 0

Para poder ejecutar el notebook desde tu entorno virtual:

1. Encontrarse dentro de la carpeta de la P0
``` shell
pwd
# Output: some_path/P0
```

2. Crear un entorno virtual.
``` shell
python -m venv venv
# si no funciona usar
python3 -m venv venv
```

3. Activar el entorno virtual.
``` shell
# Windows
. .\venv\Scripts\activate

# Linux
source /venv/bin/activate
```

4. Instalar las dependencias con pip.
``` shell
pip install -r requirements.txt
```

5. Descomprimir archivo static.zip en una carpeta con el  nombre `static`. Esta carpeta contiene las imagenes que se utilizan en la practica. 