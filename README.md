1. Crear un repositorio en vuestro GitHub llamado **masteruah**.

<img src="./img/1.png"/>

2. Clonar vuestro repositio en local.

git clone https://github.com/RafaGarcia24/masteruah.git

3. Crear (si no lo habéis creado ya) en vuestro repositorio local
  un documento **README.md**. 
 
El documento README.md se creo automaticamente al crear el repositorio.

4. Añadir al README.md los comanddos utilizados hasta ahora
  y hacer un coomit inicial con el mensaje **commit inicial**.
  
git commit -m "commit inicial"

5. Subir los cambios al repositorio remoto.n llamada **masteruah-tunombredeusua

git push

6. Añadir fichero **1.txt** al repositorio local.

echo "1" > 1.txt

7. Crear un tag **v0.1**.
  
git tag v0.1

8. Subir los cambios al repositorio remoto.

git push --tag

9. Crear una rama **v0.2**.

git branch v0.2

10. Posiciona tu carpeta de trabajo en esta rama.

git checkout v0.2

11. Añadir un fichero **2.txt** en la rama **v0.2**.

echo "2" > 2.txt

12. Subir los cambios al reposiorio remoto.

git push --branch

13. Posicionarse en la rama **master**.

git checkout main

14. Hacer un merge de la rama **v0.2** en la rama **master**.

git merge v0.2

15. En la rama **master** poner **Hola** en el fichero **1.txt** y hacer commit.

16. Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit.

17. Posicionarse de nuevo en la rama **master** y hacer un merge con la rama **v0.2**

+ git checkout (rama al la que quieras pasar)
+ git merge (ramas que quieras unir a la rama en la que estes)

18. Listar las ramas con merge y las ramas sin merge.

Con merge: git branch --merge
Sin merge: git branch --no-merge

19. Arreglar el conflicto anterior y hacer un commit.

vim (nombre del archivo que da conflicto)
<img src="./img/2.png"/>

20. Crear un tag **v0.2**

git tag v0.2

21. Borrar la rama **v0.2**

git branch -D v0.2

22. Listar los distintos commits con sus ramas y sus tags.

git log --oneline

23. Poner una foto en vuestro perfil de GitHub.

<img src="./img/3.png"/>

24. Poner el doble factor de autentificación en vuestra cuenta de GitHub.

<img src="./img/4.png"/>

25. Añadir (si no lo habéis hecho ya) la clave pública que se corresponde a tu ordenador.

<img src="./img/5.png"/>

26. Preguntar los nombres de usuario de GitHub de tus compañeros de trabajo en grupo, búscalos, y sigueles.

<img src="./img/6.png"/>

27. Añadir una estrella a los repositorios del resto de tus compañeros.

<img src="./img/7.png"/>

28.Crear una tabla de este estilo en el fichero **README.md** con la información
  de varios de tus compañeros de clase

|        NOMBRE          |                     GITHUB                         |
|------------------------|----------------------------------------------------|
| Javier Gómez 			     | [jalefrcracker](https://github.com/JLFcmd) 		    |
| Rafael García          | [Rafagarcia24](https://github.com/RafaGarcia24 )   |
| Lydia Moya             | [lydiamoyar](https://github.com/lydiamoyar)        |
| Alejandro Sánchez 	   | [AlexSancheez02](https://github.com/AlexSancheez02)|
| Juan Manuel Porras 	   | [Juanma104](https://github.com/Juanma104) 		      |

29. Poner a Alvaro como colaborador
  del repositorio **masteruah**
  
  (<img src="./img/8b.png"/>

30. Crear una organización llamada **masteruah-tunombredeusuariodegithub**

<img src="./img/9.png"/>

31. Crear 2 equipos en la organización **masteruah-tunombredeusuariodegithub**,
  uno llamado **administradores** con más permisos y otro **colaboradores** con menos permisos.

<img src="./img/10.png"/>
<img src="./img/11.png"/>

32. Meter a Alvaro y a 2 de vuestros
  compañeros de clase en el equipo **administradores**.

<img src="./img/12b.png"/>

33. Meter a Alvaro y a otros 2 de vuestros
  compañeros de clase en el equipo **colaboradores**.

<img src="./img/13b.png"/>

34. Crear un index.html que se pueda ver como página web en la organización.

<img src="./img/14.png"/>

35. Hacer 2 forks de 2 repositorios **masteruah-tunombredeusuariodegithub.github.io**
  de 2 organizaciones de las que no seais ni administradiores ni colaboradores.
  
<img src="./img/18.png"/>
<img src="./img/19.png"/>

36. Crearos una rama en cada fork.

<img src="./img/17.png"/>

37. En cada rama modificar el fichero **index.html** añadiendo vuestro nombre.

<img src="./img/16.png"/>

38. Con cada rama hacer un pull-request.

<img src="./img/15.png"/>

39. Aceptar los pull-request que lleguen a los repositorios de tu organización.

<img src="./img/20.png"/>
