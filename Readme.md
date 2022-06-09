# Página web con Azure App Services
![](screenshots/K_007.jpg)

Recordar que Azure App Services es una herramienta que te permite crear una aplicación web en Azure y es necesario tener una cuenta de Azure.
![](screenshots/K.jpg)


Desde el [portal de Azure](https://portal.azure.com) es necesario seleccionar la opción **App Service** y llenar los formularios:

## Datos básicos
- Suscripción
- Grupo de recursos
- Nombre de la aplicación web
- Pila del entorno (en este caso PHP)
- SKU y tamaño (en este caso la opción **Gratis F1**)

## Revisar y crear 
Si todo esta bien podemos acceder a nuestro recurso de App Service. Dentro de **Implementación > Centro de implementación** seleccionaremos GitHub como el origen de nuestra aplicación.

![](screenshots/K_001.jpg)

## Crear repositorio
En [GitHub](https://github.com) creamos un repositorio público. 
![](screenshots/K_002.jpg)

En nuestra máquina de trabajo creamos los archivos de nuestra aplicación web, en este caso los archivos de nuestra aplicación web estan basados en el [Ejemplo de Azure App Services](https://github.com/josejesusguzman/lab-subir-app-service-azure).
![](screenshots/K_004.jpg)

Después de crear de subir nuestro trabajo al repositorio, en el recurso de App Service seleccionaremos el repositorio que acabamos de crear y lo guardamos.
![](screenshots/K_005.jpg)

Desde la sección **Actions** de GitHub podemos ver el estado de nuestro trabajo. Cuando el deploy termina, podemos ver el link de nuestra aplicación web. 
![](screenshots/K_006.jpg)