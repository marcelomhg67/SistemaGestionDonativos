# # Sistema de Gestión de Donativos

## Descripción
Sistema para gestionar donativos, inventarios y distribución de recursos para Regalando Estrellas A.C.

## Problema Identificado
Falta de automatización en el manejo de inventarios y donativos.

## Solución
Creación de un sistema digital centralizado.

## Arquitectura
- Frontend: React.
- Backend: Node.js.
- Base de datos: PostgreSQL.

 ## Tabla de Contenidos
- [Descripción](#descripción)
- [Problema Identificado](#problema-identificado)
- [Solución](#solución)
- [Arquitectura](#arquitectura)
- [Requerimientos](#requerimientos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Contribución](#contribución)
- [Roadmap](#roadmap)

## Requerimientos
- Servidor de aplicación: Node.js.
- Base de datos: PostgreSQL.
- Librerías: Express, dotenv, pg.
- Versión de Node.js: 16.x

## Instalación
1. Clona el repositorio: `git clone <URL_DEL_REPOSITORIO>`
2. Instala las dependencias: `npm install`
3. Configura las variables de entorno en un archivo `.env`.
4. Ejecuta el servidor: `npm start`

### Pruebas manuales
1. Ejecuta el comando: `npm test`.
2. Verifica los resultados en la terminal.

## Configuración
- Crea un archivo `.env` con las siguientes variables:

## Uso
### Usuario Final
- Ingresa a la aplicación con tu cuenta.
- Registra donativos desde el panel principal.
### Administrador
- Accede a la sección de configuración.
- Administra permisos de usuarios.

## Contribución
1. Clona el repositorio: `git clone <URL>`
2. Crea un nuevo branch: `git checkout -b feature/nueva-funcionalidad`.
3. Envía un pull request con tus cambios.

## Roadmap
- Integración de API para notificaciones.
- Reportes gráficos avanzados.

### Instalación de PostgreSQL
- Descarga PostgreSQL desde [su sitio oficial](https://www.postgresql.org/).
- Configura un usuario y una base de datos para el sistema.
- Usa el comando: `CREATE DATABASE nombre_base_datos;`.

## Uso
### Usuario Final
- Abre la aplicación en tu navegador en `http://localhost:3000`.
- Accede con tu cuenta o regístrate.
- Registra un donativo llenando el formulario en la sección "Registrar Donativo".
- Revisa el inventario desde el menú "Inventario".

### Administrador
- Accede al panel de administración en `http://localhost:3000/admin`.
- Agrega nuevos usuarios desde la pestaña "Usuarios".
- Configura alertas en la sección "Notificaciones".
