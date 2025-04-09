# arquitectura-presentacion-grupo2
Proyecto académico de arquitectura distribuida con Flutter, Spring Boot y MongoDB. Incluye microservicios, CQRS, REST, Kafka y estilos monolíticos MVC/MVVM y cebolla.
##  Temas tratados

- Arquitectura distribuida
- Microservicios
- CQRS (Command Query Responsibility Segregation)
- Estilo monolítico (MVC/MVVM en frontend, cebolla en backend)
- REST/JSON
- Integración con Kafka
- MongoDB como base de datos NoSQL

---

##  Stack tecnológico

| Componente       | Tecnología                                    |
|------------------|-----------------------------------------------|
| Frontend         | Flutter + Dart (MVVM/MVC)                     |
| Backend          | Spring Boot (Arquitectura en capas - cebolla) |
| Base de datos    | MongoDB                                       |
| Comunicación     | REST + JSON                                   |
| Mensajería       | Apache Kafka                                  |
| Contenedores     | Docker                                        |
| Pruebas API      | Postman                                       |

---

##  Estructura del repositorio

```bash
arquitectura-presentacion-grupo2/
│
├── frontend/                    # Proyecto Flutter
│   └── README.md                # Instrucciones específicas del frontend
│
├── backend/                     # Proyecto Spring Boot
│   ├── docker-compose.yml       # Contenedores para backend, Mongo y Kafka
│   ├── postman_collection.json  # Colección para pruebas
│   └── README.md                # Instrucciones específicas del backend
│
├── .gitignore
├── README.md                    # Este archivo
└── LICENSE                      # MIT u otra si aplica
```
Ejecución del proyecto
## 1. Clonar el repositorio
```bash
git clone https://github.com/tu_usuario/arquitectura-presentacion-grupo2.git
cd arquitectura-presentacion-grupo2
```
## 2. Ejecutar el backend y dependencias
```bash
cd backend
docker-compose up --build
```
## 3. Ejecutar el frontend
```bash
cd frontend
flutter pub get
flutter run
```
## 4. Probar con Postman
Importar backend/postman_collection.json y probar los endpoints disponibles.

## Integrantes del grupo 2
- Nombre Apellido
- Nombre Apellido
- Nombre Apellido

