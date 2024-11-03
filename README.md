# CRM-GraphQL

**CRM-GraphQL** es un proyecto desarrollado para gestionar relaciones con clientes utilizando la potencia de **GraphQL** como API para consultas y mutaciones. Este proyecto está diseñado para optimizar las operaciones de CRM y proporcionar una experiencia de desarrollo más eficiente y flexible en comparación con las APIs tradicionales.

## Tabla de Contenidos
- [Descripción](#descripción)
- [Características](#características)
- [Requisitos del Sistema](#requisitos-del-sistema)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Descripción
**CRM-GraphQL** permite la gestión de clientes, contactos y negocios en una plataforma moderna que utiliza **GraphQL** para realizar consultas y mutaciones eficientes. Este proyecto está pensado para desarrolladores que buscan integrar soluciones CRM con tecnologías de última generación.

## Características
- **Consultas personalizadas**: Obtén solo los datos que necesitas, optimizando el rendimiento.
- **Mutaciones flexibles**: Realiza operaciones de creación, actualización y eliminación de datos de manera intuitiva.
- **Gestión de clientes**: Crea y administra perfiles de clientes.
- **Control de negocios y contactos**: Lleva un registro detallado de las interacciones y oportunidades.
- **API basada en GraphQL**: Integra la funcionalidad de CRM en otras aplicaciones de manera fácil y escalable.

## Requisitos del Sistema
- **Node.js** 14.x o superior
- **npm** o **yarn**
- **MongoDB** (local o en la nube para la base de datos)
- **Apollo Server** como motor de GraphQL

## Instalación
1. Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/JoseLazaro15/CRM-GraphQL.git

2. Navega al directorio del proyecto:
   ```bash
   cd CRM-GraphQL

3. Instala las dependencias:
   ```bash
   npm install
    # o
   yarn install

4. Configura las variables del entorno:
   Crea un archivo .env en la raiz del proyecto, con las siguientes variables:
   ```bash
   DB_MONGO=<tu cadena de conexión de MongoDB>
   SECRETA=<tu clave secreta para autenticación>

## USO
Una vez el servidor este en funcionamiento, puedes acceder al playground de GraphQL en
    
    http://localhost:4000/graphql
para realizar consultas y pruebas.

## Contribucion
  Las contribuciones son bienvenidas. Si deseas colaborar:
  1. Haz un fork del repositorio.
  2. Crea una rama de características (feature/nueva-funcionalidad).
  3. Haz commit de tus cambios.
  4. Haz push a tu rama.
  5. Abre un Pull Request.

## Licencia
Este proyecto esta licenciado bajo la Licencia MIT.




