# Guía de Colaboración: Cómo Contribuir a The Boy With The Mask

Este proyecto utiliza Git y GitHub para el control de versiones, asegurando que el trabajo de todos los colaboradores se combine de forma segura y eficiente.

# 1. Requisitos Iniciales

Asegúrate de tener instalado el sistema de control de versiones Git en tu máquina.

# 2. Configuración Inicial del Proyecto (Clonar)

Para obtener tu copia de trabajo del repositorio, sigue estos comandos en tu terminal:

   # Clonar el Repositorio: Descarga el proyecto completo de GitHub a tu máquina local.

    git clone https://github.com/SylphRX9/The-Boy-With-The-Gas-Mask.git

# Acceder a la Carpeta: Entra al directorio del proyecto.

    cd The-Boy-With-The-Gas-Mask

<hr>

# 3. El Ciclo de Colaboración (DevOps)

IMPORTANTE: Para evitar sobrescribir el trabajo de tus compañeros, debes seguir siempre esta secuencia:
Paso	Comando	Propósito
Paso A: Actualizar	git pull origin main	Siempre ejecutar primero. Descarga y fusiona los cambios más recientes que otros hayan subido a GitHub (la rama main).
Paso B: Trabajar	(Modificar archivos, agregar código, etc.)	Realiza tus tareas de desarrollo en la carpeta local.
Paso C: Preparar	git add .	Prepara todos tus archivos modificados para guardarlos.
Paso D: Guardar (Commit)	git commit -m "Descripción concisa del cambio"	Crea un punto de guardado local (commit) con una descripción clara de lo que se hizo.
Paso E: Subir	git push origin main	Envía tus commits locales a la rama main en GitHub.

# Regla de Oro de Git

    "Primero Tira (Pull), Luego Empuja (Push)." Si intentas git push sin haber hecho git pull antes (y un compañero subió cambios), Git lo rechazará para proteger su trabajo.
