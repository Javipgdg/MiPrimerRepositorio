# MiPrimerRepositorio
1. Instalación y configuración de Git
   Ejecutamos Git y procedemos a configurarlo.
   ![ej1](https://github.com/user-attachments/assets/93cfca5e-bdf3-44cc-a2b3-ec50d3c65eef)

2. Trabajando con un repositorio local
   creamos un repositorio
   ![ej2 1](https://github.com/user-attachments/assets/ca659d2e-3655-4107-be31-5af12e3d3911)
   Creamos un archivo md
   ![ej2 2](https://github.com/user-attachments/assets/fd1649d9-6c02-4b69-b237-846b8ec50aed)
   Realizamos el primer commit
   ![ej2 3](https://github.com/user-attachments/assets/0bdedaaa-65f4-4e74-881a-fe16e471ce74)

3. Subir un repositorio a GitHub
   Desde github creamos un repositorio
   ![ej2](https://github.com/user-attachments/assets/4ecdaf28-17fd-4406-8f50-c53158929981)
   Ejecutamos desde la terminal  git remote add origin       
   https://github.com/Javipgdg/MiPrimerRepositorio

4. Trabajando con ramas
   Creamos y nos movemos de rama
   ![ej4](https://github.com/user-attachments/assets/1cb29815-b95d-4887-982a-5387cdc417f3)
   Realizamos cambios en la rama dev
   git branch dev -- creamos nueva rama
   git checkout dev -- cambiamos de rama
   echo console.log("texto") -- creamos archivo
   ![ej4 1](https://github.com/user-attachments/assets/7eda1d26-0f9b-4054-b40b-747b9a5f5841)
   git commit -m -- hacemos un commit
   git checkout master -- volvemos a la rama principal
   git merge master -- fusionamos las ramas


5. Descargar cambios
   // " Este es un cambio hecho desde github por Javi" //
   ![image](https://github.com/user-attachments/assets/61f4743c-ad2f-4920-bc93-f0a92bec4155)


6. Resolución de conflictos
   ![ej6](https://github.com/user-attachments/assets/fc4e2cba-fab0-4811-901a-6989ef2c6686)
   El conflicto deberia surgir al intentar combinar master y dev al haber realizado cambios en la    misma version, se debe acceder manuakmente al archivo y guardar la rama master

7. Investigación sobre colaboración en equipo con Git y GitHub
   
   ¿Qué es un repositorio remoto y en qué se diferencia de uno local?
   Un repositorio remoto lo podemos encontrar en servidores com es en este caso en github, que    
   nos permite trabajar facilmente en equipo a traves de github, mientras que un repositorio local esta almacenado en nuestro pc , por lo que se usa para trabajo personal

   ¿Qué es un "fork" en GitHub y cómo se usa en proyectos colaborativos?
   Fork es una copia de un repositorio en el cual se pueden realizar combios sin afectar al original.

   ¿Qué es un "pull request" (PR) y cuál es su propósito? Describe el flujo de trabajo típico.
   Se denomina PR a una peticion para fusionar cambios desde un fork a la rama principal
   Se revisan los cambios/ Se analizan y aprueban si todo OK/

   ¿Qué son los "issues" y los "proyectos" en GitHub? ¿Para qué sirven?
   Los issues son reportes de errores y los proyectos son herramientas para planificar y hacer un seguimiento de las tareas dispuestas en el repositorio.

   Explica la importancia de las ramas en un entorno de trabajo colaborativo. ¿Cómo se suelen organizar 
   las ramas en proyectos grandes (ejemplo: main, dev, feature)?
   Gracias a las ramas podemos gestionar el desrrollo del proyecto sin que miembros de un mismo equipo interfieran entre si, es decir que trabajen de forma independiente
   Ventajas del uso de ramas:
   Aislamiento de cambios: permiten a los trabajadores trabajar en partes especificas (como correccion de bugs) sin que estos cambios afecten al codigo base 
   Mejor colaboracion: los desrrolladores pueden trabajar de manera simultanea en diferentes tareas
   Control de version: Facilita la identificacion de cabios, seguimiento de errores
   Pruebas sin afectar el codigo: se pueden probar nuevas funciones sin comprometer el codigo original

   Las ramas se organizan de la siguiente forma:

   main(master)/dev(desarrollo)/feature(funcionalidad)/hotfix(arreglo)/release(varsion casi lista)
   

   
   


   
    
   

     

   

   

   
   



   

   
