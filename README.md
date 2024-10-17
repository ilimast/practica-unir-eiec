# Repo para EIEC - DevOps - UNIR

Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas mas.

---

Los comandos del Makefile funcionarán en Linux y MacOS. En caso de usar Windows, necesitarás adaptarlos o ejecutarlos en una máquina virtual Linux.

## Ejecución

python3 main.py <filename> <dup>
  filename: **ruta** al fichero que contiene la lista de palabras, una por línea
  dup: **yes|no**, yes para eliminar palabras duplicadas, no para mantener la lista


Ejecuta el script de la siguiente manera, segun los siguientes casos de uso:

Con duplicados eliminados:
python3 main.py palabras.txt yes

Sin eliminar duplicados:
python3 main.py palabras.txt no

Si el archivo palabras.txt no existe, se usan palabras por defecto:
python3 main.py noexiste.txt yes
