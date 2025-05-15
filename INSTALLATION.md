![image](https://github.com/user-attachments/assets/9cd77c11-cb52-4a82-8e38-940b15d7764e)

![image](https://github.com/user-attachments/assets/65605b02-8697-40d7-bccb-8f3052c8df3a)

![image](https://github.com/user-attachments/assets/4abfed73-282b-4361-afd3-543d701777dc)

Ya esta nuestra maquina creada.

Esperamos a que se cargue.

![image](https://github.com/user-attachments/assets/8cfbb232-f830-4014-ad8f-2d9688754b37)

Una vez se carga, le damos a los tres puntos y editamos los parametros de la siguiente manera.

![image](https://github.com/user-attachments/assets/804e2542-a0b0-4101-a238-b29c33e037c1)

## Requisitos de Hardware

Antes de empezar la instalación, es importante configurar la máquina virtual con los siguientes recursos:

- **vCPUs:** 8
- **Memoria RAM:** 32 GB
- 
![image](https://github.com/user-attachments/assets/bc2456b9-04cb-4cb8-8669-555501b861fc)

Nos quedará así:

![image](https://github.com/user-attachments/assets/74a5c62d-c189-492b-ac09-df7db0d3624d)



Esta configuración asegura que ownCloud funcione de forma fluida y sin problemas de rendimiento.

Bajamos abajo una vez hecho los pasos anteriores y le damos a **Enviar**

![image](https://github.com/user-attachments/assets/c884cbb8-1e67-43f1-a27c-ea81b5a6b2f9)

## Inicio de la Máquina Virtual

Una vez configurado el hardware de la máquina virtual, podemos iniciarla para comenzar con la **configuración interna** del sistema.

A partir de este momento, realizaremos todos los pasos necesarios desde dentro del sistema operativo para preparar e instalar ownCloud.


![image](https://github.com/user-attachments/assets/1da0ff2a-81bb-4932-a60c-620a50384a18)


## Acceso al Sistema Operativo

Al iniciar la máquina virtual, se mostrará el **menú del sistema operativo**. 

Cuando aparezca, simplemente pulsa la tecla **Enter** para arrancar el sistema y acceder a la terminal de la máquina.

![image](https://github.com/user-attachments/assets/6a1f8ba1-b8de-4692-9fa9-35b5002563d4)


## Inicio de Sesión

Una vez que el sistema haya arrancado, se nos pedirá iniciar sesión.

- Introducimos el **nombre de usuario** (por ejemplo: `usuario`)
- Luego escribimos la **contraseña**, que en este caso también es: `usuario`

![image](https://github.com/user-attachments/assets/55f35834-b1a3-4346-b0e5-c534ade34f28)
![image](https://github.com/user-attachments/assets/ac4cd2f5-314f-496f-89f3-decc444d5a22)


Después de esto, ya estaremos dentro del sistema listos para comenzar la instalación.

## Dentro del Sistema

Ya estamos dentro del sistema operativo con el usuario correctamente iniciado.

Ahora podemos empezar con la instalación de los paquetes necesarios para configurar ownCloud en nuestra máquina.


![image](https://github.com/user-attachments/assets/8f5dd802-dc0a-4869-95ad-f6f106ce888d)

## Abrir la Terminal

Para comenzar con la instalación, necesitamos abrir una terminal.

1. Haz clic en el **cuadro de la esquina superior izquierda** (icono de aplicaciones).
2. Escribe `terminal` en el buscador.
3. Haz clic en el icono de la **Terminal** para abrirla.

Desde aquí ejecutaremos todos los comandos necesarios.


![image](https://github.com/user-attachments/assets/0d35802b-e269-4c57-bcb0-82a1febfff20)

## Terminal Abierta

Ya tenemos la **terminal abierta** y lista para usar.

A partir de ahora, escribiremos en ella todos los comandos necesarios para instalar y configurar ownCloud en nuestra máquina virtual.


![image](https://github.com/user-attachments/assets/e1732968-bf35-4f02-94cd-2d153280c235)


## Actualización del Sistema e Instalación de Dependencias

Antes de instalar ownCloud, vamos a actualizar el sistema y a instalar los paquetes necesarios: **Apache2**, **MySQL** y algunas librerías adicionales.

### 1. Actualizar la máquina

Ejecuta los siguientes comandos en la terminal para actualizar los repositorios y los paquetes del sistema:

```console
sudo update
```
![image](https://github.com/user-attachments/assets/870ecd46-9789-4c67-a8d9-6902d6b80236)

Nos pedira una contraseña, ponemos como contraseña **usuario**

![image](https://github.com/user-attachments/assets/aaf6645c-1e0f-4594-9aee-dd7dcb19d5fc)

## Mensajes Durante la Actualización

Cuando ejecutes los comandos de actualización, verás que en la terminal se empiezan a **mostrar muchos mensajes y comandos automáticos**.

No te preocupes, esto es **normal**. El sistema está descargando e instalando las actualizaciones necesarias. Solo espera a que el proceso termine.

![image](https://github.com/user-attachments/assets/20bc492c-7614-4e8f-8c8a-71a256e1e2fa)

### 3. Ejecutar la actualización completa

Después de actualizar los repositorios, ahora ejecutamos el siguiente comando para aplicar las actualizaciones:

![image](https://github.com/user-attachments/assets/50baad50-5fe5-4b6d-ba25-01516a8d01d8)

```console
sudo apt upgrade
```

Cuando nos salga **[S/n]** le damos al enter

![image](https://github.com/user-attachments/assets/a1e620ac-caaa-4898-a239-17b6c507d631)

Ahora esperamos a que se instale.

![image](https://github.com/user-attachments/assets/46783a8b-33c2-4dd3-a699-be7504ee20de)

Ya estaría


Ahora instalamos el servidor web
![image](https://github.com/user-attachments/assets/b73181c0-012b-4114-83de-c214b72a1f28)

Ahora hacemos la instalacion del servidor de la base de datos mysql-server

![image](https://github.com/user-attachments/assets/a5434061-0930-4a82-8b21-ecc9b1808015)

Ahora hacemos la instalación de algunas librerías de PHP, que es el lenguaje principal que utilizan las aplicaciones

![image](https://github.com/user-attachments/assets/b6a10ccd-068c-459d-b140-ebb5926c0614)
![image](https://github.com/user-attachments/assets/fe8bac58-6397-46f7-92fc-2305e15aa036)


Ahora reiniciamos el servidor apache2.

![image](https://github.com/user-attachments/assets/82e75e40-389b-4fea-b4b1-a679b2e6b4bd)

## Configuración de MySQL

Una vez instalado MySQL, vamos a acceder a su consola para crear la base de datos que ownCloud usará.

### 1. Acceder a la consola de MySQL

![image](https://github.com/user-attachments/assets/a4d5ef16-c22d-4be9-89bd-e9b9ecd5ea3b)

### 2. Crear la base de datos para ownCloud

Una vez dentro de la consola de MySQL, ejecuta los siguientes comandos uno por uno:

![image](https://github.com/user-attachments/assets/141ab9db-93fc-41a3-a6c6-f30cd35e406d)

El siguiente comando que tienes que poner es:
```console
CREATE USER 'usuario'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
```
Y despues teneis que poner:
```console
GRANT ALL ON bbdd.* to 'usuario'@'localhost';
```
En mi caso ya lo habia hecho y me da error porque ya los habia creado.

Cuando estemos saldremos al apartado de **mysql** para escribir **exit**

![image](https://github.com/user-attachments/assets/1840d644-6eb5-41ea-8cc6-1abe376f06f0)

## Descarga y extracción de los archivos de la aplicación web

Primero de todo nos tenemos que descargar el archivo zip para poder hacer todos los procedimientos que veremos a continuacion.

https://download.owncloud.com/server/stable/owncloud-complete-20240724.zip 

![image](https://github.com/user-attachments/assets/ea2cf8eb-1cb3-499d-9202-a14925784dcc)


Ahora vamos a colocar los archivos de ownCloud en el directorio correcto para que funcionen con Apache.

1. Nos movemos a la carpeta donde se aloja la descarga del zip, en mi caso es en Documentos:
![image](https://github.com/user-attachments/assets/dd3f7224-cf6f-4351-a1ea-a6055880e105)

Ahora cambiamos el nombre al que queramos para que nos sea mas facil de identificar y escribirlo despues en la terminal.
![image](https://github.com/user-attachments/assets/85a5fb8f-9cf3-44ba-b6fb-72725068eb28)

Borramos el nombre que tiene actualmente y lo substituimos por el que queramos, en mi caso lo llamaré **app-web**
![image](https://github.com/user-attachments/assets/2f07c4c6-6056-4838-8a58-0991273294ba)

![image](https://github.com/user-attachments/assets/57a258e4-578b-4d16-9194-cd2a68bf213c)

Ya estaría

Ahora nos vamos a la terminal y ponemos lo siguiente:
![image](https://github.com/user-attachments/assets/fcb9c019-76b7-4a5d-a653-27e0ef7ac3d6)

Teneis que vigilar, porque yo le he puesto de nombre a mi zip **app-web**, pero ahi debeis poner cada uno el nombre que le hayais puesto. También cuidado porque hay gente que tiene el idioma del linux en catalan, pues en **Descargas** teneis que poner **Baixades**.

Después entramos a nuestro directorio `/var/www/html`
```console
cd /var/www/html
```
![image](https://github.com/user-attachments/assets/7613452d-90c5-4bb8-9648-66bbadac5224)

![image](https://github.com/user-attachments/assets/07bc9c46-2fad-487d-b8b7-14848114d035)

Ahora ponemos el siguiente comando para descomprimir el fichero que hemos descargado:
![image](https://github.com/user-attachments/assets/4a7f1693-4935-468c-80b1-587d2d9231c5)

Ahora ponemos esto



Si nos sale ese apartado azul, ya hemos entrado al directorio.

## Copiar los archivos a la carpeta de Apache

Después de descomprimir el archivo ZIP, vamos a mover la carpeta de ownCloud al directorio donde Apache busca las páginas web.

En el siguiente paso, debemos vigilar y mirar como se llama nuestra ruta, en vez de poner **app-web** tenemos que cambiarlo y poner **owncloud** como se ve en la imagen.

![image](https://github.com/user-attachments/assets/7e79f024-8744-4b62-a474-f0a8ebdf3c1a)

Para continuar eliminamos la carpeta original después de descomprimir.

![image](https://github.com/user-attachments/assets/6482357e-2599-465b-a163-0d74b47430e3)

Después eliminamos el fichero **index.html** de nuestro apache2.

![image](https://github.com/user-attachments/assets/41e496d8-35ef-4bcf-8406-32a9ae4af21d)

## Aplicar permisos a los archivos de ownCloud

Una vez que hemos descomprimido y movido los archivos de ownCloud al directorio `/var/www/html`, es importante **asignar los permisos correctos** para que el servidor web pueda acceder sin problemas.

![image](https://github.com/user-attachments/assets/4e94775f-614a-44d8-9919-f1d32c31b071)


## Acceder desde el navegador

Ahora que todo está preparado, vamos a comprobar si ownCloud funciona correctamente.

1. Abre tu **navegador web**.
2. Escribe la siguiente dirección en la barra de búsqueda: **Localhost** y nos daremos cuenta que debemos instalar nuevas versiones para que podamos acceder al enlace.
3. Ahora instalaremos las versiones que nos piden para poder acceder a nuestro **localhost**

## Instalar PHP 7.4 en Ubuntu 24.04

ownCloud necesita la versión **7.4 de PHP**, pero Ubuntu 24.04 viene con versiones más nuevas, así que debemos instalar manualmente la versión correcta.

### 1. Actualizar el sistema

Primero actualizamos los repositorios y paquetes:

![image](https://github.com/user-attachments/assets/fcb75d1e-a123-474e-8aaf-611a140a0a05)

```bash
sudo apt install software-properties-common -y
```

![image](https://github.com/user-attachments/assets/38a00972-bb0b-42a4-98e8-c44a1196f3cb)


Ahora instalamos las herramientas necesarias para poder añadir repositorios PPA, que son los que usaremos para instalar PHP 7.4:

![image](https://github.com/user-attachments/assets/dbd5df95-2cd8-417b-8e6b-ba3e3dc91284)


```bash
LC_ALL=C.UTF-8 sudo add-apt-repository ppa:ondrej/php -y
```

Ahora vamos a actualizar los repositorios del sistema

![image](https://github.com/user-attachments/assets/cc9ca8f5-f722-4745-a117-c73ab7bb92da)

Después instalaremos las librerias PHP 7.4

![image](https://github.com/user-attachments/assets/2bb9dac0-4915-413d-9148-3033f2542428)

![image](https://github.com/user-attachments/assets/f5313059-49f4-475b-8ff4-b8ad02fe2449)

![image](https://github.com/user-attachments/assets/fec7d24f-71bf-436a-94dd-0e8cce0e1994)

Ahora tenemos que seleccionar la version de apache2

![image](https://github.com/user-attachments/assets/6bc0533c-b270-407b-a627-2d8608496559)

![image](https://github.com/user-attachments/assets/3bf2078a-3eaf-40c1-99e4-eea2cb7b2071)

![image](https://github.com/user-attachments/assets/e6f9c4f6-21b0-47cb-914d-f657813f62d7)

Ahora activamos los modulos de apache2 necesarios:

![image](https://github.com/user-attachments/assets/6b1e33ab-e77a-414c-a731-aad0714a0c9d)

![image](https://github.com/user-attachments/assets/8534c60c-230f-459e-89d6-7a2a3f000137)

Por ultimo, reiniciamos el apache2:

![image](https://github.com/user-attachments/assets/873b6fdd-f62a-4e1d-bf79-e3b5b32894cf)

## Comprobar conexión en localhost

Para verificar que la configuración y la instalación funcionan correctamente:

1. Abre el navegador web.
2. En la barra de búsqueda, escribe: **localhost**

Nos deberia de salir esto:

![image](https://github.com/user-attachments/assets/e19bf749-3b93-40ee-ac9b-4830ea7b6d90)

## Datos para la configuración inicial

Al llegar a la pantalla de configuración de ownCloud en el navegador, usa estos datos si no has cambiado nada:

- **Usuario:** usuario  
- **Contraseña:** password  
- **Base de datos:** bbdd  
- **Dominio:** localhost  

Con estos datos podrás completar la configuración y dejar ownCloud listo para usar.

![image](https://github.com/user-attachments/assets/a3410aba-f330-470d-8cf7-0386b627a6eb)

![image](https://github.com/user-attachments/assets/717394a7-acaa-4cae-bd5a-42f074bdd3d9)

Cuando acabemos, bajamos abajo y le damos a **finish setup**

![image](https://github.com/user-attachments/assets/54c7dae1-a4b2-4aa6-9dc7-867cda6433d9)


Se nos despliega otra ventana de inicio de sesion:

![image](https://github.com/user-attachments/assets/1364e690-b0f2-4872-adf7-233396307745)

Ahora solo falta poner el usuario y la contraseña:

![image](https://github.com/user-attachments/assets/072c316b-735a-4b20-bcd2-92f2ec27ec50)

Para acabar, le damos a **Login** y se l¡nos despliega el siguiente menu que ya estariamos dentro de owncloud, y listos para iniciar la configuracion.

![image](https://github.com/user-attachments/assets/9fa2ab72-e688-4e6c-98ce-9e4db7e5a07b)

Fin de la instalación.







































