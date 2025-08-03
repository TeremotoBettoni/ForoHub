# ForoHub
Practica Spring Framework: Challenge Foro Hub

# Challenge-foro-alura

Este proyecto es una API REST para el foro de Alura, construida utilizando Spring Boot.

![Insignia](./imagenes/Badge-Spring.png)

## Requisitos

- Java JDK: versión 17 en adelante - Descarga la última versión LTS de Java gratuita 
- Maven: versión 4 en adelante 

## Tecnologías Utilizadas

- **Spring Boot 3.0.6** - https://start.spring.io/
- **Spring Data JPA**: Para la interacción con la base de datos.
- **Lombok**: Para reducir el código boilerplate.
- **MySQL**: Base de datos relacional.

## Instalación

1. Clona el repositorio:
    ```bash
    git clone <https://github.com/TeremotoBettoni/ForoHub.git>
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd Challenge-foro-alura
    ```

3. Configura la base de datos MySQL. Crea una base de datos y actualiza las credenciales en el archivo `application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/tu_base_de_datos
    spring.datasource.username=tu_usuario
    spring.datasource.password=tu_contraseña
    ```

4. Compila el proyecto utilizando Maven:
    ```bash
    ./mvnw clean install
    ```

5. Ejecuta la aplicación:
    ```bash
    ./mvnw spring-boot:run
    ```

## Uso

Una vez que la aplicación esté en funcionamiento, puedes acceder a la API REST utilizando herramientas como Postman o cURL. La URL base será `http://localhost:8080`.

## Desarrollo

Durante el desarrollo, puedes beneficiarte de las herramientas adicionales proporcionadas por `spring-boot-devtools`, como la recarga automática de la aplicación.

### Compilar y Ejecutar Pruebas

Para compilar el proyecto y ejecutar las pruebas, usa:
```bash
./mvnw test
```
### Diagrama Be Base De Datos
![Insignia](./imagenes/diagrama-DB-forohub.png)
---

