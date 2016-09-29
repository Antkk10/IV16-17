`meta`
======

Directorio para objetivos. Inicialmente repositorio de objetivos
cumplidos, pero mas adelante podría ser otra cosa.

## Cómo usarlo

Ya deberías tener un *fork* de éste repositorio en tu cuenta
particular. Al principio del curso, crea un fichero de objetivos. Cada
vez que lo actualices,
[haz un *pull request*](http://aprendegit.com/que-es-un-pull-request/)
para poder incorporarlo aquí. En [este fichero](JJ.md) tienes un
ejemplo de cómo tienes que formatear los objetivos, que puedes
copiar/pegar de la página correspondiente.

Recuerda que tienes que mantener tu copia actualizada con el
repositorio original. Para ello, define un repositorio *upstream* de
esta forma

<<<<<<< HEAD
	git remote add upstream git@github.com:JJ/IV16-17.git
=======
	git remote add upstream git@github.com:JJ/IV16-17.git 
>>>>>>> f6f77419ab89ab87599f363a16cc108a077f4517

y antes de ponerte a trabajar con tu *fork* local del repositorio
recuerda hacer

	git pull upstream master
