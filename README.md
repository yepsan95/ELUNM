# ELUNM 2024

Este directorio aloja los archivos del patch de sampleo
desarrollado para los proyectos del ELUNM de 2024 y en adelante.
El proyecto consiste en un sampler de 8 canales con múltiples efectos y posibilidades.

## Directorios

### 	__lib__

		Contiene las abstracciones usadas en el patch principal main.

### 	__samples__

		Contiene los directorios desde donde se cargarán los samples.
		Estos directorios tienen por nombre:

			- samples0
			- samples1
			- samples2
			- samples3
			- samples4

		Cada uno de estos directorios puede funcionar hasta con 8 samples a la vez.

## Cómo usar

	Todo se ejecuta desde el archivo main.

	Instrucciones:

		1. Copiar los samples deseados a uno de los directorios de la carpeta samples.
		2. Abrir el archivo main.
		3. Cargar la carpeta correspondiente con los bangs verdes de la sección superior.
		4. Reproducir los samples en cada instancia y manipular los parámetros a placer.

## Instalación

	Para descargar y mantener actualizar el proyecto en tu computadora,
	necesitas tener instalado git.

	Una vez instalado, los pasos a seguir son:

### 	Clonar el repositorio

			1. Abre el explorador de archivos y ve hacia la carpeta donde deseas alojar el repositorio.
			2. Una vez allí, escribe 'cmd' en la barra de dirección.
			3. Se abrirá una ventana de la terminal de Windows. En ella, escribe el siguiente comando:
				git clone https://github.com/electroacustica-unm/ELUNM.git

	Una vez hecho esto, tendrás todos los archivos del repositorio ELUNM en tu máquina local.

###		Actualizar el repositorio

		En caso hayan actualizaciones en los proyectos del repositorio, puedes actualizar los archivos en tu máquina local de la siguiente manera:

			1. Abre el explorador de archivos y ve hacia la carpeta donde está alojado el repositorio (ELUNM).
			2. Una vez allí, escribe el cmd en la barra de dirección.
			3. Se abrirá una ventana de la terminal de Windows. En ella, escribe el siguiente comando:
				git pull

### Dependencias

	Librerías:

		- zexy
		- else

####  [Link to Official website of ELUNM](https://www.unm.edu.pe/investigacion/direccion-de-innovacion-y-transferencia-tecnologica/laboratorio-de-musica-electroacustica-y-arte-sonoro/elunm/)
