# CLASE 11 DE PYTHON

Hoy vamos a hacer actividad en Python en un día como programadores:

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

mkdir python-final

3. Entramos en ella: 

cd python-final

4. Iniciamos el repositorio:

git init

5. Creamos un archivo:

touch finales.py

6. Abrimos VSC:

code .

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

python -V

python3 -V

8. Creamos el entorno virtual en Python:

python3 -m venv venv #Creamos el entorno virtual

9. Activamos el entorno virtual:

source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows

10. Hacemos actualización del pip de Python

python3 -m pip install --upgrade pip #Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.


# RESPUESTA A LA PREGUNTA 11
## ¿Qué es el pip y porque lo actualizamos?

Pip es el administrador de paquetes de Python que permite instalar, actualizar y desinstalar paquetes de software. Pip viene preinstalado con Python 3.4 y versiones posteriores, y se puede verificar su instalación ejecutando pip --version en la terminal.

Actualizar Pip es crucial por varias razones:

Seguridad: Las actualizaciones a menudo incluyen parches de seguridad que protegen el entorno de desarrollo contra vulnerabilidades conocidas.
Nuevas Funcionalidades: Las nuevas versiones de Pip pueden incorporar nuevas características que mejoran su funcionalidad y uso.
Corrección de Errores: Las actualizaciones corrigen errores que podrían afectar el rendimiento y la estabilidad.
Compatibilidad: Mantener Pip actualizado asegura la compatibilidad con las versiones más recientes de Python y otros paquetes.

<sub>Para actualizar Pip a su versión más reciente, se puede utilizar el siguiente comando en la terminal:</sub>
```sh
    pip install --upgrade pip
```

