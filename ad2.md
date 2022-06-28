# Actividad Dirigida 2

La Actividad Dirigida 2 consiste en **explicar los procedimientos 
efectuados a la hora de efectuar el cambio de README.md** en la Actividad 
Dirigida 1. Así pues, a continuación se detalla una guía numerada del 
proceso.

## Primeros pasos en GitHub

1. En primer lugar, **traduje el contenido redactado en Markdown al 
formato HTML**. Para ello, simplemente debía acceder a mi cuenta de GitHub 
para, desde *Source*, seleccionar *main* en la opción 1 y *root* en la 
opción 2.

2. A continuación, creé el archivo pertinente para poder desarrollar este 
documento. Cliqué en *Add file* y **generé un nuevo archivo al que 
denominé ad2.md**.

3. En la dirección https://github.com/settings/tokkens **generé un nuevo 
token** al que denominé “PD2”

Habiendo concluido los primeros pasos, abrí la terminal de mi MacBook Pro 
y proseguí con el ejercicio.

## El trabajo desde la terminal

3. Primeramente, escribí el comando **pwd** y después lo ejecuté **para 
conocer el directorio** desde donde estaba trabajando. Acto seguido, 
ejecuté el comando **git clone** 
https://github.com/nebrijas/celiamiguelm-web **para copiar el directorio 
del repositorio en el directorio local** de mi portátil. 

*Inciso. En este punto cerré el ordenador y después me metí en un pequeño 
entuerto al desconocer el lugar exacto en el que había clonado el 
repositorio. Creé un nuevo repositorio para iniciar los pasos desde el 
principio, pero comencé a mezclar la información de ambos repositorios y 
hube de solicitar una tutoría mediante la que el profesor me sacó de aquel 
bucle pernicioso. **Para conocer el lugar en el que se ubica el 
repositorio clonado** simplemente debía escribir el comando **ls***

4. Habiendo realizado la copia, utilicé el comando **cd para acceder a la 
carpeta pertinente** y después escribí **git confing user.name 
celiamiguelm**. A continuación, realicé un paso similar, pero igualmente 
necesario: escribir **git confing user.email 
cmiguelma@alumnos.nebrija.es**

5. El quinto punto me obligó a salir momentáneamente de la terminal: [debí 
regresar al sitio web](https://github.com/nebrijas/celiamiguelm-web) 
incluido en el 
punto 3 para copiar el token creado. Este constituía la contraseña que 
debía utilizar en el siguiente paso.

6. De nuevo en la terminal, escribí **echo “(+ el token)”> ../.token  para 
agregar un archivo oculto** en la carpeta superior del árbol.

7. Después escribí **README.md ad1.md** y ejecuté la orden **para copiar 
en una nueva carpeta el contenido** del archivo ad1.md.

8. A continuación, escribí **nano README.md para abrir la consola nano** 
mediante la que modifiqué el archivo. Añadí dos enlaces: el primero me 
redimiría a la ad1.md y el segundo a la ad2.md, es decir, al directorio 
donde se está desarrollando este ejercicio.

9. Escribí **git add README.md ad1.md para que la carpeta creada fuera** 
también **visible en la web**.

10. Por último, escribí **git push** para guardar el contenido en GitHub.


