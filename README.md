# 🚀 MongoDB Admin Web - Gestión Visual de Bases de Datos MongoDB

![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-6.0-purple)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0-green)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)

Aplicación web para administrar bases de datos MongoDB sin necesidad de comandos. Ideal para desarrolladores y administradores que buscan una interfaz intuitiva.

## 🌟 Características Principales

- **CRUD Completo**: Crear, leer, actualizar y eliminar bases de datos, colecciones y documentos.
- **Seguridad**: Gestión de usuarios y roles con autenticación integrada.
- **Backups**: Copias de seguridad y restauración con `mongodump`/`mongorestore`.
- **Importación/Exportación**: Soporte para JSON y CSV.
- **Dockerizado**: Fácil despliegue con contenedores.

## 📚 Documentación Estructurada

Explora nuestra guía completa:

1. **Parte 1**: Configuración de MongoDB en Docker
2. **Parte 2**: Creación de Bases de Datos e Inserción de Datos
3. **Parte 3**: Copias de Seguridad y Restauración
4. **Parte 4**: Exportación/Importación (JSON/CSV)
5. **Parte 5**: Administración de Seguridad (Roles y Permisos)
6. **Parte 6**: Desarrollo de la Aplicación Web

## 🛠️ Tecnologías Clave

| Componente       | Tecnología           |
|------------------|---------------------|
| Backend          | ASP.NET Core 6       |
| Frontend         | Razor Pages + Bootstrap 5 |
| Base de Datos    | MongoDB 6.0          |
| Contenerización  | Docker + Docker Compose |

## 🚀 Cómo Empezar

### Requisitos Previos
- Docker Desktop
- .NET 6 SDK
- MongoDB (opcional, puede usarse el contenedor)

### Instalación Rápida
```bash
git clone https://github.com/OrlandoGalvanVargas/BaseDeDatosDinamicasMongoDB.git
cd mongodb-admin-web
docker-compose up -d
```

La aplicación estará disponible en: [http://localhost:5000](http://localhost:5000)

## 📊 Estructura del Proyecto
```
├── Pages/
│   ├── PanelAdmin/       # Gestión de BD/colecciones
│   ├── Copias/          # Backups
│   ├── ImpExp/          # Importación/Exportación
│   └── MongoUsers/      # Control de acceso
├── Services/            # Lógica de negocio
└── appsettings.json     # Configuración
```

## 🤝 Contribuir
¡Contribuciones son bienvenidas! Sigue estos pasos:

1. Haz fork del proyecto
2. Crea tu rama (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -m 'Añadir x funcionalidad'`)
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

