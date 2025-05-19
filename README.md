# HUGO-VALLEJO-PT2

Este es mi repositorio. El contenido que hay aquí trata sobre la **instalación y configuración de ownCloud** en una máquina virtual usando **IsardVDI**.

A continuación, tenéis dos manuales:

1. **Manual de instalación de ownCloud**  
   Explica paso a paso cómo preparar el sistema, instalar Apache2, MySQL, PHP y descargar ownCloud para dejarlo funcionando.
   - [Manual de Instalación](INSTALLATION.md) 

2. **Manual de configuración de ownCloud**  
   Aquí detallo cómo configurar ownCloud desde el navegador: crear usuarios, asignar permisos, compartir archivos, cambiar nombres, establecer políticas de seguridad y acceder desde otra máquina.
   - [Manual de Configuración](CONFIGURATION.md)


Todo está explicado de forma clara para que se pueda seguir fácilmente.

## Descripción del proyecto

En este proyecto he instalado **ownCloud**, que es como una nube privada que tú mismo puedes montar para guardar tus datos.

ownCloud te permite **almacenar archivos en internet** en lugar de tenerlos solo en tu ordenador, así puedes acceder a ellos desde **cualquier lugar y en cualquier momento**.

También puedes:

- Compartir archivos con otros usuarios.
- Crear carpetas personalizadas.
- Dar permisos distintos (solo ver, editar, etc.).
- Controlar todo tú mismo, ya que tú eres el administrador del sistema.

Este proyecto sirve para aprender a montar tu propia nube y gestionar un servicio web desde cero.

## Problemas encontrados

Durante la instalación, después de descomprimir el fichero de ownCloud, me encontré con un problema:

- **Error al copiar el directorio**:  
  Pensaba que el nombre de la carpeta descomprimida era igual al del archivo `.zip`, pero no era así.  
  Al intentar copiarla al directorio `/var/www/html`, me aparecía un error porque el nombre del directorio no coincidía.

### Solución:
Tuve que substituir esto:

```bash
sudo cp -R app-web.zip/. /var/www/html
```

Por el comando correcto que es este:

```bash
sudo cp -R owncloud.zip/. /var/www/html
```

