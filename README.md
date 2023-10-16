# Ejercicio de clase

## modificación de clase


1) En consola nos posicionamos en la carpeta donde queremos copiar el directorio

Ej: cd COD

2) Se copia la url del repositorio en github

3) En consola se utiliza: git clone -o (nombre repositorio) (url del repositorio a clonar)

Ej:  git clone -o pruebasReadme https://github.com/danielcastelao/pruebasReadme.git

4) En consola nos posicionamos dentro del repositorio que acabamos de clonar

Ej: cd pruebasReadme

5) Se utiliza: git remote add origin (url del repositorio donde se quiere agragar el repositorio clonado)

Ej: git remote add origin https://github.com/LuciaPosada/Clonado2.git

6) Se utiliza el comando: git remote -v

7) Se realizan los cambios que se quieran realizar al repositorio

8) Se utilizan los comandos:

git add (README.md)

git commit -m ("cambios en el readme")

git brach -M main

git push -u origin main
