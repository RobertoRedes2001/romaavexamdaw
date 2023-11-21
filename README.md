# romaavexamdaw

El examen está resuelto con todo el amor y el padreo posible.

"Devoró" - se usa para cuando una persona lo hace muy bien. Ejemplo: Devoraste en la presentacion. (La presentacion le salio excelente)

## Instrucciones para levantar el container:

1. Clonar el repositorio o descargar la información que se encuentra en este.
   (NOTA: se proporcionará un archivo.zip con la información de Florida Oberta).

2. Una vez descargada la información, asegurarse de contar con todos estos archivos:
   - Directorio `web`: `index.php` y `dockerfile`
   - Directorio `php`: `dockerfile`
   - Directorio `db`: `init.sql` y `dockerfile`
   - Directorio raíz: `docker-compose.yml`

3. Una vez comprobado que tenemos todos estos archivos en sus correspondientes carpetas, abrir Docker Desktop.

4. Abrir la consola de comandos de tu preferencia (VSCode cmd, Windows CMD, Windows Powershell, etc).

5. Ubicarse en el directorio donde se tiene el `docker-compose.yml`.

6. Ejecutar el comando:
   ```bash
   docker-compose up -d

Con esto, al ingresar en localhost desde el navegador, la página hará esperar unos 20 segundos mientras se arma la base de datos, y después podremos visualizar la web.
