# Sistema Digital SST - YPF / UTN BA / Grupo 22

Paquete listo para publicar como sitio estático en GitHub Pages.

## Publicación

1. Crear un repositorio nuevo en GitHub.
2. Subir todos los archivos de esta carpeta a la raíz del repositorio.
3. Abrir `Settings > Pages`.
4. En `Build and deployment`, seleccionar `Deploy from a branch`.
5. Elegir la rama `main`, carpeta `/ (root)` y guardar.
6. Esperar a que GitHub muestre la dirección pública del sitio.

No cambiar los nombres de los PDF: la aplicación utiliza estas rutas para abrirlos desde Documentación y Emergencias.

## Supabase

El HTML contiene la URL y la clave publicable del proyecto Supabase. Antes de usar información real, verificar que todas las tablas expuestas tengan RLS activado y políticas limitadas a las operaciones necesarias.

Nunca publicar una clave `service_role` dentro del HTML o del repositorio.
