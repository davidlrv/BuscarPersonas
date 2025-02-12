# Consulta de Personas

## Descripción

Este proyecto es un sitio web que permite la consulta de información de personas mediante un buscador intuitivo. Los usuarios pueden ingresar datos como nombre, documento de identidad u otros criterios para obtener información relevante.

## Características

- Búsqueda rápida y eficiente de personas
- Interfaz intuitiva y fácil de usar
- Integración con bases de datos externas
- Resultados detallados con información relevante
- Seguridad en el manejo de datos

## Tecnologías Utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** ASP.NET Core con C#
- **Base de Datos:** SQL Server
- **Otros:** SweetAlert2 para notificaciones, API de HubSpot para integraciones

## Instalación y Configuración

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/consulta-personas.git
   ```
2. Configurar la base de datos en `appsettings.json`.
3. Restaurar paquetes de NuGet:
   ```bash
   dotnet restore
   ```
4. Ejecutar la migración de la base de datos:
   ```bash
   dotnet ef database update
   ```
5. Iniciar el servidor:
   ```bash
   dotnet run
   ```

## Uso

- Ingresar a la URL del servidor local (por defecto `https://localhost:5001`).
- Usar el buscador para ingresar criterios de búsqueda.
- Ver los resultados y detalles de la persona consultada.

## Contribución

Si deseas contribuir:

1. Haz un fork del repositorio.
2. Crea una rama con tu nueva funcionalidad (`git checkout -b nueva-funcionalidad`).
3. Realiza los cambios y haz un commit (`git commit -m 'Agrega nueva funcionalidad'`).
4. Sube los cambios (`git push origin nueva-funcionalidad`).
5. Crea un Pull Request.

## Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Contacto

Para consultas o sugerencias, puedes contactarnos en [correo@example.com](mailto\:correo@example.com).

a
