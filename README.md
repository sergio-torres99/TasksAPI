# TasksAPI

Este es un proyecto de demostración que implementa una API RESTful para la gestión de tareas. La aplicación fue desarrollada con Spring Boot y utiliza una base de datos para persistir la información.

## Características

* **CRUD Completo**: Permite crear, leer, actualizar y eliminar tareas.
* **API RESTful**: Sigue los principios de las APIs REST para una comunicación cliente-servidor eficiente.
* **Entidad Única**: La API se centra en la entidad `Task` para todas las operaciones.

## Tecnologías Utilizadas

* **Java 17**
* **Spring Boot**: Framework principal para el desarrollo de la API.
* **Maven**: Herramienta de gestión de dependencias y construcción de proyectos.
* **JPA / Hibernate**: Para la persistencia de datos.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

* `src/main/java/com/myAPI/task_manager_api/`: Contiene el código fuente de la aplicación, incluyendo:
    * `Task.java`
    * `TaskController.java`
    * `TaskRepository.java`
    * `TaskManagerApiApplication.java`

## Uso

La API expone los siguientes endpoints para la entidad `Task`:

| Método HTTP | Endpoint | Descripción |
| :--- | :--- | :--- |
| `GET` | `/api/tasks` | Obtiene todas las tareas |
| `GET` | `/api/tasks/{id}` | Obtiene una tarea por su ID |
| `POST` | `/api/tasks` | Crea una nueva tarea |
| `PUT` | `/api/tasks/{id}` | Actualiza una tarea existente |
| `DELETE` | `/api/tasks/{id}` | Elimina una tarea |

## Metodología de Desarrollo

Este proyecto sigue la metodología de Gitflow para la gestión de ramas, asegurando un flujo de trabajo organizado y colaborativo.
