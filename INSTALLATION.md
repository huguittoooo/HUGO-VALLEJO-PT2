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

















