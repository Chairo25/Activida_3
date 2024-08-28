# Sistema de Gestión de Libros

## Descripción

Este proyecto es un sistema de gestión de libros desarrollado en PHP utilizando el patrón de diseño Modelo-Vista-Controlador (MVC). La aplicación permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre los libros. Además, está integrada con solicitudes asíncronas mediante Axios para una experiencia de usuario más fluida.

## Tecnologías Utilizadas

- **PHP**: Lenguaje de programación del lado del servidor.
- **MySQL**: Sistema de gestión de bases de datos relacional.
- **Bootstrap**: Framework de CSS para una interfaz moderna y responsiva.
- **Axios**: Biblioteca para realizar solicitudes HTTP asíncronas.
- **Composer**: Herramienta para la gestión de dependencias en PHP.
- **HTML5** y **CSS3**: Tecnologías para estructurar y diseñar la interfaz de usuario.

## Estructura del Proyecto

- `/app` - Contiene la lógica de la aplicación, incluidos los controladores y modelos.
- `/public` - Contiene archivos públicos accesibles, como `index.php`, que sirve como punto de entrada.
- `/router` - Contiene las definiciones de rutas.
- `style.css` - Archivo de estilos CSS para la aplicación.

## Instalación

Sigue estos pasos para instalar y ejecutar el proyecto localmente:

1. **Clona el repositorio**:

    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```

2. **Accede al directorio del proyecto**:

    ```bash
    cd <NOMBRE_DEL_DIRECTORIO_DEL_PROYECTO>
    ```

3. **Instala las dependencias de PHP utilizando Composer**:

    ```bash
    composer install
    ```

4. **Configura la base de datos**:
   - Crea una base de datos MySQL.
   - Configura los detalles de la base de datos en el archivo `/config/database.php` (ajusta el nombre de la base de datos, el usuario y la contraseña).

5. **Ejecuta las migraciones** (si es necesario) para crear las tablas en la base de datos:

    ```bash
    php /app/migrations/run.php
    ```

6. **Inicia el servidor web**:

    Puedes utilizar el servidor integrado de PHP para propósitos de desarrollo:

    ```bash
    php -S localhost:8000 -t public
    ```

7. **Accede a la aplicación**:

    Abre tu navegador y visita `http://localhost:8000` para interactuar con la aplicación.

## Uso

Una vez que la aplicación esté en ejecución, puedes realizar las siguientes acciones:

- **Agregar un nuevo libro**: Usa el formulario de entrada para ingresar los detalles del libro y guardarlo.
- **Ver libros existentes**: La lista de libros se mostrará en una tabla.
- **Actualizar un libro**: Selecciona un libro de la lista y edita sus detalles.
- **Eliminar un libro**: Elimina un libro de la lista utilizando la opción correspondiente.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva característica'`).
4. Envía la rama (`git push origin feature/nueva-caracteristica`).
5. Crea un pull request.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).

---

Para más detalles, consulta la documentación de [PHP](https://www.php.net/), [Bootstrap](https://getbootstrap.com/), y [Axios](https://axios-http.com/).
