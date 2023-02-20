# Como crear repositorio y subir proyecto de GIT

1 - git init

El comando git init crea un nuevo repositorio de Git. Puede utilizarse para convertir un proyecto existente y sin versión en un repositorio de Git, o para inicializar un nuevo repositorio vacío.

![Referecia01](https://user-images.githubusercontent.com/124690541/220130725-7c512c44-3736-41a7-9636-68f69910b269.png)

2 - git remote add origin "URL repo"

El comando git remote add origin "URL repo" te permite crear una conexion con otro repositorio. Las conexiones remotas se asemejan más a marcadores que a enlaces directos con otros repositorios.

![referecia 02](https://user-images.githubusercontent.com/124690541/220135238-e394d9ed-bc5e-4f02-a27a-23677cfcfc90.png)

3 - git status

!INPORTANTE¡
El comando git status muestra el estado del directorio de trabajo y del área del entorno de ensayo. Permite ver los cambios que se han preparado, los que no y los archivos en los que Git no va a realizar el seguimiento. El resultado del estado no muestra ninguna información relativa al historial del proyecto.

![referencia 03](https://user-images.githubusercontent.com/124690541/220136625-5d37fb75-9f2c-44c5-b686-89ff6f147ce9.png)

4 - git fetch origin main

El comando git fetch descarga commits, archivos y referencias de un repositorio remoto a tu repositorio local.

![referencia 04](https://user-images.githubusercontent.com/124690541/220137931-c6c784c7-3076-4d71-94f5-ca9f2695241b.png)

5 - git pull origin main

El comando git pull se emplea para extraer y descargar contenido desde un repositorio remoto y actualizar al instante el repositorio local para reflejar ese contenido. La fusión de cambios remotos de nivel superior en tu repositorio local es una tarea habitual de los flujos de trabajo de colaboración basados en Git.

![Sin título](https://user-images.githubusercontent.com/124690541/220138910-52ca771b-8609-4938-8b90-952b1ec9df61.png)

6 - git add .

El comando git add añade un cambio del directorio de trabajo en el entorno de ensayo. De este modo, indica a Git que quieres incluir actualizaciones en un archivo concreto en la próxima confirmación.

![Sin título](https://user-images.githubusercontent.com/124690541/220139626-f99dab92-dd11-4ce2-a361-f76ec97344ac.png)

7 - git commit -m "Fist Commit"

El comando git commit -m "Fist Commit" permite hacer instantáneas del estado actual del trabajo y guardar los cambios es necesario incluir un mensaje. El mensaje debe ser una breve descripción de los cambios a los que se les está realizando commit en este caso "Fist Commit".

8 - git push -u origin main

Este comando especifica que usted está “empujando” o sincronizando el contenido hacia la rama main










