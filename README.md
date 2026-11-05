*¿Que aprendi del curso?*
Concepto de Control de Versiones:La importancia fundamental de utilizar un Sistema de Control de Versiones (VCS) como Git, creado originalmente por Linus Torvalds en 2005, para administrar de forma limpia, segura y ordenada los cambios e historial de un proyecto de software a lo largo de su ciclo de vida.

Características Clave:La gestión eficiente de ramas (branches), la escalabilidad para proyectos grandes y el soporte robusto para la colaboración simultánea en equipo sobre un mismo código base.

Flujo de Trabajo Esencial: Se entendió cómo manejar proyectos con Git y GitHub, agregando archivos al área de preparación, realizando commits para guardar cambios y sincronizando todo con repositorios remotos.

Igual tome otro curso un poco mas largo donde aprendi a buscar los comandos y navegar desde la terminal por una carpeta, en ese tuve algunos problemas porque en un momento utilizo un comando que no reconocia mi terminal, asi que tuve que preguntar a Copilot y me explico que para mi terminal era distinto.

*¿Que comandos utilizaste?*

Paso 1: Verificar que la terminal funciona y su version:

![alt text](image.png)

Paso 2:Realizar la credencial con el nombre y el email:

![alt text](image-1.png)

Paso 3:Acceder a la carpeta(No podiaaa):

![alt text](image-2.png)

Paso 4:Inicializar el repositorio con Git init:

![alt text](image-3.png)

Paso 5:Visualizar los archivos ocultos:

![alt text](image-4.png)

Paso 6:Verificar el estado de los archivos
    Para comprobar que Git detecta la carpeta, con el comando status:

![alt text](image-5.png)

Paso 7:Preparar los archivos (Stage-listos para ser confirmados)
    Añadi todos los archivos de la carpeta actual al área de preparación con el comando add:

![alt text](image-6.png)

Paso 8:Guardar los cambios (commit)
     Primera instantánea del proyecto con un mensaje descriptivo con el comando commit -m:
     El comando git commit toma todos los archivos que estaban en esa zona de espera y les toma una instantánea o foto permanente en la historia de tu proyecto.

![alt text](image-7.png)

Dato :Cuando realizas un cambio en un archivo utilizas status para conocer que un archivo fue modificado:

![alt text](image-8.png)

Dato 2 : Para conocer cual fue la modificacion utilizas diff:

![alt text](image-9.png)

Dato 3: Para revertir la situacion al ultimo commit se utiliza checkout:

![alt text](image-10.png)

Modificaremos el titulo y revisaremos status:

![alt text](image-11.png)

Colocamos add . para llevarlos a stage y un commit para guardar los cambios en el repoitorio:

![alt text](image-12.png)

Para ver la lista de cambios con log:

![alt text](image-13.png)

*STAGE Y LOGS*
-Para llevar el control unico de un archivo en repositorio se debe poner add y el nombre del archivo:

![alt text](image-14.png)

-Se realiza un commit para guardar los cambios:

![alt text](image-15.png)

-Se añaden dos archivos en css:
--Se agrega con add nombre del archivo (css/*.css):

![alt text](image-16.png)

--Se agregan todos los archivos con add .

![alt text](image-17.png)

perooo...se quiere quitar un archivo del stage, enonces se utiliza reset nombre del archivo:

![alt text](image-18.png)

Para agregar de nuevo se puede utilizar add -A:

![alt text](image-19.png)

--exixte otra forma de quitar un archivo del stage y es similar:
![alt text](image-20.png)

--para agregar de nuevo se realiza asi:

![alt text](image-21.png)

Dato 4: Para conocerlas definiciones de los comandos se utiliza git help commit:

*ALIAS*
